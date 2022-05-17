---
title: C# 3D Formats Watermark Verification
url: /net/verify-watermark/
description: Add blind Watermark Verification to 3D format 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x via .NET library using a few lines of C# code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D Formats Watermark Verification Via C#" h2="Add blind Watermark Verification to 3D document formats without any 3D modeling and rendering software to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
Developers can use the 3D library to verify blind watermarks for 3D files. The few formats supported by the API are WavefrontOBJ, Discreet3DS, STL (ASCII, Binary), FBX (ASCII, Binary), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco formats, etc. The process of validating a blind watermark is simple. Load the source file through the instance of [Scene Class](https://apireference.aspose.com/3d/net/aspose.threed/scene), and then implement the watermark verification through the DecodeWatermark method of the 3D library.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Add blind Watermark Verification to 3D Scene to various formats" %}}
Developers can easily go through the same process listed above to verify blind watermarks in 3d files. Consider a few examples, such as **3DS File watermark verification**. Load 3DS files via scene class objects. Create save options using [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions) to create save options and call the scene save method with the output file path and fbx options as parameters. API has appropriate options classes for saving into relevant classes like [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) and more. Here is the full list of 3D [Watermark Validation Formats](https://apireference.aspose.com/3d/net/aspose.threed.formats) options.

{{% blocks/products/pf/feature-page-code h3="C# Code for 3DS file Watermark Verification" %}}
```cs

//Source files that need to be watermarked for verification
string file = "template.3ds";

// create an instance of Scene
Scene scene = new Scene(file);
string text =null;

//Add password to verify watermark by DecodeWatermark method
try
{
    scene.RootNode.Accept((Node node) =>
    {
        var mesh = node.GetEntity<Mesh>();
        if (mesh != null)
        {
            text = Watermark.DecodeWatermark(mesh, "1234");
            if (text != null)
                return false;
            }
            return true;
    });
}
catch (UnauthorizedAccessException)
{
    return "Password error";
}

//Returns null if this file has no watermark,If there is a watermark, return the watermark content
return text;


```

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Watermark Verification" >}}