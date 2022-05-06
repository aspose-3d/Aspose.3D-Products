﻿---
title: Convertir DXF a OBJ a través de C# 
weight: 1660
url: /es/net/conversion/dxf-to-obj/ 
description: Ejemplo de código para la conversión de DXF a OBJ C#. Utilice el código de ejemplo API para la conversión por lotes de archivos DXF a OBJ dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir DXF a OBJ a través de C#" h2="Renderizar DXF como OBJ sin ningún software de modelado y renderizado 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir DXF a OBJ usando C#" %}}

 Para convertir DXF a OBJ, usaremos
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, que es una manipulación y conversión de documentos rica en funciones, potente y fácil de usar API para la plataforma C#. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 administrador de paquetes, busque
 Aspose.3D 
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de la consola del Administrador de paquetes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir DXF a OBJ a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

 Los programadores de .NET pueden cargar y convertir fácilmente archivos DXF a OBJ con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo DXF a través del constructor de la clase Escena1. Crear una instancia de ObjSaveOptions1. Establecer OBJ propiedades específicas para la conversión avanzada1. Llame al método Scene.Save1. Pase la ruta de salida con la extensión de archivo OBJ y el objeto de ObjSaveOptions1. Compruebe el archivo OBJ resultante en la ruta especificada
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de conversión .NET, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Mono.- Entorno de desarrollo como Microsoft Visual Studio.- Aspose.3D for .NET DLL a la que se hace referencia en tu proyecto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de muestra muestra la conversión de DXF a OBJ C#" offSpacer="" %}}

```cs
// carga el DXF en un objeto de Escena 
var document = new Aspose.ThreeD.Scene("template.dxf");
// crear una instancia de ObjSaveOptions 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// guardar DXF como OBJ 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicación gratuita para convertir DXF a OBJ" sectionDescription="Consulte nuestras demostraciones en vivo para [conversión de DXF a OBJ](https://products.aspose.app/3d/conversion/dxf-to-obj) con los siguientes beneficios." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo DXF y presione el botón \"Convertir\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá instantáneamente el enlace de descarga para el archivo OBJ resultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una biblioteca de procesamiento de archivos 3D para manipular archivos 3D sin ningún software de modelado y renderizado. 3D API admite Discreet3DS, WavefrontOBJ, FBX (ASCII, binario), STL (ASCII, binario), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formatos de archivo y más. Los desarrolladores pueden crear, leer, convertir, modificar y controlar la esencia de los formatos de documentos 3D fácilmente.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}
DXF, formato de intercambio de dibujos o formato de intercambio de dibujos, es una representación de datos etiquetados del archivo de dibujo de AutoCAD. Cada elemento en el archivo tiene un número entero de prefijo llamado código de grupo. Este código de grupo en realidad representa el elemento que sigue e indica el significado de un elemento de datos para un tipo de objeto dado. DXF permite representar casi toda la información especificada por el usuario en un archivo de dibujo. El formato de archivo DXF fue desarrollado por Autodesk como formato de archivo de datos CAD para la interoperabilidad de datos entre AutoCAD y otras aplicaciones. Por lo tanto, los datos se pueden importar desde otros formatos a DXF a AutoCAD según las especificaciones de interoperabilidad del formato de archivo DXF.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
Los archivos OBJ son utilizados por la aplicación Visualizador avanzado de Wavefront para definir y almacenar los objetos geométricos. La transmisión hacia adelante y hacia atrás de datos geométricos es posible a través de archivos OBJ. Tanto la geometría poligonal como puntos, líneas, vértices de textura, caras y geometría de forma libre (curvas y superficies) son compatibles con el formato OBJ. Este formato no admite animación ni información relacionada con la luz y la posición de las escenas. Un archivo OBJ suele ser un producto final del proceso de modelado 3D generado por un CAD (diseño asistido por computadora). El orden predeterminado para almacenar los vértices es en sentido contrario a las agujas del reloj, lo que evita la declaración explícita de caras normales. Aunque los archivos OBJ declaran información de escala en una línea de comentario, aún no se han declarado unidades para las coordenadas OBJ.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir DXF en muchos otros formatos de archivo, incluidos algunos de los que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-3ds/" name="DXF A 3DS" description="3D Malla DOS de estudio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-amf/" name="DXF A AMF" description="Formato de fabricación aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-dae/" name="DXF A DAE" description="Intercambio de activos digitales" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-fbx/" name="DXF A FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-html/" name="DXF A HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-pdf/" name="DXF A PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-ply/" name="DXF A PLY" description="Formato de archivo de polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-rvm/" name="DXF A RVM" description="Modelo de diseño de planta de AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-stl/" name="DXF A STL" description="Geometría de superficie intercambiable 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-u3d/" name="DXF A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}