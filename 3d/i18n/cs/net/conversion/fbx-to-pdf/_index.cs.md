﻿---
title: Convert FBX to PDF via C# 
weight: 2590
url: /cs/net/conversion/fbx-to-pdf/ 
description: Vzorový kód pro konverzaci FBX na PDF C#. Použijte API příklad kódu pro dávku FBX souborů na PDF konverzaci v rámci vb .NET, asp .NET nebo kterékoli aplikace založené na .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convert FBX to PDF via C#" h2="Render FBX as PDF without any 3D modeling and rendering software." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést FBX na PDF pomocí C#" %}}

 Pro převádění FBX na PDF použijeme
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, který je bohatý na funkce, výkonný a snadno použitelné manipulace a konverzace dokumentů API pro platformu C#. Otevřít
 [Nuget](https://www.nuget.org/packages/aspose.3d) 
 Správce balíčků, hledat
 Aspose.3D 
 A nainstalovat. Můžete použít také následující příkaz z konzoly správce balíků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly správce balíků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod FBX na PDF prostřednictvím C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programátoři mohou snadno načíst a převést FBX soubory do PDF v několika řadách kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načíst soubor FBX prostřednictvím konstruktora třídy scény1. Vytvořit instanci pdfsaveoptions1. Nastavit specifické vlastnosti PDF pro pokročilou konverzii1. Volejte scénu. uložit metodu1. Přejít výstupní cestu s PDF příponou souboru a objektem pdfsaveoptions1. Zkontrolovat výsledný soubor PDF při zadané cestě
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním kódu .NET se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft windows nebo kompatibilní os s .NET framework, .NET core, Mono.- Vývojové prostředí jako microsoft visual studio.- Aspose.3D for .NET dll odkazovaný ve vašem projektu.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tento vzorový kód ukazuje konverzaci FBX na PDF C#" offSpacer="" %}}

```cs
// Načíst FBX v objektu scény 
var document = new Aspose.ThreeD.Scene("template.fbx");
// Vytvořit instanci pdfsaveoptions 
var options = new Aspose.ThreeD.Formats.PdfSaveOptions();
// Uložit FBX jako PDF 
document.Save("output.pdf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Free app to convert FBX to PDF" sectionDescription="Check our live demos for [Konverzace FBX na PDF](https://products.aspose.app/3d/conversion/fbx-to-pdf) S následujícími přínosy." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba nic stáhnout nebo instalovat." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba napsat žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your FBX file and hit the \"convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will immediately get the download link for resultant PDF file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Knihovna zpracování souborů 3D pro manipulaci souborů 3D bez modelování a vykreslování softwaru. 3D API podporuje Discreet3DS, WavefrontOBJ, FBX (ascii, binární), STL (ascii, binární), Universal3D, Collada, glTF, GLB, PLY, directx, Google Draco formáty souborů a další. Vývojáři mohou snadno vytvořit, číst, převést, upravit a ovládat obsah formátů 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, filmbox, je populární formát 3D, který původně vyvinul kaydara pro motionbuilder. It was acquired by autodesk inc in 2006 and now is one of the main 3D exchange formats as used by many 3D tools. FBX je k dispozici v binárním i ascii formátu. Formát byl vytvořen tak, aby zajistil interoperabilitu mezi aplikacemi pro vytváření digitálního obsahu. There are many tools available for conversion from/to FBX file format.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable document format (PDF) is a type of document created by adobe back in 1990s. Účelem tohoto formátu souboru bylo zavést standard pro reprezentaci dokumentů a jiných referenčních materiálů ve formátu, který je nezávislý na aplikačním softwaru, hardwaru i operačním systému. PDF soubory lze otevřít v adobe acrobat reader/writer i ve většině moderních prohlížečů jako chrome, safari, firefox prostřednictvím rozšíření/zásuvných modulů. Většina komerčně dostupných softwarových balíčků také nabízí konverzaci jejich dokumentů do PDF formátu souboru bez požadavku jakékoli další softwarové složky. PDF formát souborů má plnou schopnost obsahovat informace jako text, obrázky, hypertextové odkazy, pole formulářů, bohaté média, digitální podpisy, přílohy, metadata, geospatial features and 3D objects in it that can become as part of source document.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované převody" subTitle="Můžete také převést FBX do mnoha jiných formátů souborů, včetně několika uvedených níže." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-3ds/" name="FBX až 3DS" description="3D studio dos mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-amf/" name="FBX až AMF" description="Aditivní formát výroby" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-dae/" name="FBX až DAE" description="Výměna digitálních aktiv" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-html/" name="FBX až HTML" description="Jazyk označování hypertextů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-obj/" name="FBX až OBJ" description="3D formát souboru" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-ply/" name="FBX až PLY" description="Formát souboru polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-rvm/" name="FBX až RVM" description="Aveva plant design model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-stl/" name="FBX až STL" description="Zaměnitelná geometrie povrchu 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-u3d/" name="FBX až U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}