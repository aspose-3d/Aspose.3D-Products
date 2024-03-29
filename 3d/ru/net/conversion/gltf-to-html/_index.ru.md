﻿---
title: Преобразование GLTF в HTML через C# 
url: /ru/net/conversion/gltf-to-html/ 
description: Пример кода для преобразования GLTF в HTML C#. Используйте пример кода API для пакетного преобразования GLTF файлов в HTML в VB.NET, Asp.NET или любом приложении на основе .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование GLTF в HTML через C#" h2="Визуализировать GLTF как HTML без какого-либо программного обеспечения для моделирования и визуализации 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать GLTF в HTML с помощью C#" %}}

 Чтобы преобразовать GLTF в HTML, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию GLTF в HTML через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты .NET могут легко загружать и преобразовывать файлы GLTF в HTML, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл GLTF через конструктор класса Scene1. Создайте экземпляр AmfSaveOptions1. Установите определенные свойства HTML для расширенного преобразования1. Вызов метода Scene.Save1. Передайте выходной путь с расширением файла HTML и объектом Html5SaveOptions1. Проверить результирующий файл HTML по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования .NET убедитесь, что выполнены следующие предварительные требования.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono.- Среда разработки, такая как Microsoft Visual Studio.- Aspose.3D for .NET DLL, на которые ссылается ваш проект.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В этом примере кода показано преобразование GLTF в HTML C#" offSpacer="" %}}

```cs
// загрузить GLTF в объект сцены 
var document = new Aspose.ThreeD.Scene("template.gltf");
// создать экземпляр Html5SaveOptions 
var options = new Aspose.ThreeD.Formats.Html5SaveOptions();
// сохранить GLTF как HTML 
document.Save("output.html", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования GLTF в HTML" sectionDescription="Проверьте наши живые демонстрации для [Преобразование GLTF в HTML](https://products.aspose.app/3d/conversion/gltf-to-html) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл GLTF и нажмите кнопку \"Конвертировать\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего файла HTML." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека обработки файлов 3D для управления файлами 3D без какого-либо программного обеспечения для моделирования и визуализации. 3D API поддерживает Discreet3DS, WavefrontOBJ, FBX (ASCII, двоичный), STL (ASCII, двоичный), Universal3D, Collada, glTF, GLB, PLY, DirectX, форматы файлов Google Draco и многое другое. Разработчики могут легко создавать, читать, преобразовывать, изменять и контролировать содержание форматов документов 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (формат передачи GL) – это формат файла 3D, в котором хранится 3D информация о модели в формате JSON. Использование JSON сводит к минимуму как размер ресурсов 3D, так и время выполнения, необходимое для распаковки и использования этих ресурсов. Он был адаптирован для эффективной передачи и загрузки 3D сцен и моделей приложениями. glTF был разработан Рабочей группой форматов 3D Khronos Group и также описывается его создателями как JPEG из 3D. Этот формат определяет расширяемый общий формат публикации для 3D инструментов и служб контента, который оптимизирует рабочие процессы разработки и обеспечивает функциональное взаимодействие использования контента в отрасли. Цель создания формата файлов glTF заключалась в том, чтобы определить расширяемый общий формат публикации для инструментов и служб контента 3D, который должен упростить рабочие процессы разработки и обеспечить возможность функционального использования контента в отрасли. Это сводит к минимуму обработку во время выполнения приложениями, использующими WebGL и другие API.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="html" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (Hyper Text Markup Language) – это расширение для веб-страниц, созданных для отображения в браузерах. Известный как веб-язык, HTML развивался с учетом новых требований к информации, которая должна отображаться как часть веб-страниц. Последний вариант известен как HTML 5, что обеспечивает большую гибкость при работе с языком. HTML страниц либо принимаются с сервера, на котором они размещены, либо также могут быть загружены из локальной системы. Каждая страница HTML состоит из элементов HTML, таких как формы, текст, изображения, анимация, ссылки и т. д. Эти элементы представлены такими тегами, как img, a, p и некоторыми другими, где каждый тег имеет начало и конец. . Он также может встраивать приложения, написанные на языках сценариев, таких как JavaScript и таблицы стилей (CSS), для общего представления макета.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}