﻿---
title: Převést GLTF na GLB prostřednictvím Java
weight: 530
url: /cs/java/conversion/gltf-to-glb/ 
description: Ukázkový konverzní kód Java pro formát GLTF na soubor GLB. Pomocí tohoto příkladu kódu převeďte GLTF na GLB v jakékoli webové nebo desktopové aplikaci založené na Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést GLTF na GLB prostřednictvím Java" h2="Převod GLTF na GLB pomocí knihovny Java bez jakéhokoli modelovacího softwaru 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Jak převést GLTF na GLB pomocí Java" %}}

 K vykreslení GLTF do GLB použijeme
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API, což je funkčně bohatá, výkonná a snadno použitelná konverzní API for Java platforma. Jeho nejnovější verzi si můžete stáhnout přímo z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky ke konverzi GLTF na GLB prostřednictvím Java" %}}

{{% blocks/products/pf/agp/text %}}

 Programátoři Java mohou snadno převést soubor GLTF na GLB pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor GLTF pomocí konstruktoru třídy Scene1. Volejte metodu Scene.save s formátem GLB.1. Zkontrolujte výsledný soubor GLB v zadané cestě
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním konverzního kódu Java se ujistěte, že splňujete následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.- Získejte nejnovější verzi Aspose.3D for Java přímo od společnosti Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód konverze GLTF na GLB Java" offSpacer="" %}}

```cs
// Načtěte zdrojový soubor GLTF
Scene scene = new Scene("sourceFile.gltf");
// Převeďte scénu 3D na soubor v binárním formátu GLTF
scene.save("output.glb", FileFormat.GLTF2_BINARY)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Živá ukázka konverzí GLTF na GLB" sectionDescription="[Převést GLTF na GLB](https://products.aspose.app/3d/conversion/gltf-to-glb) právě teď na naší webové stránce s živými ukázkami. Živá ukázka má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát svůj soubor GLTF, bude okamžitě převeden na GLB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Dostanete odkaz ke stažení." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Knihovna manipulace se scénami" %}}

 Aspose.3D je CAD a herní software API k načítání, úpravě a převodu souborů 3D. API je samostatný a nevyžaduje žádný 3D modelovací nebo vykreslovací software. Lze snadno použít API pro USD, Discreet3DS, WavefrontOBJ, STL (ASCII, binární), Universal3D, FBX (ASCII, binární), Collada, glTF, PLY, GLB, DirectX a další formáty. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF (GL Transmission Format) je 3D formát souboru, který ukládá 3D informací o modelu ve formátu JSON. Použití JSON minimalizuje velikost prostředků 3D i běhové zpracování potřebné k rozbalení a použití těchto prostředků. Byl přijat pro efektivní přenos a načítání 3D scén a modelů aplikacemi. glTF byl vyvinut Khronos Group 3D Formats Working Group a jeho tvůrci jej také popisují jako JPEG z 3D. Tento formát definuje rozšiřitelný, společný formát publikování pro nástroje a služby obsahu 3D, který zjednodušuje pracovní postupy tvorby a umožňuje interoperabilní použití obsahu v celém odvětví. Záměrem vytvoření formátu souboru glTF bylo definovat rozšiřitelný, společný publikační formát pro nástroje a služby obsahu 3D, který by měl zjednodušit pracovní postupy tvorby a umožnit interoperabilní používání obsahu v celém odvětví. Minimalizuje zpracování za běhu aplikacemi používajícími WebGL a další API.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}

GLB je binární reprezentace formátu souboru 3D modelů uložených ve formátu GL Transmission Format (glTF). Informace o modelech 3D, jako je hierarchie uzlů, kamery, materiály, animace a sítě v binárním formátu. Tento binární formát ukládá aktivum glTF (JSON, .bin a obrázky) do binárního objektu blob. Také se vyhnete problému zvětšení velikosti souboru, ke kterému dochází v případě glTF. Formát souboru GLB má za následek kompaktní velikosti souborů, rychlé načítání, kompletní reprezentaci scény 3D a rozšiřitelnost pro další vývoj. Formát používá model/gltf-binary jako typ MIME.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="Můžete také převést soubor GLTF do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-glb/" name="GLTF DO GLB" description="Binární přenosový formát GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-pdf/" name="GLTF DO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-fbx/" name="GLTF DO FBX" description="Interchange File Autodesk FBX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-stl/" name="GLTF DO STL" description="Stereolitografický soubor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-obj/" name="GLTF DO OBJ" description="Wavefront 3D Objektový soubor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-3ds/" name="GLTF DO 3DS" description="3D Studiová scéna" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-dae/" name="GLTF DO DAE" description="Soubor pro výměnu digitálních aktiv" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-u3d/" name="GLTF DO U3D" description="Universal 3D Soubor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-ply/" name="GLTF DO PLY" description="Formát souboru polygonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-drc/" name="GLTF DO DRC" description="Google Formát souboru Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-rvm/" name="GLTF DO RVM" description="AVEVA RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-jt/" name="GLTF DO JT" description="JT Otevřít soubor CAD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-amf/" name="GLTF DO AMF" description="Soubor aditivní výroby" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-html/" name="GLTF DO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-usd/" name="GLTF DO USD" description="Univerzální formát popisu scény" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-usdz/" name="GLTF DO USDZ" description="Univerzální popis scény Formát na zip" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}