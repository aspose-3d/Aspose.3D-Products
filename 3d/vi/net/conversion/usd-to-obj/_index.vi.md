﻿---
title: Chuyển đổi USD sang OBJ qua C# 
description: Chuyển đổi USD và các tệp 3D khác bằng cách sử dụng .NET API
url: /vi/net/conversion/usd-to-obj/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: OBJ
otherformats: PDF FBX PLY RVM JT ASE HTML GLTF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Chuyển đổi USD sang OBJ qua C#" h2="Xuất các tệp USD và 3D khác bằng cách sử dụng .NET Framework, .NET Core và Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Xuất USD Cảnh dưới dạng OBJ với C#" %}}
1. Tải tệp USD bằng cách sử dụng hàm tạo của [Bối cảnh](https://apireference.aspose.com/3d/net/aspose.threed/scene) lớp2. Gọi [Scene.Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) phương pháp
3. Chuyển tên tệp đầu ra có phần mở rộng .obj làm tham số đầu tiên
4. Chỉ định giá trị trường `WavefrontOBJ` từ [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) lớp
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Chuyển đổi Định dạng API for .NET" %}}
Cài đặt từ dòng lệnh dưới dạng `` nuget install Aspose.3d '' 'hoặc qua Bảng điều khiển Trình quản lý Gói của Visual Studio với `` Gói cài đặt Aspose.3D' '.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Mã cho Chuyển đổi USD sang OBJ" gistPath="" %}}
```cs
// tải USD trong một đối tượng của Scene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// lưu USD dưới dạng OBJ 
scene.Save("output.obj", Aspose.ThreeD.FileFormat.WavefrontOBJ);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}