﻿---
title: C# aracılığıyla STL'i DAE'ye dönüştürün 
weight: 2040
url: /tr/net/conversion/stl-to-dae/ 
description: STL - DAE C# dönüşümü için örnek kod. VB.NET, Asp.NET veya herhangi bir .NET tabanlı uygulama içinde toplu STL dosyaları DAE dönüştürme için API örnek kodunu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# aracılığıyla STL\'i DAE\'ye dönüştürün" h2="Herhangi bir 3D modelleme ve oluşturma yazılımı olmadan STL\'i DAE olarak oluşturun." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DAE" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="STL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanılarak STL, DAE\'ye Nasıl Dönüştürülür" %}}

 STL'i DAE'ye dönüştürmek için kullanacağız
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 C# platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge işleme ve dönüştürme API olan API. Açık
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 paket yöneticisi, ara
 Aspose.3D 
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yöneticisi Konsol Komutu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# aracılığıyla STL\'i DAE\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programcıları, yalnızca birkaç kod satırıyla STL dosyalarını kolayca yükleyebilir ve DAE'ye dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. STL dosyasını Scene sınıfının yapıcısı aracılığıyla yükleyin1. DaeSaveOptions örneğini oluşturun1. Gelişmiş dönüştürme için DAE belirli özelliği ayarlayın1. Scene.Save yöntemini çağırın1. DAE dosya uzantısı ve DaeSaveOptions nesnesi ile çıktı yolunu iletin1. Belirtilen yolda ortaya çıkan DAE dosyasını kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 .NET dönüştürme kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono ile uyumlu bir işletim sistemi.- Microsoft Visual Studio gibi geliştirme ortamı.- Projenizde başvurulan Aspose.3D for .NET DLL.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod, STL - DAE C# Dönüşümünü gösterir" offSpacer="" %}}

```cs
// STL öğesini bir Sahne nesnesine yükleyin 
var document = new Aspose.ThreeD.Scene("template.stl");
// DaeSaveOptions örneğini oluşturun 
var options = new Aspose.ThreeD.Formats.DaeSaveOptions();
// STL'i DAE olarak kaydet 
document.Save("output.dae", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="STL\'i DAE\'e Dönüştürmek için Ücretsiz Uygulama" sectionDescription="için canlı demolarımızı kontrol edin [STL - DAE dönüşüm](https://products.aspose.app/3d/conversion/stl-to-dae) aşağıdaki faydaları ile." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Herhangi bir şey indirmenize veya kurmanıza gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece STL dosyanızı yükleyin ve \"Dönüştür\" düğmesine basın." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Elde edilen DAE dosyasının indirme bağlantısını anında alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D dosyalarını herhangi bir modelleme ve işleme yazılımı olmadan işlemek için bir 3D Dosya İşleme Kitaplığı. 3D API, Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB'i destekler, PLY, DirectX, Google Draco dosya biçimleri ve daha fazlası. Geliştiriciler, 3D belge biçimlerinin özünü kolayca oluşturabilir, okuyabilir, dönüştürebilir, değiştirebilir ve kontrol edebilir.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, stereolitrografinin kısaltması, 3 boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya biçimidir. Dosya biçimi, hızlı prototip oluşturma, 3D yazdırma ve bilgisayar destekli üretim gibi çeşitli alanlarda kullanımını bulur. Her yüzün dik bir yön ve üçgenin köşelerini temsil eden üç nokta ile tanımlandığı, yüzeyler olarak bilinen bir dizi küçük üçgen olarak bir yüzeyi temsil eder. Elde edilen veriler, uygulamalar tarafından fabber tarafından oluşturulacak 3D şeklinin enine kesitini belirlemek için kullanılır. STL dosya biçiminde renk, doku veya diğer yaygın CAD model niteliklerinin temsili için hiçbir bilgi bulunmamaktadır.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="dae" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}
DAE dosyası, etkileşimli 3D uygulamaları arasında veri alışverişi için kullanılan bir Dijital Varlık Değişimi dosya biçimidir. Bu dosya formatı, dijital varlıkların grafik yazılım uygulamaları arasında değişimi için açık standart bir XML şeması olan COLLADA (COLLAborative Design Activity) XML şemasına dayanmaktadır. ISO tarafından halka açık bir spesifikasyon olarak ISO/pAS 17506 olarak kabul edilmiştir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca, STL\'i aşağıda listelenen birkaç dosya biçimi de dahil olmak üzere birçok başka dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-3ds/" name="STL - 3DS" description="3D Studio DOS Ağı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-amf/" name="STL - AMF" description="Eklemeli Üretim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-fbx/" name="STL - FBX" description="3D Biçim" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-html/" name="STL - HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-obj/" name="STL - OBJ" description="3D Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-pdf/" name="STL - PDF" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-ply/" name="STL - PLY" description="Çokgen Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-rvm/" name="STL - RVM" description="AVEVA Fabrika Tasarım Modeli" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-u3d/" name="STL - U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}