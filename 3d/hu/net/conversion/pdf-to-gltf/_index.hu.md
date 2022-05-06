﻿---
title: "PDF konvertálása GLTF-re a következőn keresztül: C# "
url: /hu/net/conversion/pdf-to-gltf/ 
description: Mintakód a(z) PDF–GLTF C# konverzióhoz. Használjon API példakódot a kötegelt PDF fájlok GLTF konvertálásához VB.NET, Asp.NET vagy bármely .NET alapú alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="PDF konvertálása GLTF-re a következőn keresztül: C#" h2="A(z) PDF megjelenítése GLTF-ként 3D modellező és megjelenítő szoftver nélkül." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PDF konvertálása GLTF-re a C# használatával" %}}

 A(z) PDF GLTF-re konvertálásához a következőt használjuk:
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési és -konverziós API a C# platformhoz. Nyisd ki
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 csomagkezelő, keressen
 Aspose.3D 
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Csomagkezelő konzolparancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Lépések a(z) PDF konvertálásához GLTF-re a következőn keresztül: C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programozói könnyedén betölthetnek és konvertálhatnak PDF fájlt GLTF formátumba, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. PDF fájl betöltése a Scene osztály konstruktorán keresztül1. Hozzon létre egy AmfSaveOptions példányt1. Állítson be GLTF speciális tulajdonságot a speciális konverzióhoz1. Hívja a Scene.Save metódust1. Adja meg a kimeneti útvonalat GLTF fájlkiterjesztéssel és a GltfSaveOptions objektumával1. Ellenőrizze a kapott GLTF fájlt a megadott elérési úton
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A .NET konverziós kód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy egy kompatibilis operációs rendszer .NET Framework, .NET Core, Mono rendszerrel.- Fejlesztői környezet, például a Microsoft Visual Studio.- Aspose.3D for .NET DLL-re hivatkozik a projektben.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ez a mintakód PDF–GLTF C# konverziót mutat" offSpacer="" %}}

```cs
// töltse be a(z) PDF elemet a jelenet egyik objektumába 
var document = new Aspose.ThreeD.Scene("template.pdf");
// hozzon létre egy GltfSaveOptions példányt 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions();
// PDF mentése GLTF-ként 
document.Save("output.gltf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ingyenes alkalmazás a(z) PDF konvertálásához GLTF-re" sectionDescription="Tekintse meg élő bemutatóinkat [PDF–GLTF konverzió](https://products.aspose.app/3d/conversion/pdf-to-gltf) a következő előnyökkel." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni vagy beállítani semmit." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel a(z) PDF fájlt, és nyomja meg a „Konvertálás” gombot." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Azonnal megkapja a letöltési linket az eredményül kapott GLTF fájlhoz." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Egy 3D fájlfeldolgozó könyvtár 3D fájlok kezeléséhez modellező és megjelenítő szoftverek nélkül. A 3D API támogatja a következőt: Discreet3DS, WavefrontOBJ, FBX (ASCII, bináris), STL (ASCII, bináris), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco fájlformátumok és egyebek. A fejlesztők könnyedén hozhatnak létre, olvashatnak, konvertálhatnak, módosíthatnak és szabályozhatnak 3D dokumentumformátumokat.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
A Portable Document Format (PDF) az Adobe által az 1990-es években létrehozott dokumentumtípus. Ennek a fájlformátumnak az volt a célja, hogy szabványt vezessen be a dokumentumok és egyéb referenciaanyagok olyan formátumban, amely független az alkalmazásszoftvertől, a hardvertől és az operációs rendszertől. A(z) PDF fájl megnyitható az Adobe Acrobat Reader/Writer programban, valamint a legtöbb modern böngészőben, például Chrome, Safari, Firefox bővítményeken/beépülő modulokon keresztül. A legtöbb kereskedelmi forgalomban kapható szoftvercsomag lehetőséget kínál a dokumentumok PDF fájlformátumra való konvertálására további szoftverkomponensek használata nélkül. Így a PDF fájlformátum teljes mértékben képes olyan információkat tartalmazni, mint például szöveg, képek, hiperhivatkozások, űrlapmezők, multimédiás média, digitális aláírások, mellékletek, metaadatok, térinformatikai jellemzők és 3D objektumok, amelyek a forrás részévé válhatnak. dokumentum.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="gltf" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (GL átviteli formátum) egy 3D fájlformátum, amely 3D modellinformációkat tárol JSON formátumban. A JSON használata minimálisra csökkenti mind a 3D-elemek méretét, mind az eszközök kicsomagolásához és használatához szükséges futásidejű feldolgozást. 3D jelenet és modell alkalmazás általi hatékony átvitelére és betöltésére alkalmazták. A(z) glTF fájlt a Khronos Group 3D Formátumok Munkacsoportja fejlesztette ki, és alkotói a(z) 3D JPEG-ként is leírták. A formátum egy bővíthető, általános közzétételi formátumot határoz meg a 3D tartalmi eszközök és szolgáltatások számára, amely leegyszerűsíti a szerzői munkafolyamatokat, és lehetővé teszi a tartalom interoperábilis felhasználását az iparágban. A glTF fájlformátum létrehozásának szándéka az volt, hogy egy bővíthető, közös közzétételi formátumot határozzanak meg a 3D tartalmi eszközök és szolgáltatások számára, amelyek egyszerűsítik a szerzői munkafolyamatokat, és lehetővé teszik a tartalom interoperábilis felhasználását az iparágban. Minimalizálja a WebGL-t és más API-kat használó alkalmazások futásidejű feldolgozását.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A(z) PDF fájlt számos más fájlformátumra is konvertálhatja, köztük néhány alább felsorolt fájlformátumra." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-3ds/" name="PDF - 3DS" description="3D Studio DOS Mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-amf/" name="PDF - AMF" description="Additív gyártási formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-dae/" name="PDF - DAE" description="Digitális Eszközcsere" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-fbx/" name="PDF - FBX" description="3D Formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-html/" name="PDF - HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-obj/" name="PDF - OBJ" description="3D Fájlformátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-ply/" name="PDF - PLY" description="Sokszög fájlformátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-rvm/" name="PDF - RVM" description="AVEVA üzemtervezési modell" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-stl/" name="PDF - STL" description="Cserélhető 3D felületi geometria" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-u3d/" name="PDF - U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}