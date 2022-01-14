---
title: C# 3D Formats Repairing
url: /net/repairing/
description: Repair 3D formats 3ds 3mf amf ase dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x with few lines of C# code via .NET library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft® 3D Formats Repairing Via C#" h2="Repair 3D document formats without any 3D modeling and rendering software to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
Developers can easily read, repair, convert, update and control content in 3D format using 3D graphics library. The repair process is very simple. Load the source file through the instance of scene class, and then analyze the problem of 3D file and repair it. Call the save method with the relevant output format parameters.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Repair 3D files in various formats" %}}

You can repair 3D files in 3DS,3MF,AMF,ASE,DAE,DRC,DXF,FBX,GLTF,JT,OBJ,PLY,RVM,STL,U3D,USDZ,USD,VRML,X and other formats. The repair process is very simple. Load the 3D file through the scene class, analyze the problem of the file and repair it. Create the saving options using [ObjSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/objsaveoptions),Here is complete list for 3D [save format](https://apireference.aspose.com/3d/net/aspose.threed.formats) options. Moreover, Developers can easily save 3D scenes in various formats.
{{% blocks/products/pf/feature-page-summary %}}
{{% /blocks/products/pf/feature-page-summary  %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".3ds";

// List of file issues
var issuesToRepair = new List<IssueType>();

//Add question list
switch (question)
        {
            case "PartHasHoles":
                issuesToRepair.Add(IssueType.PartHasHoles);
                    break;
            case "PartHasNoNormal":
                issuesToRepair.Add(IssueType.PartHasNoNormal);
                    break;
            case "PartHasNoThickness":
                issuesToRepair.Add(IssueType.PartHasNoThickness);
                    break;
            case "PartHasReversedNormals":
                issuesToRepair.Add(IssueType.PartHasReversedNormals);
                    break;
            case "SceneIsNotCentered":
                issuesToRepair.Add(IssueType.SceneIsNotCentered);
                    break;
            case "SceneIsNotMerged":
                issuesToRepair.Add(IssueType.SceneIsNotMerged);
                    break;
        }

//Fix problems with files
    using (var fs = new FileStream("analyze-result.sd", FileMode.Open))
        {
            var sd = SceneDiagnoser.LoadFromStream(fs);
            var result = sd.Repair(issuesToRepair);
            Scene scene = new Scene(result);
            scene.Save(output,FileFormat.STLASCII); 
        }

```

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Repairing">}}