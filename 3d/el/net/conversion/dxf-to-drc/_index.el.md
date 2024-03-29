﻿---
title: Μετατροπή DXF σε DRC μέσω C# 
url: /el/net/conversion/dxf-to-drc/ 
description: Δείγμα κώδικα για μετατροπή DXF σε DRC C#. Χρησιμοποιήστε API παράδειγμα κώδικα για ομαδικά αρχεία DXF σε DRC μετατροπή εντός VB.NET, Asp.NET ή οποιασδήποτε εφαρμογής που βασίζεται σε .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή DXF σε DRC μέσω C#" h2="Αποδώστε το DXF ως DRC χωρίς κανένα λογισμικό μοντελοποίησης και απόδοσης 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DRC" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το DXF σε DRC χρησιμοποιώντας το C#" %}}

 Για να μετατρέψουμε το DXF σε DRC, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή DXF σε DRC μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές .NET μπορούν εύκολα να φορτώσουν και να μετατρέψουν αρχεία DXF σε DRC σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου DXF μέσω του κατασκευαστή της κλάσης Scene1. Δημιουργήστε μια παρουσία του AmfSaveOptions1. Ορίστε DRC συγκεκριμένες ιδιότητες για σύνθετη μετατροπή1. Καλέστε τη μέθοδο Scene.Save1. Περάστε τη διαδρομή εξόδου με την επέκταση αρχείου DRC και το αντικείμενο του DrcSaveOptions1. Ελέγξτε το προκύπτον αρχείο DRC στην καθορισμένη διαδρομή
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε τον κωδικό μετατροπής .NET, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με .NET Framework, .NET Core, Mono.- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.- Aspose.3D for .NET DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή DXF σε DRC C#" offSpacer="" %}}

```cs
// φορτώστε το DXF σε ένα αντικείμενο της σκηνής 
var document = new Aspose.ThreeD.Scene("template.dxf");
// δημιουργήστε μια παρουσία του DrcSaveOptions 
var options = new Aspose.ThreeD.Formats.DrcSaveOptions();
// αποθήκευση DXF ως DRC 
document.Save("output.drc", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Δωρεάν εφαρμογή για μετατροπή DXF σε DRC" sectionDescription="Ελέγξτε τις ζωντανές επιδείξεις μας για [μετατροπή DXF σε DRC](https://products.aspose.app/3d/conversion/dxf-to-drc) με τα ακόλουθα οφέλη." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς μεταφορτώστε το αρχείο σας DXF και πατήστε το κουμπί \"Μετατροπή\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε αμέσως τον σύνδεσμο λήψης για το αρχείο DRC που προκύπτει." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Μια 3D Βιβλιοθήκη Επεξεργασίας Αρχείων για χειρισμό αρχείων 3D χωρίς λογισμικό μοντελοποίησης και απόδοσης. Το 3D API υποστηρίζει Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco μορφές αρχείων και άλλα. Οι προγραμματιστές μπορούν να δημιουργήσουν, να διαβάσουν, να μετατρέψουν, να τροποποιήσουν και να ελέγξουν την ουσία των 3D μορφών εγγράφων εύκολα.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}
Το DXF, Drawing Interchange Format ή Drawing Exchange Format, είναι μια αναπαράσταση δεδομένων με ετικέτα του αρχείου σχεδίασης AutoCAD. Κάθε στοιχείο στο αρχείο έχει έναν ακέραιο αριθμό προθέματος που ονομάζεται κωδικός ομάδας. Αυτός ο κωδικός ομάδας αντιπροσωπεύει στην πραγματικότητα το στοιχείο που ακολουθεί και υποδεικνύει τη σημασία ενός στοιχείου δεδομένων για έναν δεδομένο τύπο αντικειμένου. Το DXF καθιστά δυνατή την αναπαράσταση σχεδόν όλων των πληροφοριών που καθορίζονται από τον χρήστη σε ένα αρχείο σχεδίασης. Η μορφή αρχείου DXF αναπτύχθηκε από την Autodesk ως μορφή αρχείου δεδομένων CAD για διαλειτουργικότητα δεδομένων μεταξύ του AutoCAD και άλλων εφαρμογών. Έτσι, τα δεδομένα μπορούν να εισαχθούν από άλλες μορφές στο DXF στο AutoCAD σύμφωνα με τις προδιαγραφές διαλειτουργικότητας μορφής αρχείου DXF.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="drc" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
Ένα αρχείο με επέκταση .drc είναι μια συμπιεσμένη μορφή αρχείου 3D που δημιουργήθηκε με τη βιβλιοθήκη Google Draco. Το Google προσφέρει το Draco ως βιβλιοθήκη ανοιχτού κώδικα για τη συμπίεση και την αποσυμπίεση 3D γεωμετρικών ματιών και νέφους σημείων και βελτιώνει την αποθήκευση και τη μετάδοση γραφικών 3D. Κωδικοποιεί τα δεδομένα εισόδου και τα αποθηκεύει ως αρχείο .drc. Στο τέλος λήψης, το API διαβάζει αρχεία .drc και μπορεί να τα εξάγει ως αρχεία PLY ή OBJ. Το συμπιεσμένο αρχείο εξόδου επιτρέπει στους χρήστες να κάνουν λήψη εφαρμογών πιο γρήγορα και να παρέχουν γρήγορη φόρτωση 3D γραφικών στα προγράμματα περιήγησης.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το DXF σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-3ds/" name="DXF ΠΡΟΣ 3DS" description="3D Studio DOS Mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-amf/" name="DXF ΠΡΟΣ AMF" description="Μορφή κατασκευής πρόσθετων" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-dae/" name="DXF ΠΡΟΣ DAE" description="Ανταλλαγή ψηφιακών περιουσιακών στοιχείων" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-fbx/" name="DXF ΠΡΟΣ FBX" description="3D Μορφή" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-html/" name="DXF ΠΡΟΣ HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-obj/" name="DXF ΠΡΟΣ OBJ" description="3D Μορφή αρχείου" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-pdf/" name="DXF ΠΡΟΣ PDF" description="Μορφή φορητού εγγράφου" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-ply/" name="DXF ΠΡΟΣ PLY" description="Μορφή αρχείου Polygon" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-rvm/" name="DXF ΠΡΟΣ RVM" description="Μοντέλο σχεδίασης φυτών AVEVA" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-stl/" name="DXF ΠΡΟΣ STL" description="Εναλλάξιμη Γεωμετρία Επιφανειών 3D" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-u3d/" name="DXF ΠΡΟΣ U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}