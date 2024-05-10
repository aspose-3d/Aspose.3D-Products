---
title: Aspose.3D Create box with material
weight: 7700
limit: 
description: Learn how to create Box with material
keywords: [3d scene, Box, pbr material]
url: /tutorial/create-box-with-material
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to create a box and attach it to a scene, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a box in a scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to add metal material to the box and make its surface rough.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
//create a box to which the material will be applied
var boxNode = scene.RootNode.CreateChildNode("box", new Box());

//ExStep:2-
//initialize PBR material object
PbrMaterial mat = new PbrMaterial();

// an almost metal material
mat.MetallicFactor = 0.9;

mat.Albedo = new Vector3(0.3, 0.8, 0.8);

// material surface is very rough
mat.RoughnessFactor = 0.4;

boxNode.Material = mat;

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we will create a box in a 3D scene and apply materials to it. <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/">Materials</a> are a powerful feature of 3D, and adding materials to it can make the scene visually more attractive.

We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a> and create a box. Then we will add metal materials to the box and make the surface rough. Finally, we will attach this box to the scene.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Non-PBR to PBR Material Conversion](https://docs.aspose.com/3d/net/customize-non-pbr-to-pbr-materials-conversion-before-saving-3d-scenes-to-gltf-2-0-format/)
* [API PbrMaterial](https://reference.aspose.com/3d/net/aspose.threed.shading/pbrmaterial/)
* [API RoughnessFactor](https://reference.aspose.com/3d/net/aspose.threed.shading/pbrmaterial/roughnessfactor/)
* [API MetallicFactor](https://reference.aspose.com/3d/net/aspose.threed.shading/pbrmaterial/metallicfactor/)
* [API Box](https://reference.aspose.com/3d/net/aspose.threed.entities/box/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

