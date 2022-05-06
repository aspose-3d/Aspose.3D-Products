﻿---
title: C#を介してRVMをSTLに変換します 
weight: 3650
url: /ja/net/conversion/rvm-to-stl/ 
description: RVMからSTLC#への変換のサンプルコード。 VB .NET、Asp .NET、または任意の.NETベースのアプリケーション内でのバッチRVMファイルからSTLへの変換にはAPIサンプルコードを使用します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#を介してRVMをSTLに変換します" h2="3Dモデリングおよびレンダリングソフトウェアを使用せずに、RVMをSTLとしてレンダリングします。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="RVM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してRVMをSTLに変換する方法" %}}

 RVMをSTLに変換するには、
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 APIは、機能が豊富で、強力で、使いやすいドキュメント操作と変換APIforC#プラットフォームです。開ける
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

{{% blocks/products/pf/agp/feature-section-col title="C#を介してRVMをSTLに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 .NETプログラマーは、わずか数行のコードでRVMファイルを簡単にロードしてSTLに変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介してRVMファイルをロードします1. StlSaveOptionsのインスタンスを作成します1. 高度な変換のためにSTL固有のプロパティを設定します1. Scene.Saveメソッドを呼び出します1. STLファイル拡張子とStlSaveOptionsのオブジェクトを使用して出力パスを渡します1. 指定されたパスで結果のSTLファイルを確認します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 .NET変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windowsまたは.NETフレームワーク、.NETコア、Monoと互換性のあるOS。- MicrosoftVisualStudioのような開発環境。- Aspose.3Dfor .NETプロジェクトで参照されているDLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このサンプルコードは、RVMからSTLC#への変換を示しています" offSpacer="" %}}

```cs
// シーンのオブジェクトにRVMをロードします 
var document = new Aspose.ThreeD.Scene("template.rvm");
// StlSaveOptionsのインスタンスを作成します 
var options = new Aspose.ThreeD.Formats.StlSaveOptions();
// RVMをSTLとして保存 
document.Save("output.stl", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="RVMをSTLに変換する無料アプリ" sectionDescription="ライブデモをチェックしてください [RVMからSTLへの変換](https://products.aspose.app/3d/conversion/rvm-to-stl) 以下の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 何かをダウンロードしたりセットアップしたりする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" RVMファイルをアップロードして[変換]ボタンを押すだけです。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 結果のSTLファイルのダウンロードリンクがすぐに表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 モデリングおよびレンダリングソフトウェアなしで3Dファイルを操作するための3Dファイル処理ライブラリ。 3D APIは、Discreet3DS、WavefrontOBJ、FBX（ASCII、バイナリ）、STL（ASCII、バイナリ）、Universal3D、Collada、glTF、GLB、 PLY、DirectX、GoogleDracoファイル形式など。開発者は、3Dドキュメント形式の実体を簡単に作成、読み取り、変換、変更、および制御できます。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="RVM" readMoreLink="https://docs.fileformat.com/3d/rvm/" >}}
RVMデータファイルはAVEVAPDMSに関連しています。 RVMファイルはAVEVAプラント設計管理システムモデルです。 AVEVAのプラント設計管理システム（PDMS）は、プロジェクトを管理するためにデータ中心のテクノロジーを使用する最も人気のある3D設計システムです。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="stl" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
ステレオリソグラフィーの略語であるSTLは、3次元の表面形状を表す交換可能なファイル形式です。このファイル形式は、ラピッドプロトタイピング、3D印刷、コンピューター支援製造などのいくつかの分野で使用されています。これは、ファセットと呼ばれる一連の小さな三角形としてサーフェスを表します。各ファセットは、垂直方向と三角形の頂点を表す3つのポイントで表されます。結果のデータは、ファバーによって構築される3D形状の断面を決定するためにアプリケーションによって使用されます。色、テクスチャ、またはその他の一般的なCADモデル属性を表現するためのSTLファイル形式で利用できる情報はありません。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="RVMを、以下にリストされているものを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-3ds/" name="RVMから3DS" description="3DスタジオDOSメッシュ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-amf/" name="RVMからAMF" description="アディティブマニュファクチャリングフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-dae/" name="RVMからDAE" description="デジタル資産交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-fbx/" name="RVMからFBX" description="3D形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-html/" name="RVMからHTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-obj/" name="RVMからOBJ" description="3Dファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-pdf/" name="RVMからPDF" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-ply/" name="RVMからPLY" description="ポリゴンファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-u3d/" name="RVMからU3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}