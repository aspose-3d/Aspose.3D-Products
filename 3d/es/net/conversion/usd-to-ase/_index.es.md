﻿---
title: Convertir USD a ASE a través de C# 
description: Convierta USD y otros 3D archivos usando .NET API
url: /es/net/conversion/usd-to-ase/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: ASE
otherformats: ASE 3DS STL PLY GLTF DAE DRC HTML 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir USD a ASE a través de C#" h2="Exporte USD y otros 3D archivos usando .NET Framework, .NET Core y Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportar USD escena como ASE con C#" %}}
1. Cargue el archivo USD usando un constructor de [Escena](https://apireference.aspose.com/3d/net/aspose.threed/scene) clase2. Llamar [Escena.Guardar](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) método
3. Pase el nombre del archivo de salida con la extensión .ase como primer parámetro
4. Especifique el valor del campo `ASE` de [Formato de archivo](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) clase
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Conversión de formato API for .NET" %}}
Instale desde la línea de comandos como ```nuget install Aspose.3d``` o a través de la consola del administrador de paquetes de Visual Studio con ```Install-Package Aspose.3D```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP de [descargas](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Código para USD a ASE Conversión" gistPath="" %}}
```cs
// carga el USD en un objeto de Escena 
var scene = new Aspose.ThreeD.Scene("template.usd");
// guardar USD como ASE 
scene.Save("output.ase", Aspose.ThreeD.FileFormat.ASE);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}