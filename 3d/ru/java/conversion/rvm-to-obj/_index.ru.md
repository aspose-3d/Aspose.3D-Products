﻿---
title: Преобразование RVM в OBJ через Java 
weight: 2940
url: /ru/java/conversion/rvm-to-obj/ 
description: Пример кода преобразования Java для формата RVM в файл OBJ. Используйте этот пример кода для преобразования RVM в OBJ в любом веб-приложении или настольном приложении Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование RVM в OBJ через Java" h2="Преобразование RVM в OBJ с использованием библиотеки Java без какого-либо программного обеспечения для моделирования 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="RVM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать RVM в OBJ с помощью Java" %}}

 Чтобы преобразовать RVM в OBJ, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию RVM в OBJ через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты Java могут легко преобразовать файл RVM в OBJ, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл RVM через конструктор класса Scene1. Создайте экземпляр ObjSaveOptions1. Установите определенные свойства OBJ для расширенного преобразования1. Вызов метода Scene.save1. Передайте выходной путь с расширением файла OBJ и объектом ObjSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования Java убедитесь, что выполнены следующие предварительные требования.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с Java средой выполнения для приложений JSP/JSF и настольных приложений.- Получите последнюю версию Aspose.3D for Java непосредственно из Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="RVM в OBJ Java Исходный код преобразования" offSpacer="" %}}

```cs
// загрузить RVM в объект сцены 
Scene document = new Scene("template.rvm");
// создать экземпляр ObjSaveOptions 
ObjSaveOptions options = new ObjSaveOptions();
// сохранить RVM как OBJ 
document.save("output.obj", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Преобразование RVM в OBJ демонстрации в реальном времени" sectionDescription="[Преобразовать RVM в OBJ](https://products.aspose.app/3d/conversion/rvm-to-obj) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл RVM, и он будет мгновенно преобразован в OBJ." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Библиотека управления сценами" %}}

 Aspose.3D – это CAD и Gameware API для загрузки, изменения и преобразования файлов 3D. API является автономным и не требует никакого 3D программного обеспечения для моделирования или визуализации. Можно легко использовать API для Discreet3DS, WavefrontOBJ, STL (ASCII, двоичный), Universal3D, FBX (ASCII, двоичный), Collada, glTF, PLY, GLB, DirectX и другие форматы. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="RVM" readMoreLink="https://docs.fileformat.com/3d/rvm/" >}}

RVM файлов данных относятся к AVEVA PDMS. Файл RVM представляет собой модель системы управления проектированием предприятия AVEVA. Система управления проектированием предприятий (PDMS) компании AVEVA — это самая популярная 3D система проектирования, использующая для управления проектами технологию, ориентированную на данные.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

Файлы OBJ используются приложением Advanced Visualizer Wavefront для определения и хранения геометрических объектов. Обратная и прямая передача геометрических данных возможна через файлы OBJ. Формат OBJ поддерживает как многоугольную геометрию, такую как точки, линии, вершины текстуры, грани, так и геометрию произвольной формы (кривые и поверхности). Этот формат не поддерживает анимацию или информацию, связанную с освещением и положением сцен. Файл OBJ обычно является конечным продуктом процесса моделирования 3D, созданного CAD (автоматизированное проектирование). Порядок хранения вершин по умолчанию — против часовой стрелки, что позволяет избежать явного объявления нормалей граней. Хотя файлы OBJ объявляют информацию о масштабе в строке комментария, для координат OBJ не были объявлены единицы измерения.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать RVM во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-3ds/" name="RVM К 3DS" description="3D Студийная сетка DOS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-amf/" name="RVM К AMF" description="Формат аддитивного производства" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-ase/" name="RVM К ASE" description="Файл 2D-анимации" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-dae/" name="RVM К DAE" description="Биржа цифровых активов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-fbx/" name="RVM К FBX" description="3D Формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-gltf/" name="RVM К GLTF" description="Формат передачи GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-html/" name="RVM К HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-ply/" name="RVM К PLY" description="Формат файла многоугольника" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-stl/" name="RVM К STL" description="Взаимозаменяемая геометрия поверхности 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/rvm-to-u3d/" name="RVM К U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}