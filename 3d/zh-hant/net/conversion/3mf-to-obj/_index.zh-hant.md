﻿---
title: 通過 C# 將 3MF 轉換為 OBJ 
weight: 2190
url: /zh-hant/net/conversion/3mf-to-obj/ 
description: 3MF 到 OBJ C# 轉換的示例代碼。使用 API 示例代碼在 VB.NET、Asp.NET 或任何基於 .NET 的應用程序中將 3MF 文件批量轉換為 OBJ。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 C# 將 3MF 轉換為 OBJ" h2="將 3MF 渲染為 OBJ，無需任何 3D 建模和渲染軟件。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3MF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 將 3MF 轉換為 OBJ" %}}

 為了將 3MF 轉換為 OBJ，我們將使用
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

{{% blocks/products/pf/agp/feature-section-col title="通過 C# 將 3MF 轉換為 OBJ 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 程序員只需幾行代碼即可輕鬆加載 3MF 文件並將其轉換為 OBJ。

{{% /blocks/products/pf/agp/text %}}

1. 通過 Scene 類的構造函數加載 3MF 文件1. 創建 ObjSaveOptions 的實例1. 為高級轉換設置 OBJ 個特定屬性1. 調用 Scene.Save 方法1. 傳遞帶有 OBJ 文件擴展名和 ObjSaveOptions 對象的輸出路徑1. 檢查指定路徑的結果 OBJ 文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 .NET 轉換代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 .NET Framework、.NET Core、Mono 的兼容操作系統。- Microsoft Visual Studio 等開發環境。- Aspose.3D for .NET 項目中引用的 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此示例代碼顯示 3MF 到 OBJ C# 轉換" offSpacer="" %}}

```cs
// 在 Scene 對像中加載 3MF 
var document = new Aspose.ThreeD.Scene("template.3mf");
// 創建 ObjSaveOptions 的實例 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// 將 3MF 保存為 OBJ 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="將 3MF 轉換為 OBJ 的免費應用程序" sectionDescription="查看我們的現場演示 [3MF 到 OBJ 的轉換](https://products.aspose.app/3d/conversion/3mf-to-obj) 具有以下好處。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載或設置任何東西。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳您的 3MF 文件並點擊“轉換”按鈕。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您將立即獲得生成的 OBJ 文件的下載鏈接。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D 文件處理庫，無需任何建模和渲染軟件即可操作 3D 文件。 3D API 支持 Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY、DirectX、Google Draco 文件格式等。開發人員可以輕鬆地創建、讀取、轉換、修改和控制 3D 文檔格式的內容。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}
3MF，3D 製造格式，應用程序使用它來將 3D 對像模型呈現給各種其他應用程序、平台、服務和打印機。它旨在避免其他 3D 文件格式（如 STL）中的限制和問題，以便與最新版本的 3D 打印機一起使用。 3MF 是一種相對較新的文件格式，由 3MF 聯盟開發和發布。它足夠豐富來完全描述模型，保留內部信息、顏色和其他特性，使其可擴展以支持 3D 打印的新創新。該格式是可擴展的，能夠被廣泛採用並且沒有困擾其他廣泛使用的文件格式的問題。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
Wavefront 的 Advanced Visualizer 應用程序使用 OBJ 文件來定義和存儲幾何對象。通過 OBJ 文件可以實現幾何數據的前後傳輸。 OBJ 格式支持點、線、紋理頂點、面和自由形式幾何（曲線和曲面）等多邊形幾何。此格式不支持動畫或與場景的燈光和位置相關的信息。 OBJ 文件通常是由 CAD（計算機輔助設計）生成的 3D 建模過程的最終產品。存儲頂點的默認順序是逆時針方向，避免顯式聲明面法線。儘管 OBJ 文件在註釋行中聲明了比例信息，但尚未為 OBJ 坐標聲明任何單位。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="您還可以將 3MF 轉換為許多其他文件格式，包括下面列出的幾種。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-3ds/" name="3MF 至 3DS" description="3D Studio DOS 網格" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-amf/" name="3MF 至 AMF" description="增材製造形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-dae/" name="3MF 至 DAE" description="數字資產交易所" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-fbx/" name="3MF 至 FBX" description="3D 格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-html/" name="3MF 至 HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-pdf/" name="3MF 至 PDF" description="便攜式文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-ply/" name="3MF 至 PLY" description="多邊形文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-rvm/" name="3MF 至 RVM" description="AVEVA 工廠設計模型" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-stl/" name="3MF 至 STL" description="可互換的 3D 表面幾何形狀" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-u3d/" name="3MF 至 U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}