﻿---
title: Добавьте слепую проверку водяных знаков к U3D форматам файлов через .NET 
weight: 830
url: /ru/net/verify-watermark/u3d/ 
description: Исходный код C# для загрузки, рендеринга и добавления слепой проверки водяных знаков в U3D документы на .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Добавьте слепую проверку водяного знака в U3D через C#" h2="Создайте свои собственные приложения .NET, чтобы добавлять слепую проверку водяных знаков в файлы U3D с помощью серверных API." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="U3D" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Как установить водяной знак для проверки файла U3D с помощью C#" %}}

 Чтобы поставить водяной знак на файл проверки U3D, мы будем использовать
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API — многофункциональная, мощная и простая в использовании платформа API для C#, которую можно использовать с добавлением любой проверки водяных знаков. Открыть
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по добавлению слепой проверки водяных знаков в U3D через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D позволяет разработчикам легко добавлять слепую проверку водяных знаков в файл U3D, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

- Загрузите файл U3D через конструктор класса Scene- Получите класс сетки Aspose.3D- Добавьте пароль, используя метод DecodeWatermark Aspose.3D.- Вызов метода Scene.Save с объектом
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono- Среда разработки, такая как Microsoft Visual Studio- Aspose.3D for .NET упоминается в вашем проекте
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# код для добавления слепой проверки водяного знака в U3D" offSpacer="" %}}

```cs

//Исходные файлы, которые должны быть снабжены водяными знаками для проверки
string file = "template.u3d";

// создать экземпляр сцены
Scene scene = new Scene(file);
string text =null;

//Добавьте пароль для проверки водяного знака методом DecodeWatermark
try
{
    scene.RootNode.Accept((Node node) =>
    {
        var mesh = node.GetEntity<Mesh>();
        if (mesh != null)
        {
            text = Watermark.DecodeWatermark(mesh, "1234");
            if (text != null)
                return false;
            }
            return true;
    });
}
catch (UnauthorizedAccessException)
{
    return "Password error";
}

//Возвращает ноль, если этот файл не имеет водяного знака, если есть водяной знак, возвращает содержимое водяного знака
return text;



```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="О Aspose.3D for .NET API" %}}

 Aspose.3D – это CAD и Gameware API для загрузки, изменения и преобразования файлов 3D. API является автономным и не требует никакого 3D программного обеспечения для моделирования или визуализации. Можно легко использовать API для Discreet3DS, WavefrontOBJ, STL (ASCII, двоичный), Universal3D, FBX (ASCII, двоичный), Collada, glTF, PLY, GLB, DirectX и другие форматы. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для добавления слепой проверки водяных знаков к U3D" sectionDescription="Проверьте наши живые демонстрации, чтобы [Проверка водяного знака U3D](https://products.aspose.app/3d/verify-watermark/u3d) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать или компилировать код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл U3D и нажмите кнопку \"Водяной знак\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Загрузите файл U3D по ссылке, если требуется" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}
U3D (Universal 3D) – это сжатый формат файла и структура данных для 3D компьютерной графики. Он содержит 3D информацию о модели, такую как треугольные сетки, освещение, затенение, данные движения, линии и точки с цветом и структурой. Формат был принят в качестве стандарта ECMA-363 в августе 2005 г. Документы 3D PDF поддерживают встраивание объектов U3D и могут быть просмотрены в Adobe Reader (версия 7 и выше).

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другое поддерживаемое приложение для добавления слепой проверки водяных знаков в форматы" subTitle="Используя C#, можно также добавить слепую проверку водяных знаков ко многим другим форматам файлов, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/3mf/" name="3MF" description="3D Производственный формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/amf/" name="AMF" description="Формат аддитивного производства" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/ase/" name="ASE" description="Файл 2D-анимации" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/dae/" name="DAE" description="Биржа цифровых активов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/dxf/" name="DXF" description="Формат обмена чертежами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/fbx/" name="FBX" description="3D Формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/glb/" name="GLB" description="3D Двоичное представление файла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/gltf/" name="GLTF" description="Формат передачи GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/jt/" name="JT" description="Файл тесселяции Юпитера" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/obj/" name="OBJ" description="3D Формат файла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/ply/" name="PLY" description="Формат файла многоугольника" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/rvm/" name="RVM" description="Модель проектирования завода AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/stl/" name="STL" description="Взаимозаменяемая геометрия поверхности 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/3ds/" name="3DS" description="3D Формат файла Studio Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/vrml/" name="VRML" description="Язык моделирования виртуальной реальности" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/x/" name="Икс" description="Изображение модели DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/usd/" name="USD" description="Описание универсальной сцены" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/usdz/" name="USDZ" description="Универсальное описание сцены Zip-архив" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}