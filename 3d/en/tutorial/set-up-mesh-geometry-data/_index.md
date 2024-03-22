---
title: Aspose.3D Set Up mesh geometry data
weight: 7700
limit: 
description: Learn how to set up mesh geometry data
keywords: [3d scene, mesh, geometry, data]
url: /tutorial/set-up-mesh-geometry-data
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please review the following code that demonstrates how to set up mesh geometry data. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene and add color data.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a node object and add it to the scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to set color data.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Shading;

//Create a new 3D scene
Scene scene = new Scene();

// Define color vectors
Vector3[] colors = new Vector3[] {new Vector3(0,30,40)};

//ExStep:1-
// Initialize object by Torus class
IMeshConvertible convertible = new Torus();

//Convert a Torus to Mesh
Mesh mesh = convertible.ToMesh();

// Initialize cube node object
Node cube = new Node("cube");

//Point node to the Mesh geometry
cube.Entity = mesh;

// Add cube node to a scene
scene.RootNode.ChildNodes.Add(cube);

//ExStep:2-
//Initialize Lambert material object
LambertMaterial mat = new LambertMaterial();

//Set color
mat.DiffuseColor = colors[0];

//Set material
cube.Material = mat;

//Set translation
cube.Transform.Translation = new Vector3(2, 0, 0);

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to set up mesh geometry data.

We will set the data for the color. We initialize an <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/">IMeshConvertible</a> object using the Torus class, initialize a node object, and add it to the scene. Finally, we initialize a <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/lambertmaterial/">LambertMaterial</a> object and set the color data. We can clearly see the changes in it.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Share Mesh’s Geometry Data between Multiple Nodes](https://docs.aspose.com/3d/net/add-node-hierarchy-and-share-geometric-data-of-mesh-among-multiple-nodes-of-3d-scene/#share-meshs-geometry-data-between-multiple-nodes)
* [API IMeshConvertible](https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/)
* [API Mesh](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/)
* [API LambertMaterial](https://reference.aspose.com/3d/net/aspose.threed.shading/lambertmaterial/)
* [API Vector3](https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

