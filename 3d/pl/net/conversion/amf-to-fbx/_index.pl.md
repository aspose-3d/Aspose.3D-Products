﻿---
title: Konwertuj AMF na FBX przez C# 
weight: 2770
url: /pl/net/conversion/amf-to-fbx/ 
description: Przykładowy kod konwersji AMF na FBX C#. Użyj API przykładowego kodu dla plików wsadowych AMF do konwersji FBX w VB.NET, Asp.NET lub dowolnej aplikacji opartej na .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj AMF na FBX przez C#" h2="Renderuj AMF jako FBX bez żadnego oprogramowania do modelowania i renderowania 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="AMF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować AMF na FBX za pomocą C#" %}}

 Aby przekonwertować AMF na FBX, użyjemy
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu narzędziem do manipulacji i konwersji dokumentów API na platformę C#. otwarty
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 menedżer pakietów, szukaj
 Aspose.3D 
 i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Polecenie konsoli menedżera pakietów" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować AMF na FBX przez C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programiści mogą łatwo ładować i konwertować pliki AMF na FBX w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik AMF za pomocą konstruktora klasy Scene1. Utwórz instancję FbxSaveOptions1. Ustaw FBX określone właściwości dla zaawansowanej konwersji1. Wywołaj metodę Scene.Save1. Przekaż ścieżkę wyjściową z rozszerzeniem pliku FBX i obiektem FbxSaveOptions1. Sprawdź wynikowy plik FBX w określonej ścieżce
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu konwersji .NET upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny z .NET Framework, .NET Core, Mono.- Środowisko programistyczne, takie jak Microsoft Visual Studio.- Aspose.3D for .NET DLL, do którego odwołuje się Twój projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ten przykładowy kod pokazuje konwersję od AMF do FBX C#" offSpacer="" %}}

```cs
// załaduj AMF do obiektu sceny 
var document = new Aspose.ThreeD.Scene("template.amf");
// utwórz instancję FbxSaveOptions 
var options = new Aspose.ThreeD.Formats.FbxSaveOptions();
// zapisz AMF jako FBX 
document.Save("output.fbx", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Darmowa aplikacja do konwersji AMF na FBX" sectionDescription="Sprawdź nasze prezentacje na żywo dla [Konwersja z AMF do FBX](https://products.aspose.app/3d/conversion/amf-to-fbx) z następującymi korzyściami." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie musisz niczego pobierać ani konfigurować." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik AMF i naciśnij przycisk „Konwertuj”." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Natychmiast otrzymasz link do pobrania wynikowego pliku FBX." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Biblioteka przetwarzania plików 3D do manipulowania plikami 3D bez żadnego oprogramowania do modelowania i renderowania. 3D API obsługuje Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formaty plików i inne. Deweloperzy mogą łatwo tworzyć, czytać, konwertować, modyfikować i kontrolować treść 3D formatów dokumentów.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="AMF" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}
Format pliku wytwarzania addytywnego (AMF) definiuje otwarte standardy opisu obiektów do wykorzystania w procesach wytwarzania przyrostowego, takich jak 3D Drukowanie. Programy CAD używają formatu plików AMF, wykorzystując informacje takie jak geometria, kolor i materiał obiektów. AMF różni się od formatu STL, ponieważ strona boczna nie obsługuje kolorów, materiałów, krat i konstelacji.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="fbx" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, to popularny format plików 3D, który został pierwotnie opracowany przez firmę Kaydara dla MotionBuilder. Został przejęty przez Autodesk Inc w 2006 roku i jest obecnie jednym z głównych 3D formatów wymiany używanych przez wiele 3D narzędzi. FBX jest dostępny zarówno w formacie binarnym, jak i ASCII. Format został ustanowiony w celu zapewnienia interoperacyjności między aplikacjami do tworzenia treści cyfrowych. Dostępnych jest wiele narzędzi do konwersji z/do formatu pliku FBX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować AMF na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-3ds/" name="AMF DO 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-dae/" name="AMF DO DAE" description="Wymiana aktywów cyfrowych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-html/" name="AMF DO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-obj/" name="AMF DO OBJ" description="3D Format pliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-pdf/" name="AMF DO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-ply/" name="AMF DO PLY" description="Format pliku wielokąta" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-rvm/" name="AMF DO RVM" description="Model projektowy zakładu AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-stl/" name="AMF DO STL" description="Wymienna 3D geometria powierzchni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-u3d/" name="AMF DO U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}