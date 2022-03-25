﻿---
title: DRC FBX-re konvertálni Java-en keresztül 
url: /hu/java/conversion/drc-to-fbx/ 
description: Minta Java konverziós kód DRC formátumban FBX fájlba. Használja ezt a példakódot a DRC FBX-re történő konvertálásához bármely webes vagy asztali Java alapú alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="DRC FBX-re konvertálni Java-en keresztül" h2="DRC FBX konverzióra Java könyvtár használatával minden 3D modellezési szoftver nélkül." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Hogyan lehet konvertálni DRC FBX Java használatával" %}}

 A DRC FBX rendereléséhez használjuk
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API ami egy funkcióban gazdag, erős és könnyen használható konverziós API for Java platform. Letöltheti legújabb verzióját közvetlenül a
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 És telepítse a maven-alapú projektben a következő konfigurációk hozzáadásával a pom.xml-hez.

{{% blocks/products/pf/agp/code-block title="Adattár" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
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

{{% blocks/products/pf/agp/feature-section-col title="Lépések a DRC FBX-re való konvertálásához Java-en keresztül" %}}

{{% blocks/products/pf/agp/text %}}

 Java a programozók a DRC fájlt egyszerűen FBX-re konvertálhatják néhány sor kóddal.

{{% /blocks/products/pf/agp/text %}}

1. A DRC fájl betöltése a jelenet-osztály konstruktőrjén keresztül1. Hozzon létre egy példány fbxsaveoptions1. FBX specifikus tulajdonságok beállítása a fejlett konverzióhoz1. Hívás jelenet. mentés módszer1. Adja át a kimeneti utat FBX fájl kiterjesztés & objektum fbxsaveoptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Java konverziós kód futtatása előtt győződjön meg róla, hogy a következő feltételekkel rendelkezik.

{{% /blocks/products/pf/agp/text %}}

- Microsoft windows vagy egy kompatibilis operációs rendszer Java futásidejű környezettel a jsp/jsf alkalmazások és asztali alkalmazások számára.- A Aspose.3D for Java legújabb verzióját közvetlenül a maven-től kapja.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DRC a FBX Java konverziós forráskódhoz" offSpacer="" %}}

```cs
// A DRC-t a jelenet objektumába tölti 
Scene document = new Scene("template.drc");
// Hozzon létre egy példány fbxsaveoptions 
AmfSaveOptions options = new FbxSaveOptions();
// Mentés DRC FBX 
document.save("output.fbx", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="DRC a FBX konverziós élő demók" sectionDescription="[Konvertálni DRC FBX](https://products.aspose.app/3d/conversion/drc-to-fbx) Most az élő demók honlapunkon. az élő demó a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell semmiféle kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltsön fel a DRC fájlt, akkor azonnal átalakítani FBX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Kapsz a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D jelenetmanipulációs könyvtár" %}}

 Aspose.3D egy CAD és a gameware API 3D fájlok betöltésére, módosítására és átalakítására. API önálló és nem igényel semmilyen 3D modellezési vagy renderezési szoftvert. API Discreet3DS, WavefrontOBJ, STL (ascii, bináris), Universal3D, FBX (ascii, bináris), Collada, glTF, PLY, GLB, directx és több formátum. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}

Egy fájl. A drc kiterjesztés a Google Draco könyvtárral létrehozott tömörített 3D fájlformátum. Google a Draco nyílt forráskódú könyvtárként kínál 3D geometrikus hálók és pontfelhők tömörítésére és dekompressziójára, valamint javítja a 3D grafika tárolását és átvitelét. A bemeneti adatokat kódolja, és így takarítja meg. Drc fájlja. A fogadó végén a API olvasható. Drc fájlokat, és ezek kimenetele PLY vagy OBJ fájlok. A tömörített kimeneti fájl lehetővé teszi a felhasználók számára, hogy az alkalmazások gyorsabb letöltését és a 3D grafikák gyors betöltését nyújtsák a böngészőkben.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}

A FBX, filmbox egy népszerű 3D fájlformátum, amelyet eredetileg a kaydara fejlesztett a motionbuilder számára. 2006-ban felvásárolta az autodesk inc, és most az egyik fő 3D csereformátum, amit sok 3D eszköz használ. FBX elérhető bináris és ascii fájlformátumban egyaránt. A formátum azért jött létre, hogy a digitális tartalomteremtő alkalmazások közötti átjárhatóságot biztosítson. Számos eszköz áll rendelkezésre a konverzióról/FBX fájlformátumra.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}