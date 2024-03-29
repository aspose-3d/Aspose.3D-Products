﻿---
title: .NET aracılığıyla DAE Dosya Biçimlerinden Varlıkları Çıkarın 
weight: 830
url: /tr/net/extractor/dae/ 
description: .NET Framework, .NET Core, Mono üzerindeki DAE belgelerindeki varlıkları yüklemek, oluşturmak ve eklemek için C# kaynak kodu.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# aracılığıyla DAE öğesinden Varlıkları Çıkarın" h2="Sunucu tarafı API\'lerini kullanarak DAE dosyadan Varlıkları Çıkarmak için kendi .NET uygulamalarınızı oluşturun." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DAE" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DAE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanılarak DAE Dosyasından Varlıklar Nasıl Çıkarılır" %}}

 DAE dosyasından varlık çıkarmak için kullanacağız
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 C# platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir API olan API, özüt varlıklarla birlikte kullanılır. Açık
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 paket yöneticisi, ara
 **Aspose.3D** 
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yöneticisi Konsol Komutu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# aracılığıyla DAE öğesinden Varlıkları Çıkarma Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D, geliştiricilerin yalnızca birkaç satır kodla DAE dosyasından varlıkları çıkarmasını kolaylaştırır.

{{% /blocks/products/pf/agp/text %}}

- DAE dosyasını Scene sınıfının yapıcısı aracılığıyla yükleyin- Zip dosyası formatı nesnesini çıktı dosyası formatı olarak oluşturun- Arşiv sınıfı oluşturun ve özüt varlık sınıfını işleyin- Extract yöntemini çağırın ve dosyayı kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET, tüm büyük işletim sistemlerinde desteklenir. Sadece aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono ile uyumlu bir işletim sistemi- Microsoft Visual Studio gibi geliştirme ortamı- Projenizde referans verilen Aspose.3D for .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DAE\'den Varlıkları Ayıklamak için C# kodu" offSpacer="" %}}

