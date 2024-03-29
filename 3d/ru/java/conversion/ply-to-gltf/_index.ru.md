﻿---
title: Преобразование PLY в GLTF через Java 
weight: 660
url: /ru/java/conversion/ply-to-gltf/ 
description: Пример кода преобразования Java для формата PLY в файл GLTF. Используйте этот пример кода для преобразования PLY в GLTF в любом веб-приложении или настольном приложении Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование PLY в GLTF через Java" h2="Преобразование PLY в GLTF с использованием библиотеки Java без какого-либо программного обеспечения для моделирования 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать PLY в GLTF с помощью Java" %}}

 Чтобы преобразовать PLY в GLTF, мы будем использовать
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API – это многофункциональная, мощная и простая в использовании платформа преобразования API for Java. Вы можете скачать его последнюю версию прямо с
 [Мавен](https://repository.aspose.com/3d/) 
 и установите его в своем проекте на основе Maven, добавив следующие конфигурации в файл pom.xml.

{{% blocks/products/pf/agp/code-block title="Репозиторий" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://репозиторий.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Зависимость" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-3d</artifactId>
<version>version of aspose-3d API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию PLY в GLTF через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты Java могут легко преобразовать файл PLY в GLTF, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл PLY через конструктор класса Scene1. Создайте экземпляр GltfSaveOptions1. Установите определенные свойства GLTF для расширенного преобразования1. Вызов метода Scene.save1. Передайте выходной путь с расширением файла GLTF и объектом GltfSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования Java убедитесь, что выполнены следующие предварительные требования.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с Java средой выполнения для приложений JSP/JSF и настольных приложений.- Получите последнюю версию Aspose.3D for Java непосредственно из Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PLY в GLTF Java Исходный код преобразования" offSpacer="" %}}

```cs
// загрузить PLY в объект сцены 
Scene document = new Scene("template.ply");
// создать экземпляр GltfSaveOptions 
GltfSaveOptions options = new GltfSaveOptions();
// сохранить PLY как GLTF 
document.save("output.gltf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Преобразование PLY в GLTF демонстрации в реальном времени" sectionDescription="[Преобразовать PLY в GLTF](https://products.aspose.app/3d/conversion/ply-to-gltf) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл PLY, и он будет мгновенно преобразован в GLTF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Библиотека управления сценами" %}}

 Aspose.3D – это CAD и Gameware API для загрузки, изменения и преобразования файлов 3D. API является автономным и не требует никакого 3D программного обеспечения для моделирования или визуализации. Можно легко использовать API для Discreet3DS, WavefrontOBJ, STL (ASCII, двоичный), Universal3D, FBX (ASCII, двоичный), Collada, glTF, PLY, GLB, DirectX и другие форматы. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}

PLY, формат файла многоугольника, представляет собой формат файла 3D, в котором хранятся графические объекты, описываемые как набор многоугольников. Цель этого формата файла состояла в том, чтобы создать простой и удобный тип файла, который является достаточно общим, чтобы его можно было использовать для широкого спектра моделей. Формат файла PLY представлен как в формате ASCII, так и в двоичном формате для компактного хранения и быстрого сохранения и загрузки. Формат файла используется различными приложениями, поддерживающими чтение файлов 3D.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF (формат передачи GL) – это формат файла 3D, в котором хранится 3D информация о модели в формате JSON. Использование JSON сводит к минимуму как размер ресурсов 3D, так и время выполнения, необходимое для распаковки и использования этих ресурсов. Он был адаптирован для эффективной передачи и загрузки 3D сцен и моделей приложениями. glTF был разработан Рабочей группой форматов 3D Khronos Group и также описывается его создателями как JPEG из 3D. Этот формат определяет расширяемый общий формат публикации для 3D инструментов и служб контента, который оптимизирует рабочие процессы разработки и обеспечивает функциональное взаимодействие использования контента в отрасли. Цель создания формата файлов glTF заключалась в том, чтобы определить расширяемый общий формат публикации для инструментов и служб контента 3D, который должен упростить рабочие процессы разработки и обеспечить возможность функционального использования контента в отрасли. Это сводит к минимуму обработку во время выполнения приложениями, использующими WebGL и другие API.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PLY во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-3ds/" name="PLY К 3DS" description="3D Студийная сетка DOS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-amf/" name="PLY К AMF" description="Формат аддитивного производства" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-ase/" name="PLY К ASE" description="Файл 2D-анимации" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-dae/" name="PLY К DAE" description="Биржа цифровых активов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-fbx/" name="PLY К FBX" description="3D Формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-html/" name="PLY К HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-obj/" name="PLY К OBJ" description="3D Формат файла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-rvm/" name="PLY К RVM" description="Модель проектирования завода AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-stl/" name="PLY К STL" description="Взаимозаменяемая геометрия поверхности 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-u3d/" name="PLY К U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}