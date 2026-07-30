---
title: Extracción de Activos de Formatos 3D en C#
url: /es/net/extractor/
description: Extraer activos de formatos 3D 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x vía una biblioteca .NET usando unas pocas líneas de código C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Extraer Activos de Formatos 3D Vía C#" h2="Extraer activos de formatos de documentos 3D sin ningún software de modelado y renderizado 3D para construir aplicaciones .NET multiplataforma." >}}

{{% blocks/products/pf/feature-page-summary %}}
Los desarrolladores pueden usar la biblioteca 3D para extraer fácilmente activos de archivos 3D. Pocos formatos admitidos por la API son WavefrontOBJ, Discreet3DS, STL (ASCII, Binario), FBX (ASCII, Binario), Universal3D, Collada, GLB, glTF, PLY, DirectX, formatos de Google Draco, etc. El proceso de extracción es simple, cargue el archivo fuente a través de una instancia de la clase [scene](https://apireference.aspose.com/3d/net/aspose.threed/scene), cree la clase de archivo y maneje la clase de activo de extracción, y llame al método Save para el parámetro de formato de salida relevante.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section  h2="Extraer Activos de la Escena 3D a varios formatos" %}}
Los desarrolladores pueden extraer fácilmente activos de archivos 3D a través del mismo proceso que se enumera anteriormente. Considere algunos ejemplos como **Extractor 3DS a FBX**. Cargue archivos 3DS a través de objetos de clase de escena. Cree opciones de guardar con [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions) para crear opciones de guardar y llame al método guardar de la escena con los argumentos de la ruta de archivo de salida y las opciones fbx. La API tiene clases de opciones apropiadas para guardar en clases relacionadas, p. ej., [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) y más. Aquí está la lista completa de opciones de [extractor formatos](https://apireference.aspose.com/3d/net/aspose.threed.formats) 3D.

{{% blocks/products/pf/feature-page-code h3="Código C# para la extracción de activos de 3DS a FBX" %}}

{{< gist "aspose-3d-gists" "9563193e834f0087b554c83130fcf7c7" "Examples-CSharp-Extractor-products.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Extractor" >}}
{{< /blocks/products/pf/feature-page-wrap >}}