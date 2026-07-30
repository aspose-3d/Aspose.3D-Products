---
title: C# 三維格式提取資產
url: "/zh-hant/net/extractor/"
description: 從 3D 格式 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x 提取資源，使用 .NET 函式庫，使用幾行 C# 程式碼。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D 格式提取資產 via C#" h2="無需任何 3D 建模和渲染軟體，即可從 3D 文件格式中提取資產，以構建跨平台 .NET 應用程式。" >}}

{{% blocks/products/pf/feature-page-summary %}}
開發者可以使用 3D 庫輕鬆提取 3D 文件資產。API 支援的格式包括 WavefrontOBJ、Discreet3DS、STL（ASCII、二進位）、FBX（ASCII、二進位）、通用 3D、Collada、GLB、glTF、PLY、DirectX、Google Draco 格式等。提取過程簡單，透過 [scene class](https://apireference.aspose.com/3d/net/aspose.threed/scene) 的實例載入來源文件，建立 archive class 並處理提取資產 class，然後呼叫 Save 方法，針對相關的輸出格式參數。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="將資產從 3D 場景提取到各種格式" %}}
開發者可以透過上述相同的過程輕鬆從 3D 文件中提取資產。考慮一些範例，例如 **3DS to FBX 提取器**。透過 scene class 物件載入 3DS 文件。使用 [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions) 建立儲存選項，並使用輸出文件路徑和 fbx 選項參數呼叫場景儲存方法。API 針對儲存到相關類別，具有適當的選項類別，例如 [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) 等等。這裡有完整的 3D [extractor formats](https://apireference.aspose.com/3d/net/aspose.threed.formats) 選項列表。

{{% blocks/products/pf/feature-page-code h3="C# 程式碼用於 3DS to FBX 提取資產" %}}

{{< gist "aspose-3d-gists" "9563193e834f0087b554c83130fcf7c7" "Examples-CSharp-Extractor-products.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Extractor" >}}
{{< /blocks/products/pf/feature-page-wrap >}}