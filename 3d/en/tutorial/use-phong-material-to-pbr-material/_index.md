---
title: Aspose.3D Customize PBR Material conversion in glTF
weight: 7700
limit: 
description: Learn how to use use MaterialConverter to customize Non-PBR material to PBR material during exporting the glTF files.
keywords: [3d scene, Phong material, PBR material, glTF]
url: /tutorial/customize-material-to-pbr-material-in-gltf-export
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please review the following code that demonstrates how to convert phong material to pbr material during glTF exporting. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to add the Phong material to the box.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to customize the material converter.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Formats;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
//Create a new box object
var box = new Box();

//Add Phong material to the box object
scene.RootNode.CreateChildNode("box1", box).Material = new PhongMaterial() { DiffuseColor = new Vector3(1, 0, 1) };

//ExStep:2-
//Create format options that need to be saved
GltfSaveOptions opt = new GltfSaveOptions(FileFormat.GLTF2);

//Custom material converter to convert PhongMaterial to PbrMaterial
opt.MaterialConverter = delegate (Material material)
{
    PhongMaterial m = (PhongMaterial)material;
    return new PbrMaterial() { Albedo = new Vector3(m.DiffuseColor.x, m.DiffuseColor.y, m.DiffuseColor.z) };
};

//You can download the file below.
scene.Save("output.gltf", opt);

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to customize non-PBR material to pbr material during glTF exporting, this is useful when you have you own policy to convert the material.

We'll create a box object, add a Phong material to it, and attach the box to the scene. We will customize the material converter to convert <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/phongmaterial/">PhongMaterial</a> to <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/pbrmaterial/">PbrMaterial</a> in a GltfSaveOptions.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Non-PBR to PBR Material Conversion](https://docs.aspose.com/3d/net/customize-non-pbr-to-pbr-materials-conversion-before-saving-3d-scenes-to-gltf-2-0-format/#non-pbr-to-pbr-material-conversion)
* [API Vector3](https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/)
* [API PbrMaterial](https://reference.aspose.com/3d/net/aspose.threed.shading/pbrmaterial/)
* [API GltfSaveOptions](https://reference.aspose.com/3d/net/aspose.threed.formats/gltfsaveoptions/)
* [API Box](https://reference.aspose.com/3d/net/aspose.threed.entities/box/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

