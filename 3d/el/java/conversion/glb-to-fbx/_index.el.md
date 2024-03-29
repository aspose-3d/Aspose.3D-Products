﻿---
title: Μετατροπή GLB σε FBX μέσω Java
weight: 530
url: /el/java/conversion/glb-to-fbx/ 
description: Δείγμα κώδικα μετατροπής Java για μορφή GLB σε αρχείο FBX. Χρησιμοποιήστε αυτό το παράδειγμα κώδικα για να μετατρέψετε το GLB σε FBX σε οποιαδήποτε εφαρμογή που βασίζεται στον Ιστό ή στην επιφάνεια εργασίας Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή GLB σε FBX μέσω Java" h2="Μετατροπή GLB σε FBX με χρήση βιβλιοθήκης Java χωρίς λογισμικό μοντελοποίησης 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το GLB σε FBX χρησιμοποιώντας το Java" %}}

 Για να αποδώσουμε το GLB στο FBX, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή GLB σε FBX μέσω Java" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές Java μπορούν εύκολα να μετατρέψουν το αρχείο GLB σε FBX σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου GLB μέσω του κατασκευαστή της κλάσης Scene1. Καλέστε τη μέθοδο Scene.save με τη μορφή του FBX.1. Ελέγξτε το προκύπτον αρχείο FBX στην καθορισμένη διαδρομή
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε τον κωδικό μετατροπής Java, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για JSP/JSF Application and Desktop Applications.- Λάβετε την τελευταία έκδοση του Aspose.3D for Java απευθείας από τη Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής GLB σε FBX Java" offSpacer="" %}}

```cs
// Φορτώστε το αρχείο προέλευσης Binary GLTF
Scene scene = new Scene("sourceFile.glb");
// Μετατρέψτε τη σκηνή 3D σε αρχείο σε μορφή Autodesk FBX
scene.save("output.fbx", FileFormat.FBX7700_BINARY)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ζωντανές επιδείξεις μετατροπής GLB σε FBX" sectionDescription="[Μετατροπή GLB σε FBX](https://products.aspose.app/3d/conversion/glb-to-fbx) αυτή τη στιγμή, επισκεπτόμενοι τον ιστότοπο Live Demos. Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς μεταφορτώστε το αρχείο σας GLB, θα μετατραπεί αμέσως σε FBX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε τον σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Βιβλιοθήκη χειρισμού σκηνής" %}}

 Το Aspose.3D είναι ένα CAD και ένα Gameware API για τη φόρτωση, τροποποίηση και μετατροπή αρχείων 3D. Το API είναι αυτόνομο και δεν απαιτεί κανένα λογισμικό μοντελοποίησης ή απόδοσης 3D. Μπορεί κανείς εύκολα να χρησιμοποιήσει το API για USD, Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX και άλλες μορφές. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}

Το GLB είναι η αναπαράσταση μορφής δυαδικού αρχείου 3D μοντέλων που είναι αποθηκευμένα στη Μορφή μετάδοσης GL (glTF). Πληροφορίες σχετικά με μοντέλα 3D, όπως ιεραρχία κόμβων, κάμερες, υλικά, κινούμενα σχέδια και πλέγματα σε δυαδική μορφή. Αυτή η δυαδική μορφή αποθηκεύει το στοιχείο glTF (JSON, .bin και εικόνες) σε ένα δυαδικό blob. Αποφεύγει επίσης το ζήτημα της αύξησης του μεγέθους του αρχείου που συμβαίνει στην περίπτωση του glTF. Η μορφή αρχείου GLB έχει ως αποτέλεσμα συμπαγή μεγέθη αρχείων, γρήγορη φόρτωση, πλήρη 3D αναπαράσταση σκηνής και επεκτασιμότητα για περαιτέρω ανάπτυξη. Η μορφή χρησιμοποιεί model/gltf-binary ως τύπο MIME.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}

Το FBX, FilmBox, είναι μια δημοφιλής μορφή αρχείου 3D που αναπτύχθηκε αρχικά από την Kaydara για το MotionBuilder. Εξαγοράστηκε από την Autodesk Inc το 2006 και τώρα είναι μία από τις κύριες μορφές ανταλλαγής 3D όπως χρησιμοποιείται από πολλά εργαλεία 3D. Το FBX είναι διαθέσιμο τόσο σε δυαδικό όσο και σε μορφή αρχείου ASCII. Η μορφή δημιουργήθηκε για να παρέχει διαλειτουργικότητα μεταξύ εφαρμογών δημιουργίας ψηφιακού περιεχομένου. Υπάρχουν πολλά διαθέσιμα εργαλεία για μετατροπή από/σε μορφή αρχείου FBX.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το GLB σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-gltf/" name="GLB ΠΡΟΣ GLTF" description="Αρχείο μορφής μετάδοσης GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-pdf/" name="GLB ΠΡΟΣ PDF" description="Μορφή φορητού εγγράφου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-fbx/" name="GLB ΠΡΟΣ FBX" description="Αρχείο ανταλλαγής Autodesk FBX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-stl/" name="GLB ΠΡΟΣ STL" description="Αρχείο Στερεολιθογραφίας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-obj/" name="GLB ΠΡΟΣ OBJ" description="Wavefront 3D Αρχείο αντικειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-3ds/" name="GLB ΠΡΟΣ 3DS" description="3D Σκηνή στούντιο" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-dae/" name="GLB ΠΡΟΣ DAE" description="Αρχείο ανταλλαγής ψηφιακών στοιχείων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-u3d/" name="GLB ΠΡΟΣ U3D" description="Universal 3D Αρχείο" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-ply/" name="GLB ΠΡΟΣ PLY" description="Μορφή αρχείου Polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-drc/" name="GLB ΠΡΟΣ DRC" description="Google Draco Μορφή αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-rvm/" name="GLB ΠΡΟΣ RVM" description="AVEVA RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-jt/" name="GLB ΠΡΟΣ JT" description="JT Ανοίξτε το αρχείο CAD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-amf/" name="GLB ΠΡΟΣ AMF" description="Αρχείο Κατασκευής Πρόσθετων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-html/" name="GLB ΠΡΟΣ HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-usd/" name="GLB ΠΡΟΣ USD" description="Μορφή Περιγραφής Universal Σκηνής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-usdz/" name="GLB ΠΡΟΣ USDZ" description="Περιγραφή σκηνής γενικής χρήσης σε μορφή φερμουάρ" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}