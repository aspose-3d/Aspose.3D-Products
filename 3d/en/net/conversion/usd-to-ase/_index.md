---
title: Convert USD to ASE via C# 
description: Convert USD & other 3D files using .NET API
url: /net/conversion/usd-to-ase/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: ASE
otherformats: ASE 3DS STL PLY GLTF DAE DRC HTML 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert USD to ASE via C#" h2="Export USD & other 3D files using .NET Framework, .NET Core and Mono">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export USD Scene as ASE with C#" %}}
1. Load USD file using a constructor of [Scene](https://apireference.aspose.com/3d/net/aspose.threed/scene) class
2. Call [Scene.Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) method
3. Pass output file name with .ase extension as first parameter
4. Specify `ASE` field value from [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) class
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Format Conversion API for .NET" %}}
Install from command line as ```nuget install Aspose.3d``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.3D```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code for USD to ASE Conversion" gistPath="" %}}
```cs
// load the USD in an object of Scene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// save USD as a ASE 
scene.Save("output.ase", Aspose.ThreeD.FileFormat.ASE);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
