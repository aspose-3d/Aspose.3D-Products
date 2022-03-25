﻿---
title: C# 経由で DXF を OBJ に変換 
weight: 1660
url: /ja/net/conversion/dxf-to-obj/ 
description: DXF から OBJ C# の変換のサンプルコード。バッチ DXF ファイルからVB.NET 、Asp.NET 、または .NET ベースのアプリケーション内で OBJ への変換には、 API サンプルコードを使用します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# 経由で DXF を OBJ に変換" h2="3D モデリングおよびレンダリングソフトウェアなしで DXF を OBJ としてレンダリングします。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# を使用して DXF を OBJ に変換する方法" %}}

 DXF を OBJ に変換するには、を使用します。
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API は、機能が豊富でパワフルで使いやすいドキュメント操作と C# プラットフォーム用の変換 API です。オープン
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 パッケージマネージャー、検索
 Aspose.3D 
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="パッケージマネージャーコンソールコマンド" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# 経由で DXF を OBJ に変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 人のプログラマーは、わずか数行のコードで DXF 個のファイルを簡単にロード & 変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介した DXF ファイルの読み込み1. ObjSaveOptionsのインスタンスの作成1. 高度な変換のために OBJ 固有のプロパティを設定する1. Scene.Saveメソッドを呼び出す1. ObjSaveOptionsの OBJ ファイル拡張子とオブジェクトで出力パスを渡す1. 指定したパスで結果の OBJ ファイルを確認する
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要件" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windowsまたは、 .NET Framework、 .NET Core、 Mono の互換性のあるOS。- Microsoft Visual Studioのような開発環境。- プロジェクトで Aspose.3D for .NET DLLが参照されます。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このサンプルコードは DXF から OBJ C# の変換を示しています" offSpacer="" %}}

```cs
// Sceneのオブジェクトに DXF をロードする 
var document = new Aspose.ThreeD.Scene("template.dxf");
// ObjSaveOptionsのインスタンスを作成する 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// DXF を OBJ として保存 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DXF を OBJ に変換する無料アプリ" sectionDescription="ライブデモをチェック [DXF から OBJ への変換](https://products.aspose.app/3d/conversion/dxf-to-obj) 次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 何もダウンロードまたはセットアップする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" DXF ファイルをアップロードして「変換」ボタンを押すだけです。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 結果の OBJ ファイルのダウンロードリンクを即座に取得できます。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 モデリングおよびレンダリングソフトウェアなしで 3D ファイルを操作するための 3D ファイル処理ライブラリ。 3D API は、 Discreet3DS 、 WavefrontOBJ 、 FBX (ASCII、Binary) 、 STL (ASCII、Binary) 、 Universal3D 、 Collada 、 glTF 、 GLB 、 PLY 、DirectX、 Google Draco ファイル形式など。開発者は、 3D のドキュメント形式の内容を簡単に作成、読み取り、変換、変更、および制御できます。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}
DXF 、図面交換形式、または図面交換形式は、AutoCAD図面ファイルのタグ付きデータ表現です。ファイル内の各要素には、グループコードと呼ばれるプレフィックス整数があります。このグループコードは、実際には次の要素を表し、特定のオブジェクトタイプのデータ要素の意味を示します。 DXF では、ユーザーが指定したほとんどすべての情報を図面ファイルで表すことができます。 DXF ファイル形式は、AutoCADと他のアプリケーション間のデータ相互運用性のために、Autodeskによって CAD データファイル形式として開発されました。したがって、 DXF ファイル形式の相互運用性仕様に従って、他の形式からAutoCADにデータをインポートできます。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
OBJ 個のファイルは、 Wavefront のAdvanced Visualizerアプリケーションによって、ジオメトリオブジェクトを定義および保存するために使用されます。 OBJ 個のファイルを介して、幾何学的データの後方および前方への送信が可能になります。ポイント、ライン、テクスチャ頂点、面、自由形式ジオメトリ (曲線とサーフェス) などのポリゴンジオメトリは、 OBJ 形式でサポートされています。このフォーマットは、アニメーションやシーンの光と位置に関する情報をサポートしていません。 OBJ ファイルは通常、 CAD (Computer Aided Design) によって生成された 3D モデリングプロセスの最終製品です。頂点を格納するデフォルトの順序は、顔の法線の明示的な宣言を回避する反時計回りです。 OBJ 個のファイルがコメント行にスケール情報を宣言していますが、 OBJ 個の座標の単位は宣言されていません。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされる変換" subTitle="DXF を以下のいくつかを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-3ds/" name="DXF から 3DS" description="3D Studio DOSメッシュ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-amf/" name="DXF から AMF" description="添加剤製造フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-dae/" name="DXF から DAE" description="デジタル資産交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-fbx/" name="DXF から FBX" description="3D フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-html/" name="DXF から HTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-pdf/" name="DXF から PDF" description="ポータブルドキュメント形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-ply/" name="DXF から PLY" description="Polygonファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-rvm/" name="DXF から RVM" description="AVEVA植物デザインモデル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-stl/" name="DXF から STL" description="交換可能な 3D 面ジオメトリ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-u3d/" name="DXF から U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}