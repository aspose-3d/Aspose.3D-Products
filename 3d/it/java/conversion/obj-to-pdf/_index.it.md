﻿---
title: Converti OBJ in PDF tramite Java 
url: /it/java/conversion/obj-to-pdf/ 
description: Esempio di codice di conversione Java per il formato OBJ in file PDF. Utilizza questo codice di esempio per convertire OBJ in PDF all'interno di qualsiasi applicazione basata su Web o desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti OBJ in PDF tramite Java" h2="Conversione da OBJ a PDF utilizzando la libreria Java senza alcun software di modellazione 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Come convertire OBJ in PDF utilizzando Java" %}}

 Per eseguire il rendering da OBJ a PDF, utilizzeremo
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire OBJ in PDF tramite Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java i programmatori possono convertire facilmente il file OBJ in PDF in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file OBJ tramite il costruttore della classe Scene1. Crea un'istanza di PdfSaveOptions1. Imposta PDF proprietà specifiche per la conversione avanzata1. Chiama il metodo Scene.save1. Passa il percorso di output con PDF estensione file e oggetto di PdfSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di conversione Java, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.- Ottieni l'ultima versione di Aspose.3D for Java direttamente da Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="da OBJ a PDF Java Codice sorgente di conversione" offSpacer="" %}}

```cs
// carica OBJ in un oggetto di Scene 
Scene document = new Scene("template.obj");
// creare un'istanza di PdfSaveOptions 
AmfSaveOptions options = new PdfSaveOptions();
// salva OBJ come PDF 
document.save("output.pdf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Dimostrazioni live di conversione da OBJ a PDF" sectionDescription="[Converti OBJ in PDF](https://products.aspose.app/3d/conversion/obj-to-pdf) in questo momento visitando il nostro sito Web di demo dal vivo. La demo dal vivo ha i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il tuo file OBJ, verrà convertito immediatamente in PDF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai il link per il download." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Libreria di manipolazione delle scene" %}}

 Aspose.3D è un CAD e un Gameware API per caricare, modificare e convertire 3D file. API è autonomo e non richiede alcun 3D software di modellazione o rendering. Si può facilmente usare API per Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX e altri formati. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

OBJ i file vengono utilizzati dall'applicazione Advanced Visualizer di Wavefront per definire e archiviare gli oggetti geometrici. La trasmissione avanti e indietro di dati geometrici è resa possibile tramite file OBJ. Sia la geometria poligonale come punti, linee, vertici di texture, facce e geometria a forma libera (curve e superfici) sono supportate dal formato OBJ. Questo formato non supporta l'animazione o le informazioni relative alla luce e alla posizione delle scene. Un file OBJ è solitamente un prodotto finale del processo di modellazione 3D generato da un CAD (Computer Aided Design). L'ordine predefinito per memorizzare i vertici è in senso antiorario, evitando la dichiarazione esplicita delle normali delle facce. Sebbene i file OBJ dichiarino informazioni sulla scala in una riga di commento, non sono state dichiarate unità per le coordinate OBJ.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

Portable Document Format (PDF) è un tipo di documento creato da Adobe negli anni '90. Lo scopo di questo formato di file era quello di introdurre uno standard per la rappresentazione di documenti e altro materiale di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. PDF i file possono essere aperti in Adobe Acrobat Reader/Writer e nella maggior parte dei browser moderni come Chrome, Safari, Firefox tramite estensioni/plug-in. La maggior parte delle suite software disponibili in commercio offre anche la conversione dei propri documenti in formato file PDF senza la necessità di alcun componente software aggiuntivo. Pertanto, il formato di file PDF ha la piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, rich media, firme digitali, allegati, metadati, caratteristiche geospaziali e 3D oggetti che possono diventare parte dell'origine documento.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire OBJ in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-3ds/" name="OBJ A 3DS" description="3D Studio DOS Mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-amf/" name="OBJ A AMF" description="Formato di produzione additiva" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-ase/" name="OBJ A ASE" description="File di animazione 2D" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-dae/" name="OBJ A DAE" description="Scambio di risorse digitali" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-fbx/" name="OBJ A FBX" description="3D Formato" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-gltf/" name="OBJ A GLTF" description="Formato di trasmissione GL" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-html/" name="OBJ A HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-obj/" name="OBJ A OBJ" description="3D Formato file" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-ply/" name="OBJ A PLY" description="Formato file poligono" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-rvm/" name="OBJ A RVM" description="Modello AVEVA Plant Design" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-stl/" name="OBJ A STL" description="Geometria della superficie 3D intercambiabile" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-u3d/" name="OBJ A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}