﻿---
title: Добавьте слепой водяной знак к USD форматам файлов через .NET 
weight: 830
url: /ru/net/watermark/usd/ 
description: Исходный код C# для загрузки, рендеринга и добавления скрытого водяного знака в USD документы на .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Добавить слепой водяной знак на USD через C#" h2="Создавайте свои собственные .NET приложения для добавления водяных знаков к USD файлам с помощью серверных API." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="USD" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="USD" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Как поставить водяной знак на файл USD с помощью C#" %}}

 Чтобы пометить файл USD водяным знаком, мы будем использовать
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API — многофункциональная, мощная и простая в использовании платформа API для C#, которую можно использовать с добавлением любого водяного знака. Открыть
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 менеджер пакетов, поиск
 **Aspose.3D** 
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по добавлению слепого водяного знака в USD через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D позволяет разработчикам легко добавить слепой водяной знак в файл USD, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

- Загрузите файл USD через конструктор класса Scene- Получите класс сетки Aspose.3D- Добавьте водяной знак и пароль, используя метод EncodeWatermark Aspose.3D.- Вызов метода Scene.Save с объектом
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono- Среда разработки, такая как Microsoft Visual Studio- Aspose.3D for .NET упоминается в вашем проекте
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# код для добавления слепого водяного знака к USD" offSpacer="" %}}

```cs

//Исходный файл, на который необходимо нанести водяной знак, и выходной файл после сохранения
string file = "template.usd";
string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

// создать экземпляр сцены
Scene scene = new Scene(file);

//Добавить водяной знак и пароль к файлам
var numMeshes = 0;
scene.RootNode.Accept((Node node) =>
{
    var mesh = node.GetEntity<Mesh>();
    if (mesh != null)
    {
        numMeshes++;
        mesh = Watermark.EncodeWatermark(mesh, "HelloWorld", "1234");
        if (mesh != null)
        {
            node.Entity = mesh;
        }
    }
    return true;
});

//Сохраните файл в нужном формате
scene.Save(output, FileFormat.FBX7400ASCII);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="О Aspose.3D for .NET API" %}}

 Aspose.3D – это CAD и Gameware API для загрузки, изменения и преобразования файлов 3D. API является автономным и не требует никакого 3D программного обеспечения для моделирования или визуализации. Можно легко использовать API для Discreet3DS, WavefrontOBJ, STL (ASCII, двоичный), Universal3D, FBX (ASCII, двоичный), Collada, glTF, PLY, GLB, DirectX и другие форматы. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

   {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для добавления слепого водяного знака на USD" sectionDescription="Проверьте наши живые демонстрации, чтобы [Водяной знак USD](https://products.aspose.app/3d/watermark/usd) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать или компилировать код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл USD и нажмите кнопку \"Водяной знак\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Загрузите файл USD по ссылке, если требуется" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="USD" readMoreLink="https://docs.fileformat.com/3d/usd/" >}}
Файл с расширением .usd представляет собой формат универсального описания сцены, который кодирует данные для обмена данными и дополнения между приложениями для создания цифрового контента.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другое поддерживаемое приложение для добавления слепого водяного знака в форматы" subTitle="Используя C#, можно также добавить слепой водяной знак ко многим другим форматам файлов, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3mf/" name="3MF" description="3D Производственный формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/amf/" name="AMF" description="Формат аддитивного производства" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ase/" name="ASE" description="Файл 2D-анимации" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dae/" name="DAE" description="Биржа цифровых активов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dxf/" name="DXF" description="Формат обмена чертежами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/fbx/" name="FBX" description="3D Формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/glb/" name="GLB" description="3D Двоичное представление файла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/gltf/" name="GLTF" description="Формат передачи GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/jt/" name="JT" description="Файл тесселяции Юпитера" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/obj/" name="OBJ" description="3D Формат файла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ply/" name="PLY" description="Формат файла многоугольника" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/rvm/" name="RVM" description="Модель проектирования завода AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/stl/" name="STL" description="Взаимозаменяемая геометрия поверхности 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/vrml/" name="VRML" description="Язык моделирования виртуальной реальности" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/x/" name="Икс" description="Изображение модели DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3ds/" name="3DS" description="3D Формат файла Studio Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usdz/" name="USDZ" description="Универсальное описание сцены Zip-архив" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}