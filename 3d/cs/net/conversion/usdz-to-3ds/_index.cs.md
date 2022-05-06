﻿---
title: Převést USDZ na 3DS prostřednictvím C# 
description: Převeďte USDZ a další soubory 3D pomocí .NET API
url: /cs/net/conversion/usdz-to-3ds/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: 3DS
otherformats: OBJ PDF FBX RVM GLTF DRC ASE DXF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Převést USDZ na 3DS prostřednictvím C#" h2="Exportujte USDZ a další soubory 3D pomocí .NET Framework, .NET Core a Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportovat scénu USDZ jako 3DS pomocí C#" %}}
1. Načtěte soubor USDZ pomocí konstruktoru z [Scéna](https://apireference.aspose.com/3d/net/aspose.threed/scene) třída2. Zavolejte [Scene.Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) metoda
3. Jako první parametr předejte název výstupního souboru s příponou .3ds
4. Zadejte hodnotu pole „Discreet3DS“ od [Formát souboru](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) třída
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Převod formátu API for .NET" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.3d``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.3D```.

Případně můžete získat offline instalační program MSI nebo knihovny DLL v souboru ZIP [stahování](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Kód pro konverzi USDZ na 3DS" gistPath="" %}}
```cs
// načtěte USDZ do objektu scény 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// uložit USDZ jako 3DS 
scene.Save("output.3ds", Aspose.ThreeD.FileFormat.Discreet3DS);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}