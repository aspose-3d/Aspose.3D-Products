﻿---
title: Konvertera OBJ till FBX via Java 
weight: 2650
url: /sv/java/conversion/obj-to-fbx/ 
description: Exempel på Java-konverteringskod för OBJ-format till FBX-fil. Använd den här exempelkoden för att konvertera OBJ till FBX i valfri webb- eller datorbaserad applikation Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera OBJ till FBX via Java" h2="OBJ till FBX omvandling med Java-biblioteket utan någon 3D-modelleringsprogramvara." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du OBJ till FBX med Java" %}}

 För att rendera OBJ till FBX använder vi
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API som är en funktionsrik, kraftfull och lättanvänd konverteringsplattform API for Java. Du kan ladda ner den senaste versionen direkt från
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
 och installera det i ditt Maven-baserade projekt genom att lägga till följande konfigurationer till pom.xml.

{{% blocks/products/pf/agp/code-block title="Förvar" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Beroende" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera OBJ till FBX via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-programmerare kan enkelt konvertera OBJ-filen till FBX på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda OBJ-filen via konstruktorn för Scene-klassen1. Skapa en instans av FbxSaveOptions1. Ställ in FBX specifika egenskaper för avancerad konvertering1. Ring Scene.save-metoden1. Skicka utdatasökvägen med FBX filtillägg och objekt för FbxSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör omvandlingskoden Java, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Application och Desktop Applications.- Hämta den senaste versionen av Aspose.3D for Java direkt från Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OBJ till FBX Java Omvandlingskällkod" offSpacer="" %}}

```cs
// ladda OBJ i ett objekt av Scene 
Scene document = new Scene("template.obj");
// skapa en instans av FbxSaveOptions 
FbxSaveOptions options = new FbxSaveOptions();
// spara OBJ som en FBX 
document.save("output.fbx", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="OBJ till FBX Live Demos för konvertering" sectionDescription="[Konvertera OBJ till FBX](https://products.aspose.app/3d/conversion/obj-to-fbx) just nu genom att besöka vår Live Demos-webbplats. Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ned Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din OBJ-fil, den konverteras omedelbart till FBX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Scenmanipulationsbibliotek" %}}

 Aspose.3D är ett CAD och spelprogram API för att ladda, ändra och konvertera 3D filer. API är en fristående och kräver ingen 3D-modellerings- eller renderingsprogramvara. Man kan enkelt använda API för Discreet3DS, WavefrontOBJ, STL (ASCII, binär), Universal3D, FBX (ASCII, binär), Collada, glTF, PLY, GLB, DirectX och fler format. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

OBJ filer används av Wavefronts Advanced Visualizer-applikation för att definiera och lagra de geometriska objekten. Bakåt- och framåtöverföring av geometriska data är möjlig genom OBJ filer. Både polygonal geometri som punkter, linjer, texturhörn, ytor och friformsgeometri (kurvor och ytor) stöds av formatet OBJ. Det här formatet stöder inte animering eller information relaterad till ljus och sceners position. En OBJ-fil är vanligtvis en slutprodukt av 3D-modelleringsprocessen som genereras av en CAD (Computer Aided Design). Standardordningen för att lagra hörn är moturs för att undvika explicit deklaration av ansiktsnormaler. Även om OBJ filer deklarerar skalinformation i en kommentarsrad har inga enheter deklarerats för OBJ koordinater.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}

FBX, FilmBox, är ett populärt 3D-filformat som ursprungligen utvecklades av Kaydara för MotionBuilder. Det förvärvades av Autodesk Inc 2006 och är nu ett av de viktigaste 3D-utbytesformaten som används av många 3D-verktyg. FBX är tillgänglig i både binärt och ASCII-filformat. Formatet skapades för att tillhandahålla interoperabilitet mellan applikationer för skapande av digitalt innehåll. Det finns många tillgängliga verktyg för konvertering från/till filformatet FBX.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera OBJ till många andra filformat, inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-3ds/" name="OBJ TILL 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-amf/" name="OBJ TILL AMF" description="Additiv tillverkningsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-ase/" name="OBJ TILL ASE" description="2D-animationsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-dae/" name="OBJ TILL DAE" description="Digital Asset Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-gltf/" name="OBJ TILL GLTF" description="GL-överföringsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-html/" name="OBJ TILL HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-obj/" name="OBJ TILL OBJ" description="3D Filformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-ply/" name="OBJ TILL PLY" description="Polygon filformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-rvm/" name="OBJ TILL RVM" description="AVEVA Plant Design Model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-stl/" name="OBJ TILL STL" description="Utbytbar 3D ytgeometri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-u3d/" name="OBJ TILL U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}