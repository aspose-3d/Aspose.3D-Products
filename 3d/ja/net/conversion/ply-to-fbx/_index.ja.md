﻿---
title: C#を介してPLYをFBXに変換します 
weight: 1910
url: /ja/net/conversion/ply-to-fbx/ 
description: PLYからFBXC#への変換のサンプルコード。 VB .NET、Asp .NET、または任意の.NETベースのアプリケーション内でのバッチPLYファイルからFBXへの変換にはAPIサンプルコードを使用します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#を介してPLYをFBXに変換します" h2="3Dモデリングおよびレンダリングソフトウェアを使用せずに、PLYをFBXとしてレンダリングします。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してPLYをFBXに変換する方法" %}}

 PLYをFBXに変換するには、
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

{{% blocks/products/pf/agp/feature-section-col title="C#を介してPLYをFBXに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 .NETプログラマーは、わずか数行のコードでPLYファイルを簡単にロードしてFBXに変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介してPLYファイルをロードします1. FbxSaveOptionsのインスタンスを作成します1. 高度な変換のためにFBX固有のプロパティを設定します1. Scene.Saveメソッドを呼び出します1. FbxSaveOptionsのFBXファイル拡張子とオブジェクトで出力パスを渡します1. 指定されたパスで結果のFBXファイルを確認します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 .NET変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windowsまたは.NETフレームワーク、.NETコア、Monoと互換性のあるOS。- MicrosoftVisualStudioのような開発環境。- Aspose.3Dfor .NETプロジェクトで参照されているDLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このサンプルコードは、PLYからFBXC#への変換を示しています" offSpacer="" %}}

```cs
// シーンのオブジェクトにPLYをロードします 
var document = new Aspose.ThreeD.Scene("template.ply");
// FbxSaveOptionsのインスタンスを作成します 
var options = new Aspose.ThreeD.Formats.FbxSaveOptions();
// PLYをFBXとして保存 
document.Save("output.fbx", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="PLYをFBXに変換する無料アプリ" sectionDescription="ライブデモをチェックしてください [PLYからFBXへの変換](https://products.aspose.app/3d/conversion/ply-to-fbx) 以下の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 何かをダウンロードしたりセットアップしたりする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" PLYファイルをアップロードして[変換]ボタンを押すだけです。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 結果のFBXファイルのダウンロードリンクがすぐに表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 モデリングおよびレンダリングソフトウェアなしで3Dファイルを操作するための3Dファイル処理ライブラリ。 3D APIは、Discreet3DS、WavefrontOBJ、FBX（ASCII、バイナリ）、STL（ASCII、バイナリ）、Universal3D、Collada、glTF、GLB、 PLY、DirectX、GoogleDracoファイル形式など。開発者は、3Dドキュメント形式の実体を簡単に作成、読み取り、変換、変更、および制御できます。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}
PLY、ポリゴンファイル形式は、ポリゴンのコレクションとして記述されたグラフィカルオブジェクトを格納する3Dファイル形式を表します。このファイル形式の目的は、幅広いモデルに役立つほど一般的な、シンプルで簡単なファイルタイプを確立することでした。 PLYファイル形式はASCIIとバイナリ形式で提供され、コンパクトなストレージと迅速な保存と読み込みが可能です。ファイル形式は、3Dファイルの読み取りをサポートするさまざまなアプリケーションで使用されます。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="fbx" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX、FilmBoxは、もともとKaydaraがMotionBuilder用に開発した人気のある3Dファイル形式です。 2006年にAutodeskIncによって買収され、現在、多くの3Dツールで使用されている主要な3D交換形式の1つです。 FBXは、バイナリとASCIIの両方のファイル形式で利用できます。このフォーマットは、デジタルコンテンツ作成アプリケーション間の相互運用性を提供するために確立されました。 FBXファイル形式から/への変換に利用できる多くのツールがあります。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="PLYを、以下にリストされているものを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-3ds/" name="PLYから3DS" description="3DスタジオDOSメッシュ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-amf/" name="PLYからAMF" description="アディティブマニュファクチャリングフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-dae/" name="PLYからDAE" description="デジタル資産交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-html/" name="PLYからHTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-obj/" name="PLYからOBJ" description="3Dファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-pdf/" name="PLYからPDF" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-rvm/" name="PLYからRVM" description="AVEVAプラント設計モデル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-stl/" name="PLYからSTL" description="交換可能な3D表面形状" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-u3d/" name="PLYからU3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}