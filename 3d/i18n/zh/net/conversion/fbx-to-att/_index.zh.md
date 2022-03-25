﻿---
title: 通过 C# 将 FBX 转换为 ATT 
url: /zh/net/conversion/fbx-to-att/ 
description: FBX 到 ATT C# 转换的示例代码。在VB.NET，Asp.NET 或任何基于 .NET 的应用程序中使用 API 示例代码将批处理 FBX 文件转换为 ATT。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C# 将 FBX 转换为 ATT" h2="将 FBX 渲染为 ATT，无需任何 3D 建模和渲染软件。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ATT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 将 FBX 转换为 ATT" %}}

 为了将 FBX 转换为 ATT，我们将使用
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API 这是一个功能丰富，功能强大且易于使用的文档操作和转换 API，适用于 C# 平台。打开
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 包管理器，搜索
 Aspose.3D 
 并安装。您也可以使用包管理器控制台中的以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C# 将 FBX 转换为 ATT 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 程序员只需几行代码就可以轻松地将 FBX 文件加载和转换为 ATT。

{{% /blocks/products/pf/agp/text %}}

1. 通过场景类的构造函数加载 FBX 文件1. 创建AmfSaveOptions实例1. 为高级转换设置 ATT 特定属性1. 调用场景。保存方法1. 传递带有 ATT 文件扩展名和AttSaveOptions对象的输出路径1. 检查指定路径处的结果 ATT 文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 .NET 转换代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows或具有 .NET 框架，.NET 核心，Mono 的兼容操作系统。- 像微软Visual Studio这样的开发环境。- 项目中引用的 Aspose.3D for .NET DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此示例代码显示 FBX 到 ATT C# 的转换" offSpacer="" %}}

```cs
// 加载场景对象中的 FBX 
var document = new Aspose.ThreeD.Scene("template.fbx");
// 创建AttSaveOptions实例 
var options = new Aspose.ThreeD.Formats.AttSaveOptions();
// 将 FBX 保存为 ATT 
document.Save("output.att", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="免费应用程序将 FBX 转换为 ATT" sectionDescription="查看我们的实时演示 [FBX 到 ATT 转换](https://products.aspose.app/3d/conversion/fbx-to-att) 有以下好处。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 不需要下载或设置任何东西。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 不需要编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 FBX 文件，然后点击 “转换” 按钮。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将立即获得结果 ATT 文件的下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 一个 3D 文件处理库，用于操作 3D 文件，而无需任何建模和渲染软件。3D API 支持 Discreet3DS 、 WavefrontOBJ 、 FBX (ASCII，二进制) 、 STL (ASCII，二进制) 、 Universal3D 、 Collada 、 glTF 、 GLB 、 PLY 、DirectX、 Google Draco 文件格式和更多。开发人员可以轻松创建，阅读，转换，修改和控制 3D 文档格式的实质。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX，FilmBox，是一种流行的 3D 文件格式，最初由Kaydara为MotionBuilder开发。它2006年被Autodesk Inc收购，现在是许多 3D 工具使用的主要 3D 交换格式之一。FBX 有二进制文件和ASCII文件格式。该格式的建立是为了提供数字内容创建应用程序之间的互操作性。有许多工具可用于从/转换为 FBX 文件格式。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="att" readMoreLink="#" >}}


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 FBX 转换为许多其他文件格式，包括下面列出的几种格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-3ds/" name="FBX 至 3DS" description="3D 工作室DOS网格" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-amf/" name="FBX 至 AMF" description="增材制造格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-dae/" name="FBX 至 DAE" description="数字资产交换" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-html/" name="FBX 至 HTML" description="超文本标记语言" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-obj/" name="FBX 至 OBJ" description="3D 文件格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-pdf/" name="FBX 至 PDF" description="可移植文档格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-ply/" name="FBX 至 PLY" description="多边形文件格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-rvm/" name="FBX 至 RVM" description="AVEVA工厂设计模型" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-stl/" name="FBX 至 STL" description="可互换的 3D 曲面几何形状" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-u3d/" name="FBX 至 U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}