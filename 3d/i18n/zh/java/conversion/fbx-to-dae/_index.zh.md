﻿---
title: 通过 Java 将 FBX 转换为 DAE 
weight: 1930
url: /zh/java/conversion/fbx-to-dae/ 
description: 示例 Java 格式到 DAE 文件的转换代码。使用此示例代码可以在任何基于Web或桌面的应用程序中将 FBX 转换为 DAE。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 Java 将 FBX 转换为 DAE" h2="使用 Java 库进行 FBX 到 DAE 转换，无需任何 3D 建模软件。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="DAE" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 将 FBX 转换为 DAE" %}}

 为了将 FBX 渲染为 DAE，我们将使用
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API 这是一个功能丰富，功能强大且易于使用的转换 API for Java 平台。您可以直接从以下位置下载其最新版本
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 并通过将以下配置添加到pom.xml中，将其安装在基于Maven的项目中。

{{% blocks/products/pf/agp/code-block title="存储库" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://存储库
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依赖关系" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-3d</artifactId>
<version>version of aspose-3d API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 FBX 转换为 DAE 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 Java 程序员只需几行代码就可以轻松地将 FBX 文件转换为 DAE。

{{% /blocks/products/pf/agp/text %}}

1. 通过场景类的构造函数加载 FBX 文件1. 创建DaeSaveOptions实例1. 为高级转换设置 DAE 特定属性1. 调用场景。保存方法1. 传递带有 DAE 文件扩展名和DaeSaveOptions对象的输出路径
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 Java 转换代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- 适用于JSP/JSF应用程序和桌面应用程序的具有 Java 运行时环境的Microsoft Windows或兼容操作系统。- 直接从Maven获取最新版本的 Aspose.3D for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="FBX 到 DAE Java 的转换源代码" offSpacer="" %}}

```cs
// 加载场景对象中的 FBX 
Scene document = new Scene("template.fbx");
// 创建DaeSaveOptions实例 
DaeSaveOptions options = new DaeSaveOptions();
// 将 FBX 保存为 DAE 
document.save("output.dae", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="FBX 到 DAE 转换实时演示" sectionDescription="[将 FBX 转换为 DAE](https://products.aspose.app/3d/conversion/fbx-to-dae) 现在通过访问我们的现场演示网站。现场演示有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 不需要编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 FBX 文件，它将立即转换为 DAE。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 你会得到下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 场景操作库" %}}

 Aspose.3D 是一个 CAD 和游戏软件 API，用于加载、修改和转换 3D 文件。API 是独立的，不需要任何 3D 建模或渲染软件。人们可以轻松地将 API 用于 Discreet3DS 、 WavefrontOBJ 、 STL (ASCII，二进制) 、 Universal3D 、 FBX (ASCII，二进制) 、 Collada 、 glTF 、 PLY 、 GLB 、DirectX等多种格式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}

FBX，FilmBox，是一种流行的 3D 文件格式，最初由Kaydara为MotionBuilder开发。它2006年被Autodesk Inc收购，现在是许多 3D 工具使用的主要 3D 交换格式之一。FBX 有二进制文件和ASCII文件格式。该格式的建立是为了提供数字内容创建应用程序之间的互操作性。有许多工具可用于从/转换为 FBX 文件格式。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}

DAE 文件是一种数字资产交换文件格式，用于在交互式 3D 应用程序之间交换数据。此文件格式基于COLLADA (协作设计活动) XML模式，该模式是用于图形软件应用程序之间交换数字资产的开放标准XML模式。它已被ISO采纳为公开可用的规范，ISO/pAS 17506。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 FBX 转换为许多其他文件格式，包括下面列出的几种格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-3ds/" name="FBX 至 3DS" description="3D 工作室DOS网格" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-amf/" name="FBX 至 AMF" description="增材制造格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-ase/" name="FBX 至 ASE" description="2D动画文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-gltf/" name="FBX 至 GLTF" description="GL传输格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-html/" name="FBX 至 HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-obj/" name="FBX 至 OBJ" description="3D 文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-ply/" name="FBX 至 PLY" description="多边形文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-rvm/" name="FBX 至 RVM" description="AVEVA工厂设计模型" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-stl/" name="FBX 至 STL" description="可互换的 3D 曲面几何形状" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-u3d/" name="FBX 至 U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}