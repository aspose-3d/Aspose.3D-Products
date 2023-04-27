---
title: Java 3D 格式转换
url: /zh/java/conversion/
description: 通过 Java 库使用几行 Java 代码转换 3D 格式 amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D 通过 Java 进行格式转换" h2="无需安装任何 3D 建模和渲染软件即可转换 3D 文件格式以构建跨平台 Java 应用程序。" >}}

{{% blocks/products/pf/feature-page-summary %}}
对于创建、编辑、操作和保存 3D 图形应用程序，**Java 3D API** 提供了执行此类功能的高级方法，而无需安装任何 3D 建模和渲染软件。很少有构建不同 3D 几何形状的网格、创建 3D 场景文件、在 Cube 上设置法线或 UV、格式化元素、添加动画属性等等。 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 3D 文件转换为不同格式" %}}
转换过程很简单。只需使用加载源 3D 文件 [场景类](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene).由于场景是具有节点、几何、纹理、材质、动画、姿势、子场景等的顶级对象。创建相关的 [保存选项](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) 例如 AmfSaveOptions、ColladaSaveOptions、Discreet3dsSaveOptions、DracoSaveOptions、FbxSaveOptions、GltfSaveOptions、RvmSaveOptions、StlSaveOptions、U3dSaveOptions 等，并相应地设置属性。最后使用输出文件调用 save 方法并创建目标格式保存选项对象。此外，使用 API 程序员甚至可以将 3D 场景保存为 HTML。


{{% blocks/products/pf/feature-page-code h3="Java AMF 到 3DS 转换的代码" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="通过 Java 将 3D 场景转换为 HTML" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
