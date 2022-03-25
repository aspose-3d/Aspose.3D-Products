﻿---
title: Μετατροπή VRML σε ASE μέσω Java 
weight: 2710
url: /el/java/conversion/vrml-to-ase/ 
description: Δείγμα Java κώδικα μετατροπής για τη μορφή VRML σε αρχείο ASE. Χρησιμοποιήστε αυτό το παράδειγμα κωδικό για να μετατρέψετε VRML σε ASE μέσα σε οποιαδήποτε εφαρμογή Web ή Επιφάνεια Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή VRML σε ASE μέσω Java" h2="VRML σε ASE μετατροπή με τη χρήση βιβλιοθήκης Java χωρίς λογισμικό μοντελοποίησης 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="ASE" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="VRML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε VRML σε ASE χρησιμοποιώντας Java" %}}

 Για να αναγνωρίσουμε το VRML έως ASE, θα χρησιμοποιήσουμε τα ακόλουθα:
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα μετατροπής API for Java. Μπορείτε να κατεβάσετε την τελευταία έκδοσή του απευθείας από την τελευταία έκδοση
 [Μέιβεν](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 Και να το εγκαταστήσετε μέσα στο Maven-based project σας προσθέτοντας τις παρακάτω διαμορφώσεις στο pom.xml.

{{% blocks/products/pf/agp/code-block title="Χώρος αποθήκευσης" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/</url>
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή VRML σε ASE μέσω Java" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές Java μπορούν εύκολα να μετατρέψουν το VRML αρχείο σε ASE σε λίγες μόνο γραμμές του κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου VRML μέσω του κατασκευαστή της κλάσης σκηνής1. Δημιουργία μιας διάταξης του AseSaveOptions1. Ορισμός συγκεκριμένων ιδιοτήτων ASE για προηγμένη μετατροπή1. Μέθοδος κλήσης Scene.save1. Πέρασε τη διαδρομή εξόδου με επέκταση αρχείου ASE & αντικείμενο του AseSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε τον κώδικα μετατροπής Java, βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή ένα συμβατό OS με Java Περιβάλλον εκμετάλλευσης για εφαρμογές JSP/JSF και επιφάνειες εφαρμογές.- Πάρτε την τελευταία έκδοση του Aspose.3D for Java απευθείας από το Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="VRML σε ASE Java Πηγαίος κώδικας μετατροπής" offSpacer="" %}}

```cs
// Φόρτωση του VRML σε ένα αντικείμενο σκηνής 
Scene document = new Scene("template.vrml");
// Δημιουργία μιας ένδειξης του AseSaveOptions 
AseSaveOptions options = new AseSaveOptions();
// Αποθήκευση VRML ως ASE 
document.save("output.ase", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="VRML σε ASE Ζωντανή μετατροπή" sectionDescription="[Μετατροπή VRML σε ASE](https://products.aspose.app/3d/conversion/vrml-to-ase) Αυτή τη στιγμή επισκεπτώντας την ιστοσελίδα μας Live Demos.Το live demo έχει τα ακόλουθα οφέλη" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται λήψη Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράφεις κανένα κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλά ανεβάστε το αρχείο VRML σας, θα μετατραπεί άμεσα σε ASE." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα πάρετε το σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Βιβλιοθήκη χειραγωγής σκηνής" %}}

 Το Aspose.3D είναι ένα CAD και το λογισμικό API για τη φόρτωση, την τροποποίηση και τη μετατροπή αρχείων 3D. Το API είναι αυτόνομο και δεν απαιτεί κανένα λογισμικό μοντελοποίησης ή αποτύπωσης 3D. Μπορεί κανείς να χρησιμοποιήσει το API για Discreet3DS, WavefrontOBJ, STL (ASCII, δυαδικό), Universal3D, FBX (ASCII, δυαδικό), Collada, glTF, PLY, GLB, DirectX και περισσότερες μορφές. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="VRML" readMoreLink="https://docs.fileformat.com/3d/vrml/" >}}

Γλώσσα μοντελοποίησης εικονικής πραγματικότητας (VRML) είναι μια μορφή αρχείου για την αναπαράσταση διαδραστικών αντικειμένων 3D παγκόσμιας παγκόσμιας ιστοσελίδας (www). Βρίσκει τη χρήση του στη δημιουργία τρισδιάστατων αναπαραστάσεων περίπλοκων σκηνών, όπως εικονογραφήσεις, ορισμός και παρουσιάσεις εικονικής πραγματικότητας. Η μορφή έχει αντικατασταθεί από X3D. Πολλές εφαρμογές μοντελοποίησης 3D μπορούν να αποθηκεύσουν αντικείμενα και σκηνές σε μορφή VRML.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}

Ένα αρχείο ASE είναι ένα 2D animation ή γραφικά που περιέχει στρώματα, πλαίσια, παλέτες, ετικέτες και ρυθμίσεις.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε VRML σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων λίγα που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-3ds/" name="VRML έως 3DS" description="3D Μέσα DOS στούντιο" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-amf/" name="VRML έως AMF" description="Πρόσθετη μορφή παραγωγής παραγωγής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-dae/" name="VRML έως DAE" description="Ανταλλαγή ψηφιακών περιουσιακών στοιχείων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-fbx/" name="VRML έως FBX" description="Μορφή 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-gltf/" name="VRML έως GLTF" description="Μορφή μετάδοσης GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-html/" name="VRML έως HTML" description="Γλώσσα σήμανσης Hyper κειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-obj/" name="VRML έως OBJ" description="Μορφή αρχείου 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-ply/" name="VRML έως PLY" description="Μορφή αρχείων Πολυγόνου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-rvm/" name="VRML έως RVM" description="Σχεδιασμός φυτών AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-stl/" name="VRML έως STL" description="Εναλλάξιμο 3D Γεωμετρία επιφάνειας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-u3d/" name="VRML έως U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}