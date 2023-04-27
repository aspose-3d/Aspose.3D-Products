---
title: Java3Dフォーマット変換
url: /ja/java/conversion/
description: 3D形式を変換しますamf3dsamf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrmlxJavaライブラリを介して数行のJavaコードを使用します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3DJavaによるフォーマット変換" h2="クロスプラットフォームのJavaアプリケーションを構築するために、3Dモデリングおよびレンダリングソフトウェアをインストールせずに3Dファイル形式を変換します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
3次元グラフィックスアプリケーションを作成、編集、操作、および保存するために、** Java 3D API **は、3Dモデリングおよびレンダリングソフトウェアをインストールせずに、このような機能を実行するための高レベルのメソッドを提供します。さまざまな3次元の幾何学的形状のメッシュを構築し、3Dシーンファイルを作成し、キューブに法線またはUVを設定し、要素をフォーマットし、アニメーションプロパティを追加することはほとんどありません。 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="3Dファイルをさまざまな形式に変換する" %}}
変換プロセスは簡単です。を使用してソース3Dファイルをロードするだけです [シーンクラス](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene)。シーンは、ノード、ジオメトリ、テクスチャ、マテリアル、アニメーション、ポーズ、サブシーンなどを含むトップレベルのオブジェクトであるため、関連する関連するオブジェクトを作成します。 [オプションを保存](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) AmfSaveOptions、ColladaSaveOptions、Discreet3dsSaveOptions、DracoSaveOptions、FbxSaveOptions、GltfSaveOptions、RvmSaveOptions、StlSaveOptions、U3dSaveOptionsなどを使用して、それに応じてプロパティを設定します。最後に、出力ファイルと作成されたターゲット形式の保存オプションオブジェクトを使用してsaveメソッドを呼び出します。さらに、APIプログラマーを使用すると、3DシーンをHTMLとして保存することもできます。


{{% blocks/products/pf/feature-page-code h3="JavaAMFから3DSへの変換のコード" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Javaを介して3DシーンをHTMLに変換します" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
