﻿---
title: C# aracılığıyla USDZ'i DXF'ye dönüştürün 
description: .NET API kullanarak USDZ ve diğer 3D dosyalarını dönüştürün
url: /tr/net/conversion/usdz-to-dxf/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: DXF
otherformats: PLY OBJ PDF AMF RVM STL DXF ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C# aracılığıyla USDZ\'i DXF\'ye dönüştürün" h2=".NET Framework, .NET Core ve Mono kullanarak USDZ ve diğer 3D dosyalarını dışa aktarın" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# ile USDZ Sahneyi DXF olarak dışa aktar" %}}
1. Bir oluşturucu kullanarak USDZ dosyasını yükleyin [Sahne](https://apireference.aspose.com/3d/net/aspose.threed/scene) sınıf2. Çağrı [Sahne.Kaydet](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) yöntem
3. İlk parametre olarak .dxf uzantılı çıktı dosyası adını iletin
4. Şuradan `DXF` alan değerini belirtin: [Dosya formatı](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) sınıf
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Biçim Dönüştürme API for .NET" %}}
Komut satırından ```nuget install Aspose.3d``` veya ```Install-Package Aspose.3D`` ile Visual Studio'nun Paket Yönetici Konsolu aracılığıyla yükleyin.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri şu adresten bir ZIP dosyasında alın: [İndirilenler](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="USDZ - DXF Dönüşümü için C# Kodu" gistPath="" %}}
```cs
// USDZ öğesini bir Sahne nesnesine yükleyin 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// USDZ'i DXF olarak kaydet 
scene.Save("output.dxf", Aspose.ThreeD.FileFormat.DXF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}