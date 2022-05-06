﻿---
title: Java aracılığıyla FBX'i HTML'ye dönüştürün 
weight: 2370
url: /tr/java/conversion/fbx-to-html/ 
description: FBX biçimi için HTML dosyasına örnek Java dönüştürme kodu. Herhangi bir Web veya Masaüstü Java tabanlı uygulamada FBX'ü HTML'e dönüştürmek için bu örnek kodu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java aracılığıyla FBX\'i HTML\'ye dönüştürün" h2="Herhangi bir 3D modelleme yazılımı olmadan Java kitaplığını kullanarak FBX - HTML dönüştürme." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Java Kullanılarak FBX, HTML\'ye Nasıl Dönüştürülür" %}}

 FBX'i HTML olarak oluşturmak için kullanacağız
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 Zengin özelliklere sahip, güçlü ve kullanımı kolay bir dönüşüm API for Java platformu olan API. En son sürümünü doğrudan adresinden indirebilirsiniz.
 [Uzman](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
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

{{% blocks/products/pf/agp/feature-section-col title="Java aracılığıyla FBX\'i HTML\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Java programcıları, yalnızca birkaç satır kodla FBX dosyasını HTML'ye kolayca dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. FBX dosyasını Scene sınıfının yapıcısı aracılığıyla yükleyin1. HtmlSaveOptions örneğini oluşturun1. Gelişmiş dönüştürme için HTML belirli özelliği ayarlayın1. Scene.save yöntemini çağırın1. HTML dosya uzantısı ve HtmlSaveOptions nesnesi ile çıktı yolunu iletin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Java dönüştürme kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.- Aspose.3D for Java'in en son sürümünü doğrudan Maven'den alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="FBX - HTML Java Dönüşüm Kaynak Kodu" offSpacer="" %}}

```cs
// FBX öğesini bir Sahne nesnesine yükleyin 
Scene document = new Scene("template.fbx");
// HtmlSaveOptions örneğini oluşturun 
Html5SaveOptions options = new Html5SaveOptions();
// FBX'i HTML olarak kaydet 
document.save("output.html", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="FBX - HTML Dönüşüm Canlı Demoları" sectionDescription="[FBX\'i HTML\'ye dönüştür](https://products.aspose.app/3d/conversion/fbx-to-html) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece FBX dosyanızı yükleyin, anında HTML dosyasına dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Sahne Manipülasyon Kitaplığı" %}}

 Aspose.3D, 3D dosyalarını yüklemek, değiştirmek ve dönüştürmek için kullanılan bir CAD ve Oyun Yazılımıdır API. API bağımsızdır ve herhangi bir 3D modelleme veya işleme yazılımı gerektirmez. Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY için API kolayca kullanılabilir, GLB, DirectX ve diğer biçimler. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}

FBX, FilmBox, Kaydara tarafından MotionBuilder için geliştirilmiş, popüler bir 3D dosya biçimidir. 2006 yılında Autodesk Inc tarafından satın alındı ve şu anda birçok 3D aracı tarafından kullanılan ana 3D değişim biçimlerinden biri. FBX hem ikili hem de ASCII dosya biçiminde mevcuttur. Format, dijital içerik oluşturma uygulamaları arasında birlikte çalışabilirliği sağlamak için oluşturulmuştur. FBX dosya biçiminden/dosya biçimine dönüştürme için kullanılabilecek birçok araç vardır.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Köprü Metni İşaretleme Dili), tarayıcılarda görüntülenmek üzere oluşturulmuş web sayfalarının uzantısıdır. Web dili olarak bilinen HTML, web sayfalarının bir parçası olarak görüntülenecek yeni bilgi gereksinimleri gereksinimleriyle gelişmiştir. En son varyant, dille çalışmak için çok fazla esneklik sağlayan HTML 5 olarak bilinir. HTML sayfalar, barındırıldığı sunucudan alınır veya yerel sistemden de yüklenebilir. Her HTML sayfası, formlar, metinler, resimler, animasyonlar, bağlantılar vb. gibi HTML öğeden oluşur. Bu öğeler, img, a, p gibi etiketlerle ve her bir etiketin başlangıç ve bitiş olduğu diğer birkaç etiketle temsil edilir. . Ayrıca, genel düzen gösterimi için JavaScript ve Stil Sayfaları (CSS) gibi komut dosyası dillerinde yazılmış uygulamaları da gömebilir.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca, FBX\'i aşağıda listelenen birkaç dosya biçimi de dahil olmak üzere birçok başka dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-3ds/" name="FBX - 3DS" description="3D Studio DOS Ağı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-amf/" name="FBX - AMF" description="Eklemeli Üretim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-ase/" name="FBX - ASE" description="2D Animasyon Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-dae/" name="FBX - DAE" description="Dijital Varlık Değişimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-gltf/" name="FBX - GLTF" description="GL İletim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-obj/" name="FBX - OBJ" description="3D Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-ply/" name="FBX - PLY" description="Çokgen Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-rvm/" name="FBX - RVM" description="AVEVA Fabrika Tasarım Modeli" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-stl/" name="FBX - STL" description="Değiştirilebilir 3D Yüzey Geometrisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-u3d/" name="FBX - U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}