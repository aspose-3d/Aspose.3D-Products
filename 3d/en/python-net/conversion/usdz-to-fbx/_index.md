---
title: Convert USDZ to FBX via Python 
description: Convert USDZ & other 3D files using .NET API
url: /python-net/conversion/usdz-to-fbx/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: FBX
otherformats: GLTF PLY FBX STL JT AMF DXF DAE 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert USDZ to FBX via Python" h2="Export USDZ & other 3D files using .NET Framework, .NET Core and Mono">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export USDZ Scene as FBX with C#" %}}
1. Load USDZ file using a from_file of [Scene](https://apireference.aspose.com/3d/net/aspose.threed/scene) class
2. Call [Scene.save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) method
3. Pass output file name with .fbx extension as first parameter
4. Specify `FBX7700Binary` field value from [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) class
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Format Conversion API for Python via .NET" %}}
Install from command line as ```pip install aspose-3d``` .

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/3d/python-net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code for USDZ to FBX Conversion" gistPath="" %}}
```cs
# load the USDZ in an object of Scene 
scene = aspose.threed.Scene.from_file("template.usdz");
# save USDZ as a FBX 
scene.save("output.fbx", aspose.threed.FileFormat.FBX7700Binary);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}