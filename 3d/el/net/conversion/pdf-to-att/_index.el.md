﻿---
title: Μετατροπή PDF σε ATT μέσω C# 
url: /el/net/conversion/pdf-to-att/ 
description: Δείγμα κώδικα για μετατροπή PDF σε ATT C#. Χρησιμοποιήστε API παράδειγμα κώδικα για ομαδικά αρχεία PDF σε ATT μετατροπή εντός VB.NET, Asp.NET ή οποιασδήποτε εφαρμογής που βασίζεται σε .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή PDF σε ATT μέσω C#" h2="Αποδώστε το PDF ως ATT χωρίς κανένα λογισμικό μοντελοποίησης και απόδοσης 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ATT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το PDF σε ATT χρησιμοποιώντας το C#" %}}

 Για να μετατρέψουμε το PDF σε ATT, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή PDF σε ATT μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές .NET μπορούν εύκολα να φορτώσουν και να μετατρέψουν αρχεία PDF σε ATT σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου PDF μέσω του κατασκευαστή της κλάσης Scene1. Δημιουργήστε μια παρουσία του AmfSaveOptions1. Ορίστε ATT συγκεκριμένες ιδιότητες για σύνθετη μετατροπή1. Καλέστε τη μέθοδο Scene.Save1. Περάστε τη διαδρομή εξόδου με την επέκταση αρχείου ATT και το αντικείμενο του AttSaveOptions1. Ελέγξτε το προκύπτον αρχείο ATT στην καθορισμένη διαδρομή
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε τον κωδικό μετατροπής .NET, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με .NET Framework, .NET Core, Mono.- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.- Aspose.3D for .NET DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή PDF σε ATT C#" offSpacer="" %}}

```cs
// φορτώστε το PDF σε ένα αντικείμενο της σκηνής 
var document = new Aspose.ThreeD.Scene("template.pdf");
// δημιουργήστε μια παρουσία του AttSaveOptions 
var options = new Aspose.ThreeD.Formats.AttSaveOptions();
// αποθήκευση PDF ως ATT 
document.Save("output.att", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Δωρεάν εφαρμογή για μετατροπή PDF σε ATT" sectionDescription="Ελέγξτε τις ζωντανές επιδείξεις μας για [μετατροπή PDF σε ATT](https://products.aspose.app/3d/conversion/pdf-to-att) με τα ακόλουθα οφέλη." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς μεταφορτώστε το αρχείο σας PDF και πατήστε το κουμπί \"Μετατροπή\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε αμέσως τον σύνδεσμο λήψης για το αρχείο ATT που προκύπτει." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Μια 3D Βιβλιοθήκη Επεξεργασίας Αρχείων για χειρισμό αρχείων 3D χωρίς λογισμικό μοντελοποίησης και απόδοσης. Το 3D API υποστηρίζει Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco μορφές αρχείων και άλλα. Οι προγραμματιστές μπορούν να δημιουργήσουν, να διαβάσουν, να μετατρέψουν, να τροποποιήσουν και να ελέγξουν την ουσία των 3D μορφών εγγράφων εύκολα.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Το Portable Document Format (PDF) είναι ένας τύπος εγγράφου που δημιουργήθηκε από την Adobe στη δεκαετία του 1990. Ο σκοπός αυτής της μορφής αρχείου ήταν να εισαγάγει ένα πρότυπο για την αναπαράσταση εγγράφων και άλλου υλικού αναφοράς σε μορφή που να είναι ανεξάρτητη από το λογισμικό εφαρμογής, το υλικό καθώς και το λειτουργικό σύστημα. PDF αρχεία μπορούν να ανοίξουν στο Adobe Acrobat Reader/Writer καθώς και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox μέσω επεκτάσεων/προσθηκών. Οι περισσότερες από τις εμπορικά διαθέσιμες σουίτες λογισμικού προσφέρουν επίσης μετατροπή των εγγράφων τους σε μορφή αρχείου PDF χωρίς την απαίτηση πρόσθετου στοιχείου λογισμικού. Έτσι, η μορφή αρχείου PDF έχει πλήρη ικανότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, εμπλουτισμένα μέσα, ψηφιακές υπογραφές, συνημμένα, μεταδεδομένα, γεωχωρικά χαρακτηριστικά και 3D αντικείμενα σε αυτήν που μπορούν να γίνουν ως μέρος της πηγής έγγραφο.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="att" readMoreLink="#" >}}


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το PDF σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-3ds/" name="PDF ΠΡΟΣ 3DS" description="3D Studio DOS Mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-amf/" name="PDF ΠΡΟΣ AMF" description="Μορφή κατασκευής πρόσθετων" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-dae/" name="PDF ΠΡΟΣ DAE" description="Ανταλλαγή ψηφιακών περιουσιακών στοιχείων" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-fbx/" name="PDF ΠΡΟΣ FBX" description="3D Μορφή" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-html/" name="PDF ΠΡΟΣ HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-obj/" name="PDF ΠΡΟΣ OBJ" description="3D Μορφή αρχείου" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-ply/" name="PDF ΠΡΟΣ PLY" description="Μορφή αρχείου Polygon" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-rvm/" name="PDF ΠΡΟΣ RVM" description="Μοντέλο σχεδίασης φυτών AVEVA" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-stl/" name="PDF ΠΡΟΣ STL" description="Εναλλάξιμη Γεωμετρία Επιφανειών 3D" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-u3d/" name="PDF ΠΡΟΣ U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}