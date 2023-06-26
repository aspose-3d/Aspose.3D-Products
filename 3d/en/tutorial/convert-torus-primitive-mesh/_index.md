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
{{< blocks/products/pf/feature-page-section h2="Learn How To Convert A Torus Primitive To Mesh" >}}

<p>
In this tutorial, In this tutorial, we'll learn how to convert a torus primitive To mesh.
</p>

<p>
We'll create a sphere in the scene. We initialize an IMeshConvertible object using the torus class, and then we convert the torus into a mesh using the 'ToMesh' method.Finally, we add the node to the scene.
</p>

<br />
{{< app/3d/tutorial >}}
//ExSummary: Please check the following code to find out how to convert a torus primitive to mesh, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to convert a sphere to a mesh.
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

