﻿---
title: C#を介してVRMLをAMFに変換します 
weight: 2620
url: /ja/net/conversion/vrml-to-amf/ 
description: VRMLからAMFC#への変換のサンプルコード。 VB .NET、Asp .NET、または任意の.NETベースのアプリケーション内でのバッチVRMLファイルからAMFへの変換にはAPIサンプルコードを使用します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#を介してVRMLをAMFに変換します" h2="3Dモデリングおよびレンダリングソフトウェアを使用せずに、VRMLをAMFとしてレンダリングします。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="AMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="VRML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してVRMLをAMFに変換する方法" %}}

 VRMLをAMFに変換するには、
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

{{% blocks/products/pf/agp/feature-section-col title="C#を介してVRMLをAMFに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 .NETプログラマーは、わずか数行のコードでVRMLファイルを簡単にロードしてAMFに変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介してVRMLファイルをロードします1. AmfSaveOptionsのインスタンスを作成します1. 高度な変換のためにAMF固有のプロパティを設定します1. Scene.Saveメソッドを呼び出します1. AMFファイル拡張子とAmfSaveOptionsのオブジェクトを使用して出力パスを渡します1. 指定されたパスで結果のAMFファイルを確認します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 .NET変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windowsまたは.NETフレームワーク、.NETコア、Monoと互換性のあるOS。- MicrosoftVisualStudioのような開発環境。- Aspose.3Dfor .NETプロジェクトで参照されているDLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このサンプルコードは、VRMLからAMFC#への変換を示しています" offSpacer="" %}}

```cs
// シーンのオブジェクトにVRMLをロードします 
var document = new Aspose.ThreeD.Scene("template.vrml");
// AmfSaveOptionsのインスタンスを作成します 
var options = new Aspose.ThreeD.Formats.AmfSaveOptions();
// VRMLをAMFとして保存 
document.Save("output.amf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="VRMLをAMFに変換する無料アプリ" sectionDescription="ライブデモをチェックしてください [VRMLからAMFへの変換](https://products.aspose.app/3d/conversion/vrml-to-amf) 以下の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 何かをダウンロードしたりセットアップしたりする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" VRMLファイルをアップロードして[変換]ボタンを押すだけです。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 結果のAMFファイルのダウンロードリンクがすぐに表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 モデリングおよびレンダリングソフトウェアなしで3Dファイルを操作するための3Dファイル処理ライブラリ。 3D APIは、Discreet3DS、WavefrontOBJ、FBX（ASCII、バイナリ）、STL（ASCII、バイナリ）、Universal3D、Collada、glTF、GLB、 PLY、DirectX、GoogleDracoファイル形式など。開発者は、3Dドキュメント形式の実体を簡単に作成、読み取り、変換、変更、および制御できます。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="VRML" readMoreLink="https://docs.fileformat.com/3d/vrml/" >}}
バーチャルリアリティモデリング言語（VRML）は、ワールドワイドウェブ（www）上でインタラクティブな3Dワールドオブジェクトを表現するためのファイル形式です。イラスト、定義、バーチャルリアリティプレゼンテーションなどの複雑なシーンの3次元表現を作成する際に使用されます。このフォーマットはX3Dに取って代わられました。多くの3Dモデリングアプリケーションは、オブジェクトとシーンをVRML形式で保存できます。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="amf" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}
アディティブマニュファクチャリングファイル形式（AMF）は、3D印刷などのアディティブマニュファクチャリングプロセスで利用できるように、オブジェクト記述のオープンスタンダードを定義します。 CADプログラムは、オブジェクトの形状、色、素材などの情報を利用して、AMFファイル形式を使用します。 AMFは、側面が色、材料、格子、および星座をサポートしていないため、STL形式とは異なります。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="VRMLを、以下にリストされているものを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-3ds/" name="VRMLから3DS" description="3DスタジオDOSメッシュ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-dae/" name="VRMLからDAE" description="デジタル資産交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-fbx/" name="VRMLからFBX" description="3D形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-html/" name="VRMLからHTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-obj/" name="VRMLからOBJ" description="3Dファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-pdf/" name="VRMLからPDF" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-ply/" name="VRMLからPLY" description="ポリゴンファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-rvm/" name="VRMLからRVM" description="AVEVAプラント設計モデル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-stl/" name="VRMLからSTL" description="交換可能な3D表面形状" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-u3d/" name="VRMLからU3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}