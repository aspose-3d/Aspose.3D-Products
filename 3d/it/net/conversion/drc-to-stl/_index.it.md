﻿---
title: Converti DRC in STL tramite C# 
url: /it/net/conversion/drc-to-stl/ 
description: Codice di esempio per la conversione da DRC a STL C#. Utilizza API codice di esempio per la conversione batch di file DRC in STL all'interno di VB.NET, Asp.NET o qualsiasi applicazione basata su .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti DRC in STL tramite C#" h2="Rendi DRC come STL senza alcun 3D software di modellazione e rendering." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Come convertire DRC in STL utilizzando C#" %}}

 Per convertire DRC in STL, utilizzeremo
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire DRC in STL tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET i programmatori possono caricare e convertire facilmente DRC file in STL in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file DRC tramite il costruttore della classe Scene1. Crea un'istanza di AmfSaveOptions1. Imposta STL proprietà specifiche per la conversione avanzata1. Chiama il metodo Scene.Save1. Passa il percorso di output con STL estensione file e oggetto di StlSaveOptions1. Controlla il file STL risultante nel percorso specificato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di conversione .NET, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con .NET Framework, .NET Core, Mono.- Ambiente di sviluppo come Microsoft Visual Studio.- Aspose.3D for .NET DLL a cui si fa riferimento nel tuo progetto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo codice di esempio mostra la conversione da DRC a STL C#" offSpacer="" %}}

```cs
// carica DRC in un oggetto di Scene 
var document = new Aspose.ThreeD.Scene("template.drc");
// creare un'istanza di StlSaveOptions 
var options = new Aspose.ThreeD.Formats.StlSaveOptions();
// salva DRC come STL 
document.Save("output.stl", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita per convertire DRC in STL" sectionDescription="Controlla le nostre demo dal vivo per [conversione da DRC a STL](https://products.aspose.app/3d/conversion/drc-to-stl) con i seguenti vantaggi." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare o configurare nulla." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Carica il tuo file DRC e premi il pulsante \"Converti\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai immediatamente il link per il download del file STL risultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una 3D Libreria di elaborazione file per manipolare 3D file senza alcun software di modellazione e rendering. 3D API supporta Discreet3DS, WavefrontOBJ, FBX (ASCII, binario), STL (ASCII, binario), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formati di file e altro ancora. Gli sviluppatori possono creare, leggere, convertire, modificare e controllare facilmente la sostanza di 3D formati di documenti.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
Un file con estensione .drc è un formato di file 3D compresso creato con la libreria Google Draco. Google offre Draco come libreria open source per comprimere e decomprimere 3D mesh geometriche e nuvole di punti e migliora l'archiviazione e la trasmissione di 3D grafici. Codifica i dati di input e li salva come file .drc. All'estremità ricevente, API legge i file .drc e può emetterli come file PLY o OBJ. Il file di output compresso consente agli utenti di scaricare app più velocemente e di caricare rapidamente 3D elementi grafici nei browser.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="stl" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, abbreviazione di stereolitografia, è un formato di file intercambiabile che rappresenta la geometria della superficie tridimensionale. Il formato di file trova il suo utilizzo in diversi campi come la prototipazione rapida, la stampa 3D e la produzione assistita da computer. Rappresenta una superficie come una serie di piccoli triangoli, noti come sfaccettature, in cui ogni sfaccettatura è descritta da una direzione perpendicolare e tre punti che rappresentano i vertici del triangolo. I dati risultanti vengono utilizzati dalle applicazioni per determinare la sezione trasversale della forma 3D che deve essere costruita dal fabber. Non sono disponibili informazioni nel formato di file STL per la rappresentazione di colore, trama o altri attributi comuni del modello CAD.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}