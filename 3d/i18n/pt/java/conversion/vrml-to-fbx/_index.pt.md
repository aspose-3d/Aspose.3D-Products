﻿---
title: Converter VRML para FBX via Java 
weight: 2570
url: /pt/java/conversion/vrml-to-fbx/ 
description: Amostra de Java código de conversão para VRML formato para FBX arquivo. Use este código de exemplo para converter VRML para FBX em qualquer aplicativo baseado na Web ou Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter VRML para FBX via Java" h2="Conversão de VRML para FBX usando Java biblioteca sem qualquer software de modelagem 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="VRML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Como converter VRML para FBX usando Java" %}}

 Para renderizar VRML a FBX, usaremos
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API que é uma plataforma de conversão API for Java}, poderosa e fácil de usar. Você pode baixar sua versão mais recente diretamente de
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 E instale-o dentro do seu projeto baseado em Maven adicionando as seguintes configurações ao pom.xml.

{{% blocks/products/pf/agp/code-block title="Repositório" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependência" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Passos para converter VRML para FBX via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programadores podem facilmente converter VRML arquivo para FBX em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregar VRML arquivo através do construtor da classe Scene1. Criar uma instância de FbxSaveOptions1. Definir FBX propriedades específicas para conversão avançada1. Chame o método Scene.save1. Passe o caminho de saída com FBX extensão de arquivo e objeto de FbxSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos do sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de conversão Java, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com Java Runtime Environment for JSP/JSF Application and Desktop Applications.- Obtenha a versão mais recente de Aspose.3D for Java diretamente do Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="VRML a FBX Java Código-fonte de conversão" offSpacer="" %}}

```cs
// Carregar o VRML em um objeto de cena 
Scene document = new Scene("template.vrml");
// Criar uma instância de FbxSaveOptions 
FbxSaveOptions options = new FbxSaveOptions();
// Salvar VRML como um FBX 
document.save("output.fbx", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="VRML a FBX Demos ao vivo de conversão" sectionDescription="[Converter VRML para FBX](https://products.aspose.app/3d/conversion/vrml-to-fbx) Agora mesmo visitando nosso site Live Demos. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever qualquer código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do seu arquivo VRML, ele será convertido instantaneamente para FBX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link de download." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Biblioteca de Manipulação de Cena" %}}

 Aspose.3D é um CAD e Gameware API para carregar, modificar e converter 3D arquivos. API é autônomo e não requer nenhum 3D software de modelagem ou renderização. Pode-se usar facilmente API para Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX e mais formatos. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="VRML" readMoreLink="https://docs.fileformat.com/3d/vrml/" >}}

A Virtual Reality Modeling Language (VRML) é um formato de arquivo para representação de 3D objetos mundiais interativos na World Wide Web (www). Ele encontra seu uso na criação de representações tridimensionais de cenas complexas, como ilustrações, definição e apresentações de realidade virtual. O formato foi substituído pelo X3D. Muitos 3D aplicativos de modelagem podem salvar objetos e cenas no formato VRML.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}

FBX, FilmBox, é um formato de arquivo 3D popular que foi originalmente desenvolvido por Kaydara para MotionBuilder. Foi adquirido pela Autodesk Inc em 2006 e agora é um dos principais formatos de troca 3D usados por muitas ferramentas 3D. FBX está disponível em formato de arquivo binário e ASCII. O formato foi estabelecido para fornecer interoperabilidade entre aplicativos de criação de conteúdo digital. Existem muitas ferramentas disponíveis para conversão de/para FBX formato de arquivo.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras Conversões Suportadas" subTitle="Você também pode converter VRML em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-3ds/" name="VRML PARA 3DS" description="3D Malha de estúdio DOS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-amf/" name="VRML PARA AMF" description="Formato de fabricação aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-ase/" name="VRML PARA ASE" description="Arquivo de Animação 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-dae/" name="VRML PARA DAE" description="Troca de ativos digitais" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-gltf/" name="VRML PARA GLTF" description="Formato de Transmissão GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-html/" name="VRML PARA HTML" description="Linguagem de marcação de texto hiper" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-obj/" name="VRML PARA OBJ" description="3D Formato de arquivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-ply/" name="VRML PARA PLY" description="Formato de arquivo de polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-rvm/" name="VRML PARA RVM" description="Modelo de Design de Planta AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-stl/" name="VRML PARA STL" description="Geometria de superfície permutável 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-u3d/" name="VRML PARA U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}