﻿---
title: Wandeln Sie DRC über Java in U3D um 
url: /de/java/conversion/drc-to-u3d/ 
description: Beispiel-Umwandlungscode Java für das Format DRC in die Datei U3D. Verwenden Sie diesen Beispielcode, um DRC in U3D innerhalb einer beliebigen Web- oder Desktop-Java-basierten Anwendung zu konvertieren.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Wandeln Sie DRC über Java in U3D um" h2="Konvertierung von DRC in U3D mithilfe der Java-Bibliothek ohne 3D-Modellierungssoftware." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Konvertieren von DRC in U3D mit Java" %}}

 Um DRC in U3D zu rendern, verwenden wir
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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von DRC in U3D über Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-Programmierer können die DRC-Datei in nur wenigen Codezeilen einfach in U3D umwandeln.

{{% /blocks/products/pf/agp/text %}}

1. Laden Sie die DRC-Datei über den Konstruktor der Scene-Klasse1. Erstellen Sie eine Instanz von U3dSaveOptions1. Legen Sie U3D spezifische Eigenschaften für die erweiterte Konvertierung fest1. Rufen Sie die Scene.save-Methode auf1. Übergeben Sie den Ausgabepfad mit der Dateierweiterung U3D und dem Objekt von U3dSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Bevor Sie den Conversion-Code Java ausführen, stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Laufzeitumgebung für JSP/JSF-Anwendung und Desktop-Anwendungen.- Holen Sie sich die neueste Version von Aspose.3D for Java direkt von Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DRC bis U3D Java Conversion-Quellcode" offSpacer="" %}}

```cs
// Laden Sie die DRC in ein Objekt der Szene 
Scene document = new Scene("template.drc");
// Erstellen Sie eine Instanz von U3dSaveOptions 
AmfSaveOptions options = new U3dSaveOptions();
// speichere DRC als U3D 
document.save("output.u3d", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DRC bis U3D Conversion-Live-Demos" sectionDescription="[Wandeln Sie DRC in U3D um](https://products.aspose.app/3d/conversion/drc-to-u3d) jetzt, indem Sie unsere Live-Demo-Website besuchen. Die Live-Demo hat die folgenden Vorteile" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API muss nicht heruntergeladen werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es muss kein Code geschrieben werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre DRC-Datei hoch, sie wird sofort in U3D konvertiert." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Sie erhalten den Download-Link." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Szenenbearbeitungsbibliothek" %}}

 Aspose.3D ist eine CAD und Gameware API zum Laden, Modifizieren und Konvertieren von 3D Dateien. API ist eigenständig und erfordert keine 3D-Modellierungs- oder Rendering-Software. Man kann API einfach für Discreet3DS, WavefrontOBJ, STL (ASCII, binär), Universal3D, FBX (ASCII, binär), Collada, glTF, PLY, GLB, DirectX und weitere Formate. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}

Eine Datei mit der Erweiterung .drc ist ein komprimiertes 3D-Dateiformat, das mit der Bibliothek Google Draco erstellt wurde. Google bietet Draco als Open-Source-Bibliothek zum Komprimieren und Dekomprimieren von 3D geometrischen Netzen und Punktwolken an und verbessert die Speicherung und Übertragung von 3D-Grafiken. Es codiert die Eingabedaten und speichert sie als .drc-Datei. Auf der Empfängerseite liest API .drc-Dateien und kann diese als PLY- oder OBJ-Dateien ausgeben. Die komprimierte Ausgabedatei ermöglicht Benutzern das schnellere Herunterladen von Apps und das schnelle Laden von 3D-Grafiken in Browsern.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}

U3D (Universal 3D) ist ein komprimiertes Dateiformat und eine Datenstruktur für 3D Computergrafiken. Es enthält 3D Modellinformationen wie Dreiecksnetze, Beleuchtung, Schattierung, Bewegungsdaten, Linien und Punkte mit Farbe und Struktur. Das Format wurde im August 2005 als ECMA-363-Standard akzeptiert. 3D PDF Dokumente unterstützen das Einbetten von U3D Objekten und können in Adobe Reader (Version 7 und höher) angezeigt werden. U3D-Format wurde mit dem Ziel entwickelt, einen universellen Standard für dreidimensionale Datenspeicherung und -austausch zu etablieren. Das Format findet jedoch seine Hauptanwendung in der Codierung für 3D PDF und nicht als Austauschformat. Acrobat 3D konvertiert einen unterstützten 3D-Dateityp bei der Konvertierung in PDF entweder in U3D oder PRC.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}