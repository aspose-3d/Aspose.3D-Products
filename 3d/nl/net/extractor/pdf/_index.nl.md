﻿---
title: Middelen extraheren uit PDF bestandsindelingen via .NET 
weight: 830
url: /nl/net/extractor/pdf/ 
description: C# broncode voor het laden, weergeven en toevoegen van extract-items uit PDF documenten op .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Middelen extraheren uit PDF via C#" h2="Bouw uw eigen .NET apps om activa uit PDF bestanden te extraheren met behulp van server-side API\'s." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Middelen extraheren uit PDF-bestand met C#" %}}

 Om items uit het PDF-bestand te extraheren, gebruiken we
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, een veelzijdig, krachtig en gebruiksvriendelijk API voor C#-platform dat kan worden gebruikt met extract-items. Open
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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om activa uit PDF te extraheren via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D maakt het de ontwikkelaars gemakkelijk om items uit het PDF-bestand te extraheren met slechts enkele regels code.

{{% /blocks/products/pf/agp/text %}}

- Laad PDF bestand via de constructor van Scene klasse- Maak een zip-bestandsformaatobject als uitvoerbestandsformaat- Archiefklasse maken en activaklasse uitpakken verwerken- Roep de Extract-methode aan en sla het bestand op
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET wordt ondersteund op alle belangrijke besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Mono- Ontwikkelomgeving zoals Microsoft Visual Studio- Aspose.3D for .NET waarnaar wordt verwezen in uw project
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code om activa uit PDF te extraheren" offSpacer="" %}}

```cs

//Bronbestanden die activa moeten extraheren
var scenes = FileFormat.PDF.ExtractScene("template.pdf");
for(int i = 0; i < scenes.Count; i++)
{
    scenes[i].Save($"scene-{i}.fbx", FileFormat.FBX7400ASCII);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Over Aspose.3D for .NET API" %}}

 Aspose.3D is een CAD en Gameware API om 3D-bestanden te laden, aan te passen en te converteren. API is een standalone en vereist geen 3D-modellerings- of renderingsoftware. Men kan gemakkelijk API gebruiken voor Discreet3DS, WavefrontOBJ, STL (ASCII, Binair), Universal3D, FBX (ASCII, Binair), Collada, glTF, PLY, GLB, DirectX en meer formaten. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app om activa uit PDF te extraheren" sectionDescription="Bekijk onze live demo\'s om [Extractor PDF](https://products.aspose.app/3d/extractor/pdf) met volgende voordelen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft niets te downloaden of in te stellen" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven of te compileren" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon het bestand PDF en klik op de knop \"Uitpakken\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download PDF bestand via de link, indien nodig" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" >}}
Portable Document Format (PDF) is een type document dat in de jaren negentig door Adobe is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van applicatiesoftware, hardware en besturingssysteem. PDF bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en ook in de meeste moderne browsers zoals Chrome, Safari, Firefox via extensies/plug-ins.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde app om activa uit formaten te extraheren" subTitle="Met behulp van C# kan One ook middelen extraheren uit vele andere bestandsindelingen, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3mf/" name="3MF" description="3D Productie-indeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/amf/" name="AMF" description="Additief productieformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ase/" name="ASE" description="2D-animatiebestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/dae/" name="DAE" description="Digitale activauitwisseling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/dxf/" name="DXF" description="Tekening uitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/fbx/" name="FBX" description="3D Formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/glb/" name="GLB" description="3D Binaire weergave van bestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/gltf/" name="GLTF" description="GL-verzendformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/jt/" name="JT" description="Jupiter Tessellation-bestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/obj/" name="OBJ" description="3D Bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ply/" name="PLY" description="Polygoon-bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3ds/" name="3DS" description="3D Studio Mesh-bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/rvm/" name="RVM" description="AVEVA Plant Design Model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/stl/" name="STL" description="Verwisselbare 3D oppervlaktegeometrie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/vrml/" name="VRML" description="Virtual Reality-modelleringstaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/x/" name="X" description="DirectX-modelafbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usd/" name="USD" description="Universele scènebeschrijving" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usdz/" name="USDZ" description="Universele scènebeschrijving Zip-archief" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}