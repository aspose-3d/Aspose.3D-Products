﻿---
title: 通过 C# 将 OBJ 转换为 GLB 
url: /zh/net/conversion/obj-to-glb/ 
description: OBJ 到 GLB C# 转换的示例代码。使用 API 示例代码在 VB.NET、Asp.NET 或任何基于 .NET 的应用程序中将 OBJ 文件批量转换为 GLB。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C# 将 OBJ 转换为 GLB" h2="将 OBJ 渲染为 GLB，无需任何 3D 建模和渲染软件。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 将 OBJ 转换为 GLB" %}}

 为了将 OBJ 转换为 GLB，我们将使用
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API 是一个功能丰富、功能强大且易于使用的文档操作和转换 API C# 平台。打开
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 包管理器，搜索
 Aspose.3D 
 并安装。您也可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C# 将 OBJ 转换为 GLB 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 程序员只需几行代码即可轻松加载 OBJ 文件并将其转换为 GLB。

{{% /blocks/products/pf/agp/text %}}

1. 通过 Scene 类的构造函数加载 OBJ 文件1. 创建 AmfSaveOptions 的实例1. 为高级转换设置 GLB 个特定属性1. 调用 Scene.Save 方法1. 传递带有 GLB 文件扩展名和 StlSaveOptions 对象的输出路径1. 检查指定路径的结果 GLB 文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 .NET 转换代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 .NET Framework、.NET Core、Mono 的兼容操作系统。- Microsoft Visual Studio 等开发环境。- Aspose.3D for .NET 项目中引用的 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此示例代码显示 OBJ 到 GLB C# 转换" offSpacer="" %}}

```cs
// 在 Scene 对象中加载 OBJ 
var document = new Aspose.ThreeD.Scene("template.obj");
// 创建 GltfSaveOptions 的实例 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions(FileContentType.Binary);
// 将 OBJ 保存为 GLB 
document.Save("output.glb", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="将 OBJ 转换为 GLB 的免费应用程序" sectionDescription="查看我们的现场演示 [OBJ 到 GLB 的转换](https://products.aspose.app/3d/conversion/obj-to-glb) 具有以下好处。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载或设置任何东西。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 OBJ 文件并点击“转换”按钮。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将立即获得生成的 GLB 文件的下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D 文件处理库，无需任何建模和渲染软件即可操作 3D 文件。 3D API 支持 Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), GLB (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY、DirectX、Google Draco 文件格式等。开发人员可以轻松地创建、读取、转换、修改和控制 3D 文档格式的内容。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
Wavefront 的 Advanced Visualizer 应用程序使用 OBJ 文件来定义和存储几何对象。通过 OBJ 文件可以实现几何数据的前后传输。 OBJ 格式支持点、线、纹理顶点、面和自由形式几何（曲线和曲面）等多边形几何。此格式不支持动画或与场景的灯光和位置相关的信息。 OBJ 文件通常是由 CAD（计算机辅助设计）生成的 3D 建模过程的最终产品。存储顶点的默认顺序是逆时针方向，避免显式声明面法线。尽管 OBJ 文件在注释行中声明了比例信息，但尚未为 OBJ 坐标声明任何单位。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB 是以 GL 传输格式 (glTF) 保存的 3D 模型的二进制文件格式表示。有关 3D 模型的信息，例如二进制格式的节点层次结构、相机、材质、动画和网格。此二进制格式将 glTF 资产（JSON、.bin 和图像）存储在二进制 blob 中。它还避免了在 glTF 的情况下发生的文件大小增加的问题。 GLB 文件格式带来紧凑的文件大小、快速加载、完整的 3D 场景表示以及进一步开发的可扩展性。该格式使用 model/gltf-binary 作为 MIME 类型。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
