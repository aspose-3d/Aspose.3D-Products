﻿---
title: Converter GLTF em FBX via Java 
weight: 1420
url: /pt/java/conversion/gltf-to-fbx/ 
description: Exemplo de código de conversão Java para o formato GLTF para arquivo FBX. Use este código de exemplo para converter GLTF em FBX em qualquer aplicativo baseado na Web ou Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter GLTF em FBX via Java" h2="conversão de GLTF para FBX usando a biblioteca Java sem nenhum software de modelagem 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Como converter GLTF em FBX usando Java" %}}

 Para renderizar GLTF para FBX, usaremos
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API que é uma plataforma de conversão API for Java rica em recursos, poderosa e fácil de usar. Você pode baixar sua versão mais recente diretamente de
 [Especialista](https://repository.aspose.com/3d/) 
 e instale-o em seu projeto baseado em Maven adicionando as seguintes configurações ao pom.xml.

{{% blocks/products/pf/agp/code-block title="Repositório" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repositório.aspose.com/repo/</url>
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter GLTF em FBX via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Os programadores Java podem converter facilmente o arquivo GLTF para FBX em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregar arquivo GLTF por meio do construtor da classe Scene1. Crie uma instância de FbxSaveOptions1. Defina FBX propriedades específicas para conversão avançada1. Chame o método Scene.save1. Passe o caminho de saída com extensão de arquivo FBX e objeto de FbxSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de conversão Java, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com Java Runtime Environment para aplicativos JSP/JSF e aplicativos de desktop.- Obtenha a versão mais recente do Aspose.3D for Java diretamente do Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="GLTF para FBX Java Código-fonte de conversão" offSpacer="" %}}

```cs
// carregue o GLTF em um objeto de Scene 
Scene document = new Scene("template.gltf");
// crie uma instância de FbxSaveOptions 
FbxSaveOptions options = new FbxSaveOptions();
// salve GLTF como um FBX 
document.save("output.fbx", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Demos de conversão ao vivo de GLTF para FBX" sectionDescription="[Converter GLTF em FBX](https://products.aspose.app/3d/conversion/gltf-to-fbx) agora mesmo visitando nosso site de Demonstrações ao Vivo. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta enviar seu arquivo GLTF, ele será convertido instantaneamente para FBX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link para download." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Biblioteca de manipulação de cena" %}}

 Aspose.3D é um CAD e Gameware API para carregar, modificar e converter arquivos 3D. API é independente e não requer nenhum software de modelagem ou renderização de 3D. Pode-se facilmente usar API para Discreet3DS, WavefrontOBJ, STL (ASCII, Binário), Universal3D, FBX (ASCII, Binário), Collada, glTF, PLY, GLB, DirectX e mais formatos. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF (GL Transmission Format) é um formato de arquivo 3D que armazena informações de modelo 3D no formato JSON. O uso de JSON minimiza o tamanho dos ativos 3D e o processamento em tempo de execução necessário para descompactar e usar esses ativos. Foi adotado para a transmissão e carregamento eficiente de 3D cenas e modelos por aplicativos. glTF foi desenvolvido pelo Khronos Group 3D Formats Working Group e também é descrito como JPEG de 3D por seus criadores. O formato define um formato de publicação extensível e comum para 3D ferramentas e serviços de conteúdo que simplificam os fluxos de trabalho de autoria e permitem o uso interoperável de conteúdo em todo o setor. A intenção por trás da criação do formato de arquivo glTF foi definir um formato de publicação extensível e comum para ferramentas e serviços de conteúdo 3D que agilizem os fluxos de trabalho de autoria e permitam o uso interoperável de conteúdo em todo o setor. Ele minimiza o processamento em tempo de execução por aplicativos usando WebGL e outras APIs.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}

FBX, FilmBox, é um formato de arquivo 3D popular que foi originalmente desenvolvido por Kaydara para MotionBuilder. Foi adquirido pela Autodesk Inc em 2006 e agora é um dos principais 3D formatos de troca usados por muitas ferramentas 3D. FBX está disponível em formato de arquivo binário e ASCII. O formato foi estabelecido para fornecer interoperabilidade entre aplicativos de criação de conteúdo digital. Existem muitas ferramentas disponíveis para conversão de/para o formato de arquivo FBX.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter GLTF em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-3ds/" name="GLTF PARA 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-amf/" name="GLTF PARA AMF" description="Formato de Manufatura Aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-ase/" name="GLTF PARA ASE" description="Arquivo de animação 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-dae/" name="GLTF PARA DAE" description="Troca de ativos digitais" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-html/" name="GLTF PARA HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-obj/" name="GLTF PARA OBJ" description="3D Formato de arquivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-ply/" name="GLTF PARA PLY" description="Formato de arquivo de polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-rvm/" name="GLTF PARA RVM" description="Modelo de Projeto de Planta AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-stl/" name="GLTF PARA STL" description="Geometria de superfície 3D intercambiável" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-u3d/" name="GLTF PARA U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}