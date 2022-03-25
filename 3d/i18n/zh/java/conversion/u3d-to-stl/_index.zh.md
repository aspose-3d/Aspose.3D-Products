﻿---
title: 通过 Java 将 U3D 转换为 STL 
weight: 720
url: /zh/java/conversion/u3d-to-stl/ 
description: 示例 Java 格式到 STL 文件的转换代码。使用此示例代码可以在任何基于Web或桌面的应用程序中将 U3D 转换为 STL。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 Java 将 U3D 转换为 STL" h2="使用 Java 库进行 U3D 到 STL 转换，无需任何 3D 建模软件。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="U3D" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 将 U3D 转换为 STL" %}}

 为了将 U3D 渲染为 STL，我们将使用
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

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 U3D 转换为 STL 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 Java 程序员只需几行代码就可以轻松地将 U3D 文件转换为 STL。

{{% /blocks/products/pf/agp/text %}}

1. 通过场景类的构造函数加载 U3D 文件1. 创建StlSaveOptions实例1. 为高级转换设置 STL 特定属性1. 调用场景。保存方法1. 传递带有 STL 文件扩展名的输出路径 & StlSaveOptions的对象
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 Java 转换代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- 适用于JSP/JSF应用程序和桌面应用程序的具有 Java 运行时环境的Microsoft Windows或兼容操作系统。- 直接从Maven获取最新版本的 Aspose.3D for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="U3D 到 STL Java 的转换源代码" offSpacer="" %}}

```cs
// 加载场景对象中的 U3D 
Scene document = new Scene("template.u3d");
// 创建StlSaveOptions实例 
StlSaveOptions options = new StlSaveOptions();
// 将 U3D 保存为 STL 
document.save("output.stl", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="U3D 到 STL 转换实时演示" sectionDescription="[将 U3D 转换为 STL](https://products.aspose.app/3d/conversion/u3d-to-stl) 现在通过访问我们的现场演示网站。现场演示有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 不需要编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 U3D 文件，它将立即转换为 STL。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 你会得到下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 场景操作库" %}}

 Aspose.3D 是一个 CAD 和游戏软件 API，用于加载、修改和转换 3D 文件。API 是独立的，不需要任何 3D 建模或渲染软件。人们可以轻松地将 API 用于 Discreet3DS 、 WavefrontOBJ 、 STL (ASCII，二进制) 、 Universal3D 、 FBX (ASCII，二进制) 、 Collada 、 glTF 、 PLY 、 GLB 、DirectX等多种格式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}

U3D (Universal 3D) 是用于 3D 计算机图形的压缩文件格式和数据结构。它包含 3D 模型信息，例如三角形网格，照明，阴影，运动数据，带有颜色和结构的线和点。该格式在2005年8月中被接受为ECMA-363标准。3D PDF 文档支持 U3D 对象嵌入，可以在Adobe Reader (版本7及以上) 中查看。考虑到建立三维数据存储和交换的通用标准的目的，制定了 U3D 格式。但是，该格式在 3D PDF 的编码中找到了其主要用途，而不是用作交换格式。Acrobat 3D 在转换为 PDF 时将支持的 3D 文件类型转换为 U3D 或PRC。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}

STL，stereolitrography的缩写，是一种可互换的文件格式，表示3维表面几何形状。文件格式在快速原型制作，3D 打印和计算机辅助制造等多个领域中找到了它的用法。它将表面表示为一系列小三角形，称为小面，其中每个小面由垂直方向和代表三角形顶点的三个点描述。应用程序使用结果数据来确定要由fabber构建的 3D 形状的横截面。在 STL 文件格式中没有可用的信息来表示颜色，纹理或其他常见的 CAD 模型属性。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 U3D 转换为许多其他文件格式，包括下面列出的几种格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/u3d-to-3ds/" name="U3D 至 3DS" description="3D 工作室DOS网格" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/u3d-to-amf/" name="U3D 至 AMF" description="增材制造格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/u3d-to-ase/" name="U3D 至 ASE" description="2D动画文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/u3d-to-dae/" name="U3D 至 DAE" description="数字资产交换" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/u3d-to-fbx/" name="U3D 至 FBX" description="3D 格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/u3d-to-gltf/" name="U3D 至 GLTF" description="GL传输格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/u3d-to-html/" name="U3D 至 HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/u3d-to-obj/" name="U3D 至 OBJ" description="3D 文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/u3d-to-ply/" name="U3D 至 PLY" description="多边形文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/u3d-to-rvm/" name="U3D 至 RVM" description="AVEVA工厂设计模型" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}