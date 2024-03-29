﻿---
title: Μετατροπή JT σε FBX μέσω C# 
weight: 1780
url: /el/net/conversion/jt-to-fbx/ 
description: Δείγμα κώδικα για μετατροπή JT σε FBX C#. Χρησιμοποιήστε API παράδειγμα κώδικα για ομαδικά αρχεία JT σε FBX μετατροπή εντός VB.NET, Asp.NET ή οποιασδήποτε εφαρμογής που βασίζεται σε .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή JT σε FBX μέσω C#" h2="Αποδώστε το JT ως FBX χωρίς κανένα λογισμικό μοντελοποίησης και απόδοσης 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το JT σε FBX χρησιμοποιώντας το C#" %}}

 Για να μετατρέψουμε το JT σε FBX, θα χρησιμοποιήσουμε
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API που είναι μια πλατφόρμα πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση χειρισμό και μετατροπή εγγράφων API για C#. Ανοιξε
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 διαχειριστής πακέτων, αναζητήστε
 Aspose.3D 
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή κονσόλας διαχείρισης πακέτων" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή JT σε FBX μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές .NET μπορούν εύκολα να φορτώσουν και να μετατρέψουν αρχεία JT σε FBX σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου JT μέσω του κατασκευαστή της κλάσης Scene1. Δημιουργήστε μια παρουσία του FbxSaveOptions1. Ορίστε FBX συγκεκριμένες ιδιότητες για σύνθετη μετατροπή1. Καλέστε τη μέθοδο Scene.Save1. Περάστε τη διαδρομή εξόδου με την επέκταση αρχείου FBX και το αντικείμενο του FbxSaveOptions1. Ελέγξτε το προκύπτον αρχείο FBX στην καθορισμένη διαδρομή
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε τον κωδικό μετατροπής .NET, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με .NET Framework, .NET Core, Mono.- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.- Aspose.3D for .NET DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή JT σε FBX C#" offSpacer="" %}}

```cs
// φορτώστε το JT σε ένα αντικείμενο της σκηνής 
var document = new Aspose.ThreeD.Scene("template.jt");
// δημιουργήστε μια παρουσία του FbxSaveOptions 
var options = new Aspose.ThreeD.Formats.FbxSaveOptions();
// αποθήκευση JT ως FBX 
document.Save("output.fbx", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Δωρεάν εφαρμογή για μετατροπή JT σε FBX" sectionDescription="Ελέγξτε τις ζωντανές επιδείξεις μας για [μετατροπή JT σε FBX](https://products.aspose.app/3d/conversion/jt-to-fbx) με τα ακόλουθα οφέλη." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς μεταφορτώστε το αρχείο σας JT και πατήστε το κουμπί \"Μετατροπή\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε αμέσως τον σύνδεσμο λήψης για το αρχείο FBX που προκύπτει." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Μια 3D Βιβλιοθήκη Επεξεργασίας Αρχείων για χειρισμό αρχείων 3D χωρίς λογισμικό μοντελοποίησης και απόδοσης. Το 3D API υποστηρίζει Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco μορφές αρχείων και άλλα. Οι προγραμματιστές μπορούν να δημιουργήσουν, να διαβάσουν, να μετατρέψουν, να τροποποιήσουν και να ελέγξουν την ουσία των 3D μορφών εγγράφων εύκολα.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JT" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}
Το JT (Jupiter Tessellation) είναι μια αποτελεσματική, εστιασμένη στη βιομηχανία και ευέλικτη μορφή δεδομένων 3D με τυποποίηση ISO που αναπτύχθηκε από τη Siemens PLM Software. Οι μηχανικοί τομείς CAD της Αεροδιαστημικής, της αυτοκινητοβιομηχανίας και του Βαρύ Εξοπλισμού χρησιμοποιούν το JT ως την πιο κορυφαία μορφή οπτικοποίησης 3D. Η μορφή JT είναι ένα γράφημα σκηνής που υποστηρίζει τα χαρακτηριστικά και τους κόμβους που είναι συγκεκριμένοι CAD. Για την αποθήκευση δεδομένων όψεων (τρίγωνα) χρησιμοποιούνται εξελιγμένες τεχνικές συμπίεσης. Αυτή η μορφή είναι δομημένη ώστε να υποστηρίζει οπτικά χαρακτηριστικά, πληροφορίες προϊόντος και κατασκευής (PMI) και Μεταδεδομένα. Υπάρχει καλή υποστήριξη για ασύγχρονη ροή περιεχομένου. Στη βαριά μηχανική βιομηχανία, οι επαγγελματίες χρησιμοποιούν το αρχείο JT στις λύσεις CAD και τα προγράμματα λογισμικού διαχείρισης κύκλου ζωής προϊόντων (PLM) για να εξετάσουν τη γεωμετρία περίπλοκων προϊόντων.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="fbx" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
Το FBX, FilmBox, είναι μια δημοφιλής μορφή αρχείου 3D που αναπτύχθηκε αρχικά από την Kaydara για το MotionBuilder. Εξαγοράστηκε από την Autodesk Inc το 2006 και τώρα είναι μία από τις κύριες μορφές ανταλλαγής 3D όπως χρησιμοποιείται από πολλά εργαλεία 3D. Το FBX είναι διαθέσιμο τόσο σε δυαδικό όσο και σε μορφή αρχείου ASCII. Η μορφή δημιουργήθηκε για να παρέχει διαλειτουργικότητα μεταξύ εφαρμογών δημιουργίας ψηφιακού περιεχομένου. Υπάρχουν πολλά διαθέσιμα εργαλεία για μετατροπή από/σε μορφή αρχείου FBX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το JT σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-3ds/" name="JT ΠΡΟΣ 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-amf/" name="JT ΠΡΟΣ AMF" description="Μορφή κατασκευής πρόσθετων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-dae/" name="JT ΠΡΟΣ DAE" description="Ανταλλαγή ψηφιακών περιουσιακών στοιχείων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-html/" name="JT ΠΡΟΣ HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-obj/" name="JT ΠΡΟΣ OBJ" description="3D Μορφή αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-pdf/" name="JT ΠΡΟΣ PDF" description="Μορφή φορητού εγγράφου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-ply/" name="JT ΠΡΟΣ PLY" description="Μορφή αρχείου Polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-rvm/" name="JT ΠΡΟΣ RVM" description="Μοντέλο σχεδίασης φυτών AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-stl/" name="JT ΠΡΟΣ STL" description="Εναλλάξιμη Γεωμετρία Επιφανειών 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-u3d/" name="JT ΠΡΟΣ U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}