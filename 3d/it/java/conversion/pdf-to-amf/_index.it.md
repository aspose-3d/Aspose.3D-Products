﻿---
title: Converti PDF in AMF tramite Java 
url: /it/java/conversion/pdf-to-amf/ 
description: Esempio di codice di conversione Java per il formato PDF in file AMF. Utilizza questo codice di esempio per convertire PDF in AMF all'interno di qualsiasi applicazione basata su Web o desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti PDF in AMF tramite Java" h2="Conversione da PDF a AMF utilizzando la libreria Java senza alcun software di modellazione 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="AMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Come convertire PDF in AMF utilizzando Java" %}}

 Per eseguire il rendering da PDF a AMF, utilizzeremo
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API che è una piattaforma di conversione API for Java ricca di funzionalità, potente e facile da usare. Puoi scaricare la sua ultima versione direttamente da
 [Esperto di](https://repository.aspose.com/3d/) 
 e installalo all'interno del tuo progetto basato su Maven aggiungendo le seguenti configurazioni a pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dipendenza" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire PDF in AMF tramite Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java i programmatori possono convertire facilmente il file PDF in AMF in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file PDF tramite il costruttore della classe Scene1. Crea un'istanza di AmfSaveOptions1. Imposta AMF proprietà specifiche per la conversione avanzata1. Chiama il metodo Scene.save1. Passa il percorso di output con AMF estensione file e oggetto di AmfSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di conversione Java, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.- Ottieni l'ultima versione di Aspose.3D for Java direttamente da Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="da PDF a AMF Java Codice sorgente di conversione" offSpacer="" %}}

```cs
// carica PDF in un oggetto di Scene 
Scene document = new Scene("template.pdf");
// creare un'istanza di AmfSaveOptions 
AmfSaveOptions options = new AmfSaveOptions();
// salva PDF come AMF 
document.save("output.amf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Dimostrazioni live di conversione da PDF a AMF" sectionDescription="[Converti PDF in AMF](https://products.aspose.app/3d/conversion/pdf-to-amf) in questo momento visitando il nostro sito Web di demo dal vivo. La demo dal vivo ha i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il tuo file PDF, verrà convertito immediatamente in AMF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai il link per il download." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Libreria di manipolazione delle scene" %}}

 Aspose.3D è un CAD e un Gameware API per caricare, modificare e convertire 3D file. API è autonomo e non richiede alcun 3D software di modellazione o rendering. Si può facilmente usare API per Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX e altri formati. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

Portable Document Format (PDF) è un tipo di documento creato da Adobe negli anni '90. Lo scopo di questo formato di file era quello di introdurre uno standard per la rappresentazione di documenti e altro materiale di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. PDF i file possono essere aperti in Adobe Acrobat Reader/Writer e nella maggior parte dei browser moderni come Chrome, Safari, Firefox tramite estensioni/plug-in. La maggior parte delle suite software disponibili in commercio offre anche la conversione dei propri documenti in formato file PDF senza la necessità di alcun componente software aggiuntivo. Pertanto, il formato di file PDF ha la piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, rich media, firme digitali, allegati, metadati, caratteristiche geospaziali e 3D oggetti che possono diventare parte dell'origine documento.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="AMF" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}

Il formato file di produzione additiva (AMF) definisce standard aperti per la descrizione degli oggetti da utilizzare nei processi di produzione additiva come 3D la stampa. I programmi CAD utilizzano il formato di file AMF utilizzando le informazioni come la geometria, il colore e il materiale degli oggetti. AMF è diverso dal formato STL in quanto il lato non supporta colore, materiali, reticoli e costellazioni.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}