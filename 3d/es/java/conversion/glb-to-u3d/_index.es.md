﻿---
title: Convertir GLB a U3D a través de Java
weight: 530
url: /es/java/conversion/glb-to-u3d/ 
description: Muestra el código de conversión Java para el formato GLB en el archivo U3D. Utilice este código de ejemplo para convertir GLB a U3D dentro de cualquier aplicación basada en Java web o de escritorio.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir GLB a U3D a través de Java" h2="Conversión de GLB a U3D utilizando la biblioteca Java sin ningún software de modelado 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir GLB a U3D usando Java" %}}

 Para representar GLB a U3D, usaremos
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API, que es una plataforma de conversión API for Java rica en funciones, potente y fácil de usar. Puedes descargar su última versión directamente desde
 [Experto](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir GLB a U3D a través de Java" %}}

{{% blocks/products/pf/agp/text %}}

 Los programadores de Java pueden convertir fácilmente el archivo GLB en U3D con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo GLB a través del constructor de la clase Escena1. Llame al método Scene.save con el formato de U3D.1. Compruebe el archivo U3D resultante en la ruta especificada
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de conversión Java, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.- Obtenga la última versión de Aspose.3D for Java directamente de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código fuente de conversión de GLB a U3D Java" offSpacer="" %}}

```cs
// Cargue el archivo GLTF binario de origen
Scene scene = new Scene("sourceFile.glb");
// Convierta la escena 3D en un archivo en formato Universal 3D
scene.save("output.u3d", FileFormat.UNIVERSAL3D)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Demostraciones en vivo de conversión de GLB a U3D" sectionDescription="[Convertir GLB a U3D](https://products.aspose.app/3d/conversion/glb-to-u3d) ahora mismo visitando nuestro sitio web de demostraciones en vivo. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo GLB, se convertirá instantáneamente a U3D." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Biblioteca de manipulación de escenas" %}}

 Aspose.3D es un CAD y Gameware API para cargar, modificar y convertir archivos 3D. API es independiente y no requiere ningún 3D software de modelado o renderizado. Uno puede usar fácilmente API para USD, Discreet3DS, WavefrontOBJ, STL (ASCII, binario), Universal3D, FBX (ASCII, binario), Collada, glTF, PLY, GLB, DirectX y más formatos. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}

GLB es la representación en formato de archivo binario de 3D modelos guardados en el formato de transmisión GL (glTF). Información sobre 3D modelos como jerarquía de nodos, cámaras, materiales, animaciones y mallas en formato binario. Este formato binario almacena el activo glTF (JSON, .bin e imágenes) en un blob binario. También evita el problema del aumento del tamaño del archivo que ocurre en el caso de glTF. El formato de archivo GLB da como resultado tamaños de archivo compactos, carga rápida, representación completa de escenas 3D y extensibilidad para un mayor desarrollo. El formato usa model/gltf-binary como tipo MIME.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}

U3D (Universal 3D) es un formato de archivo comprimido y una estructura de datos para gráficos de computadora 3D. Contiene 3D información del modelo, como mallas triangulares, iluminación, sombreado, datos de movimiento, líneas y puntos con color y estructura. El formato fue aceptado como estándar ECMA-363 en agosto de 2005. 3D PDF documentos admiten U3D objetos incrustados y se pueden ver en Adobe Reader (versión 7 y posteriores). El formato U3D se desarrolló teniendo en cuenta el objetivo de establecer un estándar universal para el almacenamiento e intercambio de datos tridimensionales. Sin embargo, el formato encuentra su uso principal en la codificación de 3D PDF en lugar de usarse como un formato de intercambio. Acrobat 3D convierte un tipo de archivo 3D admitido en U3D o PRC al convertirlo en PDF.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir GLB en muchos otros formatos de archivo, incluidos algunos de los que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-gltf/" name="GLB A GLTF" description="Archivo de formato de transmisión GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-pdf/" name="GLB A PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-fbx/" name="GLB A FBX" description="Archivo de intercambio de Autodesk FBX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-stl/" name="GLB A STL" description="Archivo de estereolitografía" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-obj/" name="GLB A OBJ" description="Wavefront 3D archivo de objeto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-3ds/" name="GLB A 3DS" description="3D Escena de estudio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-dae/" name="GLB A DAE" description="Archivo de intercambio de activos digitales" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-u3d/" name="GLB A U3D" description="Universal 3D Archivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-ply/" name="GLB A PLY" description="Formato de archivo de polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-drc/" name="GLB A DRC" description="Google Draco formato de archivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-rvm/" name="GLB A RVM" description="AVEVA RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-jt/" name="GLB A JT" description="JT Abrir CAD archivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-amf/" name="GLB A AMF" description="Archivo de fabricación aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-html/" name="GLB A HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-usd/" name="GLB A USD" description="Formato de descripción de escena universal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-usdz/" name="GLB A USDZ" description="Descripción de la escena universal Formato comprimido" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}