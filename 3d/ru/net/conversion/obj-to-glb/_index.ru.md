﻿---
title: Преобразование OBJ в GLB через C# 
url: /ru/net/conversion/obj-to-glb/ 
description: Пример кода для преобразования OBJ в GLB C#. Используйте пример кода API для пакетного преобразования OBJ файлов в GLB в VB.NET, Asp.NET или любом приложении на основе .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование OBJ в GLB через C#" h2="Визуализировать OBJ как GLB без какого-либо программного обеспечения для моделирования и визуализации 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать OBJ в GLB с помощью C#" %}}

 Чтобы преобразовать OBJ в GLB, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию OBJ в GLB через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты .NET могут легко загружать и преобразовывать файлы OBJ в GLB, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл OBJ через конструктор класса Scene1. Создайте экземпляр AmfSaveOptions1. Установите определенные свойства GLB для расширенного преобразования1. Вызов метода Scene.Save1. Передайте выходной путь с расширением файла GLB и объектом StlSaveOptions1. Проверить результирующий файл GLB по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования .NET убедитесь, что выполнены следующие предварительные требования.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono.- Среда разработки, такая как Microsoft Visual Studio.- Aspose.3D for .NET DLL, на которые ссылается ваш проект.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В этом примере кода показано преобразование OBJ в GLB C#" offSpacer="" %}}

```cs
// загрузить OBJ в объект сцены 
var document = new Aspose.ThreeD.Scene("template.obj");
// создать экземпляр GltfSaveOptions 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions(FileContentType.Binary);
// сохранить OBJ как GLB 
document.Save("output.glb", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования OBJ в GLB" sectionDescription="Проверьте наши живые демонстрации для [Преобразование OBJ в GLB](https://products.aspose.app/3d/conversion/obj-to-glb) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл OBJ и нажмите кнопку \"Конвертировать\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего файла GLB." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека обработки файлов 3D для управления файлами 3D без какого-либо программного обеспечения для моделирования и визуализации. 3D API поддерживает Discreet3DS, WavefrontOBJ, FBX (ASCII, двоичный), GLB (ASCII, двоичный), Universal3D, Collada, glTF, GLB, PLY, DirectX, форматы файлов Google Draco и многое другое. Разработчики могут легко создавать, читать, преобразовывать, изменять и контролировать содержание форматов документов 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
Файлы OBJ используются приложением Advanced Visualizer Wavefront для определения и хранения геометрических объектов. Обратная и прямая передача геометрических данных возможна через файлы OBJ. Формат OBJ поддерживает как многоугольную геометрию, такую как точки, линии, вершины текстуры, грани, так и геометрию произвольной формы (кривые и поверхности). Этот формат не поддерживает анимацию или информацию, связанную с освещением и положением сцен. Файл OBJ обычно является конечным продуктом процесса моделирования 3D, созданного CAD (автоматизированное проектирование). Порядок хранения вершин по умолчанию — против часовой стрелки, что позволяет избежать явного объявления нормалей граней. Хотя файлы OBJ объявляют информацию о масштабе в строке комментария, для координат OBJ не были объявлены единицы измерения.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB – это представление в формате двоичного файла моделей 3D, сохраненных в формате передачи GL (glTF). Информация о моделях 3D, такая как иерархия узлов, камеры, материалы, анимация и сетки в двоичном формате. В этом двоичном формате ресурс glTF (JSON, .bin и изображения) хранится в двоичном двоичном объекте. Это также позволяет избежать проблемы увеличения размера файла, которая происходит в случае glTF. Формат файла GLB обеспечивает компактный размер файла, быструю загрузку, полное представление сцены 3D и расширяемость для дальнейшего развития. Формат использует model/gltf-binary в качестве типа MIME.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
