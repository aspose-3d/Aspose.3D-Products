---
title: Aspose.3D Get geometric transformations
weight: 7700
limit: 
description: Learn how to get geometric transformations
keywords: [3d scene, geometric, transformations]
url: /tutorial/get-geometric-transformations
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please review the following code that demonstrates how to get geometric transformations. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene and initialize an IMeshConvertible object.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a sphere in the scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to transform a sphere using the GeometricTranslation method.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

// Initialize object by Sphere class
IMeshConvertible convertible = new Sphere();

// Convert a Sphere to Mesh
Mesh mesh = convertible.ToMesh();

//ExStep:1-
// Initialize Node class object
var n = new Node("geometry");

// Point node to the Mesh geometry
n.Entity = mesh;

// Add Node to the scene
scene.RootNode.ChildNodes.Add(n);

//ExStep:2-
// Set transform
n.Transform.GeometricTranslation  = new Vector3(-5, -5, -5);

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to get geometric transformations.

We'll use the Sphere class to initialize the <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/">IMeshConvertible</a> object, initialize the node object, and add the sphere to the scene. We use the GeometricTranslation method to transform the sphere and we can clearly see the change.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Expose Geometric Transformation](https://docs.aspose.com/3d/net/expose-geometric-transformation/)
* [API IMeshConvertible](https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/)
* [API Mesh](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/)
* [API Vector3](https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/)
* [API Transform](https://reference.aspose.com/3d/net/aspose.threed/transform/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

