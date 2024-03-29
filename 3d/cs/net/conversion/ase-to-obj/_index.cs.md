﻿---
title: Převést ASE na OBJ prostřednictvím C# 
weight: 1890
url: /cs/net/conversion/ase-to-obj/ 
description: Ukázkový kód pro konverzi ASE na OBJ C#. Použijte API ukázkový kód pro dávkový převod souborů ASE na OBJ v rámci VB.NET, Asp.NET nebo jakékoli aplikace založené na .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést ASE na OBJ prostřednictvím C#" h2="Vykreslit ASE jako OBJ bez jakéhokoli 3D modelovacího a vykreslovacího softwaru." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Jak převést ASE na OBJ pomocí C#" %}}

 Abychom převedli ASE na OBJ, použijeme
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, což je funkčně bohatý, výkonný a snadno použitelný nástroj pro manipulaci a konverzi dokumentů API pro platformu C#. Otevřeno
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 správce balíčků, vyhledejte
 Aspose.3D 
 a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly Správce balíčků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky ke konverzi ASE na OBJ prostřednictvím C#" %}}

{{% blocks/products/pf/agp/text %}}

 Programátoři .NET mohou snadno načíst a převést soubory ASE na OBJ pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor ASE pomocí konstruktoru třídy Scene1. Vytvořte instanci ObjSaveOptions1. Nastavte OBJ konkrétních vlastností pro pokročilý převod1. Zavolejte metodu Scene.Save1. Předejte výstupní cestu s příponou souboru OBJ a objektem ObjSaveOptions1. Zkontrolujte výsledný soubor OBJ v zadané cestě
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním konverzního kódu .NET se ujistěte, že splňujete následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s .NET Framework, .NET Core, Mono.- Vývojové prostředí jako Microsoft Visual Studio.- Aspose.3D for .NET DLL odkazovaná ve vašem projektu.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tento ukázkový kód ukazuje konverzi ASE na OBJ C#" offSpacer="" %}}

```cs
// načtěte ASE do objektu scény 
var document = new Aspose.ThreeD.Scene("template.ase");
// vytvořit instanci ObjSaveOptions 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// uložit ASE jako OBJ 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Bezplatná aplikace pro převod ASE na OBJ" sectionDescription="Podívejte se na naše živé ukázky [Konverze ASE na OBJ](https://products.aspose.app/3d/conversion/ase-to-obj) s následujícími výhodami." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není potřeba nic stahovat ani nastavovat." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát svůj soubor ASE a stisknout tlačítko „Převést“." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Okamžitě získáte odkaz ke stažení výsledného souboru OBJ." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Knihovna pro zpracování souborů 3D pro manipulaci se soubory 3D bez jakéhokoli modelovacího a vykreslovacího softwaru. 3D API podporuje Discreet3DS, WavefrontOBJ, FBX (ASCII, binární), STL (ASCII, binární), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formáty souborů a další. Vývojáři mohou snadno vytvářet, číst, převádět, upravovat a ovládat podstatu 3D formátů dokumentů.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}
Soubor ASE je 2D animace nebo grafika, která obsahuje vrstvy, rámečky, palety, značky a nastavení.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
Soubory OBJ jsou používány aplikací Advanced Visualizer společnosti Wavefront k definování a ukládání geometrických objektů. Zpětný a dopředný přenos geometrických dat je možný prostřednictvím OBJ souborů. Formát OBJ podporuje jak polygonální geometrii, jako jsou body, čáry, vrcholy textur, plochy, tak geometrii volného tvaru (křivky a povrchy). Tento formát nepodporuje animaci nebo informace související se světlem a polohou scén. Soubor OBJ je obvykle konečným produktem procesu modelování 3D generovaného pomocí CAD (Computer Aided Design). Výchozí pořadí pro ukládání vrcholů je proti směru hodinových ručiček, aby se zabránilo explicitní deklaraci normál ploch. Ačkoli soubory OBJ deklarují informace o měřítku v řádku komentáře, pro souřadnice OBJ nebyly deklarovány žádné jednotky.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="Můžete také převést soubor ASE do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-3ds/" name="ASE DO 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-amf/" name="ASE DO AMF" description="Formát aditivní výroby" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-dae/" name="ASE DO DAE" description="Výměna digitálních aktiv" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-fbx/" name="ASE DO FBX" description="Formát 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-html/" name="ASE DO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-pdf/" name="ASE DO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-ply/" name="ASE DO PLY" description="Formát souboru polygonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-rvm/" name="ASE DO RVM" description="Model rostlinného designu AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-stl/" name="ASE DO STL" description="Vyměnitelná 3D povrchová geometrie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-u3d/" name="ASE DO U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}