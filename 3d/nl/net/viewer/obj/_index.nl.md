﻿---
title: Bekijk OBJ Bestandsindelingen via .NET 
weight: 1070
url: /nl/net/viewer/obj/ 
description: C# broncode voor het laden, weergeven en weergeven van OBJ documenten op .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="OBJ Bestandsviewer for .NET" h2="Render OBJ bestanden zonder enige 3D modellerings- en renderingsoftware." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Hoe OBJ-bestand te bekijken met C#" %}}

 Om het OBJ-bestand te bekijken, gebruiken we
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, een veelzijdig, krachtig en gebruiksvriendelijk API voor C#-platform dat met elke kijker kan worden gebruikt. Open
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 pakketbeheerder, zoek naar
 **Aspose.3D** 
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakketbeheer Console-opdracht" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om OBJ te bekijken via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D maakt het de ontwikkelaars gemakkelijk om het OBJ-bestand te bekijken met slechts enkele regels code.

{{% /blocks/products/pf/agp/text %}}

1. Laad OBJ bestand via de constructor van Scene klasse1. Maak een instantie van Html5SaveOptions1. Eigenschappen instellen voor geavanceerde opmaak1. Roep de Scene.Save-methode aan met het object van Html5SaveOptions1. Controleer het resulterende HTML-bestand in de standaardbrowser
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET wordt ondersteund op alle belangrijke besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Mono- Ontwikkelomgeving zoals Microsoft Visual Studio- Aspose.3D for .NET waarnaar wordt verwezen in uw project
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code om te bekijken OBJ" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// laad OBJ scene via een instantie van Scene
var scene = new ThreeD.Scene("template.obj");
// maak een object van Html5SaveOptions en stel eigenschappen in voor opmaak
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // schakel het raster uit
    ShowGrid = false,
    // schakel de gebruikersinterface uit
    ShowUI = false
};

// sla 3D scene op als HTML5
scene.Save(output, options);
// laad resultaat HTML in standaardbrowser
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Over Aspose.3D for .NET API" %}}

 Aspose.3D is een CAD en Gameware API om 3D-bestanden te laden, aan te passen en te converteren. API is een standalone en vereist geen 3D-modellerings- of renderingsoftware. Men kan gemakkelijk API gebruiken voor Discreet3DS, WavefrontOBJ, STL (ASCII, Binair), Universal3D, FBX (ASCII, Binair), Collada, glTF, PLY, GLB, DirectX en meer formaten. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app om te bekijken OBJ" sectionDescription="Bekijk onze live demo\'s om [Bekijk OBJ](https://products.aspose.app/3d/viewer/obj) met volgende voordelen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft niets te downloaden of in te stellen" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven of te compileren" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon OBJ bestand en klik op de knop \"Bekijken\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download OBJ bestand via de link, indien nodig" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
OBJ-bestanden worden gebruikt door de toepassing Advanced Visualizer van Wavefront om de geometrische objecten te definiëren en op te slaan. Voorwaartse en achterwaartse overdracht van geometrische gegevens wordt mogelijk gemaakt via OBJ bestanden. Zowel veelhoekige geometrie, zoals punten, lijnen, textuurhoekpunten, vlakken als vrije-vormgeometrie (krommen en oppervlakken) worden ondersteund door het OBJ-formaat. Dit formaat ondersteunt geen animatie of informatie met betrekking tot licht en positie van scènes. Een OBJ-bestand is meestal een eindproduct van het 3D-modelleringsproces dat wordt gegenereerd door een CAD (Computer Aided Design). De standaardvolgorde om hoekpunten op te slaan is tegen de klok in om expliciete declaratie van gezichtsnormalen te vermijden. Hoewel OBJ bestanden schaalinformatie aangeven in een commentaarregel, zijn er nog geen eenheden gedeclareerd voor OBJ coördinaten.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde viewerformaten" subTitle="Met behulp van C# kan men ook vele andere bestandsindelingen bekijken, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Studio DOS-mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D Productie-indeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Additief productieformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="2D-animatiebestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Digitale activauitwisseling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="Tekening uitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D Formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D Binaire weergave van bestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="GL-verzendformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="Jupiter Tessellation-bestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Polygoon-bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="AVEVA Plant Design Model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="Verwisselbare 3D oppervlaktegeometrie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Virtual Reality-modelleringstaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="X" description="DirectX-modelafbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP Archiveringsindeling" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}