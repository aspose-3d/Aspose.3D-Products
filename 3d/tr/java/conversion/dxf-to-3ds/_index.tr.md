﻿---
title: Java aracılığıyla DXF'i 3DS'ye dönüştürün 
weight: 510
url: /tr/java/conversion/dxf-to-3ds/ 
description: DXF biçimi için 3DS dosyasına örnek Java dönüştürme kodu. Herhangi bir Web veya Masaüstü Java tabanlı uygulamada DXF'ü 3DS'e dönüştürmek için bu örnek kodu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java aracılığıyla DXF\'i 3DS\'ye dönüştürün" h2="Herhangi bir 3D modelleme yazılımı olmadan Java kitaplığını kullanarak DXF - 3DS dönüştürme." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Java Kullanılarak DXF, 3DS\'ye Nasıl Dönüştürülür" %}}

 DXF'i 3DS olarak oluşturmak için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="Java aracılığıyla DXF\'i 3DS\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Java programcıları, yalnızca birkaç satır kodla DXF dosyasını 3DS'ye kolayca dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. DXF dosyasını Scene sınıfının yapıcısı aracılığıyla yükleyin1. Bir 3dsSaveOptions örneği oluşturun1. Gelişmiş dönüştürme için 3DS belirli özelliği ayarlayın1. Scene.save yöntemini çağırın1. 3DS dosya uzantısı ve 3dsSaveOptions nesnesi ile çıktı yolunu iletin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Java dönüştürme kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.- Aspose.3D for Java'in en son sürümünü doğrudan Maven'den alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DXF - 3DS Java Dönüşüm Kaynak Kodu" offSpacer="" %}}

```cs
// DXF öğesini bir Sahne nesnesine yükleyin 
Scene document = new Scene("template.dxf");
// bir 3dsSaveOptions örneği oluşturun 
Discreet3dsSaveOptions options = new Discreet3dsSaveOptions();
// DXF'i 3DS olarak kaydet 
document.save("output.3ds", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DXF - 3DS Dönüşüm Canlı Demoları" sectionDescription="[DXF\'i 3DS\'ye dönüştür](https://products.aspose.app/3d/conversion/dxf-to-3ds) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece DXF dosyanızı yükleyin, anında 3DS dosyasına dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Sahne Manipülasyon Kitaplığı" %}}

 Aspose.3D, 3D dosyalarını yüklemek, değiştirmek ve dönüştürmek için kullanılan bir CAD ve Oyun Yazılımıdır API. API bağımsızdır ve herhangi bir 3D modelleme veya işleme yazılımı gerektirmez. Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY için API kolayca kullanılabilir, GLB, DirectX ve diğer biçimler. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}

DXF, Çizim Değişim Biçimi veya Çizim Değişim Biçimi, AutoCAD çizim dosyasının etiketli bir veri temsilidir. Dosyadaki her öğenin, grup kodu adı verilen bir ön ek tamsayı numarası vardır. Bu grup kodu aslında takip eden öğeyi temsil eder ve belirli bir nesne türü için bir veri öğesinin anlamını belirtir. DXF, bir çizim dosyasında hemen hemen tüm kullanıcı tanımlı bilgileri temsil etmeyi mümkün kılar. DXF dosya formatı, AutoCAD ve diğer uygulamalar arasında veri birlikte çalışabilirliği için Autodesk tarafından CAD veri dosyası formatı olarak geliştirilmiştir. Böylece, veriler DXF dosya formatı birlikte çalışabilirlik özelliklerine göre diğer formatlardan DXF'e AutoCAD'e aktarılabilir.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}

3DS uzantılı bir dosya, Autodesk 3D Studio tarafından kullanılan 3D Studio (DOS) ağ dosyası biçimini temsil eder. Autodesk 3D Studio, 1990'lardan beri 3D dosya formatı pazarındadır ve şimdi 3D modelleme, animasyon ve işleme ile çalışmak için 3D Studio MAX'a dönüşmüştür. Bir 3DS dosyası, sahnelerin ve görüntülerin 3D temsili için veriler içerir ve 3D veri içe ve dışa aktarma için popüler dosya biçimlerinden biridir. Bir sahneyi oluşturmak için tepe noktaları ve çokgenler oluşturmak için kamera konumları, Kafes verileri, aydınlatma bilgileri, görünüm alanı yapılandırmaları, düzleştirme grubu verileri, bitmap referansları ve öznitelikler gibi bilgileri dikkate alır.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca, DXF\'i aşağıda listelenen birkaç dosya biçimi de dahil olmak üzere birçok başka dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-amf/" name="DXF - AMF" description="Eklemeli Üretim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ase/" name="DXF - ASE" description="2D Animasyon Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-dae/" name="DXF - DAE" description="Dijital Varlık Değişimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-fbx/" name="DXF - FBX" description="3D Biçim" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-gltf/" name="DXF - GLTF" description="GL İletim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-html/" name="DXF - HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-obj/" name="DXF - OBJ" description="3D Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ply/" name="DXF - PLY" description="Çokgen Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-rvm/" name="DXF - RVM" description="AVEVA Fabrika Tasarım Modeli" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-stl/" name="DXF - STL" description="Değiştirilebilir 3D Yüzey Geometrisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-u3d/" name="DXF - U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}