---
title: Aspose.3D Get geometric scaling and rotation
weight: 7700
limit: 
description: Learn how to get geometric scaling and rotation
keywords: [3d scene, geometric, scaling, rotation]
url: /tutorial/get-geometric-scaling-rotation
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please review the following code that demonstrates how to get geometric scaling and rotation. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a cylinder in a scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to scale a cylinder using the GeometricScaling method.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to use the GeometricRotation method to rotate a cylinder.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

// Initialize object by Cylinder class
IMeshConvertible convertible = new Cylinder();

// Convert a Cylinder to Mesh
Mesh mesh = convertible.ToMesh();

// Initialize Node class object
var n = new Node("geometry");

// Point node to the Mesh geometry
n.Entity = mesh;

// Add Node to the scene
scene.RootNode.ChildNodes.Add(n);

//ExStep:1-
// Set cylinder scaling
n.Transform.GeometricScaling  = new Vector3(0.5,0.5, 0.5);

//ExStep:2-
// Set cylinder rotation
n.Transform.GeometricRotation  = new Vector3(30, 30, 30);

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to get geometric scaling and rotation.

We'll use the Cylinder class to initialize the <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/">IMeshConvertible</a> object, and add the cylinder to the scene. We use the GeometricScaling method to scale the cylinder, the GeometricRotation method to rotate the cylinder and we can clearly see the change.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Expose Geometric Transformation](https://docs.aspose.com/3d/net/expose-geometric-transformation/)
* [API IMeshConvertible](https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/)
* [API Mesh](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/)
* [API GeometricRotation](https://reference.aspose.com/3d/net/aspose.threed/transform/geometricrotation/)
* [API GeometricScaling](https://reference.aspose.com/3d/net/aspose.threed/transform/geometricscaling/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

