﻿---
title: Gere nuvem de pontos para formatos de arquivo DRC via .NET 
weight: 830
url: /pt/net/point-cloud/drc/ 
description: C# código-fonte para carregar, renderizar e adicionar gerar nuvem de pontos a DRC documentos em .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Gere nuvem de pontos para DRC via C#" h2="Crie seus próprios aplicativos .NET para gerar nuvem de pontos para arquivos DRC usando APIs do lado do servidor." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DRC" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Como gerar nuvem de pontos para arquivo DRC usando C#" %}}

 Para gerar a nuvem de pontos para o arquivo DRC, usaremos
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API que é uma plataforma rica em recursos, poderosa e fácil de usar API para C# a ser usada com gerar nuvem de pontos. Aberto
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para gerar nuvem de pontos para DRC via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D facilita para os desenvolvedores gerar nuvem de pontos para o arquivo DRC com apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

- Carregar arquivo DRC por meio do construtor da classe Scene- Obter objeto pointcloud de Aspose.3D- Crie um objeto de transformação por meio do método EvaluateGlobalTransform- Gerar nuvem de pontos usando o método Merge- Chame o método Scene.Save com o objeto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET é compatível com todos os principais sistemas operacionais. Apenas certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com .NET Framework, .NET Core, Mono- Ambiente de desenvolvimento como o Microsoft Visual Studio- Aspose.3D for .NET referenciado em seu projeto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para gerar nuvem de pontos para DRC" offSpacer="" %}}

```cs

//O arquivo de origem que precisa gerar a nuvem de pontos
string file = "template.drc";

// crie uma instância de Scene
Scene scene = new Scene(file);

//Obtenha o objeto de nuvem de pontos de Aspose.3D e gere uma nuvem de pontos
var pc = new PointCloud();
scene.RootNode.Accept((Node n) =>
{
    if (n.Entities.Count > 0)
    {
        var transform = n.EvaluateGlobalTransform(true);
        foreach (var entity in n.Entities)
        {
            if (entity is Geometry g)
            {
                Merge(pc, g, transform);
            }
            else if (entity is IMeshConvertible mc)
            {
                var mesh = mc.ToMesh();
                Merge(pc, mesh, transform);
            }

        }
    }
    return true;
});

//Mesclar método para gerar nuvens de pontos
private void Merge(PointCloud pc, Geometry g, Matrix4 transform)
{
    var tmp = PointCloud.FromGeometry(g, 10);
    for (int i = 0; i < tmp.ControlPoints.Count; i++)
    {
        var pt = transform * tmp.ControlPoints[i];
        pc.ControlPoints.Add(pt);
    }
}

// crie uma instância de newScene
var newScene = new Scene(pc);

//Ao salvar, você precisa criar um objeto SaveOptions do formato de salvamento
string output=System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".ply";
PlySaveOptions ply = new PlySaveOptions();
ply.PointCloud = true;
newScene.Save(output,ply);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.3D for .NET API" %}}

 Aspose.3D é um CAD e Gameware API para carregar, modificar e converter arquivos 3D. API é independente e não requer nenhum software de modelagem ou renderização de 3D. Pode-se facilmente usar API para Discreet3DS, WavefrontOBJ, STL (ASCII, Binário), Universal3D, FBX (ASCII, Binário), Collada, glTF, PLY, GLB, DirectX e mais formatos. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicativo gratuito para gerar nuvem de pontos para DRC" sectionDescription="Confira nossas demonstrações ao vivo para [Nuvem de pontos 3DS](https://products.aspose.app/3d/point-cloud/drc) com os seguintes benefícios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever ou compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer upload de DRC arquivo e clicar no botão \"Gerar\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Baixe o arquivo DRC do link, se necessário" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
Google Draco Arquivo e formato de arquivo associado.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outro aplicativo compatível para gerar nuvem de pontos para formatos" subTitle="Usando C#, também é possível gerar nuvem de pontos para muitos outros formatos de arquivo, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3mf/" name="3MF" description="3D Formato de fabricação" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/amf/" name="AMF" description="Formato de Manufatura Aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/ase/" name="ASE" description="Arquivo de animação 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dae/" name="DAE" description="Troca de ativos digitais" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dxf/" name="DXF" description="Formato de intercâmbio de desenho" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3ds/" name="3DS" description="3D Formato de arquivo de malha do Studio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/fbx/" name="FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/glb/" name="GLB" description="3D Representação Binária de Arquivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/gltf/" name="GLTF" description="Formato de transmissão GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/jt/" name="JT" description="Arquivo de Tesselação de Júpiter" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/obj/" name="OBJ" description="3D Formato de arquivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/ply/" name="PLY" description="Formato de arquivo de polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/rvm/" name="RVM" description="Modelo de Projeto de Planta AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/stl/" name="STL" description="Geometria de superfície 3D intercambiável" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/vrml/" name="VRML" description="Linguagem de modelagem de realidade virtual" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/x/" name="X" description="Imagem do modelo DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usd/" name="USD" description="Descrição da cena universal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usdz/" name="USDZ" description="Arquivo Zip de Descrição de Cena Universal" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}