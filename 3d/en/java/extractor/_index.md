---
title: Java 3D Formats Extract Assets
url: /java/extractor/
description: Extract Assets from 3D format 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x via Java library using a few lines of java code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D Formats Extract Assets Via Java" h2="Extract Assets from 3D document formats without any 3D modeling and rendering software to build cross-platform Java applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
Developers can use the 3D library to easily extract 3D file assets. Few formats supported by the API are WavefrontOBJ, Discreet3DS, STL (ASCII, Binary), FBX (ASCII, Binary), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco formats, etc. The extraction process is simple, load the source file through an instance of the [scene class](https://reference.aspose.com/3d/java/com.aspose.threed/scene/), create the archive class and handle the extraction asset class, and call the The Save method for the relevant output format parameter.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Extract Assets from 3D Scene to various formats" %}}
Developers can easily extract assets from 3d files through the same process listed above. Consider some examples like **3DS to FBX Extractor**. Load 3DS files via scene class objects. Create save options with [FbxSaveOptions](https://reference.aspose.com/3d/java/com.aspose.threed/fbxsaveoptions/) to create save options and call the scene save method with the output file path and fbx options arguments. The API has appropriate options classes for saving into related classes, e.g. [A3dwSaveOptions](https://reference.aspose.com/3d/java/com.aspose.threed/a3dwsaveoptions/) [AmfSaveOptions](https://reference.aspose.com/3d/java/com.aspose.threed/amfsaveoptions/) [Discreet3dsSaveOptions](https://reference.aspose.com/3d/java/com.aspose.threed/discreet3dssaveoptions/) [Html5SaveOptions](https://reference.aspose.com/3d/java/com.aspose.threed/html5saveoptions/) [RvmSaveOptions](https://reference.aspose.com/3d/java/com.aspose.threed/rvmsaveoptions/) and more. Here is the full list of 3D [extractor formats](https://reference.aspose.com/3d/java/com.aspose.threed/fileformat/) options.

{{% blocks/products/pf/feature-page-code h3="Java Code for 3DS to FBX Extract Assets" %}}

```cs

//Source files that need to extract assets
String file = "template.3ds";

//create an instance of Scene
Scene scene = new Scene();
scene.open(file, FileFormat.DISCREET3DS);

//Create zip files and perform asset extraction on source files
String zipOutput ="OutputFile.zip";
File newFile=new File(zipOutput);
newFile.createNewFile();
FileOutputStream output = new FileOutputStream(zipOutput);
Zip za = new Zip(output);
Extract(scene,za,true);

//close stream resource
za.closeIo();

//Callable Extract method,The parameter texture indicates: whether to extract the texture
private void Extract(Scene scene, Zip za, boolean texture) throws IOException {
    Extractor extractor = new Extractor(za, texture);
    extractor.Extract(scene);
}

//Create a compressed file processing class
class Zip
{
    private ZipOutputStream archive;
    private HashSet<String> entries = new HashSet<String>();

    public Zip(OutputStream stream)
    {
        archive = new ZipOutputStream(stream);
    }

    public void Add(String fileName, byte[] content, boolean enableCompression) throws IOException {
        String entryName = PickName(fileName);
        if(enableCompression){
            archive.setLevel(5);
        }else{
            archive.setLevel(0);
        }
        ZipEntry entry = new ZipEntry(entryName);
        archive.putNextEntry(entry);
        archive.write(content, 0, content.length);
    }

    public void closeIo(){
        if(archive!=null){
            try {
                archive.close();
            } catch (IOException e) {
                e.printStackTrace();
            }
        }
    }

    private String PickName(String fileName)
    {
        if (!entries.contains(fileName))
        {
            entries.add(fileName);
            return fileName;
        }
        String arrFile[]=fileName.split(".");
        String baseName = arrFile[0];
        String ext = arrFile[1];
        for (int idx = 2; ; idx++)
        {
            String newName = baseName + "_" + idx;
            if (!StringUtils.isBlank(ext))
                newName += ext;
            if (entries.contains(newName))
                continue;
            entries.add(newName);
            return newName;
        }
    }
}

//Create an asset extraction processing class
class Extractor
{
    private Zip zip;
    private boolean texture;
    HashSet<A3DObject> visited = new HashSet<A3DObject>();

    public Extractor(Zip zip,boolean texture)
    {
        this.zip = zip;
        this.texture = texture;
    }

    private boolean CanVisit(A3DObject obj)
    {
        if (visited.contains(obj))
            return false;
        visited.add(obj);
        return true;
    }

    public void Extract(Scene scene) throws IOException {
        if (scene.getLibrary() != null && scene.getLibrary().size() > 0)
        {
            for (A3DObject obj:scene.getLibrary())
            {
                Visit(obj);
            }
        }
        VisitNode(scene.getRootNode());
    }

    private void VisitNode(Node node) throws IOException {
        if (!CanVisit(node))
            return;
        if (texture)
        {
            for (Material mat:node.getMaterials())
            {
                VisitMaterial(mat);
            }
        }

        for (Entity entity:node.getEntities())
        {
            if (entity instanceof Mesh){
                Save((Mesh)entity, node.getName());
            }
        }

        for (Node child:node.getChildNodes())
        {
            VisitNode(child);
        }
    }

    private void VisitMaterial(Material mat) throws IOException {
        if (!CanVisit(mat))
            return;
        if (!texture)
            return;
        for (TextureSlot tslot: mat)
        {
            if (tslot.getTexture() instanceof Texture)
            {
                Save((Texture)tslot.getTexture());
            }
        }
    }

    private void Visit(A3DObject obj) throws IOException {
        if (texture && obj instanceof Texture)
        {
            Save((Texture)obj);
        }
            else if (obj instanceof Mesh)
        {
            Save((Mesh)obj, null);
        }
            else if (obj instanceof Node)
        {
            VisitNode((Node)obj);
        }
    }

    private void Save(Mesh mesh, String nodeName) throws IOException {
        if (!CanVisit(mesh))
            return;
        Scene scene = new Scene(mesh);
        MemoryStream ms=new MemoryStream();
        scene.save(ms, FileFormat.FBX7400ASCII);
        String name = nodeName;
        if (StringUtils.isBlank(name))
            name = mesh.getName();
        if (StringUtils.isBlank(name))
            name = "mesh";
        String ext = ".fbx";
        zip.Add(name + ext, ms.toArray(), true);
    }

    private void Save(Texture tex) throws IOException {
        if (tex.getContent() == null || !CanVisit(tex))
            return;
        String fileName=tex.getFileName();
        if(tex.getFileName()!=null){
            String arrFile[]=fileName.split(".");
            fileName = arrFile[0];
        }
        zip.Add(fileName, tex.getContent(), false);
    }
}

```

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Extractor" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
