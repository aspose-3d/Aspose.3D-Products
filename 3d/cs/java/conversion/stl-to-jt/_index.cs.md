﻿---
title: Převést STL na JT prostřednictvím Java
weight: 530
url: /cs/java/conversion/stl-to-jt/ 
description: Ukázkový konverzní kód Java pro formát STL na soubor JT. Pomocí tohoto příkladu kódu převeďte STL na JT v jakékoli webové nebo desktopové aplikaci založené na Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést STL na JT prostřednictvím Java" h2="Převod STL na JT pomocí knihovny Java bez jakéhokoli modelovacího softwaru 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="JT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="STL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Jak převést STL na JT pomocí Java" %}}

 K vykreslení STL do JT použijeme
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky ke konverzi STL na JT prostřednictvím Java" %}}

{{% blocks/products/pf/agp/text %}}

 Programátoři Java mohou snadno převést soubor STL na JT pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor STL pomocí konstruktoru třídy Scene1. Volejte metodu Scene.save s formátem JT.1. Zkontrolujte výsledný soubor JT v zadané cestě
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním konverzního kódu Java se ujistěte, že splňujete následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.- Získejte nejnovější verzi Aspose.3D for Java přímo od společnosti Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód konverze STL na JT Java" offSpacer="" %}}

```cs
// Načtěte zdrojový soubor STL
Scene scene = new Scene("sourceFile.stl");
// Převeďte scénu 3D na soubor ve formátu Siemens JT
scene.save("output.jt", FileFormat.SIEMENSJT9)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Živá ukázka konverzí STL na JT" sectionDescription="[Převést STL na JT](https://products.aspose.app/3d/conversion/stl-to-jt) právě teď na naší webové stránce s živými ukázkami. Živá ukázka má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát svůj soubor STL, bude okamžitě převeden na JT." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Dostanete odkaz ke stažení." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Knihovna manipulace se scénami" %}}

 Aspose.3D je CAD a herní software API k načítání, úpravě a převodu souborů 3D. API je samostatný a nevyžaduje žádný 3D modelovací nebo vykreslovací software. Lze snadno použít API pro USD, Discreet3DS, WavefrontOBJ, STL (ASCII, binární), Universal3D, FBX (ASCII, binární), Collada, glTF, PLY, GLB, DirectX a další formáty. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/3d/stl/" >}}

STL, zkratka pro stereolitrografii, je zaměnitelný formát souboru, který představuje 3-rozměrnou geometrii povrchu. Souborový formát nachází uplatnění v několika oblastech, jako je rychlé prototypování, 3D tisk a počítačově podporovaná výroba. Představuje povrch jako řadu malých trojúhelníků, známých jako fasety, kde každá faseta je popsána kolmým směrem a třemi body představujícími vrcholy trojúhelníku. Výsledná data používají aplikace k určení průřezu tvaru 3D, který má být vyroben výrobcem. Ve formátu souboru STL nejsou k dispozici žádné informace pro znázornění barvy, textury nebo jiných běžných atributů modelu CAD.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JT" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}

JT (Jupiter Tessellation) je účinný, průmyslově zaměřený a flexibilní datový formát standardizovaný ISO 3D vyvinutý společností Siemens PLM Software. Mechanické CAD domény letectví, automobilového průmyslu a těžkého vybavení používají JT jako svůj nejvýznamnější 3D vizualizační formát.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="Můžete také převést soubor STL do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-gltf/" name="STL DO GLTF" description="Soubor formátu přenosu GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-glb/" name="STL DO GLB" description="Binární přenosový formát GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-pdf/" name="STL DO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-fbx/" name="STL DO FBX" description="Interchange File Autodesk FBX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-obj/" name="STL DO OBJ" description="Wavefront 3D Objektový soubor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-3ds/" name="STL DO 3DS" description="3D Studiová scéna" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-dae/" name="STL DO DAE" description="Soubor pro výměnu digitálních aktiv" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-u3d/" name="STL DO U3D" description="Universal 3D Soubor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-ply/" name="STL DO PLY" description="Formát souboru polygonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-drc/" name="STL DO DRC" description="Google Formát souboru Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-rvm/" name="STL DO RVM" description="AVEVA RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-jt/" name="STL DO JT" description="JT Otevřít soubor CAD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-amf/" name="STL DO AMF" description="Soubor aditivní výroby" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-html/" name="STL DO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-usd/" name="STL DO USD" description="Univerzální formát popisu scény" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-usdz/" name="STL DO USDZ" description="Univerzální popis scény Formát na zip" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}