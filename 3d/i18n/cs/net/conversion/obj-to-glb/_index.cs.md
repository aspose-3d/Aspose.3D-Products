﻿---
title: Convert OBJ to GLB via C# 
url: /cs/net/conversion/obj-to-glb/ 
description: Vzorový kód pro konverzaci OBJ na GLB C#. Použijte API příklad kódu pro dávku OBJ souborů na GLB konverzaci v rámci vb .NET, asp .NET nebo kterékoli aplikace založené na .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convert OBJ to GLB via C#" h2="Render OBJ as GLB without any 3D modeling and rendering software." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést OBJ na GLB pomocí C#" %}}

 Pro převádění OBJ na GLB použijeme
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod OBJ na GLB prostřednictvím C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programátoři mohou snadno načíst a převést OBJ soubory do GLB v několika řadách kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načíst soubor OBJ prostřednictvím konstruktora třídy scény1. Vytvořit instance of amfsaveoptions1. Nastavit specifické vlastnosti GLB pro pokročilou konverzii1. Volejte scénu. uložit metodu1. Přejít výstupní cestu s GLB příponou souboru a objektem stlsaveoptions (% % % % + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + +1. Zkontrolovat výsledný soubor GLB při zadané cestě
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním kódu .NET se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft windows nebo kompatibilní os s .NET framework, .NET core, Mono.- Vývojové prostředí jako microsoft visual studio.- Aspose.3D for .NET dll odkazovaný ve vašem projektu.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tento vzorový kód ukazuje konverzaci OBJ na GLB C#" offSpacer="" %}}

```cs
// Načíst OBJ v objektu scény 
var document = new Aspose.ThreeD.Scene("template.obj");
// Vytvořit instanci gltfsaveoptions 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions(FileContentType.Binary);
// Uložit OBJ jako GLB 
document.Save("output.glb", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Free app to convert OBJ to GLB" sectionDescription="Check our live demos for [Konverzace OBJ na GLB](https://products.aspose.app/3d/conversion/obj-to-glb) S následujícími přínosy." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba nic stáhnout nebo instalovat." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba napsat žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your OBJ file and hit the \"convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will immediately get the download link for resultant GLB file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Knihovna zpracování souborů 3D pro manipulaci souborů 3D bez modelování a vykreslování softwaru. 3D API podporuje Discreet3DS, WavefrontOBJ, FBX (ascii, binární), GLB (ascii, binární), Universal3D, Collada, glTF, GLB, PLY, directx, Google Draco formáty souborů a další. Vývojáři mohou snadno vytvořit, číst, převést, upravit a ovládat obsah formátů 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
OBJ soubory používají aplikace advanced visualizer aplikace Wavefront pro definování a ukládání geometrických objektů. Zpětný a přední přenos geometrických dat je umožněn pomocí OBJ souborů. Obě polygonální geometrie jako body, čáry, texturní vrcholy, tváře a geometrie volné formy (křivky a povrchy) jsou podporovány OBJ formátem. Tento formát nepodporuje animaci ani informace týkající se světla a polohy scén. OBJ soubor je obvykle konečný produkt procesu modelování 3D generovaného CAD (computer aided design). Výchozí pořadí pro ukládání vrcholů je proti směru hodinových ručiček, aby se vyhýbalo výslovnému deklaraci normů obličeje. Ačkoli soubory OBJ v příznakovém řádku deklarují informace o stupnici, nebyly pro souřadnice OBJ deklarovány žádné jednotky.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB je binární formát formátu zobrazení modelů 3D uložených ve formátu přenos gl (glTF). Informace o modelech 3D, jako je hierarchie uzlů, kamery, materiály, animace a sítě v binárním formátu. Tento binární formát ukládá glTF aktivum (json,. Bin a obrázky) v binárním blobu. Rovněž se vyhýbá problému zvýšení velikosti souboru, které se odehrává v případě glTF. GLB formát souborů má za následek kompaktní velikost souborů, rychlé načítání, úplné zobrazování scény 3D a rozšiřovatelnost pro další vývoj. Formát používá model/gltf-binární jako typ mime.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}