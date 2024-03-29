﻿---
title: "X fájlformátum megtekintése a következőn keresztül: .NET "
weight: 2050
url: /hu/net/viewer/x/ 
description: C# forráskód az X dokumentumok betöltéséhez, megjelenítéséhez és megjelenítéséhez a .NET Framework, .NET Core, Mono rendszerben.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="fájlnézegető for .NET" h2="Rendereljen le X fájlokat 3D modellező és renderelő szoftver nélkül." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="X" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="X" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="X fájl megtekintése a következővel: C#" %}}

 Az X fájl megtekintéséhez használjuk
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, amely funkciókban gazdag, hatékony és könnyen használható API a C# platformhoz, amely bármely Viewer-rel használható. Nyisd ki
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 csomagkezelő, keressen
 **Aspose.3D** 
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Csomagkezelő konzolparancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Az X megtekintése a következőn keresztül: C#" %}}

{{% blocks/products/pf/agp/text %}}

 A Aspose.3D segítségével a fejlesztők egyszerűen megtekinthetik az X-fájlt néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be az X fájlt a Scene osztály konstruktorán keresztül1. Hozzon létre egy Html5SaveOptions példányt1. Állítsa be a speciális formázás tulajdonságait1. Hívja meg a Scene.Save metódust a Html5SaveOptions objektumával1. Ellenőrizze a kapott HTML fájlt az alapértelmezett böngészőben
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A(z) Aspose.3D for .NET minden nagyobb operációs rendszeren támogatott. Csak győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy egy kompatibilis operációs rendszer .NET Framework, .NET Core, Mono- Fejlesztői környezet, például a Microsoft Visual Studio- A projektben hivatkozott Aspose.3D for .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód az X megtekintéséhez" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// betölteni az X jelenetet a Scene egy példányán keresztül
var scene = new ThreeD.Scene("template.x");
// hozzon létre egy Html5SaveOptions objektumot, és állítsa be a formázás tulajdonságait
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // kapcsolja ki a rácsot
    ShowGrid = false,
    // kapcsolja ki a felhasználói felületet
    ShowUI = false
};

// 3D jelenet mentése HTML5 néven
scene.Save(output, options);
// a kapott HTML betöltése az alapértelmezett böngészőben
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Körülbelül Aspose.3D for .NET API" %}}

 A Aspose.3D egy CAD és egy Gameware API, amely 3D fájlok betöltésére, módosítására és konvertálására szolgál. A API önálló, és nem igényel semmilyen 3D modellező vagy megjelenítő szoftvert. A API egyszerűen használható a következőhöz: Discreet3DS, WavefrontOBJ, STL (ASCII, bináris), Universal3D, FBX (ASCII, bináris), Collada, glTF, PLY, GLB, DirectX és további formátumok. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ingyenes alkalmazás az X megtekintéséhez" sectionDescription="Tekintse meg élő bemutatóinkat [X megtekintése](https://products.aspose.app/3d/viewer/x) a következő előnyökkel." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni vagy beállítani semmit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni vagy fordítani" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltsön fel X fájlt, és nyomja meg a \"Nézet\" gombot" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ha szükséges, töltsön le X fájlt a linkről" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="X" readMoreLink="https://docs.fileformat.com/3d/x/" >}}
Az X egy DirectX-modell képfájl, amelyet a DirectX technológia használ, és amely a játékokban való 3D grafikai megjelenítésre szolgál. A fájlformátum 3D objektumstruktúrát határoz meg a hálókhoz, textúrákhoz, animációkhoz és objektumokhoz.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott megjelenítő formátumok" subTitle="A C# használatával számos más fájlformátum is megtekinthető, beleértve a." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D Gyártási formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Additív gyártási formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="2D animációs fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Digitális Eszközcsere" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="Rajzcsere formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D Formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D Fájl bináris megjelenítése" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="GL átviteli formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="Jupiter Testszellációs Fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D Fájlformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Sokszög fájlformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="AVEVA üzemtervezési modell" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="Cserélhető 3D felületi geometria" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Virtuális valóság modellező nyelv" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP Archiválási formátum" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}