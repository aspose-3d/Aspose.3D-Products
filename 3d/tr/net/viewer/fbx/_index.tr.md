﻿---
title: FBX Dosya Biçimlerini .NET aracılığıyla görüntüleyin 
weight: 910
url: /tr/net/viewer/fbx/ 
description: .NET Framework, .NET Core, Mono üzerinde FBX belgeleri yüklemek, oluşturmak ve görüntülemek için C# kaynak kodu.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="FBX Dosya Görüntüleyici for .NET" h2="FBX dosyalarını herhangi bir 3D modelleme ve işleme yazılımı olmadan işleyin." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanılarak FBX Dosyası Nasıl Görüntülenir" %}}

 FBX dosyasını görüntülemek için kullanacağız
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 C# platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir API olan API, herhangi bir Görüntüleyici ile kullanılabilir. Açık
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 paket yöneticisi, ara
 **Aspose.3D** 
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yöneticisi Konsol Komutu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# üzerinden FBX Görüntüleme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D, geliştiricilerin FBX dosyasını yalnızca birkaç satır kodla görüntülemesini kolaylaştırır.

{{% /blocks/products/pf/agp/text %}}

1. FBX dosyasını Scene sınıfının yapıcısı aracılığıyla yükleyin1. Html5SaveOptions örneğini oluşturun1. Gelişmiş biçimlendirme için özellikleri ayarlayın1. Html5SaveOptions nesnesiyle Scene.Save yöntemini çağırın1. Ortaya çıkan HTML dosyasını varsayılan tarayıcıda kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET, tüm büyük işletim sistemlerinde desteklenir. Sadece aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono ile uyumlu bir işletim sistemi- Microsoft Visual Studio gibi geliştirme ortamı- Projenizde referans verilen Aspose.3D for .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="FBX görüntülemek için C# kodu" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// FBX sahnesini bir Sahne örneği aracılığıyla yükle
var scene = new ThreeD.Scene("template.fbx");
// bir Html5SaveOptions nesnesi oluşturun ve biçimlendirme için özellikleri ayarlayın
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // şebekeyi kapat
    ShowGrid = false,
    // kullanıcı arayüzünü kapat
    ShowUI = false
};

// 3D sahnesini HTML5 olarak kaydet
scene.Save(output, options);
// HTML sonucunu varsayılan tarayıcıya yükle
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.3D for .NET API hakkında" %}}

 Aspose.3D, 3D dosyalarını yüklemek, değiştirmek ve dönüştürmek için kullanılan bir CAD ve Oyun Yazılımıdır API. API bağımsızdır ve herhangi bir 3D modelleme veya işleme yazılımı gerektirmez. Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY için API kolayca kullanılabilir, GLB, DirectX ve diğer biçimler. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Görüntülemek için Ücretsiz Uygulama FBX" sectionDescription="için canlı demolarımızı kontrol edin [FBX görüntüle](https://products.aspose.app/3d/viewer/fbx) aşağıdaki faydaları ile." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Hiçbir şey indirmenize veya kurmanıza gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Kod yazmaya veya derlemeye gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece FBX dosyasını yükleyin ve \"Görüntüle\" düğmesine basın" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Gerekirse bağlantıdan FBX dosyasını indirin" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, Kaydara tarafından MotionBuilder için geliştirilmiş, popüler bir 3D dosya biçimidir. 2006 yılında Autodesk Inc tarafından satın alındı ve şu anda birçok 3D aracı tarafından kullanılan ana 3D değişim biçimlerinden biri. FBX hem ikili hem de ASCII dosya biçiminde mevcuttur. Format, dijital içerik oluşturma uygulamaları arasında birlikte çalışabilirliği sağlamak için oluşturulmuştur. FBX dosya biçiminden/dosya biçimine dönüştürme için kullanılabilecek birçok araç vardır.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Görüntüleyici Formatları" subTitle="C# kullanılarak One, aşağıdakiler de dahil olmak üzere diğer birçok dosya biçimini görüntüleyebilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Studio DOS Ağı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D Üretim Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Eklemeli Üretim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="2D Animasyon Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Dijital Varlık Değişimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="Çizim Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D Dosya İkili Temsili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="GL İletim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="Jüpiter Mozaik Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Çokgen Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="AVEVA Fabrika Tasarım Modeli" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="Değiştirilebilir 3D Yüzey Geometrisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Sanal Gerçeklik Modelleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="x" description="DirectX Model Resmi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP Arşivleme Biçimi" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}