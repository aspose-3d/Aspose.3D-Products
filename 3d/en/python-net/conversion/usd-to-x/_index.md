---
title: Convert USD to X via Python 
description: Convert USD & other 3D files using .NET API
url: /python-net/conversion/usd-to-x/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: X
otherformats: PLY FBX AMF ASE 3DS JT HTML STL 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert USD to X via Python" h2="Export USD & other 3D files using .NET Framework, .NET Core and Mono">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export USD Scene as X with C#" %}}
1. Load USD file using a from_file of [Scene](https://apireference.aspose.com/3d/python-net/aspose.threed/scene) class
2. Call [Scene.save](https://apireference.aspose.com/3d/python-net/aspose.threed/scene/methods/save/index) method
3. Pass output file name with .x extension as first parameter
4. Specify `XBinary` field value from [FileFormat](https://apireference.aspose.com/3d/python-net/aspose.threed/fileformat/fields/index) class
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Format Conversion API for Python via .NET" %}}
Install from command line as ```pip install aspose-3d``` .

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/3d/python-net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code for USD to X Conversion" gistPath="" %}}
```cs
# load the USD in an object of Scene 
scene = aspose.threed.Scene.from_file("template.usd");
# save USD as a X 
scene.save("output.x", aspose.threed.FileFormat.XBinary);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
