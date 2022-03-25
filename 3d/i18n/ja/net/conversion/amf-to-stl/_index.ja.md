﻿---
title: C# 経由で AMF を STL に変換 
weight: 3000
url: /ja/net/conversion/amf-to-stl/ 
description: AMF から STL C# の変換のサンプルコード。バッチ AMF ファイルからVB.NET 、Asp.NET 、または .NET ベースのアプリケーション内で STL への変換には、 API サンプルコードを使用します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# 経由で AMF を STL に変換" h2="3D モデリングおよびレンダリングソフトウェアなしで AMF を STL としてレンダリングします。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="AMF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# を使用して AMF を STL に変換する方法" %}}

 AMF を STL に変換するには、を使用します。
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

{{% blocks/products/pf/agp/feature-section-col title="C# 経由で AMF を STL に変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 人のプログラマーは、わずか数行のコードで AMF 個のファイルを簡単にロード & 変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介した AMF ファイルの読み込み1. StlSaveOptionsのインスタンスの作成1. 高度な変換のために STL 固有のプロパティを設定する1. Scene.Saveメソッドを呼び出す1. STL ファイル拡張子とStlSaveOptionsのオブジェクトで出力パスを渡す1. 指定したパスで結果の STL ファイルを確認する
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要件" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windowsまたは、 .NET Framework、 .NET Core、 Mono の互換性のあるOS。- Microsoft Visual Studioのような開発環境。- プロジェクトで Aspose.3D for .NET DLLが参照されます。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このサンプルコードは AMF から STL C# の変換を示しています" offSpacer="" %}}

```cs
// Sceneのオブジェクトに AMF をロードする 
var document = new Aspose.ThreeD.Scene("template.amf");
// StlSaveOptionsのインスタンスを作成する 
var options = new Aspose.ThreeD.Formats.StlSaveOptions();
// AMF を STL として保存 
document.Save("output.stl", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="AMF を STL に変換する無料アプリ" sectionDescription="ライブデモをチェック [AMF から STL への変換](https://products.aspose.app/3d/conversion/amf-to-stl) 次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 何もダウンロードまたはセットアップする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" AMF ファイルをアップロードして「変換」ボタンを押すだけです。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 結果の STL ファイルのダウンロードリンクを即座に取得できます。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 モデリングおよびレンダリングソフトウェアなしで 3D ファイルを操作するための 3D ファイル処理ライブラリ。 3D API は、 Discreet3DS 、 WavefrontOBJ 、 FBX (ASCII、Binary) 、 STL (ASCII、Binary) 、 Universal3D 、 Collada 、 glTF 、 GLB 、 PLY 、DirectX、 Google Draco ファイル形式など。開発者は、 3D のドキュメント形式の内容を簡単に作成、読み取り、変換、変更、および制御できます。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="AMF" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}
Additive Manufacturingファイル形式 (AMF) は、 3D Printingなどの積層造形プロセスで利用するために、オブジェクト記述のオープンスタンダードを定義しています。 CAD プログラムは、オブジェクトのジオメトリ、色、素材などの情報を利用して AMF ファイル形式を使用します。 AMF は、横方向が色、素材、格子、星座をサポートしていないため、 STL 形式とは異なります。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="stl" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL (ステレオリスログラフィーの略語) は、3次元の表面ジオメトリを表す交換可能なファイル形式です。ファイル形式は、ラピッドプロトタイピング、 3D 印刷、コンピューター支援製造などのいくつかの分野で使用されます。これは、ファセットと呼ばれる一連の小さな三角形としてサーフェスを表します。各ファセットは、垂直方向と三角形の頂点を表す3つのポイントによって記述されます。得られたデータは、fabberによって構築される 3D 形状の断面を決定するためにアプリケーションによって使用される。 STL ファイル形式では、色、テクスチャ、またはその他の一般的な CAD モデル属性を表現するための情報はありません。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされる変換" subTitle="AMF を以下のいくつかを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-3ds/" name="AMF から 3DS" description="3D Studio DOSメッシュ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-dae/" name="AMF から DAE" description="デジタル資産交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-fbx/" name="AMF から FBX" description="3D フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-html/" name="AMF から HTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-obj/" name="AMF から OBJ" description="3D ファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-pdf/" name="AMF から PDF" description="ポータブルドキュメント形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-ply/" name="AMF から PLY" description="Polygonファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-rvm/" name="AMF から RVM" description="AVEVA植物デザインモデル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-u3d/" name="AMF から U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}