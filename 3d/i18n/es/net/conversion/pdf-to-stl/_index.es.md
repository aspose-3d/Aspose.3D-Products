﻿---
title: Convertir PDF a STL a través de C# 
weight: 450
url: /es/net/conversion/pdf-to-stl/ 
description: Código de muestra para la conversión de PDF a STL C#. Use API código de ejemplo para los archivos por lotes PDF a la conversión de STL dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir PDF a STL a través de C#" h2="Render PDF como STL sin ningún 3D software de modelado y renderizado." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir PDF a STL usando C#" %}}

 Para convertir PDF a STL, usaremos
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API que es una plataforma de conversión y manipulación de documentos rica en funciones, potente y fácil de usar API para C#. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Gestor de paquetes, búsqueda
 Aspose.3D 
 E instalar. También puede utilizar el siguiente comando de la Consola del Administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de consola de Package Manager" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir PDF a STL a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programadores pueden cargar y convertir fácilmente PDF archivos a STL en solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargar PDF archivo a través del constructor de la clase Scene1. Crear una instancia de StlSaveOptions1. Establecer STL propiedades específicas para la conversión avanzada1. Llame al método Scene.Save1. Pase la ruta de salida con STL extensión de archivo y objeto de StlSaveOptions1. Comprobar STL archivo resultante en la ruta especificada
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de conversión .NET, asegúrese de que tiene los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Mono.- Entorno de desarrollo como Microsoft Visual Studio.- Aspose.3D for .NET DLL al que se hace referencia en su proyecto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de ejemplo muestra la conversión de PDF a STL C#" offSpacer="" %}}

```cs
// Cargar el PDF en un objeto de Escena 
var document = new Aspose.ThreeD.Scene("template.pdf");
// Crear una instancia de StlSaveOptions 
var options = new Aspose.ThreeD.Formats.StlSaveOptions();
// Guardar PDF como STL 
document.Save("output.stl", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicación gratuita para convertir PDF a STL" sectionDescription="Consulte nuestras demostraciones en vivo para [Conversión de PDF a STL](https://products.aspose.app/3d/conversion/pdf-to-stl) Con los siguientes beneficios." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su PDF archivo y presione el botón \"Convertir\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá instantáneamente el enlace de descarga para el archivo STL resultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una biblioteca de procesamiento de archivos 3D para manipular 3D archivos sin ningún software de modelado y renderizado. El 3D API es compatible con Discreet3DS, WavefrontOBJ, FBX (ASCII, binario), STL (ASCII, binario), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formatos de archivo y más. Los desarrolladores pueden crear, leer, convertir, modificar y controlar la sustancia de 3D formatos de documentos fácilmente.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) es un tipo de documento creado por Adobe en la década de 1990. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato que sea independiente del software de aplicación, hardware y sistema operativo. PDF archivos se pueden abrir en Adobe Acrobat Reader/Writer, así como en la mayoría de los navegadores modernos como Chrome, Safari, Firefox a través de extensiones/complementos. La mayoría de las suites de software disponibles comercialmente también ofrecen la conversión de sus documentos al formato de archivo PDF sin el requisito de ningún componente de software adicional. Por lo tanto, PDF formato de archivo tiene plena capacidad para contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, firmas digitales, archivos adjuntos, metadatos, funciones geoespaciales y 3D objetos que pueden convertirse en parte del documento de origen.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="stl" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, abreviatura de estereolitrografía, es un formato de archivo intercambiable que representa la geometría de superficie tridimensional. El formato de archivo encuentra su uso en varios campos, como la creación rápida de prototipos, la impresión 3D y la fabricación asistida por computadora. Representa una superficie como una serie de pequeños triángulos, conocidos como facetas, donde cada faceta se describe mediante una dirección perpendicular y tres puntos que representan los vértices del triángulo. Las aplicaciones utilizan datos resultantes para determinar la sección transversal de la forma 3D que construirá el fabricante. No hay información disponible en el formato de archivo STL para la representación del color, la textura u otros atributos comunes del modelo CAD.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones soportadas" subTitle="También puede convertir PDF en muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-3ds/" name="PDF A 3DS" description="3D Malla DOS de estudio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-amf/" name="PDF A AMF" description="Formato de fabricación aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-dae/" name="PDF A DAE" description="Intercambio de activos digitales" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-fbx/" name="PDF A FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-html/" name="PDF A HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-obj/" name="PDF A OBJ" description="3D Formato de archivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-ply/" name="PDF A PLY" description="Formato de archivo Polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-rvm/" name="PDF A RVM" description="Modelo de diseño de planta AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-u3d/" name="PDF A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}