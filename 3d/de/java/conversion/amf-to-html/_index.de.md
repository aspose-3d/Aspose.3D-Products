﻿---
title: Wandeln Sie AMF über Java in HTML um 
weight: 3340
url: /de/java/conversion/amf-to-html/ 
description: Beispiel-Umwandlungscode Java für das Format AMF in die Datei HTML. Verwenden Sie diesen Beispielcode, um AMF in HTML innerhalb einer beliebigen Web- oder Desktop-Java-basierten Anwendung zu konvertieren.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Wandeln Sie AMF über Java in HTML um" h2="Konvertierung von AMF in HTML mithilfe der Java-Bibliothek ohne 3D-Modellierungssoftware." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="AMF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Konvertieren von AMF in HTML mit Java" %}}

 Um AMF in HTML zu rendern, verwenden wir
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API, einer funktionsreichen, leistungsstarken und benutzerfreundlichen Conversion-API for Java-Plattform. Sie können die neueste Version direkt von herunterladen
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von AMF in HTML über Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-Programmierer können die AMF-Datei in nur wenigen Codezeilen einfach in HTML umwandeln.

{{% /blocks/products/pf/agp/text %}}

1. Laden Sie die AMF-Datei über den Konstruktor der Scene-Klasse1. Erstellen Sie eine Instanz von HtmlSaveOptions1. Legen Sie HTML spezifische Eigenschaften für die erweiterte Konvertierung fest1. Rufen Sie die Scene.save-Methode auf1. Übergeben Sie den Ausgabepfad mit der Dateierweiterung HTML und dem Objekt von HtmlSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Bevor Sie den Conversion-Code Java ausführen, stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Laufzeitumgebung für JSP/JSF-Anwendung und Desktop-Anwendungen.- Holen Sie sich die neueste Version von Aspose.3D for Java direkt von Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="AMF bis HTML Java Conversion-Quellcode" offSpacer="" %}}

```cs
// Laden Sie die AMF in ein Objekt der Szene 
Scene document = new Scene("template.amf");
// Erstellen Sie eine Instanz von HtmlSaveOptions 
Html5SaveOptions options = new Html5SaveOptions();
// speichere AMF als HTML 
document.save("output.html", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="AMF bis HTML Conversion-Live-Demos" sectionDescription="[Wandeln Sie AMF in HTML um](https://products.aspose.app/3d/conversion/amf-to-html) jetzt, indem Sie unsere Live-Demo-Website besuchen. Die Live-Demo hat die folgenden Vorteile" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API muss nicht heruntergeladen werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es muss kein Code geschrieben werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre AMF-Datei hoch, sie wird sofort in HTML konvertiert." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Sie erhalten den Download-Link." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Szenenbearbeitungsbibliothek" %}}

 Aspose.3D ist eine CAD und Gameware API zum Laden, Modifizieren und Konvertieren von 3D Dateien. API ist eigenständig und erfordert keine 3D-Modellierungs- oder Rendering-Software. Man kann API einfach für Discreet3DS, WavefrontOBJ, STL (ASCII, binär), Universal3D, FBX (ASCII, binär), Collada, glTF, PLY, GLB, DirectX und weitere Formate. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="AMF" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}

Das Dateiformat für additive Fertigung (AMF) definiert offene Standards für die Beschreibung von Objekten, um von additiven Fertigungsverfahren wie 3D Drucken verwendet zu werden. CAD-Programme verwenden das AMF-Dateiformat, indem sie sich Informationen wie Geometrie, Farbe und Material der Objekte zunutze machen. AMF unterscheidet sich vom STL-Format, da das laterale Format keine Farben, Materialien, Gitter und Konstellationen unterstützt.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language) ist die Erweiterung für Webseiten, die für die Anzeige in Browsern erstellt wurden. Bekannt als Sprache des Webs, hat sich HTML mit Anforderungen an neue Informationsanforderungen entwickelt, die als Teil von Webseiten angezeigt werden müssen. Die neueste Variante ist als HTML 5 bekannt und bietet viel Flexibilität für die Arbeit mit der Sprache. HTML Seiten werden entweder vom Server empfangen, auf dem diese gehostet werden, oder können auch vom lokalen System geladen werden. Jede HTML-Seite besteht aus HTML-Elementen wie Formularen, Text, Bildern, Animationen, Links usw. Diese Elemente werden durch Tags wie img, a, p und mehrere andere dargestellt, wobei jedes Tag einen Anfang und ein Ende hat . Es kann auch Anwendungen einbetten, die in Skriptsprachen wie JavaScript und Style Sheets (CSS) geschrieben sind, um das Gesamtlayout darzustellen.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können AMF auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-3ds/" name="AMF AN 3DS" description="3D Studio-DOS-Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-dae/" name="AMF AN DAE" description="Austausch digitaler Assets" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-fbx/" name="AMF AN FBX" description="3D-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-gltf/" name="AMF AN GLTF" description="GL-Übertragungsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-obj/" name="AMF AN OBJ" description="3D Dateiformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-ply/" name="AMF AN PLY" description="Polygon-Dateiformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-rvm/" name="AMF AN RVM" description="AVEVA Anlagendesignmodell" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-stl/" name="AMF AN STL" description="Austauschbare 3D Oberflächengeometrie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-u3d/" name="AMF AN U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}