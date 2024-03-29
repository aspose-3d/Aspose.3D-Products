﻿---
title: Java aracılığıyla DRC'i PDF'ye dönüştürün
weight: 530
url: /tr/java/conversion/drc-to-pdf/ 
description: DRC biçimi için PDF dosyasına örnek Java dönüştürme kodu. Herhangi bir Web veya Masaüstü Java tabanlı uygulamada DRC'ü PDF'e dönüştürmek için bu örnek kodu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java aracılığıyla DRC\'i PDF\'ye dönüştürün" h2="Herhangi bir 3D modelleme yazılımı olmadan Java kitaplığını kullanarak DRC - PDF dönüştürme." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Java Kullanılarak DRC, PDF\'ye Nasıl Dönüştürülür" %}}

 DRC'i PDF olarak oluşturmak için kullanacağız
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 Zengin özelliklere sahip, güçlü ve kullanımı kolay bir dönüşüm API for Java platformu olan API. En son sürümünü doğrudan adresinden indirebilirsiniz.
 [Uzman](https://repository.aspose.com/3d/) 
 ve pom.xml dosyasına aşağıdaki konfigürasyonları ekleyerek Maven tabanlı projenize kurun.

{{% blocks/products/pf/agp/code-block title="depo" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Bağımlılık" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Java aracılığıyla DRC\'i PDF\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Java programcıları, yalnızca birkaç satır kodla DRC dosyasını PDF'ye kolayca dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. DRC dosyasını Scene sınıfının yapıcısı aracılığıyla yükleyin1. PDF biçimiyle Scene.save yöntemini çağırın.1. Belirtilen yolda ortaya çıkan PDF dosyasını kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Java dönüştürme kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.- Aspose.3D for Java'in en son sürümünü doğrudan Maven'den alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DRC - PDF Java Dönüşüm Kaynak Kodu" offSpacer="" %}}

```cs
// Kaynak Google Draco dosyasını yükleyin
Scene scene = new Scene("sourceFile.drc");
// 3D sahnesini 3D PDF biçiminde dosyaya dönüştürün
scene.save("output.pdf", FileFormat.PDF)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DRC - PDF Dönüşüm Canlı Demoları" sectionDescription="[DRC\'i PDF\'ye dönüştür](https://products.aspose.app/3d/conversion/drc-to-pdf) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece DRC dosyanızı yükleyin, anında PDF dosyasına dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Sahne Manipülasyon Kitaplığı" %}}

 Aspose.3D, 3D dosyalarını yüklemek, değiştirmek ve dönüştürmek için kullanılan bir CAD ve Oyun Yazılımıdır API. API bağımsızdır ve herhangi bir 3D modelleme veya işleme yazılımı gerektirmez. USD, Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF için API kolayca kullanılabilir, PLY, GLB, DirectX ve diğer biçimler. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}

.drc uzantılı bir dosya, Google Draco kitaplığıyla oluşturulmuş sıkıştırılmış bir 3D dosya biçimidir. Google, 3D geometrik ağları ve nokta bulutlarını sıkıştırmak ve sıkıştırmasını açmak için açık kaynak kitaplığı olarak Draco sunar ve 3D grafiklerinin depolanmasını ve iletimini iyileştirir. Girilen verileri kodlar ve .drc dosyası olarak kaydeder. Alıcı tarafta, API .drc dosyalarını okur ve bunların çıktısını PLY veya OBJ dosyaları olarak verebilir. Sıkıştırılmış çıktı dosyası, kullanıcıların uygulamaları daha hızlı indirmesini sağlar ve 3D grafiğin tarayıcılara hızlı yüklenmesini sağlar.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/3d/pdf/" >}}

Taşınabilir Belge Biçimi (PDF), Adobe tarafından 1990'larda oluşturulmuş bir belge türüdür. Bu dosya biçiminin amacı, belgelerin ve diğer başvuru malzemelerinin uygulama yazılımı, donanım ve İşletim Sisteminden bağımsız bir biçimde temsil edilmesi için bir standart getirmekti. PDF dosyaları, uzantılar/eklentiler aracılığıyla Adobe Acrobat Reader/Writer'da ve Chrome, Safari, Firefox gibi çoğu modern tarayıcıda açılabilir. Ticari olarak satılan yazılım paketlerinin çoğu, herhangi bir ek yazılım bileşenine gerek duymadan belgelerinin PDF dosya biçimine dönüştürülmesini de sağlar.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca, DRC\'i aşağıda listelenen birkaç dosya biçimi de dahil olmak üzere birçok başka dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-gltf/" name="DRC - GLTF" description="GL İletim Format Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-glb/" name="DRC - GLB" description="İkili GL İletim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-pdf/" name="DRC - PDF" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-fbx/" name="DRC - FBX" description="Autodesk FBX Değişim Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-stl/" name="DRC - STL" description="Stereolitografi Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-obj/" name="DRC - OBJ" description="Wavefront 3D Nesne Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-3ds/" name="DRC - 3DS" description="3D Stüdyo Sahnesi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-dae/" name="DRC - DAE" description="Dijital Varlık Değişim Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-u3d/" name="DRC - U3D" description="Universal 3D Dosya" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-ply/" name="DRC - PLY" description="Çokgen Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-rvm/" name="DRC - RVM" description="AVVA RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-jt/" name="DRC - JT" description="JT CAD Dosyasını Aç" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-amf/" name="DRC - AMF" description="Eklemeli İmalat Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-html/" name="DRC - HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-usd/" name="DRC - USD" description="Evrensel Sahne Tanımlama Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/drc-to-usdz/" name="DRC - USDZ" description="Evrensel Sahne Açıklaması Sıkıştırılmış Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}