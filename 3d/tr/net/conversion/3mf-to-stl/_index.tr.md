﻿---
title: C# aracılığıyla 3MF'i STL'ye dönüştürün 
weight: 1810
url: /tr/net/conversion/3mf-to-stl/ 
description: 3MF - STL C# dönüşümü için örnek kod. VB.NET, Asp.NET veya herhangi bir .NET tabanlı uygulama içinde toplu 3MF dosyaları STL dönüştürme için API örnek kodunu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# aracılığıyla 3MF\'i STL\'ye dönüştürün" h2="Herhangi bir 3D modelleme ve oluşturma yazılımı olmadan 3MF\'i STL olarak oluşturun." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3MF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanılarak 3MF, STL\'ye Nasıl Dönüştürülür" %}}

 3MF'i STL'ye dönüştürmek için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="C# aracılığıyla 3MF\'i STL\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programcıları, yalnızca birkaç kod satırıyla 3MF dosyalarını kolayca yükleyebilir ve STL'ye dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. 3MF dosyasını Scene sınıfının yapıcısı aracılığıyla yükleyin1. Bir StlSaveOptions örneği oluşturun1. Gelişmiş dönüştürme için STL belirli özelliği ayarlayın1. Scene.Save yöntemini çağırın1. STL dosya uzantısı ve StlSaveOptions nesnesi ile çıktı yolunu iletin1. Belirtilen yolda ortaya çıkan STL dosyasını kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 .NET dönüştürme kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono ile uyumlu bir işletim sistemi.- Microsoft Visual Studio gibi geliştirme ortamı.- Projenizde başvurulan Aspose.3D for .NET DLL.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod, 3MF - STL C# Dönüşümünü gösterir" offSpacer="" %}}

```cs
// 3MF öğesini bir Sahne nesnesine yükleyin 
var document = new Aspose.ThreeD.Scene("template.3mf");
// bir StlSaveOptions örneği oluşturun 
var options = new Aspose.ThreeD.Formats.StlSaveOptions();
// 3MF'i STL olarak kaydet 
document.Save("output.stl", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="3MF\'i STL\'e Dönüştürmek için Ücretsiz Uygulama" sectionDescription="için canlı demolarımızı kontrol edin [3MF - STL dönüşüm](https://products.aspose.app/3d/conversion/3mf-to-stl) aşağıdaki faydaları ile." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Herhangi bir şey indirmenize veya kurmanıza gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece 3MF dosyanızı yükleyin ve \"Dönüştür\" düğmesine basın." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Elde edilen STL dosyasının indirme bağlantısını anında alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D dosyalarını herhangi bir modelleme ve işleme yazılımı olmadan işlemek için bir 3D Dosya İşleme Kitaplığı. 3D API, Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB'i destekler, PLY, DirectX, Google Draco dosya biçimleri ve daha fazlası. Geliştiriciler, 3D belge biçimlerinin özünü kolayca oluşturabilir, okuyabilir, dönüştürebilir, değiştirebilir ve kontrol edebilir.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}
3MF, 3D Üretim Biçimi, uygulamalar tarafından 3D nesne modellerini çeşitli başka uygulamalara, platformlara, hizmetlere ve yazıcılara sunmak için kullanılır. 3D yazıcıların en son sürümleriyle çalışmak için STL gibi diğer 3D dosya biçimlerindeki sınırlamalardan ve sorunlardan kaçınmak için oluşturulmuştur. 3MF, 3MF konsorsiyumu tarafından geliştirilmiş ve yayınlanmış nispeten yeni bir dosya biçimidir. Bir modeli tam olarak tanımlayacak kadar zengindir, dahili bilgileri, rengi ve onu 3D baskıda yeni yenilikleri desteklemek için genişletilebilir kılan diğer özellikleri korur. Format genişletilebilir, geniş çapta benimsenebilir ve yaygın olarak kullanılan diğer dosya formatlarını besleyen sorunlardan muaftır.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="stl" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, stereolitrografinin kısaltması, 3 boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya biçimidir. Dosya biçimi, hızlı prototip oluşturma, 3D yazdırma ve bilgisayar destekli üretim gibi çeşitli alanlarda kullanımını bulur. Her yüzün dik bir yön ve üçgenin köşelerini temsil eden üç nokta ile tanımlandığı, yüzeyler olarak bilinen bir dizi küçük üçgen olarak bir yüzeyi temsil eder. Elde edilen veriler, uygulamalar tarafından fabber tarafından oluşturulacak 3D şeklinin enine kesitini belirlemek için kullanılır. STL dosya biçiminde renk, doku veya diğer yaygın CAD model niteliklerinin temsili için hiçbir bilgi bulunmamaktadır.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca, 3MF\'i aşağıda listelenen birkaç dosya biçimi de dahil olmak üzere birçok başka dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-3ds/" name="3MF - 3DS" description="3D Studio DOS Ağı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-amf/" name="3MF - AMF" description="Eklemeli Üretim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-dae/" name="3MF - DAE" description="Dijital Varlık Değişimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-fbx/" name="3MF - FBX" description="3D Biçim" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-html/" name="3MF - HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-obj/" name="3MF - OBJ" description="3D Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-pdf/" name="3MF - PDF" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-ply/" name="3MF - PLY" description="Çokgen Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-rvm/" name="3MF - RVM" description="AVEVA Fabrika Tasarım Modeli" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-u3d/" name="3MF - U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}