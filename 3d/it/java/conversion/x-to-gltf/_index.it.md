﻿---
title: Converti X in GLTF tramite Java 
weight: 3220
url: /it/java/conversion/x-to-gltf/ 
description: Esempio di codice di conversione Java per il formato X in file GLTF. Usa questo codice di esempio per convertire X in GLTF all'interno di qualsiasi applicazione basata su Web o Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti X in GLTF tramite Java" h2="Conversione da X a GLTF utilizzando la libreria Java senza alcun software di modellazione 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="X" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Come convertire X in GLTF utilizzando Java" %}}

 Per rendere X su GLTF, useremo
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API che è una piattaforma di conversione API for Java ricca di funzionalità, potente e facile da usare. Puoi scaricare la sua ultima versione direttamente da
 [Esperto di](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire X in GLTF tramite Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java i programmatori possono convertire facilmente il file X in GLTF in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file X tramite il costruttore della classe Scene1. Crea un'istanza di GltfSaveOptions1. Imposta GLTF proprietà specifiche per la conversione avanzata1. Chiama il metodo Scene.save1. Passa il percorso di output con GLTF estensione file e oggetto di GltfSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di conversione Java, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.- Ottieni l'ultima versione di Aspose.3D for Java direttamente da Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice sorgente di conversione da X a GLTF Java" offSpacer="" %}}

```cs
// carica la X in un oggetto di Scene 
Scene document = new Scene("template.x");
// creare un'istanza di GltfSaveOptions 
GltfSaveOptions options = new GltfSaveOptions();
// salva X come GLTF 
document.save("output.gltf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Demo live di conversione da X a GLTF" sectionDescription="[Converti X in GLTF](https://products.aspose.app/3d/conversion/x-to-gltf) in questo momento visitando il nostro sito Web di demo dal vivo. La demo dal vivo ha i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il tuo file X, verrà convertito immediatamente in GLTF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai il link per il download." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Libreria di manipolazione delle scene" %}}

 Aspose.3D è un CAD e un Gameware API per caricare, modificare e convertire 3D file. API è autonomo e non richiede alcun 3D software di modellazione o rendering. Si può facilmente usare API per Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX e altri formati. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="X" readMoreLink="https://docs.fileformat.com/3d/x/" >}}

X è un file immagine del modello DirectX utilizzato dalla tecnologia DirectX che è per 3D il rendering grafico nei giochi. Il formato del file specifica 3D strutture di oggetti per mesh, trame, animazioni e oggetti.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF (GL Transmission Format) è un formato di file 3D che memorizza 3D informazioni sul modello in formato JSON. L'uso di JSON riduce al minimo sia la dimensione di 3D asset che l'elaborazione di runtime necessaria per decomprimere e utilizzare tali asset. È stato adottato per la trasmissione e il caricamento efficienti di 3D scene e modelli dalle applicazioni. glTF è stato sviluppato dal Khronos Group 3D Formats Working Group ed è anche descritto come JPEG di 3D dai suoi creatori. Il formato definisce un formato di pubblicazione estensibile e comune per 3D strumenti e servizi per i contenuti che semplifica i flussi di lavoro di creazione e consente l'uso interoperabile dei contenuti in tutto il settore. L'intenzione alla base della creazione del formato di file glTF era definire un formato di pubblicazione estensibile e comune per 3D strumenti e servizi per i contenuti che dovrebbe semplificare i flussi di lavoro di creazione e consentire l'uso interoperabile dei contenuti in tutto il settore. Riduce al minimo l'elaborazione del runtime da parte delle applicazioni che utilizzano WebGL e altre API.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire X in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-3ds/" name="X A 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-amf/" name="X A AMF" description="Formato di produzione additiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-ase/" name="X A ASE" description="File di animazione 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-dae/" name="X A DAE" description="Scambio di risorse digitali" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-fbx/" name="X A FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-html/" name="X A HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-obj/" name="X A OBJ" description="3D Formato file" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-ply/" name="X A PLY" description="Formato file poligono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-rvm/" name="X A RVM" description="Modello AVEVA Plant Design" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-stl/" name="X A STL" description="Geometria della superficie 3D intercambiabile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-u3d/" name="X A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}