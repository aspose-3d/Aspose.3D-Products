﻿---
title: Extraiga activos de PDF formatos de archivo a través de .NET 
weight: 830
url: /es/net/extractor/pdf/ 
description: Código fuente de C# para cargar, renderizar y agregar activos extraídos de PDF documentos en .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Extraer activos de PDF a través de C#" h2="Cree sus propias aplicaciones .NET para extraer recursos de archivos PDF mediante las API del lado del servidor." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Cómo extraer activos del archivo PDF usando C#" %}}

 Para extraer activos del archivo PDF, usaremos
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, que es una plataforma API para C# rica en funciones, potente y fácil de usar para usar con recursos de extracción. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 administrador de paquetes, busque
 **Aspose.3D** 
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de la consola del Administrador de paquetes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para extraer activos de PDF a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D facilita a los desarrolladores la extracción de activos del archivo PDF con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

- Cargue el archivo PDF a través del constructor de la clase Escena- Crear objeto de formato de archivo zip como formato de archivo de salida- Crear clase de archivo y manejar la clase de activo de extracción- Llame al método Extract y guarde el archivo
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET es compatible con todos los principales sistemas operativos. Solo asegúrese de tener los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Mono- Entorno de desarrollo como Microsoft Visual Studio- Aspose.3D for .NET referenciado en su proyecto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código C# para extraer recursos de PDF" offSpacer="" %}}

```cs

//Archivos de origen que necesitan extraer activos
var scenes = FileFormat.PDF.ExtractScene("template.pdf");
for(int i = 0; i < scenes.Count; i++)
{
    scenes[i].Save($"scene-{i}.fbx", FileFormat.FBX7400ASCII);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Acerca de Aspose.3D for .NET API" %}}

 Aspose.3D es un CAD y Gameware API para cargar, modificar y convertir archivos 3D. API es independiente y no requiere ningún 3D software de modelado o renderizado. Uno puede usar fácilmente API para Discreet3DS, WavefrontOBJ, STL (ASCII, binario), Universal3D, FBX (ASCII, binario), Collada, glTF, PLY, GLB, DirectX y más formatos. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicación gratuita para extraer activos de PDF" sectionDescription="Consulte nuestras demostraciones en vivo para [Extractor PDF](https://products.aspose.app/3d/extractor/pdf) con los siguientes beneficios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir o compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue el archivo PDF y presione el botón \"Extraer\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Descargue el archivo PDF desde el enlace, si es necesario" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" >}}
El formato de documento portátil (PDF) es un tipo de documento creado por Adobe en la década de 1990. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato que es independiente del software de la aplicación, el hardware y el sistema operativo. Los archivos PDF se pueden abrir en Adobe Acrobat Reader/Writer también en la mayoría de los navegadores modernos como Chrome, Safari, Firefox a través de extensiones/complementos.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otra aplicación compatible para extraer activos de formatos" subTitle="Con C#, también se pueden extraer activos de muchos otros formatos de archivo, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3mf/" name="3MF" description="3D formato de fabricación" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/amf/" name="AMF" description="Formato de fabricación aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ase/" name="ASE" description="Archivo de animación 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/dae/" name="DAE" description="Intercambio de activos digitales" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/dxf/" name="DXF" description="Formato de intercambio de dibujos" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/fbx/" name="FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/glb/" name="GLB" description="3D Representación binaria de archivos" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/gltf/" name="GLTF" description="Formato de transmisión GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/jt/" name="JT" description="Archivo de teselado de Júpiter" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/obj/" name="OBJ" description="3D formato de archivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ply/" name="PLY" description="Formato de archivo de polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3ds/" name="3DS" description="3D Formato de archivo de malla de Studio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/rvm/" name="RVM" description="Modelo de diseño de planta de AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/stl/" name="STL" description="Geometría de superficie intercambiable 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/vrml/" name="VRML" description="Lenguaje de modelado de realidad virtual" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/x/" name="X" description="Imagen del modelo de DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usd/" name="USD" description="Descripción de la escena universal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usdz/" name="USDZ" description="Universal Escena Descripción Zip Archivo" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}