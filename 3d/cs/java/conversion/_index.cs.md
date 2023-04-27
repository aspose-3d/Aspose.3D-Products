---
title: Převod formátů Java 3D
url: /cs/java/conversion/
description: Převeďte formáty 3D amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x pomocí několika řádků kódu Java prostřednictvím knihovny Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D Převod formátů prostřednictvím Java" h2="Převádějte formáty souborů 3D bez instalace softwaru pro modelování a vykreslování 3D a sestavujte aplikace Java pro více platforem." >}}

{{% blocks/products/pf/feature-page-summary %}}
Pro vytváření, úpravy, manipulaci a ukládání trojrozměrných grafických aplikací poskytuje **Java 3D API** vysokou úroveň metod k provádění takových funkcí bez instalace jakéhokoli 3D softwaru pro modelování a vykreslování. Jen málo z nich vytváří síť různých trojrozměrných geometrických tvarů, vytváří soubor scény 3D, nastavuje normály nebo UV na krychli, formátuje prvky, přidává vlastnosti animace a další. 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Převeďte soubor 3D do různých formátů" %}}
Proces převodu je jednoduchý. Stačí načíst zdrojový soubor 3D pomocí [Třída scén](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene)Protože scéna je objekt nejvyšší úrovně, který má uzly, geometrie, textury, materiály, animace, pozice, podscény atd. Vytvořte příslušné [Uložit možnosti](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) jako jsou AmfSaveOptions, ColladaSaveOptions, Discreet3dsSaveOptions, DracoSaveOptions, FbxSaveOptions, GltfSaveOptions, RvmSaveOptions, StlSaveOptions, U3dSaveOptions atd. a podle toho nastavte vlastnosti. Nakonec zavolejte metodu uložení s výstupním souborem a vytvořeným objektem možností uložení cílového formátu. Navíc pomocí programátorů API lze dokonce uložit 3D scénu jako HTML.


{{% blocks/products/pf/feature-page-code h3="Java Kód pro konverzi AMF na 3DS" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Převést scénu 3D na HTML prostřednictvím Java" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
