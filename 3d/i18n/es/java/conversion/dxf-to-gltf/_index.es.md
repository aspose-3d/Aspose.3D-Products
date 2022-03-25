﻿---
title: Convertir DXF a GLTF a través de Java 
weight: 2080
url: /es/java/conversion/dxf-to-gltf/ 
description: Ejemplo de Java código de conversión para DXF formato a GLTF archivo. Utilice este código de ejemplo para convertir DXF a GLTF dentro de cualquier aplicación basada en Web o Escritorio Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir DXF a GLTF a través de Java" h2="Conversión de DXF a GLTF mediante Java biblioteca sin software de modelado de 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir DXF a GLTF usando Java" %}}

 Para representar DXF a GLTF, usaremos
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API que es una plataforma de conversión de API for Java rica en funciones, potente y fácil de usar. Puede descargar su última versión directamente desde
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 E instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones al pom.xml.

{{% blocks/products/pf/agp/code-block title="Repositorio" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependencia" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir DXF a GLTF a través de Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programadores pueden convertir fácilmente DXF archivo a GLTF en solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargar DXF archivo a través del constructor de la clase Scene1. Crear una instancia de GltfSaveOptions1. Establecer GLTF propiedades específicas para la conversión avanzada1. Call Scene salvar método1. Pase la ruta de salida con GLTF extensión de archivo y objeto de GltfSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de conversión Java, asegúrese de que tiene los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con Java Entorno de tiempo de ejecución para aplicaciones JSP/JSF y aplicaciones de escritorio.- Obtenga la última versión de Aspose.3D for Java directamente de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DXF a GLTF Java Código fuente de conversión" offSpacer="" %}}

```cs
// Cargar el DXF en un objeto de Escena 
Scene document = new Scene("template.dxf");
// Crear una instancia de GltfSaveOptions 
GltfSaveOptions options = new GltfSaveOptions();
// Guardar DXF como GLTF 
document.save("output.gltf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="DXF a GLTF Demos en vivo de conversión" sectionDescription="[Convertir DXF a GLTF](https://products.aspose.app/3d/conversion/dxf-to-gltf) Ahora mismo visitando nuestro sitio web Live Demos. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su DXF archivo, se convertirá instantáneamente a GLTF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Biblioteca de manipulación de escenas" %}}

 Aspose.3D es CAD y Gameware API para cargar, modificar y convertir 3D archivos. API es independiente y no requiere ningún 3D software de modelado o renderizado. Uno puede usar fácilmente API para Discreet3DS, WavefrontOBJ, STL (ASCII, Binario), Universal3D, FBX (ASCII, Binario), Collada, glTF, PLY, GLB, DirectX y más formatos. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}

DXF, Formato de intercambio de dibujos o Formato de intercambio de dibujos es una representación de datos etiquetada del archivo de dibujo de AutoCAD. Cada elemento del archivo tiene un número entero de prefijo llamado código de grupo. Este código de grupo representa en realidad el elemento que sigue e indica el significado de un elemento de datos para un tipo de objeto dado. DXF permite representar casi toda la información especificada por el usuario en un archivo de dibujo. El formato de archivo DXF fue desarrollado por Autodesk como CAD formato de archivo de datos para la interoperabilidad de datos entre AutoCAD y otras aplicaciones. Por lo tanto, los datos se pueden importar de otros formatos a DXF a AutoCAD según las especificaciones de interoperabilidad del formato de archivo DXF.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF (Formato de transmisión GL) es un 3D formato de archivo que almacena 3D información de modelo en formato JSON. El uso de JSON minimiza tanto el tamaño de 3D activos como el procesamiento en tiempo de ejecución necesario para desempaquetar y usar esos activos. Fue adoptado para la transmisión y carga eficiente de 3D escenas y modelos por aplicaciones. glTF fue desarrollado por el Grupo de Trabajo de Formatos de Khronos Group 3D y sus creadores también lo describen como JPEG de 3D. El formato define un formato de publicación común y extensible para 3D herramientas y servicios de contenido que agiliza los flujos de trabajo de creación y permite el uso interoperable del contenido en toda la industria. La intención detrás de la creación del formato de archivo glTF era definir un formato de publicación común y extensible para 3D herramientas y servicios de contenido que deberían agilizar los flujos de trabajo de creación y permitir el uso interoperable del contenido en toda la industria. Minimiza el procesamiento en tiempo de ejecución de las aplicaciones que utilizan WebGL y otras API.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones soportadas" subTitle="También puede convertir DXF en muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-3ds/" name="DXF A 3DS" description="3D Malla DOS de estudio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-amf/" name="DXF A AMF" description="Formato de fabricación aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ase/" name="DXF A ASE" description="Archivo de animación 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-dae/" name="DXF A DAE" description="Intercambio de activos digitales" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-fbx/" name="DXF A FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-html/" name="DXF A HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-obj/" name="DXF A OBJ" description="3D Formato de archivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ply/" name="DXF A PLY" description="Formato de archivo Polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-rvm/" name="DXF A RVM" description="Modelo de diseño de planta AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-stl/" name="DXF A STL" description="Geometría de superficie intercambiable 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-u3d/" name="DXF A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}