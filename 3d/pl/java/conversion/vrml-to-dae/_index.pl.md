﻿---
title: Konwertuj VRML na DAE przez Java 
weight: 3160
url: /pl/java/conversion/vrml-to-dae/ 
description: Przykładowy kod konwersji Java dla formatu VRML na plik DAE. Użyj tego przykładowego kodu, aby przekonwertować VRML na DAE w dowolnej aplikacji internetowej lub na komputerze Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj VRML na DAE przez Java" h2="Konwersja z VRML do DAE przy użyciu biblioteki Java bez żadnego oprogramowania do modelowania 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="DAE" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="VRML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować VRML na DAE za pomocą Java" %}}

 Aby wyrenderować VRML do DAE, użyjemy
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API, która jest bogatą w funkcje, wydajną i łatwą w użyciu platformą konwersji API for Java. Możesz pobrać jego najnowszą wersję bezpośrednio z
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować VRML na DAE przez Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programiści mogą łatwo przekonwertować plik VRML na DAE w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik VRML za pomocą konstruktora klasy Scene1. Utwórz instancję DaeSaveOptions1. Ustaw DAE określone właściwości dla zaawansowanej konwersji1. Zadzwoń do metody Scene.save1. Przekaż ścieżkę wyjściową z rozszerzeniem pliku DAE i obiektem DaeSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu konwersji Java upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.- Pobierz najnowszą wersję Aspose.3D for Java bezpośrednio od firmy Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="VRML do DAE Java Kodu źródła konwersji" offSpacer="" %}}

```cs
// załaduj VRML do obiektu sceny 
Scene document = new Scene("template.vrml");
// utwórz instancję DaeSaveOptions 
DaeSaveOptions options = new DaeSaveOptions();
// zapisz VRML jako DAE 
document.save("output.dae", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Od VRML do DAE demonstracji konwersji na żywo" sectionDescription="[Konwertuj VRML na DAE](https://products.aspose.app/3d/conversion/vrml-to-dae) teraz, odwiedzając naszą stronę Live Demos. Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik VRML, zostanie on natychmiast przekonwertowany na DAE." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Otrzymasz link do pobrania." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Biblioteka manipulacji scenami" %}}

 Aspose.3D to CAD i Gameware API do ładowania, modyfikowania i konwertowania plików 3D. API jest samodzielny i nie wymaga żadnego 3D oprogramowania do modelowania ani renderowania. Można łatwo użyć API dla Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX i inne formaty. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="VRML" readMoreLink="https://docs.fileformat.com/3d/vrml/" >}}

Język modelowania rzeczywistości wirtualnej (VRML) to format pliku do reprezentacji interaktywnych obiektów świata 3D w sieci WWW (www). Znajduje zastosowanie w tworzeniu trójwymiarowych reprezentacji złożonych scen, takich jak ilustracje, definicje i prezentacje rzeczywistości wirtualnej. Format został zastąpiony przez X3D. Wiele aplikacji do modelowania 3D może zapisywać obiekty i sceny w formacie VRML.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}

Plik DAE to format pliku Digital Asset Exchange używany do wymiany danych między interaktywnymi aplikacjami 3D. Ten format pliku jest oparty na schemacie XML COLLADA (COLLAborative Design Activity), który jest otwartym standardowym schematem XML służącym do wymiany zasobów cyfrowych między aplikacjami graficznymi. Została przyjęta przez ISO jako publicznie dostępna specyfikacja, ISO/pAS 17506.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować VRML na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-3ds/" name="VRML DO 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-amf/" name="VRML DO AMF" description="Format wytwarzania przyrostowego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-ase/" name="VRML DO ASE" description="Plik animacji 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-fbx/" name="VRML DO FBX" description="3D Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-gltf/" name="VRML DO GLTF" description="Format transmisji GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-html/" name="VRML DO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-obj/" name="VRML DO OBJ" description="3D Format pliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-ply/" name="VRML DO PLY" description="Format pliku wielokąta" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-rvm/" name="VRML DO RVM" description="Model projektowy zakładu AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-stl/" name="VRML DO STL" description="Wymienna 3D geometria powierzchni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-u3d/" name="VRML DO U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}