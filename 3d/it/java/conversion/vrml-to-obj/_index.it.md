﻿---
title: Converti VRML in OBJ tramite Java 
weight: 2720
url: /it/java/conversion/vrml-to-obj/ 
description: Esempio di codice di conversione Java per il formato VRML in file OBJ. Utilizza questo codice di esempio per convertire VRML in OBJ all'interno di qualsiasi applicazione basata su Web o desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti VRML in OBJ tramite Java" h2="Conversione da VRML a OBJ utilizzando la libreria Java senza alcun software di modellazione 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="VRML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Come convertire VRML in OBJ utilizzando Java" %}}

 Per eseguire il rendering da VRML a OBJ, utilizzeremo
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire VRML in OBJ tramite Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java i programmatori possono convertire facilmente il file VRML in OBJ in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file VRML tramite il costruttore della classe Scene1. Crea un'istanza di ObjSaveOptions1. Imposta OBJ proprietà specifiche per la conversione avanzata1. Chiama il metodo Scene.save1. Passa il percorso di output con OBJ estensione file e oggetto di ObjSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di conversione Java, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.- Ottieni l'ultima versione di Aspose.3D for Java direttamente da Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="da VRML a OBJ Java Codice sorgente di conversione" offSpacer="" %}}

```cs
// carica VRML in un oggetto di Scene 
Scene document = new Scene("template.vrml");
// creare un'istanza di ObjSaveOptions 
ObjSaveOptions options = new ObjSaveOptions();
// salva VRML come OBJ 
document.save("output.obj", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Dimostrazioni live di conversione da VRML a OBJ" sectionDescription="[Converti VRML in OBJ](https://products.aspose.app/3d/conversion/vrml-to-obj) in questo momento visitando il nostro sito Web di demo dal vivo. La demo dal vivo ha i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il tuo file VRML, verrà convertito immediatamente in OBJ." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai il link per il download." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Libreria di manipolazione delle scene" %}}

 Aspose.3D è un CAD e un Gameware API per caricare, modificare e convertire 3D file. API è autonomo e non richiede alcun 3D software di modellazione o rendering. Si può facilmente usare API per Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX e altri formati. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="VRML" readMoreLink="https://docs.fileformat.com/3d/vrml/" >}}

Il Virtual Reality Modeling Language (VRML) è un formato di file per la rappresentazione di oggetti del mondo interattivi 3D sul World Wide Web (www). Trova il suo utilizzo nella creazione di rappresentazioni tridimensionali di scene complesse come illustrazioni, definizioni e presentazioni di realtà virtuale. Il formato è stato sostituito da X3D. Molte applicazioni di modellazione 3D possono salvare oggetti e scene nel formato VRML.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

OBJ i file vengono utilizzati dall'applicazione Advanced Visualizer di Wavefront per definire e archiviare gli oggetti geometrici. La trasmissione avanti e indietro di dati geometrici è resa possibile tramite file OBJ. Sia la geometria poligonale come punti, linee, vertici di texture, facce e geometria a forma libera (curve e superfici) sono supportate dal formato OBJ. Questo formato non supporta l'animazione o le informazioni relative alla luce e alla posizione delle scene. Un file OBJ è solitamente un prodotto finale del processo di modellazione 3D generato da un CAD (Computer Aided Design). L'ordine predefinito per memorizzare i vertici è in senso antiorario, evitando la dichiarazione esplicita delle normali delle facce. Sebbene i file OBJ dichiarino informazioni sulla scala in una riga di commento, non sono state dichiarate unità per le coordinate OBJ.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire VRML in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-3ds/" name="VRML A 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-amf/" name="VRML A AMF" description="Formato di produzione additiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-ase/" name="VRML A ASE" description="File di animazione 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-dae/" name="VRML A DAE" description="Scambio di risorse digitali" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-fbx/" name="VRML A FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-gltf/" name="VRML A GLTF" description="Formato di trasmissione GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-html/" name="VRML A HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-ply/" name="VRML A PLY" description="Formato file poligono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-rvm/" name="VRML A RVM" description="Modello AVEVA Plant Design" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-stl/" name="VRML A STL" description="Geometria della superficie 3D intercambiabile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-u3d/" name="VRML A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}