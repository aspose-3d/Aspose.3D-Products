﻿---
title: Converteer USDZ naar DXF via C# 
description: Converteer USDZ en andere 3D bestanden met .NET API
url: /nl/net/conversion/usdz-to-dxf/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: DXF
otherformats: PLY OBJ PDF AMF RVM STL DXF ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converteer USDZ naar DXF via C#" h2="Exporteer USDZ en andere 3D bestanden met .NET Framework, .NET Core en Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exporteer USDZ Scene als DXF met C#" %}}
1. Laad USDZ bestand met een constructor van [Tafereel](https://apireference.aspose.com/3d/net/aspose.threed/scene) klas2. Bel [Scène.Opslaan](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) methode
3. Geef de naam van het uitvoerbestand door met de extensie .dxf als eerste parameter
4. Geef veldwaarde 'DXF' op van [Bestandsformaat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) klas
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Formaatconversie API for .NET" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.3d``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.3D```.

kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code voor USDZ naar DXF conversie" gistPath="" %}}
```cs
// laad de USDZ in een object van Scene 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// sla USDZ op als een DXF 
scene.Save("output.dxf", Aspose.ThreeD.FileFormat.DXF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}