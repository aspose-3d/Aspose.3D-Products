﻿---
title: Javaを介してGLTFをHTMLに変換します 
weight: 1700
url: /ja/java/conversion/gltf-to-html/ 
description: GLTF形式からHTMLファイルへのJava変換コードのサンプル。このサンプルコードを使用して、WebまたはデスクトップのJavaベースのアプリケーション内でGLTFをHTMLに変換します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Javaを介してGLTFをHTMLに変換します" h2="3Dモデリングソフトウェアを使用せずにJavaライブラリを使用してGLTFからHTMLに変換します。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してGLTFをHTMLに変換する方法" %}}

 GLTFをHTMLにレンダリングするために、
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 APIは、機能が豊富で、強力で、使いやすい変換APIfor Javaプラットフォームです。最新バージョンはから直接ダウンロードできます
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
 次の構成をpom.xmlに追加して、Mavenベースのプロジェクトにインストールします。

{{% blocks/products/pf/agp/code-block title="リポジトリ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/ </ url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依存" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-3d</artifactId>
<version>version of aspose-3d API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Javaを介してGLTFをHTMLに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Javaプログラマーは、わずか数行のコードでGLTFファイルをHTMLに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介してGLTFファイルをロードします1. HtmlSaveOptionsのインスタンスを作成します1. 高度な変換のためにHTML固有のプロパティを設定します1. Scene.saveメソッドを呼び出す1. HTMLファイル拡張子とHtmlSaveOptionsのオブジェクトを使用して出力パスを渡します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Java変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。- Mavenから直接Aspose.3Dfor Javaの最新バージョンを入手します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="GLTFからHTMLJavaへの変換ソースコード" offSpacer="" %}}

```cs
// シーンのオブジェクトにGLTFをロードします 
Scene document = new Scene("template.gltf");
// HtmlSaveOptionsのインスタンスを作成します 
Html5SaveOptions options = new Html5SaveOptions();
// GLTFをHTMLとして保存 
document.save("output.html", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="GLTFからHTMLへの変換ライブデモ" sectionDescription="[GLTFをHTMLに変換](https://products.aspose.app/3d/conversion/gltf-to-html) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" GLTFファイルをアップロードするだけで、すぐにHTMLに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Java3Dシーン操作ライブラリ" %}}

 Aspose.3Dは、3Dファイルをロード、変更、変換するためのCADおよびゲームウェアAPIです。 APIはスタンドアロンであり、3Dモデリングまたはレンダリングソフトウェアを必要としません。 Discreet3DS、WavefrontOBJ、STL（ASCII、バイナリ）、Universal3D、FBX（ASCII、バイナリ）、Collada、glTF、PLY、 GLB、DirectXおよびその他の形式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF（GL Transmission Format）は、3Dモデル情報をJSON形式で保存する3Dファイル形式です。 JSONを使用すると、3Dアセットのサイズと、それらのアセットを解凍して使用するために必要なランタイム処理の両方が最小限に抑えられます。アプリケーションによる3Dシーンとモデルの効率的な送信とロードに採用されました。 glTFは、Khronos Group 3D Formats Working Groupによって開発され、その作成者によって3DのJPEGとしても説明されています。この形式は、3Dコンテンツツールとサービスの拡張可能な共通の公開形式を定義し、オーサリングワークフローを合理化し、業界全体でコンテンツの相互運用可能な使用を可能にします。 glTFファイル形式の作成の背後にある意図は、オーサリングワークフローを合理化し、業界全体でコンテンツの相互運用可能な使用を可能にする3Dコンテンツツールとサービスの拡張可能な共通の公開形式を定義することでした。 WebGLやその他のAPIを使用するアプリケーションによるランタイム処理を最小限に抑えます。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML（ハイパーテキストマークアップ言語）は、ブラウザで表示するために作成されたWebページの拡張機能です。 Webの言語として知られるHTMLは、Webページの一部として表示される新しい情報要件の要件とともに進化してきました。最新のバリアントはHTML5として知られており、言語を操作するための多くの柔軟性を提供します。 HTMLページは、これらがホストされているサーバーから受信されるか、ローカルシステムからロードすることもできます。各HTMLページは、フォーム、テキスト、画像、アニメーション、リンクなどのHTML要素で構成されています。これらの要素は、img、a、pなどのタグで表され、各タグには開始と終了があります。 。また、全体的なレイアウト表現のために、JavaScriptやスタイルシート（CSS）などのスクリプト言語で記述されたアプリケーションを埋め込むこともできます。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="GLTFを、以下にリストされているものを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-3ds/" name="GLTFから3DS" description="3DスタジオDOSメッシュ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-amf/" name="GLTFからAMF" description="アディティブマニュファクチャリングフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-ase/" name="GLTFからASE" description="2Dアニメーションファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-dae/" name="GLTFからDAE" description="デジタル資産交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-fbx/" name="GLTFからFBX" description="3D形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-obj/" name="GLTFからOBJ" description="3Dファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-ply/" name="GLTFからPLY" description="ポリゴンファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-rvm/" name="GLTFからRVM" description="AVEVAプラント設計モデル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-stl/" name="GLTFからSTL" description="交換可能な3D表面形状" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-u3d/" name="GLTFからU3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}