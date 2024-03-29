﻿---
title: 通過 Java 將 3MF 轉換為 STL 
weight: 1180
url: /zh-hant/java/conversion/3mf-to-stl/ 
description: 3MF 格式到 STL 文件的示例 Java 轉換代碼。使用此示例代碼在任何基於 Web 或桌面 Java 的應用程序中將 3MF 轉換為 STL。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 Java 將 3MF 轉換為 STL" h2="在沒有任何 3D 建模軟件的情況下，使用 Java 庫進行 3MF 到 STL 的轉換。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3MF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 將 3MF 轉換為 STL" %}}

 為了將 3MF 呈現為 STL，我們將使用
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API 是一個功能豐富、功能強大且易於使用的轉換API for Java 平台。您可以直接從
 [馬文](https://repository.aspose.com/3d/) 
 並通過將以下配置添加到 pom.xml 將其安裝在基於 Maven 的項目中。

{{% blocks/products/pf/agp/code-block title="存儲庫" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依賴" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="通過 Java 將 3MF 轉換為 STL 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 Java 程序員只需幾行代碼即可輕鬆地將 3MF 文件轉換為 STL。

{{% /blocks/products/pf/agp/text %}}

1. 通過 Scene 類的構造函數加載 3MF 文件1. 創建 StlSaveOptions 的實例1. 為高級轉換設置 STL 個特定屬性1. 調用 Scene.save 方法1. 傳遞帶有 STL 文件擴展名和 StlSaveOptions 對象的輸出路徑
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 Java 轉換代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 應用程序和桌面應用程序運行時環境的兼容操作系統。- 直接從 Maven 獲取最新版本的 Aspose.3D for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="3MF 到 STL Java 轉換源代碼" offSpacer="" %}}

```cs
// 在 Scene 對像中加載 3MF 
Scene document = new Scene("template.3mf");
// 創建一個 StlSaveOptions 實例 
StlSaveOptions options = new StlSaveOptions();
// 將 3MF 保存為 STL 
document.save("output.stl", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="3MF 到 STL 轉換現場演示" sectionDescription="[將 3MF 轉換為 STL](https://products.aspose.app/3d/conversion/3mf-to-stl) 立即訪問我們的現場演示網站。現場演示具有以下好處" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳您的 3MF 文件，它就會立即轉換為 STL。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您將獲得下載鏈接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 場景操作庫" %}}

 Aspose.3D 是用於加載、修改和轉換 3D 文件的 CAD 和遊戲軟件 API。 API 是獨立的，不需要任何 3D 建模或渲染軟件。可以輕鬆地將 API 用於 Discreet3DS、WavefrontOBJ、STL（ASCII，二進制）、Universal3D、FBX（ASCII，二進制）、Collada、glTF、PLY、 GLB、DirectX 和更多格式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}

3MF，3D 製造格式，應用程序使用它來將 3D 對像模型呈現給各種其他應用程序、平台、服務和打印機。它旨在避免其他 3D 文件格式（如 STL）中的限制和問題，以便與最新版本的 3D 打印機一起使用。 3MF 是一種相對較新的文件格式，由 3MF 聯盟開發和發布。它足夠豐富來完全描述模型，保留內部信息、顏色和其他特性，使其可擴展以支持 3D 打印的新創新。該格式是可擴展的，能夠被廣泛採用並且沒有困擾其他廣泛使用的文件格式的問題。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}

STL，stereolithrography 的縮寫，是一種可互換的文件格式，表示 3 維表面幾何形狀。該文件格式可用於多個領域，例如快速原型製作、3D 打印和計算機輔助製造。它將一個表面表示為一系列小三角形，稱為小平面，其中每個小平面由一個垂直方向描述，三個點表示三角形的頂點。應用程序使用結果數據來確定製造商要構建的 3D 形狀的橫截面。 STL 文件格式中沒有可用於表示顏色、紋理或其他常見 CAD 模型屬性的信息。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="您還可以將 3MF 轉換為許多其他文件格式，包括下面列出的幾種。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-3ds/" name="3MF 至 3DS" description="3D Studio DOS 網格" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-amf/" name="3MF 至 AMF" description="增材製造形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-dae/" name="3MF 至 DAE" description="數字資產交易所" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-fbx/" name="3MF 至 FBX" description="3D 格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-gltf/" name="3MF 至 GLTF" description="GL 傳輸格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-html/" name="3MF 至 HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-obj/" name="3MF 至 OBJ" description="3D 文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-ply/" name="3MF 至 PLY" description="多邊形文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-rvm/" name="3MF 至 RVM" description="AVEVA 工廠設計模型" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-u3d/" name="3MF 至 U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}