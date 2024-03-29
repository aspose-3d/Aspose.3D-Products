﻿---
title: 通過 Java 將 DRC 轉換為 OBJ 
url: /zh-hant/java/conversion/drc-to-obj/ 
description: DRC 格式到 OBJ 文件的示例 Java 轉換代碼。使用此示例代碼在任何基於 Web 或桌面 Java 的應用程序中將 DRC 轉換為 OBJ。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 Java 將 DRC 轉換為 OBJ" h2="在沒有任何 3D 建模軟件的情況下，使用 Java 庫進行 DRC 到 OBJ 的轉換。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 將 DRC 轉換為 OBJ" %}}

 為了將 DRC 呈現為 OBJ，我們將使用
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

{{% blocks/products/pf/agp/feature-section-col title="通過 Java 將 DRC 轉換為 OBJ 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 Java 程序員只需幾行代碼即可輕鬆地將 DRC 文件轉換為 OBJ。

{{% /blocks/products/pf/agp/text %}}

1. 通過 Scene 類的構造函數加載 DRC 文件1. 創建 ObjSaveOptions 的實例1. 為高級轉換設置 OBJ 個特定屬性1. 調用 Scene.save 方法1. 傳遞帶有 OBJ 文件擴展名和 ObjSaveOptions 對象的輸出路徑
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 Java 轉換代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 應用程序和桌面應用程序運行時環境的兼容操作系統。- 直接從 Maven 獲取最新版本的 Aspose.3D for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DRC 到 OBJ Java 轉換源代碼" offSpacer="" %}}

```cs
// 在 Scene 對像中加載 DRC 
Scene document = new Scene("template.drc");
// 創建 ObjSaveOptions 的實例 
AmfSaveOptions options = new ObjSaveOptions();
// 將 DRC 保存為 OBJ 
document.save("output.obj", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DRC 到 OBJ 轉換現場演示" sectionDescription="[將 DRC 轉換為 OBJ](https://products.aspose.app/3d/conversion/drc-to-obj) 立即訪問我們的現場演示網站。現場演示具有以下好處" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳您的 DRC 文件，它就會立即轉換為 OBJ。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您將獲得下載鏈接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 場景操作庫" %}}

 Aspose.3D 是用於加載、修改和轉換 3D 文件的 CAD 和遊戲軟件 API。 API 是獨立的，不需要任何 3D 建模或渲染軟件。可以輕鬆地將 API 用於 Discreet3DS、WavefrontOBJ、STL（ASCII，二進制）、Universal3D、FBX（ASCII，二進制）、Collada、glTF、PLY、 GLB、DirectX 和更多格式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}

擴展名為 .drc 的文件是使用 Google Draco 庫創建的壓縮 3D 文件格式。 Google 提供 Draco 作為開源庫，用於壓縮和解壓縮 3D 幾何網格和點雲，並改進了 3D 圖形的存儲和傳輸。它對輸入數據進行編碼並將其保存為 .drc 文件。在接收端，API 讀取 .drc 文件並將其輸出為 PLY 或 OBJ 文件。壓縮的輸出文件使用戶能夠更快地下載應用程序並在瀏覽器中快速加載 3D 圖形。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

Wavefront 的 Advanced Visualizer 應用程序使用 OBJ 文件來定義和存儲幾何對象。通過 OBJ 文件可以實現幾何數據的前後傳輸。 OBJ 格式支持點、線、紋理頂點、面和自由形式幾何（曲線和曲面）等多邊形幾何。此格式不支持動畫或與場景的燈光和位置相關的信息。 OBJ 文件通常是由 CAD（計算機輔助設計）生成的 3D 建模過程的最終產品。存儲頂點的默認順序是逆時針方向，避免顯式聲明面法線。儘管 OBJ 文件在註釋行中聲明了比例信息，但尚未為 OBJ 坐標聲明任何單位。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}