﻿---
title: Μετατροπή 3DS σε 3MF μέσω Java 
weight: 810
url: /el/java/conversion/3ds-to-3mf/ 
description: Δείγμα κώδικα μετατροπής Java για μορφή 3DS σε αρχείο 3MF. Χρησιμοποιήστε αυτό το παράδειγμα κώδικα για να μετατρέψετε το 3DS σε 3MF σε οποιαδήποτε εφαρμογή που βασίζεται στον Ιστό ή στην επιφάνεια εργασίας Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή 3DS σε 3MF μέσω Java" h2="Μετατροπή 3DS σε 3MF με χρήση βιβλιοθήκης Java χωρίς λογισμικό μοντελοποίησης 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="3MF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το 3DS σε 3MF χρησιμοποιώντας το Java" %}}

 Για να αποδώσουμε το 3DS στο 3MF, θα χρησιμοποιήσουμε
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API που είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα μετατροπής API for Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή 3DS σε 3MF μέσω Java" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές Java μπορούν εύκολα να μετατρέψουν το αρχείο 3DS σε 3MF σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου 3DS μέσω του κατασκευαστή της κλάσης Scene1. Δημιουργήστε μια παρουσία του U3dSaveOptions1. Ορίστε 3MF συγκεκριμένες ιδιότητες για σύνθετη μετατροπή1. Μέθοδος κλήσης Scene.save1. Περάστε τη διαδρομή εξόδου με την επέκταση αρχείου 3MF και το αντικείμενο του U3dSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε τον κωδικό μετατροπής Java, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για JSP/JSF Application and Desktop Applications.- Λάβετε την τελευταία έκδοση του Aspose.3D for Java απευθείας από τη Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής 3DS σε 3MF Java" offSpacer="" %}}

```cs
// φορτώστε το 3DS σε ένα αντικείμενο της σκηνής 
Scene document = new Scene("template.3ds");
// δημιουργήστε μια παρουσία του U3dSaveOptions 
U3dSaveOptions options = new U3dSaveOptions();
// αποθήκευση 3DS ως 3MF 
document.save("output.3mf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ζωντανές επιδείξεις μετατροπής 3DS σε 3MF" sectionDescription="[Μετατροπή 3DS σε 3MF](https://products.aspose.app/3d/conversion/3ds-to-3mf) αυτή τη στιγμή, επισκεπτόμενοι τον ιστότοπο Live Demos. Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς μεταφορτώστε το αρχείο σας 3DS, θα μετατραπεί αμέσως σε 3MF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε τον σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Βιβλιοθήκη χειρισμού σκηνής" %}}

 Το Aspose.3D είναι ένα CAD και ένα Gameware API για τη φόρτωση, τροποποίηση και μετατροπή αρχείων 3D. Το API είναι αυτόνομο και δεν απαιτεί κανένα λογισμικό μοντελοποίησης ή απόδοσης 3D. Μπορεί κανείς εύκολα να χρησιμοποιήσει το API για Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX και άλλες μορφές. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}

Ένα αρχείο με επέκταση 3DS αντιπροσωπεύει τη μορφή αρχείου πλέγματος 3D Studio (DOS) που χρησιμοποιείται από το Autodesk 3D Studio. Το Autodesk 3D Studio βρίσκεται στην αγορά μορφής αρχείων 3D από τη δεκαετία του 1990 και τώρα έχει εξελιχθεί σε 3D Studio MAX για εργασία με μοντελοποίηση, κινούμενα σχέδια και απόδοση 3D. Ένα αρχείο 3DS περιέχει δεδομένα για 3D αναπαράσταση σκηνών και εικόνων και είναι μία από τις δημοφιλείς μορφές αρχείων για εισαγωγή και εξαγωγή δεδομένων 3D. Λαμβάνει υπόψη πληροφορίες όπως τοποθεσίες κάμερας, δεδομένα Mesh, πληροφορίες φωτισμού, διαμορφώσεις θυρών προβολής, εξομάλυνση δεδομένων ομάδας, αναφορές bitmap και χαρακτηριστικά για τη δημιουργία κορυφών και πολυγώνων για την απόδοση μιας σκηνής.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}

Το 3MF, 3D Manufacturing Format, χρησιμοποιείται από εφαρμογές για την απόδοση μοντέλων αντικειμένων 3D σε διάφορες άλλες εφαρμογές, πλατφόρμες, υπηρεσίες και εκτυπωτές. Κατασκευάστηκε για να αποφεύγονται οι περιορισμοί και τα προβλήματα σε άλλες μορφές αρχείων 3D, όπως το STL, για εργασία με τις πιο πρόσφατες εκδόσεις των εκτυπωτών 3D. Το 3MF είναι μια σχετικά νέα μορφή αρχείου που έχει αναπτυχθεί και δημοσιευτεί από την κοινοπραξία 3MF. Είναι αρκετά πλούσιο για να περιγράφει πλήρως ένα μοντέλο, διατηρώντας εσωτερικές πληροφορίες, χρώμα και άλλα χαρακτηριστικά που το καθιστούν επεκτάσιμο για την υποστήριξη νέων καινοτομιών στην εκτύπωση 3D.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το 3DS σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-amf/" name="3DS ΠΡΟΣ AMF" description="Μορφή κατασκευής πρόσθετων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-dae/" name="3DS ΠΡΟΣ DAE" description="Ανταλλαγή ψηφιακών περιουσιακών στοιχείων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-fbx/" name="3DS ΠΡΟΣ FBX" description="3D Μορφή" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-gltf/" name="3DS ΠΡΟΣ GLTF" description="Μορφή μετάδοσης GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-html/" name="3DS ΠΡΟΣ HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-obj/" name="3DS ΠΡΟΣ OBJ" description="3D Μορφή αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-ply/" name="3DS ΠΡΟΣ PLY" description="Μορφή αρχείου Polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-rvm/" name="3DS ΠΡΟΣ RVM" description="Μοντέλο σχεδίασης φυτών AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-stl/" name="3DS ΠΡΟΣ STL" description="Εναλλάξιμη Γεωμετρία Επιφανειών 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}