﻿---
title: Visa DRC filformat via .NET 
url: /sv/net/viewer/drc/ 
description: C# källkod för att ladda, rendera och visa DRC dokument på .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="DRC Filvisare for .NET" h2="Rendera DRC filer utan någon 3D-modellerings- och renderingsprogramvara." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Så här visar du DRC-fil med C#" %}}

För att visa filen DRC använder vi <a href="/3d/net/">Aspose.3D for .NET</a> API som är en funktionsrik, kraftfull och lättanvänd API för C#-plattform som kan användas med alla tittare. Öppen <a href="https://www.nuget.org/packages/aspose.3d">NuGet</a> pakethanterare, sök efter <b>Aspose.3D</b> och installera. Du kan också använda följande kommando från Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakethanterarens konsolkommando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att visa DRC via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D gör det enkelt för utvecklarna att visa DRC-filen med bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda DRC-filen via konstruktorn för Scene-klassen1. Skapa en instans av Html5SaveOptions1. Ställ in egenskaper för avancerad formatering1. Anropa metoden Scene.Save med objektet Html5SaveOptions1. Kontrollera den resulterande filen HTML i standardwebbläsaren

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET stöds på alla större operativsystem. Se bara till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar- Utvecklingsmiljö som Microsoft Visual Studio- Aspose.3D for .NET refereras till i ditt projekt
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod för att visa DRC" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// ladda DRC scen via en instans av Scene
var scene = new ThreeD.Scene("template.drc");
// skapa ett objekt av Html5SaveOptions och ange egenskaper för formatering
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // stäng av nätet
    ShowGrid = false,
    // stänga av användargränssnittet
    ShowUI = false
};

// spara 3D scen som HTML5
scene.Save(output, options);
// ladda resulterande HTML i standardwebbläsaren
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.3D är ett CAD och spelprogram API för att ladda, ändra och konvertera 3D filer. API är en fristående och kräver ingen 3D-modellerings- eller renderingsprogramvara. Man kan enkelt använda API för Discreet3DS, WavefrontOBJ, STL (ASCII, binär), Universal3D, FBX (ASCII, binär), Collada, glTF, PLY, GLB, DirectX och fler format.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app att visa DRC" sectionDescription="Kolla våra livedemos för att [Visa DRC](https://products.aspose.app/3d/viewer/drc) med följande förmåner." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner eller ställa in någonting" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Inget behov av att skriva eller kompilera kod" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp filen DRC och tryck på knappen \"Visa\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ladda ned filen DRC från länken om det behövs" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="/{{drc_url}}" >}}
{{drc}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra visningsformat som stöds" subTitle="Med hjälp av C# kan man också se många andra filformat inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Studio DOS Mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D Tillverkningsformat" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Additiv tillverkningsformat" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="2D-animationsfil" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Digital Asset Exchange" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="Drawing Interchange Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D Fil binär representation" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="GL-överföringsformat" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="Jupiter Tessellation-fil" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D Filformat" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Polygon filformat" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="AVEVA Plant Design Model" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="Utbytbar 3D ytgeometri" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Virtual Reality Modeling Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="X" description="Direkt modellbild" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="Arkiveringsformat" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}