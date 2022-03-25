﻿---
title: DXF 'i C# ile GLTF 'ye dönüştürün 
url: /tr/net/conversion/dxf-to-gltf/ 
description: DXF ila GLTF C# dönüşümü için örnek kod. .NET, Asp.NET veya herhangi bir .NET tabanlı uygulamada GLTF dönüşümüne kadar toplu DXF dosyaları için API örnek kodu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="DXF \'i C# ile GLTF \'ye dönüştürün" h2="DXF, herhangi bir 3D modelleme ve oluşturma yazılımı olmadan GLTF olarak kullanın." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanarak DXF \'i GLTF \'e Nasıl Dönüştürebilirsiniz?" %}}

 DXF 'i GLTF 'ye dönüştürmek için kullanacağız
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, C# platformu için özellik açısından zengin, güçlü ve kullanımı kolay bir belge manipülasyonu ve dönüşümü API. Açık
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Paket yöneticisi, arama için
 Aspose.3D 
 Ve yükleyin. Paket Yöneticisi Konsolu'ndan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yöneticisi Konsolu Komutanlığı" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# üzerinden DXF ile GLTF \'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programcılar, DXF dosyalarını sadece birkaç satır kodla GLTF 'ye kolayca yükleyebilir ve dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. Scene sınıfının kurucusu aracılığıyla DXF dosyasını yükle1. AmfSaveOptions örneğini oluşturun1. Gelişmiş dönüşüm için GLTF özel özellikler ayarlayın1. Sahneyi arayın. Kaydet yöntemi1. GLTF dosya uzantısı ve GltfSaveOptions nesnesi ile çıkış yolunu geçin1. Belirtilen yolda ortaya çıkan GLTF dosyasını kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sistem Gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 .NET dönüştürme kodunu çalıştırmadan önce, aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono ile uyumlu bir işletim sistemi.- Microsoft Visual Studio gibi geliştirme ortamı.- Aspose.3D for .NET DLL projenizde referans alınmıştır.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod DXF ila GLTF C# Dönüşümü gösterir" offSpacer="" %}}

```cs
// Bir sahne nesnesine DXF yükleyin 
var document = new Aspose.ThreeD.Scene("template.dxf");
// GltfSaveOptions örneğini oluşturun 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions();
// DXF 'i GLTF olarak kaydedin 
document.Save("output.gltf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DXF \'i GLTF \'e Dönüştürmek için Ücretsiz Uygulama" sectionDescription="Canlı demolarımızı kontrol edin [DXF ila GLTF dönüşüm](https://products.aspose.app/3d/conversion/dxf-to-gltf) Aşağıdaki faydaları ile." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Hiçbir şey indirmeye veya kurmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece DXF dosyanızı yükleyin ve \"Dönüştür\" düğmesine basın." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ortaya çıkan GLTF dosyası için indirme bağlantısını anında alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D Dosya İşleme Kitaplığı, herhangi bir modelleme ve oluşturma yazılımı olmadan 3D dosyayı işlemek için. 3D API, Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, İkili), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco dosya formatları ve daha fazlası. Geliştiriciler, 3D belge formatlarının maddesini kolayca oluşturabilir, okuyabilir, dönüştürebilir, değiştirebilir ve kontrol edebilir.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}
DXF, Drawing Interchange Format veya Drawing Exchange Format, AutoCAD çizim dosyasının etiketli bir veri temsilidir. Dosyadaki her öğenin grup kodu adı verilen bir önek tam sayı numarası vardır. Bu grup kodu aslında takip eden öğeyi temsil eder ve belirli bir nesne türü için bir veri öğesinin anlamını gösterir. DXF, bir çizim dosyasında neredeyse tüm kullanıcı tarafından belirtilen bilgileri temsil etmeyi mümkün kılar. DXF dosya formatı Autodesk tarafından AutoCAD ve diğer uygulamalar arasında veri birlikte çalışabilirlik için CAD veri dosyası biçimi olarak geliştirilmiştir. Böylece veriler, DXF dosya biçimi birlikte çalışabilirlik özelliklerine göre diğer formatlardan DXF AutoCAD'e diğer formatlardan içe aktarılabilir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="gltf" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (GL İletim Biçimi), 3D model bilgilerini JSON formatında depolayan bir 3D dosya biçimidir. JSON kullanımı, hem 3D varlıkların boyutunu hem de bu varlıkları açmak ve kullanmak için gereken çalışma zamanı işlemeyi en aza indirir. 3D sahnelerin ve modellerin uygulamalar tarafından verimli bir şekilde iletilmesi ve yüklenmesi için benimsenmiştir. glTF, Khronos Group 3D Biçimleri Çalışma Grubu tarafından geliştirilmiştir ve yaratıcıları tarafından 3D 'in JPEG olarak tanımlanmaktadır. Biçim, yazma iş akışlarını kolaylaştıran ve endüstri genelinde birlikte çalışabilir içerik kullanımını sağlayan 3D içerik araçları ve hizmetleri için genişletilebilir, yaygın bir yayınlama biçimini tanımlar. glTF dosya formatının oluşturulmasının arkasındaki amaç, yazma iş akışlarını kolaylaştırması ve endüstri genelinde birlikte çalışabilir içerik kullanımını etkinleştirmesi gereken 3D içerik araçları ve hizmetleri için genişletilebilir, ortak bir yayınlama formatı tanımlamaktı. WebGL ve diğer API'leri kullanan uygulamalar tarafından çalışma zamanı işlemeyi en aza indirir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Dönüşümler" subTitle="Ayrıca DXF \'i aşağıda listelenen birkaç dosya da dahil olmak üzere diğer birçok dosya formatına dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-3ds/" name="DXF TO 3DS" description="3D Stüdyo DOS Mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-amf/" name="DXF TO AMF" description="Katkı Üretim Formatı" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-dae/" name="DXF TO DAE" description="Dijital Varlık Değişimi" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-fbx/" name="DXF TO FBX" description="3D Formatı" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-html/" name="DXF TO HTML" description="Hiper Metin Biçimlendirme Dili" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-obj/" name="DXF TO OBJ" description="3D Dosya Biçimi" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-pdf/" name="DXF TO PDF" description="Taşınabilir Belge Biçimi" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-ply/" name="DXF TO PLY" description="Çokgen Dosya Biçimi" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-rvm/" name="DXF TO RVM" description="AVEVA Bitki Tasarım Modeli" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-stl/" name="DXF TO STL" description="Değiştirilebilir 3D Yüzey Geometrisi" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-u3d/" name="DXF TO U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}