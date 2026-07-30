---
title: "C# 3D-formatvisare"
url: /sv/net/viewer/
description: "Visa 3D-format 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x via .NET-bibliotek med några rader C#-kod."
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D-formatvisare via C#" h2="Visa 3D-dokumentformat utan någon 3D-modellerings- och renderingsprogramvara för att bygga plattformsoberoende .NET-applikationer." >}}

{{% blocks/products/pf/feature-page-summary %}}
Utvecklare kan använda 3D-grafikbiblioteket för att enkelt läsa, skapa, transformera, uppdatera och styra innehållet i 3D-format. Få format som stöds av API:et är WavefrontOBJ, Discreet3DS, STL (ASCII, Binär), FBX (ASCII, Binär), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco-format, etc. Visningsprocessen är mycket enkel, ladda källfilen via en instans av [scene class](https://apireference.aspose.com/3d/net/aspose.threed/scene), och anropa Save-metoden med de relevanta utdataformatparametrarna.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Visa 3D-scen till olika format" %}}
Utvecklare kan enkelt visa 3d-filer genom samma process som anges ovan. Tänk på några exempel som **3DS till HTML5-visning**. Ladda 3DS-filer via scene class-objekt. Skapa spara alternativ med [Html5SaveOptions ](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5SaveOptions) för att skapa spara alternativ och anropa scene save-metoden med utdatafilens sökväg och html5-alternativargument. API:et har lämpliga options-klasser för att spara till relaterade klasser, t.ex. [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) och mer. Här är hela listan över 3D [viewer formats](https://apireference.aspose.com/3d/net/aspose.threed.formats) alternativ.

{{% blocks/products/pf/feature-page-code h3="C#-kod för 3DS till HTML5-visare" %}}

{{< gist "aspose-3d-gists" "9563193e834f0087b554c83130fcf7c7" "Examples-CSharp-Viewer-products.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Viewer" >}}
{{< /blocks/products/pf/feature-page-wrap >}}