---
title: Java 3D Formátumkonverzió
url: /hu/java/conversion/
description: Konvertálja az 3D formátumot amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x néhány soros Java kóddal a Java könyvtáron keresztül.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D Formátumkonverzió a következőn keresztül: Java" h2="Konvertáljon 3D fájlformátumot 3D modellező és renderelő szoftver telepítése nélkül, hogy platformokon átívelő Java alkalmazásokat készítsen." >}}

{{% blocks/products/pf/feature-page-summary %}}
A háromdimenziós grafikus alkalmazások létrehozásához, szerkesztéséhez, manipulálásához és mentéséhez a **Java 3D API** magas szintű módszereket kínál az ilyen funkciók végrehajtására, a 3D modellező és megjelenítő szoftver telepítése nélkül. Kevesen építik fel a különböző háromdimenziós geometriai formák hálóját, hoznak létre 3D jelenetfájlt, állítanak be normált vagy UV-t a kockán, formázzák meg az elemeket, adnak hozzá animációs tulajdonságokat és így tovább. 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja a(z) 3D fájlt különböző formátumokba" %}}
Az átalakítási folyamat egyszerű. Csak töltse be a forrás 3D fájlt a használatával [Jelenet osztály](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene)Mivel a jelenet egy legfelső szintű objektum, amely csomópontokkal, geometriákkal, textúrákkal, anyagokkal, animációkkal, pózokkal, aljelenetekkel stb. rendelkezik. Hozza létre a megfelelő [Mentse el a beállításokat](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) például AmfSaveOptions, ColladaSaveOptions, Discreet3dsSaveOptions, DracoSaveOptions, FbxSaveOptions, GltfSaveOptions, RvmSaveOptions, StlSaveOptions, U3dSaveOptions stb., és ennek megfelelően állítsa be a tulajdonságokat. Végül hívja meg a mentési metódust a kimeneti fájllal és a létrehozott célformátum mentési beállítások objektummal. Ezenkívül a(z) API programozók akár 3D jelenetet is elmenthetnek HTML néven.


{{% blocks/products/pf/feature-page-code h3="Java Kód a(z) AMF – 3DS konverzióhoz" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="A(z) 3D jelenet konvertálása a következőre: HTML a következőn keresztül: Java" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
