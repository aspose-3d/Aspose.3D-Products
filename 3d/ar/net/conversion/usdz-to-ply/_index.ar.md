﻿---
title: تحويل USDZ إلى PLY عبر C# 
description: تحويل USDZ وملفات 3D أخرى باستخدام .NET API
url: /ar/net/conversion/usdz-to-ply/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: PLY
otherformats: AMF DRC HTML FBX DAE ASE JT RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل USDZ إلى PLY عبر C#" h2="تصدير USDZ وملفات 3D أخرى باستخدام .NET Framework و .NET Core و Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تصدير USDZ المشهد كـ PLY بـ C#" %}}
1. تحميل ملف USDZ باستخدام مُنشئ لـ [مشهد](https://apireference.aspose.com/3d/net/aspose.threed/scene) صف دراسي2. الاتصال [المشهد](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) طريقة
3. قم بتمرير اسم ملف الإخراج بامتداد .ply كمعامل أول
4. حدد قيمة الحقل "PLY" من [تنسيق الملف](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) صف دراسي
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D تنسيق التحويل API for .NET" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.3d '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.3D ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# رمز التحويل من USDZ إلى PLY" gistPath="" %}}
```cs
// تحميل USDZ في كائن من المشهد 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// حفظ USDZ باسم PLY 
scene.Save("output.ply", Aspose.ThreeD.FileFormat.PLY);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}