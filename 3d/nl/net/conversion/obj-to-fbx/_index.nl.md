﻿---
title: Converteer OBJ naar FBX via C# 
weight: 3600
url: /nl/net/conversion/obj-to-fbx/ 
description: Voorbeeldcode voor conversie van OBJ naar FBX C#. Gebruik API voorbeeldcode voor batch OBJ-bestanden naar FBX-conversie binnen VB.NET, Asp.NET of een op .NET gebaseerde applicatie.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer OBJ naar FBX via C#" h2="Geef OBJ weer als FBX zonder enige 3D modellerings- en weergavesoftware." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Hoe u OBJ naar FBX converteert met C#" %}}

 Om OBJ naar FBX te converteren, gebruiken we
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, een veelzijdige, krachtige en gebruiksvriendelijke documentmanipulatie en conversie API voor C#-platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 pakketbeheerder, zoek naar
 Aspose.3D 
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakketbeheer Console-opdracht" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om OBJ te converteren naar FBX via C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programmeurs kunnen gemakkelijk OBJ bestanden laden en converteren naar FBX in slechts een paar regels code.

{{% /blocks/products/pf/agp/text %}}

1. Laad OBJ bestand via de constructor van Scene klasse1. Maak een instantie van FbxSaveOptions1. Stel FBX specifieke eigenschappen in voor geavanceerde conversie1. Roep de Scene.Save-methode aan1. Geef het uitvoerpad door met FBX bestandsextensie & object van FbxSaveOptions1. Controleer het resulterende FBX-bestand op het opgegeven pad
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Voordat u de conversiecode .NET uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Mono.- Ontwikkelomgeving zoals Microsoft Visual Studio.- Aspose.3D for .NET DLL waarnaar wordt verwezen in uw project.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Deze voorbeeldcode toont OBJ naar FBX C# Conversie" offSpacer="" %}}

```cs
// laad de OBJ in een object van Scene 
var document = new Aspose.ThreeD.Scene("template.obj");
// maak een instantie van FbxSaveOptions 
var options = new Aspose.ThreeD.Formats.FbxSaveOptions();
// sla OBJ op als een FBX 
document.Save("output.fbx", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app om OBJ naar FBX te converteren" sectionDescription="Check onze live demo\'s voor [OBJ naar FBX conversie](https://products.aspose.app/3d/conversion/obj-to-fbx) met volgende voordelen." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft niets te downloaden of in te stellen." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon uw OBJ-bestand en klik op de knop \'Converteren\'." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" U krijgt direct de downloadlink voor het resulterende FBX-bestand." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Een 3D bestandsverwerkingsbibliotheek om 3D bestanden te manipuleren zonder enige modellerings- en weergavesoftware. De 3D API ondersteunt Discreet3DS, WavefrontOBJ, FBX (ASCII, Binair), STL (ASCII, Binair), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco bestandsindelingen en meer. Ontwikkelaars kunnen eenvoudig 3D documentformaten creëren, lezen, converteren, wijzigen en beheren.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
OBJ-bestanden worden gebruikt door de toepassing Advanced Visualizer van Wavefront om de geometrische objecten te definiëren en op te slaan. Voorwaartse en achterwaartse overdracht van geometrische gegevens wordt mogelijk gemaakt via OBJ bestanden. Zowel veelhoekige geometrie, zoals punten, lijnen, textuurhoekpunten, vlakken als vrije-vormgeometrie (krommen en oppervlakken) worden ondersteund door het OBJ-formaat. Dit formaat ondersteunt geen animatie of informatie met betrekking tot licht en positie van scènes. Een OBJ-bestand is meestal een eindproduct van het 3D-modelleringsproces dat wordt gegenereerd door een CAD (Computer Aided Design). De standaardvolgorde om hoekpunten op te slaan is tegen de klok in om expliciete declaratie van gezichtsnormalen te vermijden. Hoewel OBJ bestanden schaalinformatie aangeven in een commentaarregel, zijn er nog geen eenheden gedeclareerd voor OBJ coördinaten.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="fbx" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, is een populaire 3D-bestandsindeling die oorspronkelijk is ontwikkeld door Kaydara voor MotionBuilder. Het werd in 2006 overgenomen door Autodesk Inc en is nu een van de belangrijkste 3D uitwisselingsformaten die door veel 3D-tools worden gebruikt. FBX is beschikbaar in zowel binaire als ASCII-bestandsindeling. Het formaat is opgezet om interoperabiliteit te bieden tussen toepassingen voor het maken van digitale inhoud. Er zijn veel tools beschikbaar voor conversie van/naar FBX bestandsformaat.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt OBJ ook converteren naar vele andere bestandsindelingen, waaronder enkele die hieronder worden vermeld." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-3ds/" name="OBJ NAAR 3DS" description="3D Studio DOS-mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-amf/" name="OBJ NAAR AMF" description="Additief productieformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-dae/" name="OBJ NAAR DAE" description="Digitale activauitwisseling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-html/" name="OBJ NAAR HTML" description="Hypertekst-opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-pdf/" name="OBJ NAAR PDF" description="Draagbaar documentformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-ply/" name="OBJ NAAR PLY" description="Polygoon-bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-rvm/" name="OBJ NAAR RVM" description="AVEVA Plant Design Model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-stl/" name="OBJ NAAR STL" description="Verwisselbare 3D oppervlaktegeometrie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-u3d/" name="OBJ NAAR U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}