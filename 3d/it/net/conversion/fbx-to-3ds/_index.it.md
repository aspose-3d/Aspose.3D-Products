﻿---
title: Converti FBX in 3DS tramite C# 
weight: 1680
url: /it/net/conversion/fbx-to-3ds/ 
description: Codice di esempio per la conversione da FBX a 3DS C#. Utilizza API codice di esempio per la conversione batch di file FBX in 3DS all'interno di VB.NET, Asp.NET o qualsiasi applicazione basata su .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti FBX in 3DS tramite C#" h2="Rendi FBX come 3DS senza alcun 3D software di modellazione e rendering." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Come convertire FBX in 3DS utilizzando C#" %}}

 Per convertire FBX in 3DS, utilizzeremo
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API che è una piattaforma di manipolazione e conversione di documenti API ricca di funzionalità, potente e facile da usare per C#. Aprire
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 gestore pacchetti, cerca
 Aspose.3D 
 e installa. È inoltre possibile utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di gestione dei pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire FBX in 3DS tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET i programmatori possono caricare e convertire facilmente FBX file in 3DS in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file FBX tramite il costruttore della classe Scene1. Crea un'istanza di 3dsSaveOptions1. Imposta 3DS proprietà specifiche per la conversione avanzata1. Chiama il metodo Scene.Save1. Passa il percorso di output con 3DS estensione file e oggetto di 3dsSaveOptions1. Controlla il file 3DS risultante nel percorso specificato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di conversione .NET, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con .NET Framework, .NET Core, Mono.- Ambiente di sviluppo come Microsoft Visual Studio.- Aspose.3D for .NET DLL a cui si fa riferimento nel tuo progetto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo codice di esempio mostra la conversione da FBX a 3DS C#" offSpacer="" %}}

```cs
// carica FBX in un oggetto di Scene 
var document = new Aspose.ThreeD.Scene("template.fbx");
// creare un'istanza di 3dsSaveOptions 
var options = new Aspose.ThreeD.Formats.Discreet3dsSaveOptions();
// salva FBX come 3DS 
document.Save("output.3ds", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita per convertire FBX in 3DS" sectionDescription="Controlla le nostre demo dal vivo per [conversione da FBX a 3DS](https://products.aspose.app/3d/conversion/fbx-to-3ds) con i seguenti vantaggi." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare o configurare nulla." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Carica il tuo file FBX e premi il pulsante \"Converti\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai immediatamente il link per il download del file 3DS risultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una 3D Libreria di elaborazione file per manipolare 3D file senza alcun software di modellazione e rendering. 3D API supporta Discreet3DS, WavefrontOBJ, FBX (ASCII, binario), STL (ASCII, binario), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formati di file e altro ancora. Gli sviluppatori possono creare, leggere, convertire, modificare e controllare facilmente la sostanza di 3D formati di documenti.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, è un popolare formato di file 3D originariamente sviluppato da Kaydara per MotionBuilder. È stato acquisito da Autodesk Inc nel 2006 ed è ora uno dei principali 3D formati di scambio utilizzati da molti 3D strumenti. FBX è disponibile sia in formato binario che ASCII. Il formato è stato creato per fornire l'interoperabilità tra le applicazioni di creazione di contenuti digitali. Sono disponibili molti strumenti per la conversione da/in formato file FBX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3ds" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
Un file con estensione 3DS rappresenta il formato di file mesh 3D Studio (DOS) utilizzato da Autodesk 3D Studio. Autodesk 3D Studio è presente nel mercato dei formati di file 3D dagli anni '90 e ora si è evoluto in 3D Studio MAX per lavorare con 3D modellazione, animazione e rendering. Un file 3DS contiene dati per la rappresentazione 3D di scene e immagini ed è uno dei formati di file più diffusi per l'importazione e l'esportazione di dati 3D. Considera informazioni come le posizioni delle telecamere, i dati Mesh, le informazioni sull'illuminazione, le configurazioni del viewport, i dati di gruppo di smoothing, i riferimenti bitmap e gli attributi per creare vertici e poligoni per il rendering di una scena.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire FBX in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-amf/" name="FBX A AMF" description="Formato di produzione additiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-dae/" name="FBX A DAE" description="Scambio di risorse digitali" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-html/" name="FBX A HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-obj/" name="FBX A OBJ" description="3D Formato file" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-pdf/" name="FBX A PDF" description="Formato documento portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-ply/" name="FBX A PLY" description="Formato file poligono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-rvm/" name="FBX A RVM" description="Modello AVEVA Plant Design" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-stl/" name="FBX A STL" description="Geometria della superficie 3D intercambiabile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-u3d/" name="FBX A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}