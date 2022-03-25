﻿---
title: Convert DAE to OBJ via C# 
weight: 240
url: /cs/net/conversion/dae-to-obj/ 
description: Vzorový kód pro konverzaci DAE na OBJ C#. Použijte API příklad kódu pro dávku DAE souborů na OBJ konverzaci v rámci vb .NET, asp .NET nebo kterékoli aplikace založené na .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convert DAE to OBJ via C#" h2="Render DAE as OBJ without any 3D modeling and rendering software." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DAE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést DAE na OBJ pomocí C#" %}}

 Pro převádění DAE na OBJ použijeme
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod DAE na OBJ prostřednictvím C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programátoři mohou snadno načíst a převést DAE soubory do OBJ v několika řadách kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načíst soubor DAE prostřednictvím konstruktora třídy scény1. Vytvořit instance objsaveoptions1. Nastavit specifické vlastnosti OBJ pro pokročilou konverzii1. Volejte scénu. uložit metodu1. Přejít výstupní cestu s OBJ rozšířením souboru a objektem opcí objsaveoptions1. Zkontrolovat výsledný soubor OBJ při zadané cestě
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním kódu .NET se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft windows nebo kompatibilní os s .NET framework, .NET core, Mono.- Vývojové prostředí jako microsoft visual studio.- Aspose.3D for .NET dll odkazovaný ve vašem projektu.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tento vzorový kód ukazuje konverzaci DAE na OBJ C#" offSpacer="" %}}

```cs
// Načíst DAE v objektu scény 
var document = new Aspose.ThreeD.Scene("template.dae");
// Vytvořit instance objsaveoptions 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// Uložit DAE jako OBJ 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Free app to convert DAE to OBJ" sectionDescription="Check our live demos for [Konverzace DAE na OBJ](https://products.aspose.app/3d/conversion/dae-to-obj) S následujícími přínosy." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba nic stáhnout nebo instalovat." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba napsat žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DAE file and hit the \"convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will immediately get the download link for resultant OBJ file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Knihovna zpracování souborů 3D pro manipulaci souborů 3D bez modelování a vykreslování softwaru. 3D API podporuje Discreet3DS, WavefrontOBJ, FBX (ascii, binární), STL (ascii, binární), Universal3D, Collada, glTF, GLB, PLY, directx, Google Draco formáty souborů a další. Vývojáři mohou snadno vytvořit, číst, převést, upravit a ovládat obsah formátů 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}
Soubor DAE je formát souboru pro výměnu digitálních aktiv, který se používá pro výměnu dat mezi interaktivními aplikacemi 3D. Tento formát souboru je založen na schématu collada (collaborative design activity) xml, což je otevřená standardní schéma xml pro výměnu digitálních aktiv mezi aplikacemi grafického softwaru. Byla přijata iso jako veřejně dostupná specifikace, iso/pas 17506.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
OBJ soubory používají aplikace advanced visualizer aplikace Wavefront pro definování a ukládání geometrických objektů. Zpětný a přední přenos geometrických dat je umožněn pomocí OBJ souborů. Obě polygonální geometrie jako body, čáry, texturní vrcholy, tváře a geometrie volné formy (křivky a povrchy) jsou podporovány OBJ formátem. Tento formát nepodporuje animaci ani informace týkající se světla a polohy scén. OBJ soubor je obvykle konečný produkt procesu modelování 3D generovaného CAD (computer aided design). Výchozí pořadí pro ukládání vrcholů je proti směru hodinových ručiček, aby se vyhýbalo výslovnému deklaraci normů obličeje. Ačkoli soubory OBJ v příznakovém řádku deklarují informace o stupnici, nebyly pro souřadnice OBJ deklarovány žádné jednotky.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované převody" subTitle="Můžete také převést DAE do mnoha jiných formátů souborů, včetně několika uvedených níže." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-3ds/" name="DAE až 3DS" description="3D studio dos mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-amf/" name="DAE až AMF" description="Aditivní formát výroby" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-fbx/" name="DAE až FBX" description="Formát 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-html/" name="DAE až HTML" description="Jazyk označování hypertextů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-pdf/" name="DAE až PDF" description="Formát přenosného dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-ply/" name="DAE až PLY" description="Formát souboru polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-rvm/" name="DAE až RVM" description="Aveva plant design model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-stl/" name="DAE až STL" description="Zaměnitelná geometrie povrchu 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-u3d/" name="DAE až U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}