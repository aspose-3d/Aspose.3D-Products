﻿---
title: Převést OBJ na JT prostřednictvím Java
weight: 530
url: /cs/java/conversion/obj-to-jt/ 
description: Ukázkový konverzní kód Java pro formát OBJ na soubor JT. Pomocí tohoto příkladu kódu převeďte OBJ na JT v jakékoli webové nebo desktopové aplikaci založené na Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést OBJ na JT prostřednictvím Java" h2="Převod OBJ na JT pomocí knihovny Java bez jakéhokoli modelovacího softwaru 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="JT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Jak převést OBJ na JT pomocí Java" %}}

 K vykreslení OBJ do JT použijeme
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API, což je funkčně bohatá, výkonná a snadno použitelná konverzní API for Java platforma. Jeho nejnovější verzi si můžete stáhnout přímo z
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
 a nainstalujte jej do svého projektu založeného na Maven přidáním následujících konfigurací do souboru pom.xml.

{{% blocks/products/pf/agp/code-block title="úložiště" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Závislost" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-3d</artifactId>
<version>version of aspose-3d API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky ke konverzi OBJ na JT prostřednictvím Java" %}}

{{% blocks/products/pf/agp/text %}}

 Programátoři Java mohou snadno převést soubor OBJ na JT pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor OBJ pomocí konstruktoru třídy Scene1. Volejte metodu Scene.save s formátem JT.1. Zkontrolujte výsledný soubor JT v zadané cestě
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním konverzního kódu Java se ujistěte, že splňujete následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.- Získejte nejnovější verzi Aspose.3D for Java přímo od společnosti Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód konverze OBJ na JT Java" offSpacer="" %}}

```cs
// Načtěte zdrojový soubor Wavefront OBJ
Scene scene = new Scene("sourceFile.obj");
// Převeďte scénu 3D na soubor ve formátu Siemens JT
scene.save("output.jt", FileFormat.SIEMENSJT9)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Živá ukázka konverzí OBJ na JT" sectionDescription="[Převést OBJ na JT](https://products.aspose.app/3d/conversion/obj-to-jt) právě teď na naší webové stránce s živými ukázkami. Živá ukázka má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát svůj soubor OBJ, bude okamžitě převeden na JT." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Dostanete odkaz ke stažení." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Knihovna manipulace se scénami" %}}

 Aspose.3D je CAD a herní software API k načítání, úpravě a převodu souborů 3D. API je samostatný a nevyžaduje žádný 3D modelovací nebo vykreslovací software. Lze snadno použít API pro USD, Discreet3DS, WavefrontOBJ, STL (ASCII, binární), Universal3D, FBX (ASCII, binární), Collada, glTF, PLY, GLB, DirectX a další formáty. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

Soubory OBJ jsou používány aplikací Advanced Visualizer společnosti Wavefront k definování a ukládání geometrických objektů. Zpětný a dopředný přenos geometrických dat je možný prostřednictvím OBJ souborů. Formát OBJ podporuje jak polygonální geometrii, jako jsou body, čáry, vrcholy textur, plochy, tak geometrii volného tvaru (křivky a povrchy). Tento formát nepodporuje animaci nebo informace související se světlem a polohou scén. Soubor OBJ je obvykle konečným produktem procesu modelování 3D generovaného pomocí CAD (Computer Aided Design). Výchozí pořadí pro ukládání vrcholů je proti směru hodinových ručiček, aby se zabránilo explicitní deklaraci normál ploch. Ačkoli soubory OBJ deklarují informace o měřítku v řádku komentáře, pro souřadnice OBJ nebyly deklarovány žádné jednotky.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JT" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}

JT (Jupiter Tessellation) je účinný, průmyslově zaměřený a flexibilní datový formát standardizovaný ISO 3D vyvinutý společností Siemens PLM Software. Mechanické CAD domény letectví, automobilového průmyslu a těžkého vybavení používají JT jako svůj nejvýznamnější 3D vizualizační formát.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="Můžete také převést soubor OBJ do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-gltf/" name="OBJ DO GLTF" description="Soubor formátu přenosu GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-glb/" name="OBJ DO GLB" description="Binární přenosový formát GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-pdf/" name="OBJ DO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-fbx/" name="OBJ DO FBX" description="Interchange File Autodesk FBX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-stl/" name="OBJ DO STL" description="Stereolitografický soubor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-3ds/" name="OBJ DO 3DS" description="3D Studiová scéna" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-dae/" name="OBJ DO DAE" description="Soubor pro výměnu digitálních aktiv" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-u3d/" name="OBJ DO U3D" description="Universal 3D Soubor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-ply/" name="OBJ DO PLY" description="Formát souboru polygonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-drc/" name="OBJ DO DRC" description="Google Formát souboru Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-rvm/" name="OBJ DO RVM" description="AVEVA RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-jt/" name="OBJ DO JT" description="JT Otevřít soubor CAD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-amf/" name="OBJ DO AMF" description="Soubor aditivní výroby" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-html/" name="OBJ DO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-usd/" name="OBJ DO USD" description="Univerzální formát popisu scény" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-usdz/" name="OBJ DO USDZ" description="Univerzální popis scény Formát na zip" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}