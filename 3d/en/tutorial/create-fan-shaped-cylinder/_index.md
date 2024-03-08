---
title: Aspose.3D Create fan-shaped Cylinder
weight: 7700
limit: 
description: Learn how to create fan-shaped Cylinder
keywords: [3d scene, Cylinder, fan-shaped]
url: /tutorial/create-fan-shaped-cylinder
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to create regular cylinder and fan-shaped cylinder,you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a regular cylinder in a scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to create a fan-shaped cylinder in a scene.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
//Create a cylinder without a fan
var nonfan = new Cylinder(2, 2, 2, 20, 1, false);

// Set GenerateFanCylinder to false
nonfan.GenerateFanCylinder = false;

// Set ThetaLengeth 
nonfan.ThetaLength = MathUtils.ToRadian(270);

// Create ChildNode
scene.RootNode.CreateChildNode(nonfan).Transform.Translation = new Vector3(-4, 0, 0);

//ExStep:2-
// Create a fan-shaped cylinder
var fan = new Cylinder(2, 2, 2, 20, 1, false);

// Set GenerateFanCylinder to true
fan.GenerateFanCylinder = true;

// Set ThetaLength
fan.ThetaLength = MathUtils.ToRadian(270);

// Create ChildNode
scene.RootNode.CreateChildNode(fan).Transform.Translation = new Vector3(2, 0, 0);

//ExStep:0-
scene
//ExEnd
//ExLinkCategory: API References
//ExLink: Scene:https://reference.aspose.com/3d/net/aspose.threed/scene/
//ExLink: Cylinder:https://reference.aspose.com/3d/net/aspose.threed.entities/cylinder/
//ExLink: Vector3:https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/
//ExLink: Transform:https://reference.aspose.com/3d/net/aspose.threed/transform/
//ExLink: ThetaLength:https://reference.aspose.com/3d/net/aspose.threed.entities/cylinder/thetalength/
//ExLinkCategory: Documents
//ExLink: Working with Cylinder:https://docs.aspose.com/3d/net/working-with-cylinder/
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we will create a fan-shaped cylinder. We complete this operation through the GenerateFanCylinder property. We can clearly see the differences by creating ordinary cylinders for comparison.

We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>. Then we will create a fan-shaped cylinder and a regular cylinder for intuitive comparison.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)


{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

