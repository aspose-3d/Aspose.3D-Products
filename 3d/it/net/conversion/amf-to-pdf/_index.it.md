﻿---
title: Converti AMF in PDF tramite C# 
weight: 1400
url: /it/net/conversion/amf-to-pdf/ 
description: Codice di esempio per la conversione da AMF a PDF C#. Utilizza API codice di esempio per la conversione batch di file AMF in PDF all'interno di VB.NET, Asp.NET o qualsiasi applicazione basata su .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti AMF in PDF tramite C#" h2="Rendi AMF come PDF senza alcun 3D software di modellazione e rendering." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="AMF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Come convertire AMF in PDF utilizzando C#" %}}

 Per convertire AMF in PDF, utilizzeremo
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire AMF in PDF tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET i programmatori possono caricare e convertire facilmente AMF file in PDF in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file AMF tramite il costruttore della classe Scene1. Crea un'istanza di PdfSaveOptions1. Imposta PDF proprietà specifiche per la conversione avanzata1. Chiama il metodo Scene.Save1. Passa il percorso di output con PDF estensione file e oggetto di PdfSaveOptions1. Controlla il file PDF risultante nel percorso specificato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di conversione .NET, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con .NET Framework, .NET Core, Mono.- Ambiente di sviluppo come Microsoft Visual Studio.- Aspose.3D for .NET DLL a cui si fa riferimento nel tuo progetto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo codice di esempio mostra la conversione da AMF a PDF C#" offSpacer="" %}}

```cs
// carica AMF in un oggetto di Scene 
var document = new Aspose.ThreeD.Scene("template.amf");
// creare un'istanza di PdfSaveOptions 
var options = new Aspose.ThreeD.Formats.PdfSaveOptions();
// salva AMF come PDF 
document.Save("output.pdf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita per convertire AMF in PDF" sectionDescription="Controlla le nostre demo dal vivo per [conversione da AMF a PDF](https://products.aspose.app/3d/conversion/amf-to-pdf) con i seguenti vantaggi." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare o configurare nulla." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Carica il tuo file AMF e premi il pulsante \"Converti\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai immediatamente il link per il download del file PDF risultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una 3D Libreria di elaborazione file per manipolare 3D file senza alcun software di modellazione e rendering. 3D API supporta Discreet3DS, WavefrontOBJ, FBX (ASCII, binario), STL (ASCII, binario), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formati di file e altro ancora. Gli sviluppatori possono creare, leggere, convertire, modificare e controllare facilmente la sostanza di 3D formati di documenti.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="AMF" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}
Il formato file di produzione additiva (AMF) definisce standard aperti per la descrizione degli oggetti da utilizzare nei processi di produzione additiva come 3D la stampa. I programmi CAD utilizzano il formato di file AMF utilizzando le informazioni come la geometria, il colore e il materiale degli oggetti. AMF è diverso dal formato STL in quanto il lato non supporta colore, materiali, reticoli e costellazioni.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) è un tipo di documento creato da Adobe negli anni '90. Lo scopo di questo formato di file era quello di introdurre uno standard per la rappresentazione di documenti e altro materiale di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. PDF i file possono essere aperti in Adobe Acrobat Reader/Writer e nella maggior parte dei browser moderni come Chrome, Safari, Firefox tramite estensioni/plug-in. La maggior parte delle suite software disponibili in commercio offre anche la conversione dei propri documenti in formato file PDF senza la necessità di alcun componente software aggiuntivo. Pertanto, il formato di file PDF ha la piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, rich media, firme digitali, allegati, metadati, caratteristiche geospaziali e 3D oggetti che possono diventare parte dell'origine documento.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire AMF in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-3ds/" name="AMF A 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-dae/" name="AMF A DAE" description="Scambio di risorse digitali" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-fbx/" name="AMF A FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-html/" name="AMF A HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-obj/" name="AMF A OBJ" description="3D Formato file" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-ply/" name="AMF A PLY" description="Formato file poligono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-rvm/" name="AMF A RVM" description="Modello AVEVA Plant Design" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-stl/" name="AMF A STL" description="Geometria della superficie 3D intercambiabile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-u3d/" name="AMF A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}