```cs

//Varlıkları ayıklaması gereken kaynak dosyalar
string file = "template.dae";
Scene scene = new Scene(file);  

//Çıktı sıkıştırılmış bir dosya biçimindedir ve Dizin mevcut bir klasörün adını temsil eder
var zipOutput = Path.Combine("Directory", "OutputFile.zip");
using var output = new FileStream(zipOutput, FileMode.Create);
using var za = new Zip(output);

//Varlık çıkarma işlemlerini gerçekleştirmek için Extract yöntemini çağırın
Extract(scene,za,true);

//Çağrılabilir Çıkarma yöntemi, Parametre dokusu şunları gösterir: doku çıkarılıp çıkarılmayacağı
private void Extract(Scene scene, Zip za,bool texture)
{
    var extractor = new Extractor(za,texture);
    extractor.Extract(scene);
}

//Sıkıştırılmış bir dosya işleme sınıfı oluşturun
class Zip : IDisposable
{
    private ZipArchive archive;
    private HashSet<string> entries = new HashSet<string>();

    public Zip(Stream stream)
    {
        archive = new ZipArchive(stream, ZipArchiveMode.Create);
    }
    public void Dispose()
    {
        archive.Dispose();
    }

    public void Add(string fileName, byte[] content, bool enableCompression)
    {
        var entryName = PickName(fileName);
        var compressionLevel = enableCompression ? CompressionLevel.Fastest : CompressionLevel.NoCompression;
        var entry = archive.CreateEntry(entryName, compressionLevel);
        using var stream = entry.Open();
        stream.Write(content, 0, content.Length);
    }
    
    private string PickName(string fileName)
    {
        if (!entries.Contains(fileName))
        {
            entries.Add(fileName);
            return fileName;
        }
        var baseName = Path.GetFileNameWithoutExtension(fileName);
        var ext = Path.GetExtension(fileName);
        for (var idx = 2; ; idx++)
        {
            var newName = baseName + "_" + idx;
            if (!string.IsNullOrEmpty(ext))
                newName += ext;
            if (entries.Contains(newName))
                continue;
            entries.Add(newName);
            return newName;
        }
    }
}

//Bir varlık çıkarma işleme sınıfı oluşturun
class Extractor
{
    private Zip zip;
    private bool texture;
    HashSet<A3DObject> visited = new HashSet<A3DObject>();
    public Extractor(Zip zip,bool texture)
    {
        this.zip = zip;
        this.texture = texture;
    }

    private bool CanVisit(A3DObject obj)
    {
        if (visited.Contains(obj))
            return false;
        visited.Add(obj);
        return true;
    }
    public void Extract(Scene scene)
    {
        if (scene.Library != null && scene.Library.Count > 0)
        {
            foreach (var obj in scene.Library)
            {
                Visit(obj);
            }
        }
        VisitNode(scene.RootNode);
    }
    private void VisitNode(Node node)
    {
        if (!CanVisit(node))
            return;
        if (texture)
        {
            foreach (var mat in node.Materials)
            {
                VisitMaterial(mat);
            }
        }

        foreach (var entity in node.Entities)
        {
            if (entity is Mesh)
                Save((Mesh)entity, node.Name);
        }
        
        foreach (var child in node.ChildNodes)
        {
            VisitNode(child);
        }
    }
    private void VisitMaterial(Material mat)
    {
        if (!CanVisit(mat))
            return;
        if (!texture)
            return;
        foreach (var tslot in mat)
        {
            if (tslot.Texture is Texture)
            {
                Save((Texture)tslot.Texture);
            }
        }
    }
    private void Visit(A3DObject obj)
    {
        if (texture && obj is Texture)
        {
            Save((Texture)obj);
        }
        else if (obj is Mesh)
        {
            Save((Mesh)obj, null);
        }
        else if (obj is Node)
        {
            VisitNode((Node)obj);
        }
    }
    private void Save(Mesh mesh, string? nodeName)
    {
        if (!CanVisit(mesh))
            return;
        Scene scene = new Scene(mesh);
        using (var ms = new MemoryStream())
        {
            scene.Save(ms, FileFormat.FBX7400ASCII);
            var name = nodeName;
            if (string.IsNullOrEmpty(name))
                name = mesh.Name;
            if (string.IsNullOrEmpty(name))
                name = "mesh";
            var ext = ".fbx";
            zip.Add(name + ext, ms.ToArray(), true);
        }
    }
    private void Save(Texture tex)
    {
        if (tex.Content == null || !CanVisit(tex))
            return;
        var fileName = tex.FileName != null ? Path.GetFileName(tex.FileName) : null;
        zip.Add(fileName, tex.Content, false);
    }
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.3D for .NET API hakkında" %}}

 Aspose.3D, 3D dosyalarını yüklemek, değiştirmek ve dönüştürmek için kullanılan bir CAD ve Oyun Yazılımıdır API. API bağımsızdır ve herhangi bir 3D modelleme veya işleme yazılımı gerektirmez. Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY için API kolayca kullanılabilir, GLB, DirectX ve diğer biçimler. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DAE\'den Varlıkları Çıkarmak için Ücretsiz Uygulama" sectionDescription="için canlı demolarımızı kontrol edin [Çıkarıcı DAE](https://products.aspose.app/3d/extractor/dae) aşağıdaki faydaları ile." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Hiçbir şey indirmenize veya kurmanıza gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Kod yazmaya veya derlemeye gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece DAE dosyasını yükleyin ve \"Çıkar\" düğmesine basın" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Gerekirse bağlantıdan DAE dosyasını indirin" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}
DAE dosyası, etkileşimli 3D uygulamaları arasında veri alışverişi için kullanılan bir Dijital Varlık Değişimi dosya biçimidir. Bu dosya formatı, dijital varlıkların grafik yazılım uygulamaları arasında değişimi için açık standart bir XML şeması olan COLLADA (COLLAborative Design Activity) XML şemasına dayanmaktadır. ISO tarafından halka açık bir spesifikasyon olarak ISO/pAS 17506 olarak kabul edilmiştir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Varlıkları Biçimlerden Ayıklamak için Desteklenen Diğer Uygulama" subTitle="C# kullanarak One, aşağıdakiler de dahil olmak üzere diğer birçok dosya biçiminden varlıkları ayıklayabilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3mf/" name="3MF" description="3D Üretim Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/amf/" name="AMF" description="Eklemeli Üretim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ase/" name="ASE" description="2D Animasyon Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3ds/" name="3DS" description="3D Studio Mesh Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/dxf/" name="DXF" description="Çizim Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/fbx/" name="FBX" description="3D Biçim" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/glb/" name="GLB" description="3D Dosya İkili Temsili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/gltf/" name="GLTF" description="GL İletim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/jt/" name="JT" description="Jüpiter Mozaik Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/obj/" name="OBJ" description="3D Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ply/" name="PLY" description="Çokgen Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/rvm/" name="RVM" description="AVEVA Fabrika Tasarım Modeli" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/stl/" name="STL" description="Değiştirilebilir 3D Yüzey Geometrisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/vrml/" name="VRML" description="Sanal Gerçeklik Modelleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/x/" name="x" description="DirectX Model Resmi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usd/" name="USD" description="Evrensel Sahne Açıklaması" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usdz/" name="USDZ" description="Evrensel Sahne Tanımı Zip Arşivi" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}