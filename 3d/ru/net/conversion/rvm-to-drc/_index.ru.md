﻿---
title: Преобразование RVM в DRC через C# 
url: /ru/net/conversion/rvm-to-drc/ 
description: Пример кода для преобразования RVM в DRC C#. Используйте пример кода API для пакетного преобразования RVM файлов в DRC в VB.NET, Asp.NET или любом приложении на основе .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование RVM в DRC через C#" h2="Визуализировать RVM как DRC без какого-либо программного обеспечения для моделирования и визуализации 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DRC" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="RVM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать RVM в DRC с помощью C#" %}}

 Чтобы преобразовать RVM в DRC, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию RVM в DRC через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты .NET могут легко загружать и преобразовывать файлы RVM в DRC, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл RVM через конструктор класса Scene1. Создайте экземпляр AmfSaveOptions1. Установите определенные свойства DRC для расширенного преобразования1. Вызов метода Scene.Save1. Передайте выходной путь с расширением файла DRC и объектом DrcSaveOptions1. Проверить результирующий файл DRC по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования .NET убедитесь, что выполнены следующие предварительные требования.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono.- Среда разработки, такая как Microsoft Visual Studio.- Aspose.3D for .NET DLL, на которые ссылается ваш проект.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В этом примере кода показано преобразование RVM в DRC C#" offSpacer="" %}}

```cs
// загрузить RVM в объект сцены 
var document = new Aspose.ThreeD.Scene("template.rvm");
// создать экземпляр DrcSaveOptions 
var options = new Aspose.ThreeD.Formats.DrcSaveOptions();
// сохранить RVM как DRC 
document.Save("output.drc", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования RVM в DRC" sectionDescription="Проверьте наши живые демонстрации для [Преобразование RVM в DRC](https://products.aspose.app/3d/conversion/rvm-to-drc) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл RVM и нажмите кнопку \"Конвертировать\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего файла DRC." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека обработки файлов 3D для управления файлами 3D без какого-либо программного обеспечения для моделирования и визуализации. 3D API поддерживает Discreet3DS, WavefrontOBJ, FBX (ASCII, двоичный), STL (ASCII, двоичный), Universal3D, Collada, glTF, GLB, PLY, DirectX, форматы файлов Google Draco и многое другое. Разработчики могут легко создавать, читать, преобразовывать, изменять и контролировать содержание форматов документов 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="RVM" readMoreLink="https://docs.fileformat.com/3d/rvm/" >}}
RVM файлов данных относятся к AVEVA PDMS. Файл RVM представляет собой модель системы управления проектированием предприятия AVEVA. Система управления проектированием предприятий (PDMS) компании AVEVA — это самая популярная 3D система проектирования, использующая для управления проектами технологию, ориентированную на данные.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="drc" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
Файл с расширением .drc представляет собой сжатый файл в формате 3D, созданный с помощью библиотеки Google Draco. Google предлагает Draco как библиотеку с открытым исходным кодом для сжатия и распаковки 3D геометрических сеток и облаков точек, а также улучшает хранение и передачу 3D графики. Он кодирует входные данные и сохраняет их как файл .drc. На принимающей стороне API считывает файлы .drc и может выводить их в виде файлов PLY или OBJ. Сжатый выходной файл позволяет пользователям быстрее загружать приложения и обеспечивает быструю загрузку графики 3D в браузерах.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать RVM во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-3ds/" name="RVM К 3DS" description="3D Студийная сетка DOS" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-amf/" name="RVM К AMF" description="Формат аддитивного производства" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-dae/" name="RVM К DAE" description="Биржа цифровых активов" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-fbx/" name="RVM К FBX" description="3D Формат" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-html/" name="RVM К HTML" description="Язык гипертекстовой разметки" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-obj/" name="RVM К OBJ" description="3D Формат файла" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-pdf/" name="RVM К PDF" description="Портативный формат документа" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-ply/" name="RVM К PLY" description="Формат файла многоугольника" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-stl/" name="RVM К STL" description="Взаимозаменяемая геометрия поверхности 3D" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/rvm-to-u3d/" name="RVM К U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}