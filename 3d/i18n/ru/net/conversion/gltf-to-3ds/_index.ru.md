﻿---
title: Конвертировать GLTF в 3DS через C# 
url: /ru/net/conversion/gltf-to-3ds/ 
description: Пример кода для преобразования GLTF в 3DS C#. Используйте API пример кода для пакетного преобразования GLTF файлов в 3DS в VB.NET, Asp.NET или любом приложении на основе .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Конвертировать GLTF в 3DS через C#" h2="Отправка GLTF как 3DS без программного обеспечения для моделирования и рендеринга 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как конвертировать GLTF в 3DS с помощью C#" %}}

 Чтобы конвертировать GLTF в 3DS, мы будем использовать
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, который представляет собой многофункциональный, мощный и простой в использовании документ обработки и преобразования API для платформы C#. Открытая
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Менеджер пакетов, поиск
 Aspose.3D 
 И установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги для преобразования GLTF в 3DS через C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET программисты могут легко загружать и конвертировать GLTF файлы в 3DS всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузить файл GLTF через конструктор класса Scene1. Создать экземпляр AmfSaveOptions1. Установите специальные свойства 3DS для расширенного преобразования1. Вызовите метод Scene.Save1. Передайте выходной путь с расширением файла 3DS и объектом Discreet3dsSaveOptions1. Проверьте результирующий файл 3DS по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к системе" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования .NET убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono.- Среда разработки, такая как Microsoft Visual Studio.- Aspose.3D for .NET DLL, упомянутые в вашем проекте.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Этот пример кода показывает GLTF в 3DS C# преобразования" offSpacer="" %}}

```cs
// Загрузить GLTF в объект сцены 
var document = new Aspose.ThreeD.Scene("template.gltf");
// Создать экземпляр Discreet3dsSaveOptions 
var options = new Aspose.ThreeD.Formats.Discreet3dsSaveOptions();
// Сохранить GLTF как 3DS 
document.Save("output.3ds", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования GLTF в 3DS" sectionDescription="Проверьте наши живые демо для [Преобразование GLTF в 3DS](https://products.aspose.app/3d/conversion/gltf-to-3ds) Со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать или настраивать что-либо." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Не нужно писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите свой GLTF файл и нажмите кнопку \"Конвертировать\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы мгновенно получите ссылку для загрузки полученного файла 3DS." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека обработки файлов 3D для управления файлами 3D без какого-либо программного обеспечения для моделирования и рендеринга. 3D API поддерживает Discreet3DS, WavefrontOBJ, FBX (ASCII, двоичный), STL (ASCII, двоичный), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco форматы файлов и многое другое. Разработчики могут легко создавать, читать, преобразовывать, изменять и контролировать содержание форматов документов 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (формат передачи GL)-это формат файла 3D, который хранит информацию о модели 3D в формате JSON. Использование JSON сводит к минимуму как размер активов 3D, так и обработку среды выполнения, необходимую для распаковки и использования этих активов. Он был принят для эффективной передачи и загрузки приложений 3D сцен и моделей. glTF был разработан Рабочей группой по форматам Khronos Group 3D и также описан его создателями как JPEG 3D. Формат определяет расширяемый общий формат публикации для инструментов и сервисов 3D контента, который оптимизирует рабочие процессы авторизации и обеспечивает совместимое использование контента в отрасли. Намерение создания формата файлов glTF состояло в том, чтобы определить расширяемый, общий формат публикации для инструментов и сервисов 3D контента, который должен упростить рабочие процессы авторства и обеспечить совместимое использование контента в отрасли. Он минимизирует обработку среды выполнения приложениями, использующими WebGL и другие API.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3ds" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
Файл с расширением 3DS представляет формат сетчатого файла 3D Studio (DOS), используемый Autodesk 3D Studio. Autodesk 3D Studio работает на рынке форматов файлов 3D с 1990-х годов и теперь превратилась в 3D Studio MAX для работы с моделированием, анимацией и рендерингом 3D. Файл 3DS содержит данные для 3D представления сцен и изображений и является одним из популярных форматов файлов для импорта и экспорта данных 3D. Он рассматривает такую информацию, как местоположение камеры, данные Mesh, информацию об освещении, конфигурации видовых экранов, данные сглаживающей группы, растровые ссылки и атрибуты для создания вершин и полигонов для рендеринга сцены.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}