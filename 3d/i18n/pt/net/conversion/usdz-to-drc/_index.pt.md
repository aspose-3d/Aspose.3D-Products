﻿---
title: Converter USDZ para DRC via C# 
description: Converta USDZ e outros 3D arquivos usando .NET API
url: /pt/net/conversion/usdz-to-drc/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: DRC
otherformats: FBX RVM OBJ PLY PDF STL DRC GLTF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converter USDZ para DRC via C#" h2="Exportar USDZ e outros arquivos 3D usando .NET Framework, .NET Core e Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportar USDZ cena como DRC com C#" %}}
1. Carregar USDZ arquivo usando um construtor de [Cena](https://apireference.aspose.com/3d/net/aspose.threed/scene) Classe2. Chamada [Cena. Salvar](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Método
3. Passe o nome do arquivo de saída com. Extensão drc como primeiro parâmetro
4. Especifique o valor do campo 'Draco' de [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Classe
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Conversão de Formato API for .NET" %}}
Instale a partir da linha de comando como '''nogget install Aspose.3d'' ''ou via Console do Package Manager do Visual Studio com'' 'Install-Package Aspose.3D'''.

Como alternativa, obtenha o instalador MSI offline ou DLLs em um arquivo ZIP de [Downloads](https://downloads.aspose.com/3d/net)...
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Código para USDZ para DRC Conversão" gistPath="" %}}
```cs
// Carregar o USDZ em um objeto de cena 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// Salvar USDZ como um DRC 
scene.Save("output.drc", Aspose.ThreeD.FileFormat.Draco);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}