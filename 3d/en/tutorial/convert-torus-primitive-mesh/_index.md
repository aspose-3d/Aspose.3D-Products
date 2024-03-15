---
title: Aspose.3D Convert a Torus primitive to mesh
weight: 7700
limit: 
description: Learn how to convert a Torus primitive to mesh
keywords: [3d scene, Torus, convert, mesh]
url: /tutorial/convert-torus-primitive-mesh
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to convert a torus primitive to mesh, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to convert a torus to a mesh.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code demonstrates how to add a node to the scene.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
// Initialize Node class object
Node cubeNode = new Node("torus");

// Initialize object by Torus class
IMeshConvertible convertible = new Torus();

// Convert a Torus to Mesh
Mesh mesh = convertible.ToMesh();

//ExStep:2-
// Point node to the Mesh geometry
cubeNode.Entity = mesh;

// Add Node to a scene
scene.RootNode.ChildNodes.Add(cubeNode);

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial,we'll learn how to convert a torus primitive To mesh.

We'll create a torus in the scene. We initialize an <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/">IMeshConvertible</a> object using the torus class, and then we convert the torus into a mesh using the 'ToMesh' method.Finally, we add the node to the scene.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Convert the Primitive to a Mesh](https://docs.aspose.com/3d/net/convert-mesh-to-triangle-mesh-and-primitive-shape-to-mesh/#convert-the-primitive-to-a-mesh)
* [API IMeshConvertible](https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/)
* [API Mesh](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/)
* [API Torus](https://reference.aspose.com/3d/net/aspose.threed.entities/torus/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

