﻿---
title: Konwertuj DRC na GLTF przez Java 
url: /pl/java/conversion/drc-to-gltf/ 
description: Przykładowy kod konwersji Java dla formatu DRC na plik GLTF. Użyj tego przykładowego kodu, aby przekonwertować DRC na GLTF w dowolnej aplikacji internetowej lub na komputerze Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj DRC na GLTF przez Java" h2="Konwersja z DRC do GLTF przy użyciu biblioteki Java bez żadnego oprogramowania do modelowania 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować DRC na GLTF za pomocą Java" %}}

 Aby wyrenderować DRC do GLTF, użyjemy
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API, która jest bogatą w funkcje, wydajną i łatwą w użyciu platformą konwersji API for Java. Możesz pobrać jego najnowszą wersję bezpośrednio z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 i zainstaluj go w swoim projekcie opartym na Maven, dodając następujące konfiguracje do pom.xml.

{{% blocks/products/pf/agp/code-block title="Magazyn" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zależność" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować DRC na GLTF przez Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programiści mogą łatwo przekonwertować plik DRC na GLTF w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik DRC za pomocą konstruktora klasy Scene1. Utwórz instancję GltfSaveOptions1. Ustaw GLTF określone właściwości dla zaawansowanej konwersji1. Zadzwoń do metody Scene.save1. Przekaż ścieżkę wyjściową z rozszerzeniem pliku GLTF i obiektem GltfSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu konwersji Java upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.- Pobierz najnowszą wersję Aspose.3D for Java bezpośrednio od firmy Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DRC do GLTF Java Kodu źródła konwersji" offSpacer="" %}}

```cs
// załaduj DRC do obiektu sceny 
Scene document = new Scene("template.drc");
// utwórz instancję GltfSaveOptions 
AmfSaveOptions options = new GltfSaveOptions();
// zapisz DRC jako GLTF 
document.save("output.gltf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Od DRC do GLTF demonstracji konwersji na żywo" sectionDescription="[Konwertuj DRC na GLTF](https://products.aspose.app/3d/conversion/drc-to-gltf) teraz, odwiedzając naszą stronę Live Demos. Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik DRC, zostanie on natychmiast przekonwertowany na GLTF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Otrzymasz link do pobrania." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Biblioteka manipulacji scenami" %}}

 Aspose.3D to CAD i Gameware API do ładowania, modyfikowania i konwertowania plików 3D. API jest samodzielny i nie wymaga żadnego 3D oprogramowania do modelowania ani renderowania. Można łatwo użyć API dla Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX i inne formaty. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}

Plik z rozszerzeniem .drc to skompresowany format pliku 3D utworzony za pomocą biblioteki Google Draco. Google oferuje Draco jako bibliotekę open source do kompresji i dekompresji 3D siatek geometrycznych i chmur punktów oraz poprawia przechowywanie i przesyłanie 3D grafik. Koduje dane wejściowe i zapisuje je jako plik .drc. Po stronie odbierającej API odczytuje pliki .drc i może je wyprowadzać jako pliki PLY lub OBJ. Skompresowany plik wyjściowy umożliwia użytkownikom szybsze pobieranie aplikacji i zapewnia szybkie ładowanie 3D grafik w przeglądarkach.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF (GL Transmission Format) to format pliku 3D, który przechowuje informacje o modelu 3D w formacie JSON. Użycie JSON minimalizuje zarówno rozmiar 3D zasobów, jak i przetwarzanie w czasie wykonywania potrzebne do rozpakowania i używania tych zasobów. Został przystosowany do wydajnej transmisji i ładowania 3D scen i modeli przez aplikacje. glTF został opracowany przez grupę roboczą ds. formatów Khronos Group 3D i jest również określany jako JPEG 3D przez jego twórców. Format definiuje rozszerzalny, wspólny format publikowania dla 3D narzędzi i usług dotyczących treści, który usprawnia przepływy pracy związane z tworzeniem i umożliwia interoperacyjne korzystanie z treści w całej branży. Intencją stworzenia formatu pliku glTF było zdefiniowanie rozszerzalnego, wspólnego formatu publikowania dla 3D narzędzi i usług dotyczących treści, które powinny usprawnić przepływy pracy związane z tworzeniem treści i umożliwić interoperacyjne korzystanie z treści w całej branży. Minimalizuje przetwarzanie w czasie wykonywania przez aplikacje korzystające z WebGL i innych interfejsów API.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}