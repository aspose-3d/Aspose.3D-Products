﻿---
title: Преобразование 3DS в DAE через C# 
weight: 470
url: /ru/net/conversion/3ds-to-dae/ 
description: Пример кода для преобразования 3DS в DAE C#. Используйте пример кода API для пакетного преобразования 3DS файлов в DAE в VB.NET, Asp.NET или любом приложении на основе .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование 3DS в DAE через C#" h2="Визуализировать 3DS как DAE без какого-либо программного обеспечения для моделирования и визуализации 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DAE" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать 3DS в DAE с помощью C#" %}}

 Чтобы преобразовать 3DS в DAE, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию 3DS в DAE через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты .NET могут легко загружать и преобразовывать файлы 3DS в DAE, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл 3DS через конструктор класса Scene1. Создайте экземпляр DaeSaveOptions1. Установите определенные свойства DAE для расширенного преобразования1. Вызов метода Scene.Save1. Передайте выходной путь с расширением файла DAE и объектом DaeSaveOptions1. Проверить результирующий файл DAE по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования .NET убедитесь, что выполнены следующие предварительные требования.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono.- Среда разработки, такая как Microsoft Visual Studio.- Aspose.3D for .NET DLL, на которые ссылается ваш проект.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В этом примере кода показано преобразование 3DS в DAE C#" offSpacer="" %}}

```cs
// загрузить 3DS в объект сцены 
var document = new Aspose.ThreeD.Scene("template.3ds");
// создать экземпляр DaeSaveOptions 
var options = new Aspose.ThreeD.Formats.DaeSaveOptions();
// сохранить 3DS как DAE 
document.Save("output.dae", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования 3DS в DAE" sectionDescription="Проверьте наши живые демонстрации для [Преобразование 3DS в DAE](https://products.aspose.app/3d/conversion/3ds-to-dae) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл 3DS и нажмите кнопку \"Конвертировать\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего файла DAE." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека обработки файлов 3D для управления файлами 3D без какого-либо программного обеспечения для моделирования и визуализации. 3D API поддерживает Discreet3DS, WavefrontOBJ, FBX (ASCII, двоичный), STL (ASCII, двоичный), Universal3D, Collada, glTF, GLB, PLY, DirectX, форматы файлов Google Draco и многое другое. Разработчики могут легко создавать, читать, преобразовывать, изменять и контролировать содержание форматов документов 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
Файл с расширением 3DS представляет формат файла сетки 3D Studio (DOS), используемый Autodesk 3D Studio. Autodesk 3D Studio существует на рынке файловых форматов 3D с 1990-х годов и теперь превратилась в 3D Studio MAX для работы с 3D моделированием, анимацией и визуализацией. Файл 3DS содержит данные для 3D представления сцен и изображений и является одним из популярных форматов файлов для импорта и экспорта данных 3D. Он учитывает такую информацию, как расположение камер, данные сетки, информацию об освещении, конфигурации области просмотра, данные группы сглаживания, ссылки на растровые изображения и атрибуты для создания вершин и полигонов для рендеринга сцены.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="dae" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}
Файл DAE — это формат файла обмена цифровыми активами, который используется для обмена данными между интерактивными приложениями 3D. Этот формат файла основан на XML-схеме COLLADA (COLLAborative Design Activity), которая представляет собой открытую стандартную XML-схему для обмена цифровыми активами между графическими приложениями. Он был принят ISO в качестве общедоступной спецификации ISO/pAS 17506.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать 3DS во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-amf/" name="3DS К AMF" description="Формат аддитивного производства" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-fbx/" name="3DS К FBX" description="3D Формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-html/" name="3DS К HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-obj/" name="3DS К OBJ" description="3D Формат файла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-pdf/" name="3DS К PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-ply/" name="3DS К PLY" description="Формат файла многоугольника" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-rvm/" name="3DS К RVM" description="Модель проектирования завода AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-stl/" name="3DS К STL" description="Взаимозаменяемая геометрия поверхности 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-u3d/" name="3DS К U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}