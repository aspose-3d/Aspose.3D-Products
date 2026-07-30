---
title: Извлечение ресурсов из 3D форматов C#
url: /ru/net/extractor/
description: Извлечение активов из 3D форматов 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x с использованием .NET библиотеки, используя несколько строк кода C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Извлечение ресурсов 3D-форматов с помощью C#" h2="Извлечение ресурсов из документов 3D-форматов без какого-либо программного обеспечения для 3D-моделирования и рендеринга для создания кросс-платформенных приложений .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}
Разработчики могут использовать 3D-библиотеку для легкого извлечения ресурсов 3D-файлов. Несколько форматов, поддерживаемых API, включают WavefrontOBJ, Discreet3DS, STL (ASCII, Binary), FBX (ASCII, Binary), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco и другие форматы. Процесс извлечения прост: загрузите исходный файл через экземпляр класса [scene](https://apireference.aspose.com/3d/net/aspose.threed/scene), создайте класс архива и обработайте класс извлечения ресурсов, а затем вызовите метод Save для соответствующего параметра формата вывода.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Извлечение ресурсов из 3D-сцены в различные форматы" %}}
Разработчики могут легко извлекать ресурсы из 3D-файлов тем же процессом, указанным выше. Рассмотрите некоторые примеры, такие как **3DS to FBX Extractor**. Загружайте файлы 3DS через объекты класса scene. Создавайте параметры сохранения с помощью [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions) для создания параметров сохранения и вызова метода сохранения сцены с аргументами пути к выходному файлу и параметрами fbx. API имеет соответствующие классы параметров для сохранения в связанные классы, например [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) и другие. Вот полный список 3D [форматов извлекателей](https://apireference.aspose.com/3d/net/aspose.threed.formats) параметров.

{{% blocks/products/pf/feature-page-code h3="Код C# для извлечения ресурсов 3DS в FBX" %}}

{{< gist "aspose-3d-gists" "9563193e834f0087b554c83130fcf7c7" "Examples-CSharp-Extractor-products.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Extractor" >}}
{{< /blocks/products/pf/feature-page-wrap >}}