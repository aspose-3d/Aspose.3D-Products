﻿---
title: Visualizar formatos de arquivo DXF por meio de .NET 
weight: 3270
url: /pt/net/viewer/dxf/ 
description: C# código-fonte para carregar, renderizar e exibir DXF documentos em .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="DXF Visualizador de arquivos for .NET" h2="Renderize arquivos DXF sem nenhum software de modelagem e renderização 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DXF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Como visualizar o arquivo DXF usando C#" %}}

 Para visualizar o arquivo DXF, usaremos
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API que é uma plataforma rica em recursos, poderosa e fácil de usar API para C# para ser usada com qualquer Visualizador. Aberto
 [NuGetName](https://www.nuget.org/packages/aspose.3d) 
 gerenciador de pacotes, procure
 **Aspose.3D** 
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando do console do gerenciador de pacotes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para visualizar DXF via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D facilita para os desenvolvedores a visualização do arquivo DXF com apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregar arquivo DXF por meio do construtor da classe Scene1. Crie uma instância de Html5SaveOptions1. Definir propriedades para formatação avançada1. Chame o método Scene.Save com objeto de Html5SaveOptions1. Verifique o arquivo HTML resultante no navegador padrão
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET é compatível com todos os principais sistemas operacionais. Apenas certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com .NET Framework, .NET Core, Mono- Ambiente de desenvolvimento como o Microsoft Visual Studio- Aspose.3D for .NET referenciado em seu projeto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para visualizar DXF" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// carregar DXF cena por meio de uma instância de Scene
var scene = new ThreeD.Scene("template.dxf");
// crie um objeto de Html5SaveOptions e defina propriedades para formatação
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // desligue a grade
    ShowGrid = false,
    // desligue a interface do usuário
    ShowUI = false
};

// salve 3D cena como HTML5
scene.Save(output, options);
// carregue o resultado HTML no navegador padrão
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.3D for .NET API" %}}

 Aspose.3D é um CAD e Gameware API para carregar, modificar e converter arquivos 3D. API é independente e não requer nenhum software de modelagem ou renderização de 3D. Pode-se facilmente usar API para Discreet3DS, WavefrontOBJ, STL (ASCII, Binário), Universal3D, FBX (ASCII, Binário), Collada, glTF, PLY, GLB, DirectX e mais formatos. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicativo gratuito para visualização DXF" sectionDescription="Confira nossas demonstrações ao vivo para [Visualizar DXF](https://products.aspose.app/3d/viewer/dxf) com os seguintes benefícios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever ou compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer upload de DXF arquivo e clicar no botão \"Visualizar\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Baixe o arquivo DXF do link, se necessário" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}
DXF, Drawing Interchange Format ou Drawing Exchange Format, é uma representação de dados marcados do arquivo de desenho do AutoCAD. Cada elemento no arquivo tem um número inteiro de prefixo chamado código de grupo. Esse código de grupo na verdade representa o elemento que segue e indica o significado de um elemento de dados para um determinado tipo de objeto. DXF possibilita representar quase todas as informações especificadas pelo usuário em um arquivo de desenho. O formato de arquivo DXF foi desenvolvido pela Autodesk como formato de arquivo de dados CAD para interoperabilidade de dados entre o AutoCAD e outros aplicativos. Assim, os dados podem ser importados de outros formatos para DXF para o AutoCAD de acordo com as especificações de interoperabilidade do formato de arquivo DXF.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de visualizador compatíveis" subTitle="Usando C#, também é possível visualizar muitos outros formatos de arquivo, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D Formato de fabricação" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Formato de Manufatura Aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="Arquivo de animação 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Troca de ativos digitais" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D Representação Binária de Arquivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="Formato de transmissão GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="Arquivo de Tesselação de Júpiter" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D Formato de arquivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Formato de arquivo de polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="Modelo de Projeto de Planta AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="Geometria de superfície 3D intercambiável" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Linguagem de modelagem de realidade virtual" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="X" description="Imagem do modelo DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP Formato de arquivamento" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}