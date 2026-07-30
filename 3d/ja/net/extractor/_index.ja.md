---
title: C# 3Dフォーマットからアセットを抽出する
url: /ja/net/extractor/
description: 3ds、3mf、amf、ase、att、dae、dxf、fbx、gltf、jt、obj、ply、rvm、stl、u3d、usdz、usd、vrml、x形式の3Dファイルを.NETライブラリを使用して、C#コードの数行でアセットを抽出します。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D形式からアセットをC#で抽出" h2="3Dモデリングおよびレンダリングソフトウェアなしで3Dドキュメント形式からアセットを抽出し、クロスプラットフォーム.NETアプリケーションを構築します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
開発者は、3Dライブラリを使用して、簡単に3Dファイルアセットを抽出できます。 APIでサポートされている形式には、WavefrontOBJ、Discreet3DS、STL（ASCII、Binary）、FBX（ASCII、Binary）、Universal3D、Collada、GLB、glTF、PLY、DirectX、Google Draco形式などがあります。 抽出プロセスは簡単です。 [sceneクラス](https://apireference.aspose.com/3d/net/aspose.threed/scene)のインスタンスを通してソースファイルをロードし、アーカイブクラスを作成し、アセット抽出クラスを処理し、関連する出力形式パラメータのSaveメソッドを呼び出します。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="3Dシーンからさまざまな形式でアセットを抽出" %}}
開発者は、上記と同じプロセスを通して、3Dファイルから簡単にアセットを抽出できます。 **3DSからFBX抽出器**のような例を検討してください。 sceneクラスオブジェクトを通して3DSファイルをロードします。 [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions)を使用して保存オプションを作成し、出力ファイルパスとfbxオプション引数でsceneのsaveメソッドを呼び出します。 APIは、関連するクラスへの保存のための適切なオプションクラスを持っています。例えば、[A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions)などがあります。 3D [抽出器形式](https://apireference.aspose.com/3d/net/aspose.threed.formats)オプションの完全なリストはこちらです。

{{% blocks/products/pf/feature-page-code h3="3DSからFBXへのアセット抽出のためのC#コード" %}}

{{< gist "aspose-3d-gists" "9563193e834f0087b554c83130fcf7c7" "Examples-CSharp-Extractor-products.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Extractor" >}}
{{< /blocks/products/pf/feature-page-wrap >}}