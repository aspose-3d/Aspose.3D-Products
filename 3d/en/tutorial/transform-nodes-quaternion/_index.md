---
title: Aspose.3D Transform Nodes by quaternion
weight: 7700
limit: 
description: Learn how to transform Nodes by quaternion
keywords: [3d scene, transform, Nodes, quaternion]
url: /tutorial/transform-nodes-quaternion
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please review the following code that demonstrates how to transform nodes by quaternion. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene and initialize an IMeshConvertible object.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a torus in a scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to use the FromRotation method of a quaternion to perform transformation operations on a torus.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Shading;

//Create a new 3D scene
Scene scene = new Scene();

// Initialize object by Torus class
IMeshConvertible convertible = new Torus();

//Convert a Torus to Mesh
Mesh mesh = convertible.ToMesh();

//ExStep:1-
// Initialize Node class object
Node cubeNode = new Node("cube");

// Point node to the Mesh geometry
cubeNode.Entity = mesh;

// Set translation
cubeNode.Transform.Translation = new Vector3(-3, 0, 0);

//Add cubeNode to the scene
scene.RootNode.ChildNodes.Add(cubeNode);

//ExStep:2-
// Initialize another node class object
Node cubeNode2 = new Node("cube2");

// Point node to the Mesh geometry
cubeNode2.Entity = mesh;

// Set rotation
cubeNode2.Transform.Rotation = Quaternion.FromRotation(new Vector3(0.3, 1, 1.7), new Vector3(0, 1, 0.3));

// Set translation
cubeNode2.Transform.Translation = new Vector3(3, 0, 0);

// Add cubeNode2 to the scene
scene.RootNode.ChildNodes.Add(cubeNode2);

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to transform nodes by quaternion.

We will use the Torus class to initialize the <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/">IMeshConvertible</a> object, initialize the node object, and add the torus to the scene. We use the FromRotation method to transform one of the torus, and we can clearly see the changes.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Rotate by Quaternion](https://docs.aspose.com/3d/net/adding-transformation-to-the-node/#rotate-by-quaternion)
* [API Vector3](https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/)
* [API IMeshConvertible](https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/)
* [API Quaternion](https://reference.aspose.com/3d/net/aspose.threed.utilities/quaternion/)
* [API Transform](https://reference.aspose.com/3d/net/aspose.threed/transform/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

