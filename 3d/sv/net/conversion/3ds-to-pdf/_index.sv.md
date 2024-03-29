﻿---
title: Konvertera 3DS till PDF via C# 
weight: 2380
url: /sv/net/conversion/3ds-to-pdf/ 
description: Exempelkod för konvertering från 3DS till PDF C#. Använd API exempelkod för batch-3DS-filer till PDFkonvertering inom VB.NET, Asp.NET eller någon .NET-baserad applikation.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera 3DS till PDF via C#" h2="Rendera 3DS som PDF utan någon 3D-modellerings- och renderingsprogramvara." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du 3DS till PDF med C#" %}}

 För att konvertera 3DS till PDF använder vi
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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera 3DS till PDF via C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programmerare kan enkelt ladda och konvertera 3DS filer till PDF på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda 3DS-filen via konstruktorn för Scene-klassen1. Skapa en instans av PdfSaveOptions1. Ställ in PDF specifika egenskaper för avancerad konvertering1. Anropa metoden Scene.Save1. Skicka utdatasökvägen med PDF filtillägg och objekt för PdfSaveOptions1. Kontrollera den resulterande filen PDF vid angiven sökväg
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör omvandlingskoden .NET, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Mono.- Utvecklingsmiljö som Microsoft Visual Studio.- Aspose.3D for .NET DLL som refereras till i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Den här exempelkoden visar omvandling från 3DS till PDF C#" offSpacer="" %}}

```cs
// ladda 3DS i ett objekt av Scene 
var document = new Aspose.ThreeD.Scene("template.3ds");
// skapa en instans av PdfSaveOptions 
var options = new Aspose.ThreeD.Formats.PdfSaveOptions();
// spara 3DS som en PDF 
document.Save("output.pdf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app för att konvertera 3DS till PDF" sectionDescription="Kolla in våra livedemos för [3DS till PDF omvandling](https://products.aspose.app/3d/conversion/3ds-to-pdf) med följande förmåner." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner eller ställa in någonting." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din 3DS-fil och tryck på \"Konvertera\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du får omedelbart nedladdningslänken för den resulterande filen PDF." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Ett 3D filbearbetningsbibliotek för att manipulera 3D filer utan några modellerings- och renderingsprogram. 3D API stöder Discreet3DS, WavefrontOBJ, FBX (ASCII, binär), STL (ASCII, binär), Universal3D, Collada, glTF, GLB, Filformaten PLY, DirectX, Google Draco och mer. Utvecklare kan enkelt skapa, läsa, konvertera, ändra och kontrollera innehållet i 3D dokumentformat.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
En fil med tillägget 3DS representerar 3D Studio (DOS) mesh-filformat som används av Autodesk 3D Studio. Autodesk 3D Studio har funnits på marknaden för 3D filformat sedan 1990-talet och har nu utvecklats till 3D Studio MAX för att arbeta med 3D-modellering, animering och rendering. En 3DS-fil innehåller data för 3D-representation av scener och bilder och är ett av de populära filformaten för 3D-dataimport och -export. Den tar hänsyn till information som kameraplatser, nätdata, ljusinformation, visningsportkonfigurationer, utjämnande gruppdata, bitmappsreferenser och attribut för att skapa hörn och polygoner för att rendera en scen.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) är en typ av dokument som skapades av Adobe på 1990-talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av applikationsprogramvara, hårdvara samt operativsystem. PDF-filer kan öppnas i Adobe Acrobat Reader/Writer också i de flesta moderna webbläsare som Chrome, Safari, Firefox via tillägg/plugin-program. De flesta av de kommersiellt tillgängliga programvarupaketen erbjuder även konvertering av sina dokument till filformatet PDF utan krav på någon ytterligare programvarukomponent. Således har filformatet PDF full förmåga att innehålla information som text, bilder, hyperlänkar, formulärfält, rich media, digitala signaturer, bilagor, metadata, geospatiala funktioner och 3D objekt i det som kan bli en del av källan dokumentera.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera 3DS till många andra filformat, inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-amf/" name="3DS TILL AMF" description="Additiv tillverkningsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-dae/" name="3DS TILL DAE" description="Digital Asset Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-fbx/" name="3DS TILL FBX" description="3D Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-html/" name="3DS TILL HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-obj/" name="3DS TILL OBJ" description="3D Filformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-ply/" name="3DS TILL PLY" description="Polygon filformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-rvm/" name="3DS TILL RVM" description="AVEVA Plant Design Model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-stl/" name="3DS TILL STL" description="Utbytbar 3D ytgeometri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-u3d/" name="3DS TILL U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}