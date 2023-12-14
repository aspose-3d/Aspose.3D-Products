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
{{< blocks/products/pf/feature-page-section h2="Learn How To Get Geometric Scaling And Rotation" >}}

<p>
In this tutorial, we'll learn how to get geometric scaling and rotation.
</p>

<p>
We'll use the Cylinder class to initialize the <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/">IMeshConvertible</a> object, and add the cylinder to the scene. We use the GeometricScaling method to scale the cylinder, the GeometricRotation method to rotate the cylinder and we can clearly see the change.
</p>

<br />
{{< app/3d/tutorial2 >}}
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
{{< /app/3d/tutorial2 >}}
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

