﻿---
title: Wandeln Sie DAE über Java in OBJ um 
weight: 1640
url: /de/java/conversion/dae-to-obj/ 
description: Beispiel-Umwandlungscode Java für das Format DAE in die Datei OBJ. Verwenden Sie diesen Beispielcode, um DAE in OBJ innerhalb einer beliebigen Web- oder Desktop-Java-basierten Anwendung zu konvertieren.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Wandeln Sie DAE über Java in OBJ um" h2="Konvertierung von DAE in OBJ mithilfe der Java-Bibliothek ohne 3D-Modellierungssoftware." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DAE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Konvertieren von DAE in OBJ mit Java" %}}

 Um DAE in OBJ zu rendern, verwenden wir
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API, einer funktionsreichen, leistungsstarken und benutzerfreundlichen Conversion-API for Java-Plattform. Sie können die neueste Version direkt von herunterladen
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
 und installieren Sie es in Ihrem Maven-basierten Projekt, indem Sie der pom.xml die folgenden Konfigurationen hinzufügen.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Abhängigkeit" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von DAE in OBJ über Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-Programmierer können die DAE-Datei in nur wenigen Codezeilen einfach in OBJ umwandeln.

{{% /blocks/products/pf/agp/text %}}

1. Laden Sie die DAE-Datei über den Konstruktor der Scene-Klasse1. Erstellen Sie eine Instanz von ObjSaveOptions1. Legen Sie OBJ spezifische Eigenschaften für die erweiterte Konvertierung fest1. Rufen Sie die Scene.save-Methode auf1. Übergeben Sie den Ausgabepfad mit der Dateierweiterung OBJ und dem Objekt von ObjSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Bevor Sie den Conversion-Code Java ausführen, stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Laufzeitumgebung für JSP/JSF-Anwendung und Desktop-Anwendungen.- Holen Sie sich die neueste Version von Aspose.3D for Java direkt von Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DAE bis OBJ Java Conversion-Quellcode" offSpacer="" %}}

```cs
// Laden Sie die DAE in ein Objekt der Szene 
Scene document = new Scene("template.dae");
// Erstellen Sie eine Instanz von ObjSaveOptions 
ObjSaveOptions options = new ObjSaveOptions();
// speichere DAE als OBJ 
document.save("output.obj", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DAE bis OBJ Conversion-Live-Demos" sectionDescription="[Wandeln Sie DAE in OBJ um](https://products.aspose.app/3d/conversion/dae-to-obj) jetzt, indem Sie unsere Live-Demo-Website besuchen. Die Live-Demo hat die folgenden Vorteile" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API muss nicht heruntergeladen werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es muss kein Code geschrieben werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre DAE-Datei hoch, sie wird sofort in OBJ konvertiert." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Sie erhalten den Download-Link." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Szenenbearbeitungsbibliothek" %}}

 Aspose.3D ist eine CAD und Gameware API zum Laden, Modifizieren und Konvertieren von 3D Dateien. API ist eigenständig und erfordert keine 3D-Modellierungs- oder Rendering-Software. Man kann API einfach für Discreet3DS, WavefrontOBJ, STL (ASCII, binär), Universal3D, FBX (ASCII, binär), Collada, glTF, PLY, GLB, DirectX und weitere Formate. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}

Eine DAE-Datei ist ein Digital Asset Exchange-Dateiformat, das zum Austauschen von Daten zwischen interaktiven 3D-Anwendungen verwendet wird. Dieses Dateiformat basiert auf dem XML-Schema COLLADA (COLLAborative Design Activity), einem offenen Standard-XML-Schema für den Austausch digitaler Assets zwischen Grafiksoftwareanwendungen. Es wurde von der ISO als öffentlich verfügbare Spezifikation, ISO/pAS 17506, übernommen.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

OBJ-Dateien werden von der Advanced Visualizer-Anwendung von Wavefront verwendet, um die geometrischen Objekte zu definieren und zu speichern. Die Rückwärts- und Vorwärtsübertragung geometrischer Daten wird durch OBJ-Dateien ermöglicht. Sowohl polygonale Geometrie wie Punkte, Linien, Texturscheitel, Flächen als auch Freiformgeometrie (Kurven und Flächen) werden vom OBJ-Format unterstützt. Dieses Format unterstützt keine Animationen oder Informationen in Bezug auf Licht und Position von Szenen. Eine OBJ-Datei ist normalerweise ein Endprodukt des 3D-Modellierungsprozesses, der von einem CAD (Computer Aided Design) generiert wird. Die Standardreihenfolge zum Speichern von Scheitelpunkten ist gegen den Uhrzeigersinn, wodurch eine explizite Deklaration von Flächennormalen vermieden wird. Obwohl OBJ-Dateien Maßstabsinformationen in einer Kommentarzeile deklarieren, wurden für OBJ-Koordinaten keine Einheiten deklariert.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können DAE auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-3ds/" name="DAE AN 3DS" description="3D Studio-DOS-Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-amf/" name="DAE AN AMF" description="Format der additiven Fertigung" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-ase/" name="DAE AN ASE" description="2D-Animationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-fbx/" name="DAE AN FBX" description="3D-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-gltf/" name="DAE AN GLTF" description="GL-Übertragungsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-html/" name="DAE AN HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-ply/" name="DAE AN PLY" description="Polygon-Dateiformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-rvm/" name="DAE AN RVM" description="AVEVA Anlagendesignmodell" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-stl/" name="DAE AN STL" description="Austauschbare 3D Oberflächengeometrie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-u3d/" name="DAE AN U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}