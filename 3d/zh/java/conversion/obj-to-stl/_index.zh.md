﻿---
title: 通过 Java 将 OBJ 转换为 STL 
weight: 2860
url: /zh/java/conversion/obj-to-stl/ 
description: OBJ 格式到 STL 文件的示例 Java 转换代码。使用此示例代码在任何基于 Web 或桌面 Java 的应用程序中将 OBJ 转换为 STL。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 Java 将 OBJ 转换为 STL" h2="在没有任何 3D 建模软件的情况下，使用 Java 库进行 OBJ 到 STL 的转换。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 将 OBJ 转换为 STL" %}}

 为了将 OBJ 呈现为 STL，我们将使用
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API 是一个功能丰富、功能强大且易于使用的转换API for Java 平台。您可以直接从
 [马文](https://repository.aspose.com/3d/) 
 并通过将以下配置添加到 pom.xml 将其安装在基于 Maven 的项目中。

{{% blocks/products/pf/agp/code-block title="存储库" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依赖" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 OBJ 转换为 STL 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 Java 程序员只需几行代码即可轻松地将 OBJ 文件转换为 STL。

{{% /blocks/products/pf/agp/text %}}

1. 通过 Scene 类的构造函数加载 OBJ 文件1. 创建 StlSaveOptions 的实例1. 为高级转换设置 STL 个特定属性1. 调用 Scene.save 方法1. 传递带有 STL 文件扩展名和 StlSaveOptions 对象的输出路径
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 Java 转换代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 应用程序和桌面应用程序运行时环境的兼容操作系统。- 直接从 Maven 获取最新版本的 Aspose.3D for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OBJ 到 STL Java 转换源代码" offSpacer="" %}}

```cs
// 在 Scene 对象中加载 OBJ 
Scene document = new Scene("template.obj");
// 创建一个 StlSaveOptions 实例 
StlSaveOptions options = new StlSaveOptions();
// 将 OBJ 保存为 STL 
document.save("output.stl", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="OBJ 到 STL 转换现场演示" sectionDescription="[将 OBJ 转换为 STL](https://products.aspose.app/3d/conversion/obj-to-stl) 立即访问我们的现场演示网站。现场演示具有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 OBJ 文件，它就会立即转换为 STL。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将获得下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 场景操作库" %}}

 Aspose.3D 是用于加载、修改和转换 3D 文件的 CAD 和游戏软件 API。 API 是独立的，不需要任何 3D 建模或渲染软件。可以轻松地将 API 用于 Discreet3DS、WavefrontOBJ、STL（ASCII，二进制）、Universal3D、FBX（ASCII，二进制）、Collada、glTF、PLY、 GLB、DirectX 和更多格式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

Wavefront 的 Advanced Visualizer 应用程序使用 OBJ 文件来定义和存储几何对象。通过 OBJ 文件可以实现几何数据的前后传输。 OBJ 格式支持点、线、纹理顶点、面和自由形式几何（曲线和曲面）等多边形几何。此格式不支持动画或与场景的灯光和位置相关的信息。 OBJ 文件通常是由 CAD（计算机辅助设计）生成的 3D 建模过程的最终产品。存储顶点的默认顺序是逆时针方向，避免显式声明面法线。尽管 OBJ 文件在注释行中声明了比例信息，但尚未为 OBJ 坐标声明任何单位。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}

STL，stereolithrography 的缩写，是一种可互换的文件格式，表示 3 维表面几何形状。该文件格式可用于多个领域，例如快速原型制作、3D 打印和计算机辅助制造。它将一个表面表示为一系列小三角形，称为小平面，其中每个小平面由一个垂直方向描述，三个点表示三角形的顶点。应用程序使用结果数据来确定制造商要构建的 3D 形状的横截面。 STL 文件格式中没有可用于表示颜色、纹理或其他常见 CAD 模型属性的信息。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 OBJ 转换为许多其他文件格式，包括下面列出的几种。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-3ds/" name="OBJ 至 3DS" description="3D Studio DOS 网格" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-amf/" name="OBJ 至 AMF" description="增材制造形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-ase/" name="OBJ 至 ASE" description="二维动画文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-dae/" name="OBJ 至 DAE" description="数字资产交易所" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-fbx/" name="OBJ 至 FBX" description="3D 格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-gltf/" name="OBJ 至 GLTF" description="GL 传输格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-html/" name="OBJ 至 HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-obj/" name="OBJ 至 OBJ" description="3D 文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-ply/" name="OBJ 至 PLY" description="多边形文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-rvm/" name="OBJ 至 RVM" description="AVEVA 工厂设计模型" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-u3d/" name="OBJ 至 U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}