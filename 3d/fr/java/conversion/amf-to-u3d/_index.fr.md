﻿---
title: Convertir AMF en U3D via Java 
weight: 3380
url: /fr/java/conversion/amf-to-u3d/ 
description: Exemple de code de conversion Java pour le format AMF vers le fichier U3D. Utilisez cet exemple de code pour convertir AMF en U3D dans n'importe quelle application Web ou de bureau Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir AMF en U3D via Java" h2="Conversion AMF en U3D à l\'aide de la bibliothèque Java sans aucun logiciel de modélisation 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="AMF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Comment convertir AMF en U3D en utilisant Java" %}}

 Afin de rendre AMF à U3D, nous utiliserons
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API qui est une plate-forme de conversion riche en fonctionnalités, puissante et facile à utiliser API for Java. Vous pouvez télécharger sa dernière version directement depuis
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
 et installez-le dans votre projet basé sur Maven en ajoutant les configurations suivantes au fichier pom.xml.

{{% blocks/products/pf/agp/code-block title="Dépôt" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dépendance" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir AMF en U3D via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Les programmeurs Java peuvent facilement convertir le fichier AMF en U3D en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

1. Charger le fichier AMF via le constructeur de la classe Scene1. Créer une instance de U3dSaveOptions1. Définir U3D propriétés spécifiques pour la conversion avancée1. Appelez la méthode Scene.save1. Passez le chemin de sortie avec l'extension de fichier U3D et l'objet de U3dSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Avant d'exécuter le code de conversion Java, assurez-vous que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec Java Runtime Environment for JSP/JSF Application and Desktop Applications.- Obtenez la dernière version de Aspose.3D for Java directement auprès de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="AMF à U3D Java code source des conversions" offSpacer="" %}}

```cs
// charger le AMF dans un objet de Scene 
Scene document = new Scene("template.amf");
// créer une instance de U3dSaveOptions 
U3dSaveOptions options = new U3dSaveOptions();
// enregistrer AMF en tant que U3D 
document.save("output.u3d", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="AMF à U3D démos en direct de conversion" sectionDescription="[Convertir AMF en U3D](https://products.aspose.app/3d/conversion/amf-to-u3d) dès maintenant en visitant notre site Web Live Demos. La démonstration en direct présente les avantages suivants" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire de code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement votre fichier AMF, il sera converti instantanément en U3D." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Vous obtiendrez le lien de téléchargement." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Bibliothèque de manipulation de scènes" %}}

 Aspose.3D est un CAD et un Gameware API pour charger, modifier et convertir des fichiers 3D. API est autonome et ne nécessite aucun logiciel de modélisation ou de rendu 3D. On peut facilement utiliser API pour Discreet3DS, WavefrontOBJ, STL (ASCII, Binaire), Universal3D, FBX (ASCII, Binaire), Collada, glTF, PLY, GLB, DirectX et d'autres formats. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="AMF" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}

Le format de fichier de fabrication additive (AMF) définit des normes ouvertes pour la description des objets afin d'être utilisés par des processus de fabrication additive tels que 3D l'impression. Les programmes CAD utilisent le format de fichier AMF en utilisant des informations telles que la géométrie, la couleur et le matériau des objets. AMF est différent du format STL car le latéral ne prend pas en charge la couleur, les matériaux, les treillis et les constellations.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}

U3D (Universal 3D) est un format de fichier compressé et une structure de données pour l'infographie 3D. Il contient 3D des informations sur le modèle telles que les maillages triangulaires, l'éclairage, l'ombrage, les données de mouvement, les lignes et les points avec couleur et structure. Le format a été accepté en tant que norme ECMA-363 en août 2005. 3D PDF documents prennent en charge l'incorporation de U3D objets et peuvent être visualisés dans Adobe Reader (version 7 et ultérieure). Le format U3D a été développé en gardant à l'esprit l'objectif d'établir une norme universelle pour le stockage et l'échange de données tridimensionnelles. Cependant, le format trouve sa principale utilisation dans l'encodage pour 3D PDF plutôt que d'être utilisé comme format d'échange. Acrobat 3D convertit un type de fichier 3D pris en charge en U3D ou PRC lors de la conversion en PDF.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir AMF dans de nombreux autres formats de fichiers, dont quelques-uns sont répertoriés ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-3ds/" name="AMF À 3DS" description="3D Maillage Studio DOS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-dae/" name="AMF À DAE" description="Échange d\'actifs numériques" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-fbx/" name="AMF À FBX" description="Format 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-gltf/" name="AMF À GLTF" description="Format de transmission GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-html/" name="AMF À HTML" description="Langage Signalétique Hyper Text" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-obj/" name="AMF À OBJ" description="3D Format de fichier" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-ply/" name="AMF À PLY" description="Format de fichier polygone" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-rvm/" name="AMF À RVM" description="Modèle de conception d\'usine AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-stl/" name="AMF À STL" description="Géométrie de surface 3D interchangeable" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}