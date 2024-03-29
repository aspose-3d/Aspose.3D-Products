﻿---
title: C# aracılığıyla GLTF'i STL'ye dönüştürün 
url: /tr/net/conversion/gltf-to-stl/ 
description: GLTF - STL C# dönüşümü için örnek kod. VB.NET, Asp.NET veya herhangi bir .NET tabanlı uygulama içinde toplu GLTF dosyaları STL dönüştürme için API örnek kodunu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# aracılığıyla GLTF\'i STL\'ye dönüştürün" h2="Herhangi bir 3D modelleme ve oluşturma yazılımı olmadan GLTF\'i STL olarak oluşturun." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanılarak GLTF, STL\'ye Nasıl Dönüştürülür" %}}

 GLTF'i STL'ye dönüştürmek için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="C# aracılığıyla GLTF\'i STL\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programcıları, yalnızca birkaç kod satırıyla GLTF dosyalarını kolayca yükleyebilir ve STL'ye dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. GLTF dosyasını Scene sınıfının yapıcısı aracılığıyla yükleyin1. Bir AmfSaveOptions örneği oluşturun1. Gelişmiş dönüştürme için STL belirli özelliği ayarlayın1. Scene.Save yöntemini çağırın1. STL dosya uzantısı ve StlSaveOptions nesnesi ile çıktı yolunu iletin1. Belirtilen yolda ortaya çıkan STL dosyasını kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 .NET dönüştürme kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono ile uyumlu bir işletim sistemi.- Microsoft Visual Studio gibi geliştirme ortamı.- Projenizde başvurulan Aspose.3D for .NET DLL.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod, GLTF - STL C# Dönüşümünü gösterir" offSpacer="" %}}

```cs
// GLTF öğesini bir Sahne nesnesine yükleyin 
var document = new Aspose.ThreeD.Scene("template.gltf");
// bir StlSaveOptions örneği oluşturun 
var options = new Aspose.ThreeD.Formats.StlSaveOptions();
// GLTF'i STL olarak kaydet 
document.Save("output.stl", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="GLTF\'i STL\'e Dönüştürmek için Ücretsiz Uygulama" sectionDescription="için canlı demolarımızı kontrol edin [GLTF - STL dönüşüm](https://products.aspose.app/3d/conversion/gltf-to-stl) aşağıdaki faydaları ile." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Herhangi bir şey indirmenize veya kurmanıza gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece GLTF dosyanızı yükleyin ve \"Dönüştür\" düğmesine basın." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Elde edilen STL dosyasının indirme bağlantısını anında alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D dosyalarını herhangi bir modelleme ve işleme yazılımı olmadan işlemek için bir 3D Dosya İşleme Kitaplığı. 3D API, Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB'i destekler, PLY, DirectX, Google Draco dosya biçimleri ve daha fazlası. Geliştiriciler, 3D belge biçimlerinin özünü kolayca oluşturabilir, okuyabilir, dönüştürebilir, değiştirebilir ve kontrol edebilir.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (GL İletim Biçimi), 3D model bilgilerini JSON biçiminde depolayan bir 3D dosya biçimidir. JSON kullanımı, hem 3D varlıkların boyutunu hem de bu varlıkları paketinden çıkarmak ve kullanmak için gereken çalışma zamanı işlemlerini en aza indirir. Uygulamalar tarafından 3D sahnelerin ve modellerin verimli iletimi ve yüklenmesi için benimsenmiştir. glTF, Khronos Group 3D Formats Working Group tarafından geliştirilmiştir ve yaratıcıları tarafından 3D JPEG olarak da tanımlanır. Biçim, 3D içerik araçları ve yazma iş akışlarını kolaylaştıran ve endüstri genelinde içeriğin birlikte çalışabilir kullanımını sağlayan hizmetler için genişletilebilir, ortak bir yayınlama biçimi tanımlar. glTF dosya biçiminin yaratılmasının ardındaki amaç, 3D içerik araçları ve hizmetleri için, yazma iş akışlarını kolaylaştıracak ve endüstri genelinde içeriğin birlikte çalışabilir kullanımına olanak sağlayacak genişletilebilir, ortak bir yayınlama biçimi tanımlamaktı. WebGL ve diğer API'leri kullanan uygulamalar tarafından çalışma zamanı işlemeyi en aza indirir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="stl" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, stereolitrografinin kısaltması, 3 boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya biçimidir. Dosya biçimi, hızlı prototip oluşturma, 3D yazdırma ve bilgisayar destekli üretim gibi çeşitli alanlarda kullanımını bulur. Her yüzün dik bir yön ve üçgenin köşelerini temsil eden üç nokta ile tanımlandığı, yüzeyler olarak bilinen bir dizi küçük üçgen olarak bir yüzeyi temsil eder. Elde edilen veriler, uygulamalar tarafından fabber tarafından oluşturulacak 3D şeklinin enine kesitini belirlemek için kullanılır. STL dosya biçiminde renk, doku veya diğer yaygın CAD model niteliklerinin temsili için hiçbir bilgi bulunmamaktadır.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}