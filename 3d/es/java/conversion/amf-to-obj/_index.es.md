﻿---
title: Convertir AMF a OBJ a través de Java 
weight: 3580
url: /es/java/conversion/amf-to-obj/ 
description: Muestra el código de conversión Java para el formato AMF en el archivo OBJ. Utilice este código de ejemplo para convertir AMF a OBJ dentro de cualquier aplicación basada en Java web o de escritorio.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir AMF a OBJ a través de Java" h2="Conversión de AMF a OBJ utilizando la biblioteca Java sin ningún software de modelado 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="AMF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir AMF a OBJ usando Java" %}}

 Para representar AMF a OBJ, usaremos
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API, que es una plataforma de conversión API for Java rica en funciones, potente y fácil de usar. Puedes descargar su última versión directamente desde
 [Experto](https://repository.aspose.com/3d/) 
 e instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones al pom.xml.

{{% blocks/products/pf/agp/code-block title="Repositorio" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repositorio.aspose.com/repo/</url>
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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir AMF a OBJ a través de Java" %}}

{{% blocks/products/pf/agp/text %}}

 Los programadores de Java pueden convertir fácilmente el archivo AMF en OBJ con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo AMF a través del constructor de la clase Escena1. Crear una instancia de ObjSaveOptions1. Establecer OBJ propiedades específicas para la conversión avanzada1. Llamar al método Scene.save1. Pase la ruta de salida con la extensión de archivo OBJ y el objeto de ObjSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de conversión Java, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.- Obtenga la última versión de Aspose.3D for Java directamente de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código fuente de conversión de AMF a OBJ Java" offSpacer="" %}}

```cs
// carga el AMF en un objeto de Escena 
Scene document = new Scene("template.amf");
// crear una instancia de ObjSaveOptions 
ObjSaveOptions options = new ObjSaveOptions();
// guardar AMF como OBJ 
document.save("output.obj", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Demostraciones en vivo de conversión de AMF a OBJ" sectionDescription="[Convertir AMF a OBJ](https://products.aspose.app/3d/conversion/amf-to-obj) ahora mismo visitando nuestro sitio web de demostraciones en vivo. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo AMF, se convertirá instantáneamente a OBJ." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Biblioteca de manipulación de escenas" %}}

 Aspose.3D es un CAD y Gameware API para cargar, modificar y convertir archivos 3D. API es independiente y no requiere ningún 3D software de modelado o renderizado. Uno puede usar fácilmente API para Discreet3DS, WavefrontOBJ, STL (ASCII, binario), Universal3D, FBX (ASCII, binario), Collada, glTF, PLY, GLB, DirectX y más formatos. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="AMF" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}

El formato de archivo de fabricación aditiva (AMF) define estándares abiertos para la descripción de objetos para ser utilizados por procesos de fabricación aditiva como la impresión 3D. Los programas CAD usan el formato de archivo AMF haciendo uso de información como la geometría, el color y el material de los objetos. AMF es diferente al formato STL ya que el lateral no admite color, materiales, entramados ni constelaciones.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

Los archivos OBJ son utilizados por la aplicación Visualizador avanzado de Wavefront para definir y almacenar los objetos geométricos. La transmisión hacia adelante y hacia atrás de datos geométricos es posible a través de archivos OBJ. Tanto la geometría poligonal como puntos, líneas, vértices de textura, caras y geometría de forma libre (curvas y superficies) son compatibles con el formato OBJ. Este formato no admite animación ni información relacionada con la luz y la posición de las escenas. Un archivo OBJ suele ser un producto final del proceso de modelado 3D generado por un CAD (diseño asistido por computadora). El orden predeterminado para almacenar los vértices es en sentido contrario a las agujas del reloj, lo que evita la declaración explícita de caras normales. Aunque los archivos OBJ declaran información de escala en una línea de comentario, aún no se han declarado unidades para las coordenadas OBJ.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir AMF en muchos otros formatos de archivo, incluidos algunos de los que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-3ds/" name="AMF A 3DS" description="3D Malla DOS de estudio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-dae/" name="AMF A DAE" description="Intercambio de activos digitales" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-fbx/" name="AMF A FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-gltf/" name="AMF A GLTF" description="Formato de transmisión GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-html/" name="AMF A HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-ply/" name="AMF A PLY" description="Formato de archivo de polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-rvm/" name="AMF A RVM" description="Modelo de diseño de planta de AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-stl/" name="AMF A STL" description="Geometría de superficie intercambiable 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-u3d/" name="AMF A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}