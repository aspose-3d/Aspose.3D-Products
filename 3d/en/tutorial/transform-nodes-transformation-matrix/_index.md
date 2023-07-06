---
title: Aspose.3D Transform Nodes using a transformation matrix
weight: 7700
limit: 
description: Learn how to transform Nodes using a transformation matrix
keywords: [3d scene, Nodes, transform, matrix]
url: /tutorial/transform-nodes-transformation-matrix
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Transform Nodes Using A Transformation Matrix" >}}

<p>
In this tutorial, we'll learn how to transform nodes using a transformation matrix.
</p>

<p>
We will use the Torus class to initialize the <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/">IMeshConvertible</a> object, initialize the node object, and add the torus to the scene. We use the TransformMatrix method to transform one of the torus, and we can clearly see the changes.
</p>

<br />
{{< app/3d/tutorial >}}
//ExSummary: Please review the following code that demonstrates how to transform nodes using a transformation matrix. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene and initialize an IMeshConvertible object.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a torus in a scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to use the TransformMatrix method to perform transformation operations on a torus.
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

// Convert a Torus to Mesh
Mesh mesh = convertible.ToMesh();

//ExStep:1-
// Initialize Node class object
Node cubeNode = new Node("cube");

// Point node to the Mesh geometry
cubeNode.Entity = mesh;

// Set translation
cubeNode.Transform.Translation = new Vector3(-4, 0, 0);

// Add cubeNode to the scene
scene.RootNode.ChildNodes.Add(cubeNode);

//ExStep:2-
// Initialize another node class object
Node cubeNode2 = new Node("cube2");

// Point node to the Mesh geometry
cubeNode2.Entity = mesh;

// Set custom translation matrix
cubeNode2.Transform.TransformMatrix = new Matrix4(
1, -0.9, 0.4, 0,
0.4, 1.2, 0.4, 0.1,
0.3, 0.3, 3.4, 0.3,
0, 2, 0.4, 1
);              

// Set translation
cubeNode2.Transform.Translation = new Vector3(3, -1, 0);

// Add cubeNode2 to the scene
scene.RootNode.ChildNodes.Add(cubeNode2);

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/3d/net/installation/">Installation of Aspose.3D</a></li>
        <li class="link-item"><a href="https://products.aspose.app/3d/editor/">3D Editor</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

