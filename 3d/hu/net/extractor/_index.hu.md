---
title: C# 3D Formátumokból Erőforrások Kinyerése
url: /hu/net/extractor/
description: 3ds, 3mf, amf, ase, att, dae, drc, dxf, fbx, gltf, jt, obj, ply, rvm, stl, u3d, usdz, usd, vrml x formátumból 3D Asseteket extráld .NET könyvtár segítségével néhány sor C# kóddal.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D Formátumokból Elem Átkészítése C# használatával" h2="Elemek kinyerése 3D dokumentum formátumokból anélkül, hogy 3D modellező és renderelő szoftverre lenne szükség, hogy keresztplatformos .NET alkalmazásokat építsen." >}}

{{% blocks/products/pf/feature-page-summary %}}
A fejlesztők könnyen kinyerhetik a 3D fájl elemeit a 3D könyvtár segítségével. Az API által támogatott formátumok közé tartozik a WavefrontOBJ, Discreet3DS, STL (ASCII, Bináris), FBX (ASCII, Bináris), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco formátumok, stb. A kivonási folyamat egyszerű: betölti a forrásfájlt a [scene class](https://apireference.aspose.com/3d/net/aspose.threed/scene) példányon keresztül, létrehozza az archivum osztályt, kezeli az elem kivonási osztályt, és meghívja a Mentés metódust a megfelelő kimeneti formátum paraméterrel.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Elemek kinyerése 3D jelenetből különböző formátumokba" %}}
A fejlesztők könnyen kinyerhetik az elemeket a 3D fájlokból a fenti folyamat szerint. Vegyünk például egy **3DS to FBX Extractornak**. Betölti a 3DS fájlokat scene class objektumokon keresztül. Létrehozással [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions) mentési opciókat, és meghívja a scene mentési metódust a kimeneti fájl elérési útja és az fbx opciók argumentumokkal. Az API megfelelő opció osztályokat biztosít a mentéshez kapcsolódó osztályokba, például [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) és még sok más. Íme a 3D [extractor formátumok](https://apireference.aspose.com/3d/net/aspose.threed.formats) teljes listája.

{{% blocks/products/pf/feature-page-code h3="C# kód 3DS-ből FBX-be elem kivonásához" %}}

{{< gist "aspose-3d-gists" "9563193e834f0087b554c83130fcf7c7" "Examples-CSharp-Extractor-products.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Extractor" >}}
{{< /blocks/products/pf/feature-page-wrap >}}