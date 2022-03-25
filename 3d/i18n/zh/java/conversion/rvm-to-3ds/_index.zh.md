﻿---
title: 通过 Java 将 RVM 转换为 3DS 
weight: 2670
url: /zh/java/conversion/rvm-to-3ds/ 
description: 示例 Java 格式到 3DS 文件的转换代码。使用此示例代码可以在任何基于Web或桌面的应用程序中将 RVM 转换为 3DS。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 Java 将 RVM 转换为 3DS" h2="使用 Java 库进行 RVM 到 3DS 转换，无需任何 3D 建模软件。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="RVM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 将 RVM 转换为 3DS" %}}

 为了将 RVM 渲染为 3DS，我们将使用
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

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 RVM 转换为 3DS 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 Java 程序员只需几行代码就可以轻松地将 RVM 文件转换为 3DS。

{{% /blocks/products/pf/agp/text %}}

1. 通过场景类的构造函数加载 RVM 文件1. 创建3个dsSaveOptions的实例1. 为高级转换设置 3DS 特定属性1. 调用场景。保存方法1. 传递具有 3DS 文件扩展名和3个dsSaveOptions对象的输出路径
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 Java 转换代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- 适用于JSP/JSF应用程序和桌面应用程序的具有 Java 运行时环境的Microsoft Windows或兼容操作系统。- 直接从Maven获取最新版本的 Aspose.3D for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="RVM 到 3DS Java 的转换源代码" offSpacer="" %}}

```cs
// 加载场景对象中的 RVM 
Scene document = new Scene("template.rvm");
// 创建3个dsSaveOptions的实例 
Discreet3dsSaveOptions options = new Discreet3dsSaveOptions();
// 将 RVM 保存为 3DS 
document.save("output.3ds", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="RVM 到 3DS 转换实时演示" sectionDescription="[将 RVM 转换为 3DS](https://products.aspose.app/3d/conversion/rvm-to-3ds) 现在通过访问我们的现场演示网站。现场演示有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 不需要编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 RVM 文件，它将立即转换为 3DS。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 你会得到下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 场景操作库" %}}

 Aspose.3D 是一个 CAD 和游戏软件 API，用于加载、修改和转换 3D 文件。API 是独立的，不需要任何 3D 建模或渲染软件。人们可以轻松地将 API 用于 Discreet3DS 、 WavefrontOBJ 、 STL (ASCII，二进制) 、 Universal3D 、 FBX (ASCII，二进制) 、 Collada 、 glTF 、 PLY 、 GLB 、DirectX等多种格式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="RVM" readMoreLink="https://docs.fileformat.com/3d/rvm/" >}}

RVM 数据文件与AVEVA PDMS相关。RVM 文件是AVEVA工厂设计管理系统模型。AVEVA的工厂设计管理系统 (PDMS) 是使用以数据为中心的技术来管理项目的最流行的 3D 设计系统。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}

扩展名为 3DS 的文件表示Autodesk 3D Studio使用的 3D Studio (DOS) 网格文件格式。Autodesk 3D Studio自20世纪90年代以来一直进入 3D 文件格式市场，现在已发展为 3D Studio MAX，用于处理 3D 建模，动画和渲染。3DS 文件包含用于 3D 表示场景和图像的数据，并且是用于 3D 数据导入和导出的流行文件格式之一。它考虑诸如摄像机位置，网格数据，照明信息，视口配置，平滑组数据，位图引用和属性之类的信息，以创建用于渲染场景的顶点和多边形。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 RVM 转换为许多其他文件格式，包括下面列出的几种格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-amf/" name="RVM 至 AMF" description="增材制造格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-ase/" name="RVM 至 ASE" description="2D动画文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-dae/" name="RVM 至 DAE" description="数字资产交换" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-fbx/" name="RVM 至 FBX" description="3D 格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-gltf/" name="RVM 至 GLTF" description="GL传输格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-html/" name="RVM 至 HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-obj/" name="RVM 至 OBJ" description="3D 文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-ply/" name="RVM 至 PLY" description="多边形文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-stl/" name="RVM 至 STL" description="可互换的 3D 曲面几何形状" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-u3d/" name="RVM 至 U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}