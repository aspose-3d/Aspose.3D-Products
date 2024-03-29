﻿---
title: Vytvořte si Lithophane z formátů souborů JPG prostřednictvím .NET 
weight: 830
url: /cs/net/lithophane/jpg/ 
description: C# zdrojový kód k načtení, vykreslení a vytvoření dokumentů typu lithophane to JPG v .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Vytvořte svůj Lithophane do JPG prostřednictvím C#" h2="Sestavte si své vlastní aplikace .NET a vytvořte si soubory lithophane to JPG pomocí rozhraní API na straně serveru." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPG" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JPG" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Jak vytvořit soubor Lithophane do JPG pomocí C#" %}}

 Abychom vytvořili váš litophane to JPG soubor, použijeme
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, což je funkčně bohatá, výkonná a snadno použitelná platforma API pro C#, kterou lze použít při vytváření litofánu. Otevřeno
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 správce balíčků, vyhledejte
 **Aspose.3D** 
 a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly Správce balíčků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky k vytvoření Lithophane do JPG prostřednictvím C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D usnadňuje vývojářům vytvořit váš litophane do souboru JPG pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

- Vytvořte nějaké nové parametry a vytvořte objekt Mesh- Provádějte výpočetní operace s objekty Mesh- Soubor JPG načte 3D scénu prostřednictvím třídy Mesh- Zavolejte metodu Scene.Save s objektem
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET je podporováno ve všech hlavních operačních systémech. Jen se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s .NET Framework, .NET Core, Mono- Vývojové prostředí jako Microsoft Visual Studio- Aspose.3D for .NET odkazované ve vašem projektu
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód k vytvoření Lithophane do JPG" offSpacer="" %}}

```cs

//Původní obrázek, který je třeba nahrát, a výstup 3D souboru po uložení
    string file = "template.jpg";
    string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

//Vytvořte nějaké nové parametry
    var td= TextureData.FromFile(file);
    const float nozzleSize = 0.9f;//0,2 mm
    const float layerHeight = 0.2f;
    var grayscale = ToGrayscale(td);
    const float width = 120.0f;//šířka plátna je 200,0 mm
    float height = width / td.Width * td.Height;
    float thickness = 10.0f;//tloušťka 10mm
    float layers = thickness / layerHeight;
    int widthSegs = (int)Math.Floor(width / nozzleSize);
    int heightSegs = (int)Math.Floor(height / nozzleSize);

//Provádějte výpočetní operace s objekty Mesh
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

//Vytvářejte 3D scénu a ukládejte objekty
    var scene = new Scene(mesh);
    scene.Save(output, FileFormat.FBX7400ASCII);

//Ukázková metoda k volání
    static float Sample(float[,] data, int w, int h, float x, float y)
    {
        return data[(int)(x * w), (int)(y * h)];
    }

//Volání metody ToGrayscale
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

    {{% blocks/products/pf/agp/content h2="Aspose.3D for .NET API" %}}

 Aspose.3D je CAD a herní software API k načítání, úpravě a převodu souborů 3D. API je samostatný a nevyžaduje žádný 3D modelovací nebo vykreslovací software. Lze snadno použít API pro Discreet3DS, WavefrontOBJ, STL (ASCII, binární), Universal3D, FBX (ASCII, binární), Collada, glTF, PLY, GLB, DirectX a další formáty. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Bezplatná aplikace pro vytvoření vašeho Lithophane do JPG" sectionDescription="Podívejte se na naše živé ukázky [Lithophane JPG](https://products.aspose.app/3d/lithophane/jpg) s následujícími výhodami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není potřeba nic stahovat ani nastavovat" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát nebo kompilovat kód" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát soubor JPG a stisknout tlačítko „lithophane“." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" V případě potřeby stáhněte soubor JPG z odkazu" >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporovaná aplikace pro vytvoření Lithophane to Formats" subTitle="Pomocí C# můžete také vytvořit svůj litophane do mnoha dalších formátů souborů včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/jpeg/" name="JPEG" description="Společná skupina fotografických expertů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/png/" name="PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/tga/" name="TGA" description="Pokročilý rastrový adaptér Truevision" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/bmp/" name="BMP" description="Bitmapa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/gif/" name="GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/tiff/" name="TIFF" description="Formát souboru označeného obrázku" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}