﻿---
title: 通過 C# 將 ASE 轉換為 PLY 
weight: 2400
url: /zh-hant/net/conversion/ase-to-ply/ 
description: ASE 到 PLY C# 轉換的示例代碼。 在VB.NET,asp.NET 或任何基於 .NET 的應用程序中使用 API 示例代碼將批處理 ASE 文件轉換為 PLY。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 C# 將 ASE 轉換為 PLY" h2="將 ASE 渲染為 PLY,無需任何 3D 建模和渲染軟件。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PLY" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 將 ASE 轉換為 PLY" %}}

 為了將 ASE 轉換為 PLY,我們將使用
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API 這是一個功能豐富,功能強大且易於使用的文檔操作和轉換 API,適用於 C# 平台。 打開
 [努get](https://www.nuget.org/packages/aspose.3d) 
 包管理器,搜索
 Aspose.3D 
 並安裝。 您也可以使用包管理器控制台中的以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通過 C# 將 ASE 轉換為 PLY 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 程序員只需幾行代碼就可以輕鬆地將 ASE 文件加載和轉換為 PLY。

{{% /blocks/products/pf/agp/text %}}

1. 通過場景類的構造函數加載 ASE 文件1. 創建PlySaveOptions實例1. 為高級轉換設置 PLY 特定屬性1. 調用場景。 保存方法1. 傳遞帶有 PLY 文件擴展名和PlySaveOptions對象的輸出路徑1. 檢查指定路徑處的結果 PLY 文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 .NET 轉換代碼之前,請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows或具有 .NET 框架,.NET 核心,Mono 的兼容操作系統。- 像微軟Visual Studio這樣的開發環境。- 項目中引用的 Aspose.3D for .NET DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此示例代碼顯示 ASE 到 PLY C# 的轉換" offSpacer="" %}}

```cs
// 加載場景對象中的 ASE 
var document = new Aspose.ThreeD.Scene("template.ase");
// 創建PlySaveOptions實例 
var options = new Aspose.ThreeD.Formats.PlySaveOptions();
// 將 ASE 保存為 PLY 
document.Save("output.ply", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="免費應用程序將 ASE 轉換為 PLY" sectionDescription="查看我們的實時演示 [ASE 到 PLY 轉換](https://products.aspose.app/3d/conversion/ase-to-ply) 有以下好處。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 不需要下載或設置任何東西。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 不需要編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳您的 ASE 文件,然後點擊 「轉換」 按鈕。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您將立即獲得結果 PLY 文件的下載鏈接。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 一個 3D 文件處理庫,用於操作 3D 文件,而無需任何建模和渲染軟件。 3D API 支持 Discreet3DS 、 WavefrontOBJ 、 FBX (ASCII,二進製) 、 STL (ASCII,二進製) 、 Universal3D 、 Collada 、 glTF 、 GLB 、 PLY 、DirectX、 Google Draco 文件格式和更多。 開發人員可以輕鬆創建、閱讀、轉換、修改和控制 3D 文檔格式的實質內容。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}
ASE 文件是包含圖層、框架、調色板、標籤和設置的2D動畫或圖形。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ply" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}
PLY,多邊形文件格式,表示存儲描述為多邊形集合的圖形對象的 3D 文件格式。 此文件格式的目的是建立一種簡單易用的文件類型,該類型足夠通用,可以用於各種模型。 PLY 文件格式作為ASCII以及二進位格式,用於緊湊存儲和快速保存和加載。 文件格式由提供 3D 文件讀取支持的不同應用程序使用。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="您還可以將 ASE 轉換為許多其他文件格式,包括下面列出的幾種格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-3ds/" name="ASE 至 3DS" description="3D 工作室DOS網格" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-amf/" name="ASE 至 AMF" description="增材製造格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-dae/" name="ASE 至 DAE" description="數字資產交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-fbx/" name="ASE 至 FBX" description="3D 格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-html/" name="ASE 至 HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-obj/" name="ASE 至 OBJ" description="3D 文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-pdf/" name="ASE 至 PDF" description="可移植文檔格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-rvm/" name="ASE 至 RVM" description="AVEVA工廠設計模型" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-stl/" name="ASE 至 STL" description="可互換的 3D 曲面幾何形狀" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-u3d/" name="ASE 至 U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}