---
title: Java 3D 格式轉換
url: /zh-hant/java/conversion/
description: 通過 Java 庫使用幾行 Java 代碼轉換 3D 格式 amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D 通過 Java 進行格式轉換" h2="無需安裝任何 3D 建模和渲染軟件即可轉換 3D 文件格式以構建跨平台 Java 應用程序。" >}}

{{% blocks/products/pf/feature-page-summary %}}
對於創建、編輯、操作和保存 3D 圖形應用程序，**Java 3D API** 提供了執行此類功能的高級方法，而無需安裝任何 3D 建模和渲染軟件。很少有構建不同 3D 幾何形狀的網格、創建 3D 場景文件、在 Cube 上設置法線或 UV、格式化元素、添加動畫屬性等等。 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 3D 文件轉換為不同格式" %}}
轉換過程很簡單。只需使用加載源 3D 文件 [場景類](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene).由於場景是具有節點、幾何、紋理、材質、動畫、姿勢、子場景等的頂級對象。創建相關的 [保存選項](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) 例如 AmfSaveOptions、ColladaSaveOptions、Discreet3dsSaveOptions、DracoSaveOptions、FbxSaveOptions、GltfSaveOptions、RvmSaveOptions、StlSaveOptions、U3dSaveOptions 等，並相應地設置屬性。最後使用輸出文件調用 save 方法並創建目標格式保存選項對象。此外，使用 API 程序員甚至可以將 3D 場景保存為 HTML。


{{% blocks/products/pf/feature-page-code h3="Java AMF 到 3DS 轉換的代碼" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="通過 Java 將 3D 場景轉換為 HTML" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
