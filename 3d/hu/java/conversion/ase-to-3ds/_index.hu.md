﻿---
title: "ASE konvertálása 3DS-re a következőn keresztül: Java "
weight: 770
url: /hu/java/conversion/ase-to-3ds/ 
description: Minta Java konverziós kód ASE formátumhoz 3DS fájlba. Ezzel a példakóddal konvertálhatja a(z) ASE kódot 3DS-re bármely web- vagy asztali Java alapú alkalmazásban.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ASE konvertálása 3DS-re a következőn keresztül: Java" h2="ASE konvertálása 3DS-re a Java könyvtár használatával, 3D modellező szoftver nélkül." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="ASE konvertálása 3DS-re a Java használatával" %}}

 A(z) ASE megjelenítéséhez a(z) 3DS számára a következőt használjuk:
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API, amely funkciókban gazdag, hatékony és könnyen használható konverziós API for Java platform. A legújabb verziót közvetlenül a webhelyről töltheti le
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
 és telepítse a Maven-alapú projekten belül a következő konfigurációk hozzáadásával a pom.xml fájlhoz.

{{% blocks/products/pf/agp/code-block title="Adattár" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Függőség" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Lépések a(z) ASE konvertálásához 3DS-re a következőn keresztül: Java" %}}

{{% blocks/products/pf/agp/text %}}

 A Java programozói könnyedén konvertálhatnak ASE fájlt 3DS formátumba, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. ASE fájl betöltése a Scene osztály konstruktorán keresztül1. Hozzon létre egy 3dsSaveOptions példányt1. Állítson be 3DS speciális tulajdonságot a speciális konverzióhoz1. Hívja a Scene.save metódust1. Adja meg a kimeneti útvonalat 3DS fájlkiterjesztéssel és a 3dsSaveOptions objektumával
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Java konverziós kód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futásidejű környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.- Szerezze be a(z) Aspose.3D for Java legújabb verzióját közvetlenül a Maventől.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ASE – 3DS Java Konverziós forráskód" offSpacer="" %}}

```cs
// töltse be a(z) ASE elemet a jelenet egyik objektumába 
Scene document = new Scene("template.ase");
// hozzon létre egy 3dsSaveOptions példányt 
Discreet3dsSaveOptions options = new Discreet3dsSaveOptions();
// ASE mentése 3DS-ként 
document.save("output.3ds", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="ASE–3DS Konverziós élő bemutatók" sectionDescription="[ASE konvertálása 3DS-re](https://products.aspose.app/3d/conversion/ase-to-3ds) most keresse fel az Élő bemutatók webhelyét.Az élő bemutató a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel a(z) ASE fájlt, és azonnal konvertálódik a(z) 3DS fájlba." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Megkapod a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Jelenetmanipulációs könyvtár" %}}

 A Aspose.3D egy CAD és egy Gameware API, amely 3D fájlok betöltésére, módosítására és konvertálására szolgál. A API önálló, és nem igényel semmilyen 3D modellező vagy megjelenítő szoftvert. A API egyszerűen használható a következőhöz: Discreet3DS, WavefrontOBJ, STL (ASCII, bináris), Universal3D, FBX (ASCII, bináris), Collada, glTF, PLY, GLB, DirectX és további formátumok. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}

A ASE fájl egy 2D animáció vagy grafika, amely rétegeket, kereteket, palettákat, címkéket és beállításokat tartalmaz.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}

A 3DS kiterjesztésű fájl az Autodesk 3D Studio által használt 3D Studio (DOS) mesh fájlformátumot képviseli. Az Autodesk 3D Studio az 1990-es évek óta működik a 3D fájlformátumok piacán, és mostanra a 3D Studio MAX-má fejlődött, hogy 3D modellezéssel, animációval és rendereléssel dolgozzon. A 3DS fájl a jelenetek és képek 3D megjelenítéséhez tartalmaz adatokat, és az egyik legnépszerűbb fájlformátum az 3D adatok importálásához és exportálásához. Figyelembe veszi az olyan információkat, mint a kamera helye, hálóadatok, világítási információk, nézetablak konfigurációk, simító csoportadatok, bittérképes hivatkozások és attribútumok csúcsok és sokszögek létrehozásához a jelenet rendereléséhez.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A(z) ASE fájlt számos más fájlformátumra is konvertálhatja, köztük néhány alább felsorolt fájlformátumra." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-amf/" name="ASE - AMF" description="Additív gyártási formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-dae/" name="ASE - DAE" description="Digitális Eszközcsere" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-fbx/" name="ASE - FBX" description="3D Formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-gltf/" name="ASE - GLTF" description="GL átviteli formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-html/" name="ASE - HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-obj/" name="ASE - OBJ" description="3D Fájlformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-ply/" name="ASE - PLY" description="Sokszög fájlformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-rvm/" name="ASE - RVM" description="AVEVA üzemtervezési modell" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-stl/" name="ASE - STL" description="Cserélhető 3D felületi geometria" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-u3d/" name="ASE - U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}