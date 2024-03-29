﻿---
title: 通過 C# 將 ASE 轉換為 U3D 
weight: 2170
url: /zh-hant/net/conversion/ase-to-u3d/ 
description: ASE 到 U3D C# 轉換的示例代碼。使用 API 示例代碼在 VB.NET、Asp.NET 或任何基於 .NET 的應用程序中將 ASE 文件批量轉換為 U3D。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 C# 將 ASE 轉換為 U3D" h2="將 ASE 渲染為 U3D，無需任何 3D 建模和渲染軟件。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 將 ASE 轉換為 U3D" %}}

 為了將 ASE 轉換為 U3D，我們將使用
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API 是一個功能豐富、功能強大且易於使用的文檔操作和轉換 API C# 平台。打開
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 包管理器，搜索
 Aspose.3D 
 並安裝。您也可以從包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通過 C# 將 ASE 轉換為 U3D 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 程序員只需幾行代碼即可輕鬆加載 ASE 文件並將其轉換為 U3D。

{{% /blocks/products/pf/agp/text %}}

1. 通過 Scene 類的構造函數加載 ASE 文件1. 創建一個 U3dSaveOptions 的實例1. 為高級轉換設置 U3D 個特定屬性1. 調用 Scene.Save 方法1. 傳遞帶有 U3D 文件擴展名和 U3dSaveOptions 對象的輸出路徑1. 檢查指定路徑的結果 U3D 文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 .NET 轉換代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 .NET Framework、.NET Core、Mono 的兼容操作系統。- Microsoft Visual Studio 等開發環境。- Aspose.3D for .NET 項目中引用的 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此示例代碼顯示 ASE 到 U3D C# 轉換" offSpacer="" %}}

```cs
// 在 Scene 對像中加載 ASE 
var document = new Aspose.ThreeD.Scene("template.ase");
// 創建一個 U3dSaveOptions 的實例 
var options = new Aspose.ThreeD.Formats.U3dSaveOptions();
// 將 ASE 保存為 U3D 
document.Save("output.u3d", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="將 ASE 轉換為 U3D 的免費應用程序" sectionDescription="查看我們的現場演示 [ASE 到 U3D 的轉換](https://products.aspose.app/3d/conversion/ase-to-u3d) 具有以下好處。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載或設置任何東西。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳您的 ASE 文件並點擊“轉換”按鈕。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您將立即獲得生成的 U3D 文件的下載鏈接。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D 文件處理庫，無需任何建模和渲染軟件即可操作 3D 文件。 3D API 支持 Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY、DirectX、Google Draco 文件格式等。開發人員可以輕鬆地創建、讀取、轉換、修改和控制 3D 文檔格式的內容。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}
ASE 文件是包含圖層、幀、調色板、標籤和設置的 2D 動畫或圖形。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="u3d" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}
U3D (Universal 3D) 是用於 3D 計算機圖形的壓縮文件格式和數據結構。它包含 3D 模型信息，例如三角形網格、照明、陰影、運動數據、具有顏色和結構的線和點。該格式於 2005 年 8 月被接受為 ECMA-363 標準。3D PDF 文檔支持 U3D 對象嵌入並且可以在 Adobe Reader（版本 7 及更高版本）中查看。 U3D 格式的開發著眼於建立三維數據存儲和交換的通用標準。但是，該格式主要用於編碼 3D PDF，而不是用作交換格式。 Acrobat 3D 在轉換為 PDF 時將支持的 3D 文件類型轉換為 U3D 或 PRC。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="您還可以將 ASE 轉換為許多其他文件格式，包括下面列出的幾種。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-3ds/" name="ASE 至 3DS" description="3D Studio DOS 網格" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-amf/" name="ASE 至 AMF" description="增材製造形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-dae/" name="ASE 至 DAE" description="數字資產交易所" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-fbx/" name="ASE 至 FBX" description="3D 格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-html/" name="ASE 至 HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-obj/" name="ASE 至 OBJ" description="3D 文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-pdf/" name="ASE 至 PDF" description="便攜式文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-ply/" name="ASE 至 PLY" description="多邊形文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-rvm/" name="ASE 至 RVM" description="AVEVA 工廠設計模型" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-stl/" name="ASE 至 STL" description="可互換的 3D 表面幾何形狀" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}