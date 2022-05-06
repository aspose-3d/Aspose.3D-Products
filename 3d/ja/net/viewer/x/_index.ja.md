﻿---
title: .NETを介してXファイル形式を表示 
weight: 2050
url: /ja/net/viewer/x/ 
description: .NETフレームワーク、.NETコア、MonoでXドキュメントをロード、レンダリング、表示するためのC#ソースコード。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Xファイルビューアfor .NET" h2="3Dモデリングおよびレンダリングソフトウェアを使用せずにXファイルをレンダリングします。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="X" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="X" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してXファイルを表示する方法" %}}

 Xファイルを表示するには、
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 APIは、機能が豊富で、強力で、使いやすいAPIforC#プラットフォームで任意のビューアで使用できます。開ける
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 パッケージマネージャー、検索
 ** Aspose.3D ** 
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="パッケージマネージャーコンソールコマンド" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#を介してXを表示する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3Dを使用すると、開発者はわずか数行のコードでXファイルを簡単に表示できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介してXファイルをロードします1. Html5SaveOptionsのインスタンスを作成します1. 高度な書式設定のプロパティを設定する1. Html5SaveOptionsのオブジェクトを使用してScene.Saveメソッドを呼び出します1. デフォルトのブラウザで結果のHTMLファイルを確認します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NETは、すべての主要なオペレーティングシステムでサポートされています。次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windowsまたは.NETフレームワーク、.NETコア、Monoと互換性のあるOS- MicrosoftVisualStudioのような開発環境- プロジェクトで参照されているAspose.3Dfor .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Xを表示するためのC#コード" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// Sceneのインスタンスを介してXシーンをロードします
var scene = new ThreeD.Scene("template.x");
// Html5SaveOptionsのオブジェクトを作成し、フォーマット用のプロパティを設定します
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // グリッドをオフにします
    ShowGrid = false,
    // ユーザーインターフェイスをオフにします
    ShowUI = false
};

// 3DシーンをHTML5として保存
scene.Save(output, options);
// 結果のHTMLをデフォルトのブラウザにロードします
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="約Aspose.3Dfor .NETAPI" %}}

 Aspose.3Dは、3Dファイルをロード、変更、変換するためのCADおよびゲームウェアAPIです。 APIはスタンドアロンであり、3Dモデリングまたはレンダリングソフトウェアを必要としません。 Discreet3DS、WavefrontOBJ、STL（ASCII、バイナリ）、Universal3D、FBX（ASCII、バイナリ）、Collada、glTF、PLY、 GLB、DirectXおよびその他の形式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Xを表示する無料アプリ" sectionDescription="ライブデモをチェックして [Xを表示](https://products.aspose.app/3d/viewer/x) 以下の利点があります。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 何かをダウンロードしたりセットアップしたりする必要はありません" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書いたりコンパイルしたりする必要はありません" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Xファイルをアップロードして[表示]ボタンを押すだけです" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" 必要に応じて、リンクからXファイルをダウンロードします" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="X" readMoreLink="https://docs.fileformat.com/3d/x/" >}}
Xは、ゲームでの3Dグラフィックレンダリング用のDirectXテクノロジで使用されるDirectXモデルの画像ファイルです。ファイル形式は、メッシュ、テクスチャ、アニメーション、およびオブジェクトの3Dオブジェクト構造を指定します。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされているビューア形式" subTitle="C#を使用すると、を含む他の多くのファイル形式を表示することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3DスタジオDOSメッシュ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D製造フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="アディティブマニュファクチャリングフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="2Dアニメーションファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="デジタル資産交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="図面交換フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3Dファイルのバイナリ表現" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="GL伝送フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="木星テッセレーションファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3Dファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="ポリゴンファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="AVEVAプラント設計モデル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="交換可能な3D表面形状" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="仮想現実モデリング言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIPアーカイブ形式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}