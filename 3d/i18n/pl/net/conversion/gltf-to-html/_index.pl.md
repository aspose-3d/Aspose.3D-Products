﻿---
title: Konwertuj GLTF na HTML za pośrednictwem C# 
url: /pl/net/conversion/gltf-to-html/ 
description: Przykładowy kod dla konwersji od GLTF do HTML C#. Użyj kodu przykładowego API dla plików wsadowych GLTF do konwersji HTML w ramach VB.NET, asp .NET lub dowolnej aplikacji opartej na .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj GLTF na HTML za pośrednictwem C#" h2="Renderuj GLTF jako HTML bez żadnego oprogramowania do modelowania i renderowania 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować GLTF na HTML za pomocą C#" %}}

 Aby przekonwertować GLTF na HTML, użyjemy
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, która jest bogatą w funkcje, potężną i łatwą w użyciu manipulacją i konwersją dokumentów API dla platformy C#. Otwarte
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Menedżer pakietów, wyszukaj
 Aspose.3D 
 I zainstaluj. Możesz także użyć następującego polecenia z Konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Menedżer pakietów Console Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować GLTF na HTML za pośrednictwem C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programiści mogą łatwo załadować i przekonwertować GLTF plików na HTML w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik GLTF przez konstruktora klasy Scene1. Utwórz instancję AmfSaveOptions1. Zestaw HTML specyficznych właściwości dla zaawansowanej konwersji1. Zadzwoń do metody Scene.Save1. Podaj ścieżkę wyjściową z rozszerzeniem i obiektem pliku HTML Html5SaveOptions1. Sprawdź wynikowy plik HTML przy określonej ścieżce
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu konwersji .NET upewnij się, że masz następujące warunki wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z .NET Framework, .NET Core, Mono.- Środowisko programistyczne, takie jak Microsoft Visual Studio.- Aspose.3D for .NET DLL odwołuje się do Twojego projektu.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ten przykładowy kod pokazuje konwersję od GLTF do HTML C#" offSpacer="" %}}

```cs
// Załaduj GLTF w obiekcie Scene 
var document = new Aspose.ThreeD.Scene("template.gltf");
// Utwórz instancję Html5SaveOptions 
var options = new Aspose.ThreeD.Formats.Html5SaveOptions();
// Zapisz GLTF jako HTML 
document.Save("output.html", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Darmowa aplikacja do konwersji GLTF na HTML" sectionDescription="Sprawdź nasze dema na żywo [Konwersja GLTF do HTML](https://products.aspose.app/3d/conversion/gltf-to-html) Z następującymi korzyściami." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie trzeba niczego pobierać ani konfigurować." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie trzeba pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik GLTF i naciśnij przycisk „ Konwertuj ”." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Natychmiast otrzymasz link do pobrania dla wynikowego pliku HTML." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Biblioteka przetwarzania plików 3D do manipulowania plikami 3D bez oprogramowania do modelowania i renderowania. 3D API obsługuje Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formatów plików i więcej. Programiści mogą łatwo tworzyć, czytać, konwertować, modyfikować i kontrolować treść 3D formatów dokumentów.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (GL Transmission Format) to 3D format pliku, który przechowuje 3D informacje o modelu w formacie JSON. Zastosowanie JSON minimalizuje zarówno rozmiar 3D zasobów, jak i przetwarzanie w czasie wykonywania potrzebne do rozpakowania i wykorzystania tych zasobów. Został przyjęty do wydajnego przesyłania i ładowania 3D scen i modeli przez aplikacje. glTF został opracowany przez Khronos Group 3D Formats Working Group i jest również opisywany przez jej twórców jako JPEG 3D. Format definiuje rozszerzalny, powszechny format publikacji dla 3D narzędzi i usług treści, który usprawnia przepływy pracy w zakresie tworzenia i umożliwia interoperacyjne wykorzystanie treści w całej branży. Intencją stworzenia formatu pliku glTF było zdefiniowanie rozszerzalnego, powszechnego formatu publikacji dla 3D narzędzi i usług treści, który powinien usprawnić przepływy pracy w zakresie tworzenia i umożliwić interoperacyjne wykorzystanie treści w całej branży. Minimalizuje przetwarzanie w czasie wykonywania przez aplikacje korzystające z WebGL i innych interfejsów API.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="html" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (Hyper Text Markup Language) to rozszerzenie dla stron internetowych utworzonych do wyświetlania w przeglądarkach. Znany jako język sieci, HTML ewoluował wraz z wymaganiami dotyczącymi nowych wymagań informacyjnych, które mają być wyświetlane jako część stron internetowych. Najnowszy wariant jest znany jako HTML 5, co daje dużą elastyczność w pracy z językiem. HTML strony są odbierane z serwera, gdzie są one hostowane, lub mogą być ładowane również z systemu lokalnego. Każda strona HTML składa się z HTML elementów, takich jak formularze, tekst, obrazy, animacje, linki itp. Elementy te są reprezentowane przez znaczniki, takie jak img, a, p i kilka innych, w których każdy znacznik ma początek i koniec. Może również osadzić aplikacje napisane w językach skryptowych, takich jak JavaScript i Arkusze stylów (CSS), w celu ogólnej reprezentacji układu.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}