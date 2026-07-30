---
title: C# 3D 格式提取资源
url: /zh/net/extractor/
description: 从 3ds、3mf、amf、ase、att、dae、drc、dxf、fbx、gltf、jt、obj、ply、rvm、stl、u3d、usdz、usd、vrml、x 等 3D 格式提取资源，使用几行 C# 代码通过 .NET 库。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D 格式提取资源 通过 C#" h2="无需任何 3D 建模和渲染软件，即可提取 3D 文档格式中的资源，以构建跨平台 .NET 应用程序。" >}}

{{% blocks/products/pf/feature-page-summary %}}
开发人员可以使用 3D 库轻松提取 3D 文件资源。 API 支持的格式包括 WavefrontOBJ、Discreet3DS、STL（ASCII、二进制）、FBX（ASCII、二进制）、通用 3D、Collada、GLB、glTF、PLY、DirectX、Google Draco 格式等。 提取过程很简单，通过 [场景类](https://apireference.aspose.com/3d/net/aspose.threed/scene) 的实例加载源文件，创建归档类并处理提取资源类，然后调用适用于相关输出格式参数的保存方法。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="提取 3D 场景资源到各种格式" %}}
开发人员可以按照上述相同过程轻松提取 3D 文件的资源。 考虑一些示例，例如 **3DS 到 FBX 提取器**。 通过场景类对象加载 3DS 文件。 使用 [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions) 创建保存选项，并使用输出文件路径和 fbx 选项参数调用场景保存方法。 API 具有适当的选项类，用于保存到相关类，例如 [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) 等。 这里是完整的 3D [提取器格式](https://apireference.aspose.com/3d/net/aspose.threed.formats) 选项列表。

{{% blocks/products/pf/feature-page-code h3="C# 代码用于 3DS 到 FBX 提取资源" %}}

{{< gist "aspose-3d-gists" "9563193e834f0087b554c83130fcf7c7" "Examples-CSharp-Extractor-products.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Extractor" >}}
{{< /blocks/products/pf/feature-page-wrap >}}