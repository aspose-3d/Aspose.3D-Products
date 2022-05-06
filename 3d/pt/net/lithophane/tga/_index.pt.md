﻿---
title: Crie seu litofane a partir de formatos de arquivo TGA via .NET 
weight: 830
url: /pt/net/lithophane/tga/ 
description: C# código-fonte para carregar, renderizar e criar seu litofane para documentos TGA em .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Crie seu Lithophane para TGA via C#" h2="Crie seus próprios aplicativos .NET para criar seu litofane para arquivos TGA usando APIs do lado do servidor." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TGA" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="TGA" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TGA" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como criar seu arquivo de litofane para TGA usando C#" %}}

 Para criar seu arquivo de litofane para TGA, usaremos
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API que é uma plataforma rica em recursos, poderosa e fácil de usar API para C# a ser usada para criar seu litofane. Aberto
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para criar seu litofane para TGA via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D torna mais fácil para os desenvolvedores criar seu litofane para o arquivo TGA com apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

- Crie alguns novos parâmetros e crie um objeto Mesh- Execute operações computacionais em objetos Mesh- O arquivo TGA carrega a cena 3d através da classe Mesh- Chame o método Scene.Save com o objeto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET é compatível com todos os principais sistemas operacionais. Apenas certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com .NET Framework, .NET Core, Mono- Ambiente de desenvolvimento como o Microsoft Visual Studio- Aspose.3D for .NET referenciado em seu projeto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para criar seu litofane para TGA" offSpacer="" %}}

```cs

//A imagem original que precisa ser carregada e a saída do arquivo 3D após salvar
    string file = "template.tga";
    string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

//Crie alguns novos parâmetros
    var td= TextureData.FromFile(file);
    const float nozzleSize = 0.9f;//0,2 mm
    const float layerHeight = 0.2f;
    var grayscale = ToGrayscale(td);
    const float width = 120.0f;//largura da tela é 200.0mm
    float height = width / td.Width * td.Height;
    float thickness = 10.0f;//10 mm de espessura
    float layers = thickness / layerHeight;
    int widthSegs = (int)Math.Floor(width / nozzleSize);
    int heightSegs = (int)Math.Floor(height / nozzleSize);

//Execute operações computacionais em objetos Mesh
    var mesh = new Mesh();
    for (int y = 0; y < heightSegs; y++)
    {
        float dy = (float)y / heightSegs;
        for (int x = 0; x < widthSegs; x++)
        {
            float dx = (float)x / widthSegs;
            float gray = Sample(grayscale, td.Width, td.Height, dx, dy);
            float v = (1 - gray) * thickness;
            mesh.ControlPoints.Add(new Vector4(dx * width, dy * height, v));
        }
    }


    for (int y = 0; y < heightSegs - 1; y++)
    {
        int row = (y * heightSegs);
        int ptr = row;
        for (int x = 0; x < widthSegs - 1; x++)
        {
            mesh.CreatePolygon(ptr, ptr + widthSegs, ptr + 1);
            mesh.CreatePolygon(ptr + 1, ptr + widthSegs, ptr + widthSegs + 1);
            ptr++;
        }
    }

//Gere cena 3d e salve objetos
    var scene = new Scene(mesh);
    scene.Save(output, FileFormat.FBX7400ASCII);

//O método de amostra a ser chamado
    static float Sample(float[,] data, int w, int h, float x, float y)
    {
        return data[(int)(x * w), (int)(y * h)];
    }

//Método ToGrayscale para chamar
    static float[,] ToGrayscale(TextureData td)
    {
        var ret = new float[td.Width, td.Height];
        var stride = td.Stride;
        var data = td.Data;
        var bytesPerPixel = td.BytesPerPixel;
        for (int y = 0; y < td.Height; y++)
        {
            int ptr = y * stride;
            for (int x = 0; x < td.Width; x++)
            {
                var v = (data[ptr] * 0.21f + data[ptr + 1] * 0.72f + data[ptr + 2] * 0.07f) / 255.0f;
                ret[x, y] = v;
                ptr += bytesPerPixel;
            }
        }
        return ret;
    }

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.3D for .NET API" %}}

 Aspose.3D é um CAD e Gameware API para carregar, modificar e converter arquivos 3D. API é independente e não requer nenhum software de modelagem ou renderização de 3D. Pode-se facilmente usar API para Discreet3DS, WavefrontOBJ, STL (ASCII, Binário), Universal3D, FBX (ASCII, Binário), Collada, glTF, PLY, GLB, DirectX e mais formatos. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicativo gratuito para criar seu litofane para TGA" sectionDescription="Confira nossas demonstrações ao vivo para [Litofano TGA](https://products.aspose.app/3d/lithophane/tga) com os seguintes benefícios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever ou compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do arquivo TGA e clicar no botão \"lithophane\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Baixe o arquivo TGA do link, se necessário" >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outro aplicativo suportado para criar seu litofane para formatos" subTitle="Usando C#, também é possível criar seu litofane para muitos outros formatos de arquivo, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/jpeg/" name="JPEG" description="Grupo Conjunto de Especialistas em Fotografia" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/png/" name="PNG" description="Gráficos Portáteis de Rede" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/jpg/" name="JPG" description="Grupo Conjunto de Especialistas em Fotografia" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/bmp/" name="BMP" description="Bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/gif/" name="GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/tiff/" name="TIFF" description="Formato de arquivo de imagem marcado" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}