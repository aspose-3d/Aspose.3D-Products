﻿---
title: Преобразование ASE в OBJ через C# 
weight: 1890
url: /ru/net/conversion/ase-to-obj/ 
description: Пример кода для преобразования ASE в OBJ C#. Используйте пример кода API для пакетного преобразования ASE файлов в OBJ в VB.NET, Asp.NET или любом приложении на основе .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование ASE в OBJ через C#" h2="Визуализировать ASE как OBJ без какого-либо программного обеспечения для моделирования и визуализации 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать ASE в OBJ с помощью C#" %}}

 Чтобы преобразовать ASE в OBJ, мы будем использовать
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API — многофункциональное, мощное и простое в использовании средство обработки и преобразования документов API для платформы C#. Открыть
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 менеджер пакетов, поиск
 Aspose.3D 
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию ASE в OBJ через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты .NET могут легко загружать и преобразовывать файлы ASE в OBJ, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл ASE через конструктор класса Scene1. Создайте экземпляр ObjSaveOptions1. Установите определенные свойства OBJ для расширенного преобразования1. Вызов метода Scene.Save1. Передайте выходной путь с расширением файла OBJ и объектом ObjSaveOptions1. Проверить результирующий файл OBJ по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования .NET убедитесь, что выполнены следующие предварительные требования.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono.- Среда разработки, такая как Microsoft Visual Studio.- Aspose.3D for .NET DLL, на которые ссылается ваш проект.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В этом примере кода показано преобразование ASE в OBJ C#" offSpacer="" %}}

```cs
// загрузить ASE в объект сцены 
var document = new Aspose.ThreeD.Scene("template.ase");
// создать экземпляр ObjSaveOptions 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// сохранить ASE как OBJ 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования ASE в OBJ" sectionDescription="Проверьте наши живые демонстрации для [Преобразование ASE в OBJ](https://products.aspose.app/3d/conversion/ase-to-obj) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл ASE и нажмите кнопку \"Конвертировать\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего файла OBJ." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека обработки файлов 3D для управления файлами 3D без какого-либо программного обеспечения для моделирования и визуализации. 3D API поддерживает Discreet3DS, WavefrontOBJ, FBX (ASCII, двоичный), STL (ASCII, двоичный), Universal3D, Collada, glTF, GLB, PLY, DirectX, форматы файлов Google Draco и многое другое. Разработчики могут легко создавать, читать, преобразовывать, изменять и контролировать содержание форматов документов 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}
Файл ASE представляет собой 2D-анимацию или графику, содержащую слои, кадры, палитры, теги и настройки.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
Файлы OBJ используются приложением Advanced Visualizer Wavefront для определения и хранения геометрических объектов. Обратная и прямая передача геометрических данных возможна через файлы OBJ. Формат OBJ поддерживает как многоугольную геометрию, такую как точки, линии, вершины текстуры, грани, так и геометрию произвольной формы (кривые и поверхности). Этот формат не поддерживает анимацию или информацию, связанную с освещением и положением сцен. Файл OBJ обычно является конечным продуктом процесса моделирования 3D, созданного CAD (автоматизированное проектирование). Порядок хранения вершин по умолчанию — против часовой стрелки, что позволяет избежать явного объявления нормалей граней. Хотя файлы OBJ объявляют информацию о масштабе в строке комментария, для координат OBJ не были объявлены единицы измерения.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать ASE во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-3ds/" name="ASE К 3DS" description="3D Студийная сетка DOS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-amf/" name="ASE К AMF" description="Формат аддитивного производства" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-dae/" name="ASE К DAE" description="Биржа цифровых активов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-fbx/" name="ASE К FBX" description="3D Формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-html/" name="ASE К HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-pdf/" name="ASE К PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-ply/" name="ASE К PLY" description="Формат файла многоугольника" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-rvm/" name="ASE К RVM" description="Модель проектирования завода AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-stl/" name="ASE К STL" description="Взаимозаменяемая геометрия поверхности 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-u3d/" name="ASE К U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}