﻿---
title: Преобразование 3DS в GLB через Java
weight: 530
url: /ru/java/conversion/3ds-to-glb/ 
description: Пример кода преобразования Java для формата 3DS в файл GLB. Используйте этот пример кода для преобразования 3DS в GLB в любом веб-приложении или настольном приложении Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование 3DS в GLB через Java" h2="Преобразование 3DS в GLB с использованием библиотеки Java без какого-либо программного обеспечения для моделирования 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать 3DS в GLB с помощью Java" %}}

 Чтобы преобразовать 3DS в GLB, мы будем использовать
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API – это многофункциональная, мощная и простая в использовании платформа преобразования API for Java. Вы можете скачать его последнюю версию прямо с
 [Мавен](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию 3DS в GLB через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты Java могут легко преобразовать файл 3DS в GLB, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл 3DS через конструктор класса Scene1. Вызовите метод Scene.save с форматом GLB.1. Проверить результирующий файл GLB по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования Java убедитесь, что выполнены следующие предварительные требования.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с Java средой выполнения для приложений JSP/JSF и настольных приложений.- Получите последнюю версию Aspose.3D for Java непосредственно из Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="3DS в GLB Java Исходный код преобразования" offSpacer="" %}}

```cs
// Загрузите исходный файл Discreet 3DS
Scene scene = new Scene("sourceFile.3ds");
// Преобразование сцены 3D в файл в двоичном формате GLTF
scene.save("output.glb", FileFormat.GLTF2_BINARY)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Преобразование 3DS в GLB демонстрации в реальном времени" sectionDescription="[Преобразовать 3DS в GLB](https://products.aspose.app/3d/conversion/3ds-to-glb) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл 3DS, и он будет мгновенно преобразован в GLB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Библиотека управления сценами" %}}

 Aspose.3D – это CAD и Gameware API для загрузки, изменения и преобразования файлов 3D. API является автономным и не требует никакого 3D программного обеспечения для моделирования или визуализации. Можно легко использовать API для USD, Discreet3DS, WavefrontOBJ, STL (ASCII, двоичный), Universal3D, FBX (ASCII, двоичный), Collada, glTF, PLY, GLB, DirectX и другие форматы. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}

Файл с расширением .3ds представляет формат файла сетки 3D Sudio (DOS), используемый Autodesk 3D Studio. Autodesk 3D Studio существует на рынке файловых форматов 3D с 1990-х годов и теперь превратилась в 3D Studio MAX для работы с 3D моделированием, анимацией и визуализацией. Файл 3DS содержит данные для 3D представления сцен и изображений и является одним из популярных форматов файлов для импорта и экспорта данных 3D. Он учитывает такую информацию, как расположение камер, данные сетки, информацию об освещении, конфигурации области просмотра, данные группы сглаживания, ссылки на растровые изображения и атрибуты для создания вершин и полигонов для рендеринга сцены.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}

GLB – это представление в формате двоичного файла моделей 3D, сохраненных в формате передачи GL (glTF). Информация о моделях 3D, такая как иерархия узлов, камеры, материалы, анимация и сетки в двоичном формате. В этом двоичном формате ресурс glTF (JSON, .bin и изображения) хранится в двоичном двоичном объекте. Это также позволяет избежать проблемы увеличения размера файла, которая происходит в случае glTF. Формат файла GLB обеспечивает компактный размер файла, быструю загрузку, полное представление сцены 3D и расширяемость для дальнейшего развития. Формат использует model/gltf-binary в качестве типа MIME.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать 3DS во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-gltf/" name="3DS К GLTF" description="Файл формата передачи GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-glb/" name="3DS К GLB" description="Двоичный формат передачи GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-pdf/" name="3DS К PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-fbx/" name="3DS К FBX" description="Обменный файл Autodesk FBX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-stl/" name="3DS К STL" description="Файл стереолитографии" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-obj/" name="3DS К OBJ" description="Wavefront 3D Объектный файл" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-dae/" name="3DS К DAE" description="Файл обмена цифровыми активами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-u3d/" name="3DS К U3D" description="Universal 3D файл" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-ply/" name="3DS К PLY" description="Формат файла многоугольника" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-drc/" name="3DS К DRC" description="Google Draco Формат файла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-rvm/" name="3DS К RVM" description="АВЕВА RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-jt/" name="3DS К JT" description="JT Открыть файл CAD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-amf/" name="3DS К AMF" description="Файл аддитивного производства" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-html/" name="3DS К HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-usd/" name="3DS К USD" description="Универсальный формат описания сцены" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-usdz/" name="3DS К USDZ" description="Универсальное описание сцены в сжатом формате" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}