﻿---
title: Μετατροπή 3DS σε USDZ μέσω Java
weight: 530
url: /el/java/conversion/3ds-to-usdz/ 
description: Δείγμα κώδικα μετατροπής Java για μορφή 3DS σε αρχείο USDZ. Χρησιμοποιήστε αυτό το παράδειγμα κώδικα για να μετατρέψετε το 3DS σε USDZ σε οποιαδήποτε εφαρμογή που βασίζεται στον Ιστό ή στην επιφάνεια εργασίας Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή 3DS σε USDZ μέσω Java" h2="Μετατροπή 3DS σε USDZ με χρήση βιβλιοθήκης Java χωρίς λογισμικό μοντελοποίησης 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="USDZ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το 3DS σε USDZ χρησιμοποιώντας το Java" %}}

 Για να αποδώσουμε το 3DS στο USDZ, θα χρησιμοποιήσουμε
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API που είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα μετατροπής API for Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
 και εγκαταστήστε το στο έργο σας που βασίζεται στο Maven προσθέτοντας τις ακόλουθες διαμορφώσεις στο pom.xml.

{{% blocks/products/pf/agp/code-block title="Αποθήκη" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Εξάρτηση" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή 3DS σε USDZ μέσω Java" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές Java μπορούν εύκολα να μετατρέψουν το αρχείο 3DS σε USDZ σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου 3DS μέσω του κατασκευαστή της κλάσης Scene1. Καλέστε τη μέθοδο Scene.save με τη μορφή του USDZ.1. Ελέγξτε το προκύπτον αρχείο USDZ στην καθορισμένη διαδρομή
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε τον κωδικό μετατροπής Java, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για JSP/JSF Application and Desktop Applications.- Λάβετε την τελευταία έκδοση του Aspose.3D for Java απευθείας από τη Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής 3DS σε USDZ Java" offSpacer="" %}}

```cs
// Φορτώστε το αρχείο πηγής Discreet 3DS
Scene scene = new Scene("sourceFile.3ds");
// Μετατρέψτε τη σκηνή 3D σε αρχείο σε μορφή USDZ
scene.save("output.usdz", FileFormat.USDZ)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ζωντανές επιδείξεις μετατροπής 3DS σε USDZ" sectionDescription="[Μετατροπή 3DS σε USDZ](https://products.aspose.app/3d/conversion/3ds-to-usdz) αυτή τη στιγμή, επισκεπτόμενοι τον ιστότοπο Live Demos. Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς μεταφορτώστε το αρχείο σας 3DS, θα μετατραπεί αμέσως σε USDZ." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε τον σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Βιβλιοθήκη χειρισμού σκηνής" %}}

 Το Aspose.3D είναι ένα CAD και ένα Gameware API για τη φόρτωση, τροποποίηση και μετατροπή αρχείων 3D. Το API είναι αυτόνομο και δεν απαιτεί κανένα λογισμικό μοντελοποίησης ή απόδοσης 3D. Μπορεί κανείς εύκολα να χρησιμοποιήσει το API για USD, Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX και άλλες μορφές. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}

Ένα αρχείο με επέκταση .3ds αντιπροσωπεύει τη μορφή αρχείου mesh 3D Sudio (DOS) που χρησιμοποιείται από το Autodesk 3D Studio. Το Autodesk 3D Studio βρίσκεται στην αγορά μορφών αρχείων 3D από τη δεκαετία του 1990 και τώρα έχει εξελιχθεί σε 3D Studio MAX για εργασία με 3D μοντελοποίηση, κινούμενα σχέδια και απόδοση. Ένα αρχείο 3DS περιέχει δεδομένα για 3D αναπαράσταση σκηνών και εικόνων και είναι μία από τις δημοφιλείς μορφές αρχείων για εισαγωγή και εξαγωγή δεδομένων 3D. Λαμβάνει υπόψη πληροφορίες όπως τοποθεσίες κάμερας, δεδομένα Mesh, πληροφορίες φωτισμού, διαμορφώσεις θυρών προβολής, εξομάλυνση δεδομένων ομάδας, αναφορές bitmap και χαρακτηριστικά για τη δημιουργία κορυφών και πολυγώνων για την απόδοση μιας σκηνής.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="USDZ" readMoreLink="https://docs.fileformat.com/3d/usdz/" >}}

Ένα αρχείο με .usdz είναι ένα μη συμπιεσμένο και μη κρυπτογραφημένο αρχείο ZIP για τη μορφή αρχείου USD (Universal Scene Description) που περιέχει και διακομιστή μεσολάβησης για αρχεία άλλων μορφών (όπως υφές και κινούμενα σχέδια) ενσωματωμένα στο αρχείο και τα εκτελεί απευθείας με το χρόνο εκτέλεσης του USD χωρίς καμία ανάγκη αποσυσκευασίας. Τα αρχεία USDZ είναι πακέτα των οποίων ο σχεδιασμός βασίζεται στη νέα αφαίρεση σε επίπεδο Ar ενός πακέτου. Το Usdz εγγράφηκε στο IANA και έχει το όνομα τύπου μέσου του μοντέλου και ένα όνομα δευτερεύοντος τύπου vnd.usd+zip και τα στοιχεία του βρίσκονται στη σελίδα εγγραφής του IANA.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το 3DS σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-gltf/" name="3DS ΠΡΟΣ GLTF" description="Αρχείο μορφής μετάδοσης GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-glb/" name="3DS ΠΡΟΣ GLB" description="Μορφή δυαδικής μετάδοσης GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-pdf/" name="3DS ΠΡΟΣ PDF" description="Μορφή φορητού εγγράφου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-fbx/" name="3DS ΠΡΟΣ FBX" description="Αρχείο ανταλλαγής Autodesk FBX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-stl/" name="3DS ΠΡΟΣ STL" description="Αρχείο Στερεολιθογραφίας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-obj/" name="3DS ΠΡΟΣ OBJ" description="Wavefront 3D Αρχείο αντικειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-dae/" name="3DS ΠΡΟΣ DAE" description="Αρχείο ανταλλαγής ψηφιακών στοιχείων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-u3d/" name="3DS ΠΡΟΣ U3D" description="Universal 3D Αρχείο" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-ply/" name="3DS ΠΡΟΣ PLY" description="Μορφή αρχείου Polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-drc/" name="3DS ΠΡΟΣ DRC" description="Google Draco Μορφή αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-rvm/" name="3DS ΠΡΟΣ RVM" description="AVEVA RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-jt/" name="3DS ΠΡΟΣ JT" description="JT Ανοίξτε το αρχείο CAD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-amf/" name="3DS ΠΡΟΣ AMF" description="Αρχείο Κατασκευής Πρόσθετων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-html/" name="3DS ΠΡΟΣ HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-usd/" name="3DS ΠΡΟΣ USD" description="Μορφή Περιγραφής Universal Σκηνής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-usdz/" name="3DS ΠΡΟΣ USDZ" description="Περιγραφή σκηνής γενικής χρήσης σε μορφή φερμουάρ" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}