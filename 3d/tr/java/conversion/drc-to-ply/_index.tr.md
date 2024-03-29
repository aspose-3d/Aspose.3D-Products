﻿---
title: Java aracılığıyla DRC'i PLY'ye dönüştürün 
url: /tr/java/conversion/drc-to-ply/ 
description: DRC biçimi için PLY dosyasına örnek Java dönüştürme kodu. Herhangi bir Web veya Masaüstü Java tabanlı uygulamada DRC'ü PLY'e dönüştürmek için bu örnek kodu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java aracılığıyla DRC\'i PLY\'ye dönüştürün" h2="Herhangi bir 3D modelleme yazılımı olmadan Java kitaplığını kullanarak DRC - PLY dönüştürme." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="PLY" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Java Kullanılarak DRC, PLY\'ye Nasıl Dönüştürülür" %}}

 DRC'i PLY olarak oluşturmak için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="Java aracılığıyla DRC\'i PLY\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Java programcıları, yalnızca birkaç satır kodla DRC dosyasını PLY'ye kolayca dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. DRC dosyasını Scene sınıfının yapıcısı aracılığıyla yükleyin1. Bir PlySaveOptions örneği oluşturun1. Gelişmiş dönüştürme için PLY belirli özelliği ayarlayın1. Scene.save yöntemini çağırın1. PLY dosya uzantısı ve PlySaveOptions nesnesi ile çıktı yolunu iletin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Java dönüştürme kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.- Aspose.3D for Java'in en son sürümünü doğrudan Maven'den alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DRC - PLY Java Dönüşüm Kaynak Kodu" offSpacer="" %}}

```cs
// DRC öğesini bir Sahne nesnesine yükleyin 
Scene document = new Scene("template.drc");
// bir PlySaveOptions örneği oluşturun 
AmfSaveOptions options = new PlySaveOptions();
// DRC'i PLY olarak kaydet 
document.save("output.ply", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DRC - PLY Dönüşüm Canlı Demoları" sectionDescription="[DRC\'i PLY\'ye dönüştür](https://products.aspose.app/3d/conversion/drc-to-ply) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece DRC dosyanızı yükleyin, anında PLY dosyasına dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Sahne Manipülasyon Kitaplığı" %}}

 Aspose.3D, 3D dosyalarını yüklemek, değiştirmek ve dönüştürmek için kullanılan bir CAD ve Oyun Yazılımıdır API. API bağımsızdır ve herhangi bir 3D modelleme veya işleme yazılımı gerektirmez. Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY için API kolayca kullanılabilir, GLB, DirectX ve diğer biçimler. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}

.drc uzantılı bir dosya, Google Draco kitaplığıyla oluşturulmuş sıkıştırılmış bir 3D dosya biçimidir. Google, 3D geometrik ağları ve nokta bulutlarını sıkıştırmak ve sıkıştırmasını açmak için açık kaynak kitaplığı olarak Draco sunar ve 3D grafiklerinin depolanmasını ve iletimini iyileştirir. Girilen verileri kodlar ve .drc dosyası olarak kaydeder. Alıcı tarafta, API .drc dosyalarını okur ve bunların çıktısını PLY veya OBJ dosyaları olarak verebilir. Sıkıştırılmış çıktı dosyası, kullanıcıların uygulamaları daha hızlı indirmesini sağlar ve 3D grafiğin tarayıcılara hızlı yüklenmesini sağlar.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}

PLY, Çokgen Dosya Biçimi, çokgenler topluluğu olarak tanımlanan grafik nesnelerini depolayan 3D dosya biçimini temsil eder. Bu dosya biçiminin amacı, çok çeşitli modeller için kullanışlı olacak kadar genel olan basit ve kolay bir dosya türü oluşturmaktı. PLY dosya biçimi, kompakt depolama ve hızlı kaydetme ve yükleme için Binary biçiminin yanı sıra ASCII olarak gelir. Dosya biçimi, 3D dosya okuma desteği sağlayan farklı uygulamalar tarafından kullanılır.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}