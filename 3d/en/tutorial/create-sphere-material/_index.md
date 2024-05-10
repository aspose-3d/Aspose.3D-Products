---
title: Aspose.3D Create a Sphere using Phong material
weight: 7700
limit: 
description: Learn how to create a Sphere using Phong material
keywords: [3d scene, Sphere, Phong material]
url: /tutorial/create-sphere-material
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to create sphere with material, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code demonstrates how to create a sphere in a scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to apply the Phong material to a sphere.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code demonstrates how to create a sphere using PBR material.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Shading;

//Create a new 3D scene
Scene scene = new Scene();

//Create a sphere without material.
var sphere=scene.RootNode.CreateChildNode("sphere", new Sphere(2, 70, 20));
sphere.Transform.Translation = new Vector3(-4, 0, 0);

//ExStep:1-
//Add Phong material to the sphere.
sphere.Material = new PhongMaterial()
{
  DiffuseColor = new Vector3(0, 1, 0)
};

//ExStep:2-
//Add another sphere with a PBR material.
var sphere1=scene.RootNode.CreateChildNode("sphere1", new Sphere(2, 70, 20));
sphere1.Transform.Translation = new Vector3(2, 0, 0);
sphere1.Material = new PbrMaterial()
{
    Albedo = new Vector3(1, 0, 0),
    RoughnessFactor = 0.6,
    MetallicFactor = 0.3
};

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we will create two spheres in a 3D file and apply material to it. <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/">Materials</a> are a powerful feature of the 3D, and adding materials to them can make your scene more visually appealing.

We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>. Then, we will create a sphere and apply the Phong material to it. Afterwards, we will create another sphere using the PBR material. By comparing them, we can clearly see the differences.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Non-PBR to PBR Material Conversion](https://docs.aspose.com/3d/net/customize-non-pbr-to-pbr-materials-conversion-before-saving-3d-scenes-to-gltf-2-0-format/)
* [API PbrMaterial](https://reference.aspose.com/3d/net/aspose.threed.shading/pbrmaterial/)
* [API Transform](https://reference.aspose.com/3d/net/aspose.threed/transform/)
* [API Vector3](https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/)
* [API Sphere](https://reference.aspose.com/3d/net/aspose.threed.entities/sphere/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

