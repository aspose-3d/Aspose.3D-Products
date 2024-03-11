---
title: Aspose.3D Rotate geometry in a scene
weight: 7700
limit: 
description: Learn how to rotate geometry in a scene
keywords: [3d scene, rotate, geometry]
url: /tutorial/rotate-geometry-scene
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to rotate geometry in a scene, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code demonstrates how to create and connect quaternions.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to rotate a geometric object using a quaternion q1.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code demonstrates how to rotate a geometric object using a quaternion q2.
//ExStepImage:2:step-3.png
//ExStepSummary:3:The following code demonstrates how to rotate a geometric object using a quaternion q3.
//ExStepImage:3:step-4.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

//Create quaternion q1
 Quaternion q1 = Quaternion.FromEulerAngle(Math.PI * 0.5, 0, 0);

//Create quaternion q2
Quaternion q2 = Quaternion.FromAngleAxis(-Math.PI * 0.5, Vector3.XAxis);

//Concatenate q1 and q2. q1 and q2 rotate alone x-axis with same angle but differentdirection,So the concatenated result will be identity quaternion. 
Quaternion q3 = q1.Concat(q2);

//ExStep:1-
// Create a cylinder to represent q1 quaternion
Node cylinder = scene.RootNode.CreateChildNode("cylinder-q1", new Cylinder(0.1, 1, 2));
cylinder.Transform.Rotation = q1;
cylinder.Transform.Translation = new Vector3(-5, 2, 0);

//ExStep:2-
// Create a cylinder to represent q2 quaternion
cylinder = scene.RootNode.CreateChildNode("cylinder-q2", new Cylinder(0.1, 1, 2));
cylinder.Transform.Rotation = q2;
cylinder.Transform.Translation = new Vector3(0, 2, 0);

//ExStep:3-
// Create a cylinder to represent q3 quaternion
cylinder = scene.RootNode.CreateChildNode("cylinder-q3", new Cylinder(0.1, 1, 2));
cylinder.Transform.Rotation = q3;
cylinder.Transform.Translation = new Vector3(5, 0, 0);

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we will create and connect quaternions. We will create multiple geometric objects in a 3D scene and use quaternions to rotate these objects. By comparing multiple geometric objects, we can clearly see the differences.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Concatenate Quaternions and apply on 3D entities](https://docs.aspose.com/3d/net/concatenate-quaternions-and-apply-on-3d-entities/)
* [API Transform](https://reference.aspose.com/3d/net/aspose.threed/transform/)
* [API Vector3](https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/)
* [API Cylinder](https://reference.aspose.com/3d/net/aspose.threed.entities/cylinder/)
* [API Quaternion](https://reference.aspose.com/3d/net/aspose.threed.utilities/quaternion/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

