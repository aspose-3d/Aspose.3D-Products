---
title: Převod formátů C# 3D
url: /cs/net/conversion/
description: Převeďte formáty 3D 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x pomocí několika řádků kódu C# prostřednictvím knihovny .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D Převod formátů prostřednictvím C#" h2="Převádějte formáty dokumentů 3D bez jakéhokoli softwaru pro modelování a vykreslování 3D, abyste mohli vytvářet aplikace pro více platforem .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}
Vývojáři mohou snadno číst, vytvářet, převádět, aktualizovat a ovládat podstatu formátů 3D pomocí grafické knihovny 3D. Několik z podporovaných formátů podle API je WavefrontOBJ, Discreet3DS, STL (ASCII, binární), FBX (ASCII, binární), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco a další. Proces převodu je snadný jako načítání zdrojového souboru prostřednictvím instance [Třída scén](https://apireference.aspose.com/3d/net/aspose.threed/scene)a voláním metody Save s příslušným parametrem výstupního formátu.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Převeďte scénu 3D do různých formátů" %}}
Vývojáři mohou snadno převést scénu 3D stejným postupem uvedeným výše. Vezměme si několik příkladů, jako je konverze **FBX na OBJ**. Načtěte soubor FBX prostřednictvím objektu Scene Class. Vytvořte možnosti uložení pomocí [ObjSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/objsaveoptions) a zavolejte metodu ukládání scény, která má jako parametry cestu k výstupnímu souboru a možnosti obj. API má vhodné třídy možností pro ukládání do relevantních tříd, např [Možnosti A3dwSave](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [Možnosti AmfSave](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxsaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) a více. Zde je úplný seznam pro 3D [převodní formát](https://apireference.aspose.com/3d/net/aspose.threed.formats) možnosti. Kromě toho mohou vývojáři snadno uložit scénu 3D do PDF.

{{% blocks/products/pf/feature-page-code h3="C# Kód pro konverzi FBX na OBJ" %}}

{{< gist "aspose-com-gists" "ed8b7177c365be75c2bf8d3e668f113a" "convert-fbx-to-obj.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod 3D scény na PDF" %}}

{{< gist "aspose-3d" "631532eeb21c3374f2ed" "Examples-CSharp-Loading-and-Saving-Save3DInPdf-Save3DInPdf.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
