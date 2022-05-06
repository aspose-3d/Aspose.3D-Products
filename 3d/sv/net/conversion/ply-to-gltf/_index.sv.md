﻿---
title: Konvertera PLY till GLTF via C# 
url: /sv/net/conversion/ply-to-gltf/ 
description: Exempelkod för konvertering från PLY till GLTF C#. Använd API exempelkod för batch-PLY-filer till GLTFkonvertering inom VB.NET, Asp.NET eller någon .NET-baserad applikation.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera PLY till GLTF via C#" h2="Rendera PLY som GLTF utan någon 3D-modellerings- och renderingsprogramvara." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du PLY till GLTF med C#" %}}

 För att konvertera PLY till GLTF använder vi
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API som är en funktionsrik, kraftfull och lättanvänd dokumenthantering och konvertering API för C#-plattformen. Öppen
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 pakethanterare, sök efter
 Aspose.3D 
 och installera. Du kan också använda följande kommando från Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakethanterarens konsolkommando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera PLY till GLTF via C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programmerare kan enkelt ladda och konvertera PLY filer till GLTF på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda PLY-filen via konstruktorn för Scene-klassen1. Skapa en instans av AmfSaveOptions1. Ställ in GLTF specifika egenskaper för avancerad konvertering1. Anropa metoden Scene.Save1. Skicka utdatasökvägen med GLTF filtillägg och objekt för GltfSaveOptions1. Kontrollera den resulterande filen GLTF vid angiven sökväg
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör omvandlingskoden .NET, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Mono.- Utvecklingsmiljö som Microsoft Visual Studio.- Aspose.3D for .NET DLL som refereras till i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Den här exempelkoden visar omvandling från PLY till GLTF C#" offSpacer="" %}}

```cs
// ladda PLY i ett objekt av Scene 
var document = new Aspose.ThreeD.Scene("template.ply");
// skapa en instans av GltfSaveOptions 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions();
// spara PLY som en GLTF 
document.Save("output.gltf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app för att konvertera PLY till GLTF" sectionDescription="Kolla in våra livedemos för [PLY till GLTF omvandling](https://products.aspose.app/3d/conversion/ply-to-gltf) med följande förmåner." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner eller ställa in någonting." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din PLY-fil och tryck på \"Konvertera\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du får omedelbart nedladdningslänken för den resulterande filen GLTF." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Ett 3D filbearbetningsbibliotek för att manipulera 3D filer utan några modellerings- och renderingsprogram. 3D API stöder Discreet3DS, WavefrontOBJ, FBX (ASCII, binär), STL (ASCII, binär), Universal3D, Collada, glTF, GLB, Filformaten PLY, DirectX, Google Draco och mer. Utvecklare kan enkelt skapa, läsa, konvertera, ändra och kontrollera innehållet i 3D dokumentformat.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}
PLY, Polygon File Format, representerar 3D filformat som lagrar grafiska objekt som beskrivs som en samling polygoner. Syftet med detta filformat var att skapa en enkel och lätt filtyp som är tillräckligt generell för att vara användbar för ett brett spektrum av modeller. Filformatet PLY kommer som ASCII och binärt format för kompakt lagring och för snabb lagring och inläsning. Filformatet används av olika program som ger stöd för läsning av 3D filer.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="gltf" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (GL-överföringsformat) är ett 3D-filformat som lagrar 3D modellinformation i JSON-format. Användningen av JSON minimerar både storleken på 3D tillgångar och den körtidsbearbetning som krävs för att packa upp och använda dessa tillgångar. Den användes för effektiv överföring och laddning av 3D scener och modeller efter applikationer. glTF har utvecklats av Khronos Group 3D Formats Working Group och beskrivs också som JPEG av 3D av dess skapare. Formatet definierar ett utbyggbart, vanligt publiceringsformat för 3D innehållsverktyg och tjänster som effektiviserar författararbetsflöden och möjliggör interoperabel användning av innehåll i hela branschen. Avsikten bakom skapandet av filformatet glTF var att definiera ett utbyggbart, vanligt publiceringsformat för 3D innehållsverktyg och tjänster som skulle effektivisera författararbetsflöden och möjliggöra interoperabel användning av innehåll i hela branschen. Det minimerar körtidsbearbetning av applikationer som använder WebGL och andra API:er.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PLY till många andra filformat, inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-3ds/" name="PLY TILL 3DS" description="3D Studio DOS Mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-amf/" name="PLY TILL AMF" description="Additiv tillverkningsformat" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-dae/" name="PLY TILL DAE" description="Digital Asset Exchange" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-fbx/" name="PLY TILL FBX" description="3D Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-html/" name="PLY TILL HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-obj/" name="PLY TILL OBJ" description="3D Filformat" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-pdf/" name="PLY TILL PDF" description="Portabelt dokumentformat" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-rvm/" name="PLY TILL RVM" description="AVEVA Plant Design Model" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-stl/" name="PLY TILL STL" description="Utbytbar 3D ytgeometri" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-u3d/" name="PLY TILL U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}