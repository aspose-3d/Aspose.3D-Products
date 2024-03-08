---
title: Aspose.3D Create cylinder with material 
weight: 7700
limit: 
description: Learn how to create a 3D scene with a Cylinder object and has material definition.
keywords: [3d scene, cylinder, pbr material]
url: /tutorial/create-cylinder-with-material
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to create a cylinder and attach it to a scene, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a new cylinder and customize its radius.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to create a material and apply it to the cylinder's node
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;

//Create a new 3D scene
var scene = new Scene();

//ExStep:1-
//Create a new cylinder and attach it to scene
var cylinder = new Cylinder();
cylinder.RadiusBottom = 5;
var node = scene.RootNode.CreateChildNode(cylinder);

//ExStep:2-
//create a new material and apply it to the node
var material = new PbrMaterial();
material.Albedo = new Vector3(0, 1, 0);
node.Material = material;

//ExStep:0-
scene
//ExEnd
//ExLinkCategory: API References
//ExLink: Scene:https://reference.aspose.com/3d/net/aspose.threed/scene/
//ExLink: Cylinder:https://reference.aspose.com/3d/net/aspose.threed.entities/cylinder/
//ExLink: Vector3:https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/
//ExLink: PbrMaterial:https://reference.aspose.com/3d/net/aspose.threed.shading/pbrmaterial/
//ExLinkCategory: Documents
//ExLink: Working with Cylinder:https://docs.aspose.com/3d/net/working-with-cylinder/
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll create a cylinder in a 3D file and apply material to it. <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/">Materials</a> are a powerful feature of the 3D, and adding materials to them can make your scene more visually appealing.

We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a> and create a cylinder. Then we'll customize its radius. Finally we'll attach this cylinder to the scene.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)


{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

