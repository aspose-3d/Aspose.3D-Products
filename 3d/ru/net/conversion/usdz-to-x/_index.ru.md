﻿---
title: Преобразовать USDZ в X через C# 
description: Преобразуйте USDZ и другие 3D файлы, используя .NET API
url: /ru/net/conversion/usdz-to-x/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: X
otherformats: HTML FBX STL DRC RVM DAE 3MF ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразовать USDZ в X через C#" h2="Экспорт USDZ и других файлов 3D с помощью .NET Framework, .NET Core и Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Экспорт USDZ сцены как X с помощью C#" %}}
1. Загрузите файл USDZ с помощью конструктора [Сцена](https://apireference.aspose.com/3d/net/aspose.threed/scene) класс2. Звонок [Сцена.Сохранить](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) метод
3. Передайте имя выходного файла с расширением .x в качестве первого параметра.
4. Укажите значение поля `XBinary` из [Формат файла](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) класс
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Преобразование формата API for .NET" %}}
Установите из командной строки как ```nuget install Aspose.3d``` или через консоль диспетчера пакетов Visual Studio с ```Install-Package Aspose.3D```.

Кроме того, можно получить автономный установщик MSI или библиотеки DLL в файле ZIP из [загрузки](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код C# для преобразования USDZ в X" gistPath="" %}}
```cs
// загрузить USDZ в объект сцены 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// сохранить USDZ как X 
scene.Save("output.x", Aspose.ThreeD.FileFormat.XBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}