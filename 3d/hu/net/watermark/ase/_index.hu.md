﻿---
title: "Adjon hozzá vak vízjelet a ASE fájlformátumokhoz a következőn keresztül: .NET "
weight: 830
url: /hu/net/watermark/ase/ 
description: C# forráskód a .NET Framework, .NET Core, Mono ASE dokumentumok betöltéséhez, megjelenítéséhez és vak vízjel hozzáadásához.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Adjon hozzá vak vízjelet a következőhöz: ASE a következőn keresztül: C#" h2="Készítse el saját .NET alkalmazásait vízjellel ASE fájlokhoz szerveroldali API-k segítségével." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ASE" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Vízjel hozzáadása ASE fájlhoz a C# használatával" %}}

 A(z) ASE fájl vízjelezéséhez a következőt használjuk:
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, amely funkciókban gazdag, hatékony és könnyen használható API a C# platformhoz, amely bármilyen vízjel hozzáadásával használható. Nyisd ki
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

{{% blocks/products/pf/agp/feature-section-col title="A vak vízjel hozzáadásának lépései a(z) ASE számára a(z) C# segítségével" %}}

{{% blocks/products/pf/agp/text %}}

 A Aspose.3D megkönnyíti a fejlesztők számára, hogy néhány kódsorral vak vízjelet adjanak a ASE fájlhoz.

{{% /blocks/products/pf/agp/text %}}

- ASE fájl betöltése a Scene osztály konstruktorán keresztül- Szerezze meg a(z) Aspose.3D mesh osztályát- Adjon hozzá vízjelet és jelszót Aspose.3D EncodeWatermark metódusával- Hívja meg a Scene.Save metódust objektummal
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A(z) Aspose.3D for .NET minden nagyobb operációs rendszeren támogatott. Csak győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy egy kompatibilis operációs rendszer .NET Framework, .NET Core, Mono- Fejlesztői környezet, például a Microsoft Visual Studio- A projektben hivatkozott Aspose.3D for .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód a vak vízjel hozzáadásához a következőhöz: ASE" offSpacer="" %}}

```cs

//forrásfájl, amelyet vízjellel kell ellátni, és a kimeneti fájl mentés után
string file = "template.ase";
string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

// hozzon létre egy jelenet példányt
Scene scene = new Scene(file);

//Vízjel és jelszó hozzáadása a fájlokhoz
var numMeshes = 0;
scene.RootNode.Accept((Node node) =>
{
    var mesh = node.GetEntity<Mesh>();
    if (mesh != null)
    {
        numMeshes++;
        mesh = Watermark.EncodeWatermark(mesh, "HelloWorld", "1234");
        if (mesh != null)
        {
            node.Entity = mesh;
        }
    }
    return true;
});

//Mentse el a fájlt a kívánt formátumban
scene.Save(output, FileFormat.FBX7400ASCII);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Körülbelül Aspose.3D for .NET API" %}}

 A Aspose.3D egy CAD és egy Gameware API, amely 3D fájlok betöltésére, módosítására és konvertálására szolgál. A API önálló, és nem igényel semmilyen 3D modellező vagy megjelenítő szoftvert. A API egyszerűen használható a következőhöz: Discreet3DS, WavefrontOBJ, STL (ASCII, bináris), Universal3D, FBX (ASCII, bináris), Collada, glTF, PLY, GLB, DirectX és további formátumok. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ingyenes alkalmazás vak vízjel hozzáadásához a következőhöz: ASE" sectionDescription="Tekintse meg élő bemutatóinkat [Vízjel ASE](https://products.aspose.app/3d/watermark/ase) a következő előnyökkel." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni vagy beállítani semmit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni vagy fordítani" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltsön fel ASE fájlt, és nyomja meg a \"Vízjel\" gombot" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ha szükséges, töltsön le ASE fájlt a linkről" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}
A ASE fájl egy 2D animáció vagy grafika, amely rétegeket, kereteket, palettákat, címkéket és beállításokat tartalmaz.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}



<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott alkalmazások vak vízjelek formátumokhoz való hozzáadásához" subTitle="A C# használatával vak vízjelet is hozzáadhat sok más fájlformátumhoz, beleértve." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3mf/" name="3MF" description="3D Gyártási formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/amf/" name="AMF" description="Additív gyártási formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3ds/" name="3DS" description="3D Studio Mesh fájlformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dae/" name="DAE" description="Digitális Eszközcsere" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dxf/" name="DXF" description="Rajzcsere formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/fbx/" name="FBX" description="3D Formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/glb/" name="GLB" description="3D Fájl bináris megjelenítése" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/gltf/" name="GLTF" description="GL átviteli formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/jt/" name="JT" description="Jupiter Testszellációs Fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/obj/" name="OBJ" description="3D Fájlformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ply/" name="PLY" description="Sokszög fájlformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/rvm/" name="RVM" description="AVEVA üzemtervezési modell" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/stl/" name="STL" description="Cserélhető 3D felületi geometria" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/vrml/" name="VRML" description="Virtuális valóság modellező nyelv" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/x/" name="x" description="DirectX modell képe" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usd/" name="USD" description="Univerzális jelenetleírás" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usdz/" name="USDZ" description="Universal Scene Description Zip Archive" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}