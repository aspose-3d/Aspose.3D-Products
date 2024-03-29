﻿---
title: Ajouter la vérification aveugle du filigrane aux formats de fichier USDZ via .NET 
weight: 830
url: /fr/net/verify-watermark/usdz/ 
description: C# code source pour charger, restituer et ajouter une vérification de filigrane aveugle à USDZ documents sur .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ajoutez la vérification aveugle du filigrane à USDZ via C#" h2="Créez vos propres applications .NET pour ajouter une vérification de filigrane aveugle aux fichiers USDZ à l\'aide d\'API côté serveur." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="USDZ" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="USDZ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Comment filigraner la vérification sur le fichier USDZ à l\'aide de C#" %}}

 Afin de filigraner le fichier de vérification USDZ, nous utiliserons
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API qui est une plate-forme riche en fonctionnalités, puissante et facile à utiliser API pour C# à utiliser avec n'importe quelle vérification de filigrane. Ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 gestionnaire de paquets, recherchez
 **Aspose.3D** 
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Commande de la console du gestionnaire de packages" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour ajouter la vérification aveugle du filigrane à USDZ via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D permet aux développeurs d'ajouter facilement une vérification de filigrane aveugle au fichier USDZ avec seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

- Charger le fichier USDZ via le constructeur de la classe Scene- Obtenir la classe de maillage de Aspose.3D- Ajouter un mot de passe à l'aide de la méthode DecodeWatermark de Aspose.3D- Appelez la méthode Scene.Save avec l'objet
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET est pris en charge sur tous les principaux systèmes d'exploitation. Assurez-vous simplement que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec .NET Framework, .NET Core, Mono- Environnement de développement comme Microsoft Visual Studio- Aspose.3D for .NET référencé dans votre projet
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code pour ajouter la vérification aveugle du filigrane à USDZ" offSpacer="" %}}

```cs

//Fichiers sources qui doivent être filigranés pour vérification
string file = "template.usdz";

// créer une instance de Scene
Scene scene = new Scene(file);
string text =null;

//Ajouter un mot de passe pour vérifier le filigrane par la méthode DecodeWatermark
try
{
    scene.RootNode.Accept((Node node) =>
    {
        var mesh = node.GetEntity<Mesh>();
        if (mesh != null)
        {
            text = Watermark.DecodeWatermark(mesh, "1234");
            if (text != null)
                return false;
            }
            return true;
    });
}
catch (UnauthorizedAccessException)
{
    return "Password error";
}

//Renvoie null si ce fichier n'a pas de filigrane, s'il y a un filigrane, renvoie le contenu du filigrane
return text;



```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="À propos de Aspose.3D for .NET API" %}}

 Aspose.3D est un CAD et un Gameware API pour charger, modifier et convertir des fichiers 3D. API est autonome et ne nécessite aucun logiciel de modélisation ou de rendu 3D. On peut facilement utiliser API pour Discreet3DS, WavefrontOBJ, STL (ASCII, Binaire), Universal3D, FBX (ASCII, Binaire), Collada, glTF, PLY, GLB, DirectX et d'autres formats. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

 {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Application gratuite pour ajouter la vérification aveugle du filigrane à USDZ" sectionDescription="Consultez nos démos en direct pour [Vérification du filigrane USDZ](https://products.aspose.app/3d/verify-watermark/usdz) avec les avantages suivants." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire ou de compiler du code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement le fichier USDZ et appuyez sur le bouton \"Filigrane\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Téléchargez le fichier USDZ à partir du lien, si nécessaire" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="USDZ" readMoreLink="https://docs.fileformat.com/3d/usdz/" >}}
Un fichier avec .usdz est une archive ZIP pour le format de fichier USD (Universal Scene Description) qui contient et proxies pour les fichiers d'autres formats intégrés dans l'archive.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autre application prise en charge pour ajouter une vérification de filigrane aveugle aux formats" subTitle="En utilisant C#, One peut également ajouter une vérification de filigrane aveugle à de nombreux autres formats de fichiers, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/3mf/" name="3MF" description="3D Format de fabrication" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/amf/" name="AMF" description="Format de fabrication additive" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/ase/" name="ASE" description="Fichier d\'animation 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/dae/" name="DAE" description="Échange d\'actifs numériques" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/dxf/" name="DXF" description="Format d\'échange de dessin" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/fbx/" name="FBX" description="Format 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/glb/" name="GLB" description="3D Représentation binaire du fichier" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/gltf/" name="GLTF" description="Format de transmission GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/jt/" name="JT" description="Fichier de tessellation Jupiter" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/obj/" name="OBJ" description="3D Format de fichier" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/ply/" name="PLY" description="Format de fichier polygone" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/rvm/" name="RVM" description="Modèle de conception d\'usine AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/stl/" name="STL" description="Géométrie de surface 3D interchangeable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/vrml/" name="VRML" description="Langage de modélisation de réalité virtuelle" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/x/" name="X" description="Image du modèle DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/usd/" name="USD" description="Description de la scène universelle" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/3ds/" name="3DS" description="3D Format de fichier Studio Mesh" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}