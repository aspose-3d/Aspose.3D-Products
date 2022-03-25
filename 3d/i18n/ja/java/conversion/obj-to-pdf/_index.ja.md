﻿---
title: Java 経由で OBJ を PDF に変換 
url: /ja/java/conversion/obj-to-pdf/ 
description: OBJ 形式の Java ファイルへの変換コードのサンプル。このコード例を使用して、Webまたはデスクトップ Java ベースのアプリケーション内で OBJ を PDF に変換します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java 経由で OBJ を PDF に変換" h2="3D モデリングソフトウェアなしで Java ライブラリを使用した OBJ から PDF への変換。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Java を使用して OBJ を PDF に変換する方法" %}}

 OBJ を PDF にレンダリングするには、を使用します。
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API は、機能が豊富でパワフルで使いやすいコンバージョン API for Java プラットフォームです。から直接最新バージョンをダウンロードできます
 [メイヴン](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 以下の設定をpom.xmlに追加して、Mavenベースのプロジェクト内にインストールします。

{{% blocks/products/pf/agp/code-block title="リポジトリ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依存関係" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Java 経由で OBJ を PDF に変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Java 人のプログラマーは、わずか数行のコードで OBJ ファイルを PDF に簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介した OBJ ファイルの読み込み1. PdfSaveOptionsのインスタンスの作成1. 高度な変換のために PDF 固有のプロパティを設定する1. Scene.saveメソッドを呼び出す1. PDF ファイル拡張子とPdfSaveOptionsのオブジェクトで出力パスを渡す
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要件" %}}

{{% blocks/products/pf/agp/text %}}

 Java 変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft WindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用の Java ランタイム環境を備えた互換性のあるOS。- 最新バージョンの Aspose.3D for Java をMavenから直接入手してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OBJ ~ PDF Java 変換ソースコード" offSpacer="" %}}

```cs
// Sceneのオブジェクトに OBJ をロードする 
Scene document = new Scene("template.obj");
// PdfSaveOptionsのインスタンスを作成する 
AmfSaveOptions options = new PdfSaveOptions();
// OBJ を PDF として保存 
document.save("output.pdf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="OBJ から PDF の変換ライブデモ" sectionDescription="[OBJ を PDF に変換](https://products.aspose.app/3d/conversion/obj-to-pdf) ライブデモのウェブサイトをご覧ください。ライブデモには次の利点があります" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API をダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" OBJ ファイルをアップロードするだけで、即座に PDF に変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D シーン操作ライブラリ" %}}

 Aspose.3D は CAD で、 3D ファイルをロード、変更、変換するためのゲームウェア API です。 API はスタンドアロンであり、 3D モデリングまたはレンダリングソフトウェアを必要としません。 Discreet3DS 、 WavefrontOBJ 、 STL (ASCII、Binary) 、 Universal3D 、 FBX (ASCII、Binary) 、 Collada 、 glTF 、 PLY 、 GLB 、DirectXなどのフォーマットに API を簡単に使用できます。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

OBJ 個のファイルは、 Wavefront のAdvanced Visualizerアプリケーションによって、ジオメトリオブジェクトを定義および保存するために使用されます。 OBJ 個のファイルを介して、幾何学的データの後方および前方への送信が可能になります。ポイント、ライン、テクスチャ頂点、面、自由形式ジオメトリ (曲線とサーフェス) などのポリゴンジオメトリは、 OBJ 形式でサポートされています。このフォーマットは、アニメーションやシーンの光と位置に関する情報をサポートしていません。 OBJ ファイルは通常、 CAD (Computer Aided Design) によって生成された 3D モデリングプロセスの最終製品です。頂点を格納するデフォルトの順序は、顔の法線の明示的な宣言を回避する反時計回りです。 OBJ 個のファイルがコメント行にスケール情報を宣言していますが、 OBJ 個の座標の単位は宣言されていません。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

ポータブルドキュメント形式 (PDF) は、1990年代にアドビによって作成されたドキュメントの一種です。このファイル形式の目的は、アプリケーションソフトウェア、ハードウェア、およびオペレーティングシステムから独立した形式でドキュメントおよびその他の参考資料を表現するための標準を導入することでした。 PDF ファイルは、Adobe Acrobat Reader/Writerでも、Chrome、Safari、Firefoxなどの最新のブラウザで拡張機能/プラグインを介して開くことができます。市販のソフトウェアスイートのほとんどは、追加のソフトウェアコンポーネントを必要とせずに、ドキュメントを PDF ファイル形式に変換することもできます。したがって、 PDF ファイル形式には、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、デジタル署名、添付ファイル、メタデータ、地理空間機能、およびソースの一部となる可能性のある 3D オブジェクトなどの情報を含める完全な機能があります。ドキュメント。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされる変換" subTitle="OBJ を以下のいくつかを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-3ds/" name="OBJ から 3DS" description="3D Studio DOSメッシュ" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-amf/" name="OBJ から AMF" description="添加剤製造フォーマット" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-ase/" name="OBJ から ASE" description="2Dアニメーションファイル" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-dae/" name="OBJ から DAE" description="デジタル資産交換" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-fbx/" name="OBJ から FBX" description="3D フォーマット" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-gltf/" name="OBJ から GLTF" description="GL伝送形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-html/" name="OBJ から HTML" description="ハイパーテキストマークアップ言語" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-obj/" name="OBJ から OBJ" description="3D ファイル形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-ply/" name="OBJ から PLY" description="Polygonファイル形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-rvm/" name="OBJ から RVM" description="AVEVA植物デザインモデル" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-stl/" name="OBJ から STL" description="交換可能な 3D 面ジオメトリ" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-u3d/" name="OBJ から U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}