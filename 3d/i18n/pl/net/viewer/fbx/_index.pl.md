﻿---
title: Wyświetl FBX formatów plików za pośrednictwem .NET 
weight: 910
url: /pl/net/viewer/fbx/ 
description: C# kodu źródłowego do załadowania, renderowania i wyświetlania FBX dokumentów na .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="FBX Przeglądarka plików for .NET" h2="Renderuj FBX plików bez oprogramowania do modelowania i renderowania 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak wyświetlić plik FBX za pomocą C#" %}}

 Aby wyświetlić plik FBX, użyjemy
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, która jest platformą bogatą w funkcje, wydajną i łatwą w użyciu API dla C# do użytku z dowolną przeglądarką. Otwarte
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Menedżer pakietów, wyszukaj
 **Aspose.3D** 
 I zainstaluj. Możesz także użyć następującego polecenia z Konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Menedżer pakietów Console Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby wyświetlić FBX za pośrednictwem C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D ułatwia programistom przeglądanie pliku FBX za pomocą zaledwie kilku linii kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik FBX przez konstruktora klasy Scene1. Utwórz instancję Html5SaveOptions1. Ustawianie właściwości zaawansowanego formatowania1. Zadzwoń do sceny. Zapisz metodę z obiektem Html5SaveOptions1. Sprawdź wynikowy plik HTML w domyślnej przeglądarce
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET jest obsługiwany we wszystkich głównych systemach operacyjnych. Tylko upewnij się, że masz następujące warunki wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z .NET Framework, .NET Core, Mono- Środowisko programistyczne, takie jak Microsoft Visual Studio- Aspose.3D for .NET wymienione w Twoim projekcie
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kodu, aby wyświetlić FBX" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// Załaduj FBX sceny za pomocą instancji Scene
var scene = new ThreeD.Scene("template.fbx");
// Utwórz obiekt Html5SaveOptions i ustaw właściwości do formatowania
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // Wyłącz siatkę
    ShowGrid = false,
    // Wyłącz interfejs użytkownika
    ShowUI = false
};

// Zapisz 3D sceny jako HTML5
scene.Save(output, options);
// Obciążenie wynikowe HTML w domyślnej przeglądarce
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Około Aspose.3D for .NET API" %}}

 Aspose.3D to CAD i Gameware API do ładowania, modyfikowania i konwertowania plików 3D. API jest samodzielny i nie wymaga żadnego 3D oprogramowania do modelowania lub renderowania. Można z łatwością użyć API dla Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX i więcej formatów. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Darmowa aplikacja do przeglądania FBX" sectionDescription="Sprawdź nasze dema na żywo [Zobacz FBX](https://products.aspose.app/3d/viewer/fbx) Z następującymi korzyściami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania ani konfigurowania czegokolwiek" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie trzeba pisać ani kompilować kodu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik FBX i naciśnij przycisk „ Widok”" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Pobierz plik FBX z linku, jeśli jest to wymagane" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, to popularny format pliku 3D, który został pierwotnie opracowany przez Kaydara dla MotionBuilder. Został przejęty przez Autodesk Inc w 2006 roku i jest obecnie jednym z głównych formatów wymiany 3D używanych przez wiele 3D narzędzi. FBX jest dostępny zarówno w formacie binarnym, jak i ASCII. Format został ustanowiony w celu zapewnienia interoperacyjności między aplikacjami do tworzenia treści cyfrowych. Dostępnych jest wiele narzędzi do konwersji z/do formatu pliku FBX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty przeglądarki" subTitle="Korzystając z C#, można również wyświetlić wiele innych formatów plików, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D Format produkcji" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Format wytwarzania dodatków" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="Plik animacji 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Cyfrowa wymiana aktywów" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="Rysowanie formatu wymiany" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D Reprezentacja binarna pliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="GL Format transmisji" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="Plik teselacji Jupitera" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="Format pliku 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Format pliku Polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="Model projektowy zakładu AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="Wymienna 3D geometria powierzchni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Język modelowania wirtualnej rzeczywistości" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="X" description="Obraz modelu DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="Format archiwizacji ZIP" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}