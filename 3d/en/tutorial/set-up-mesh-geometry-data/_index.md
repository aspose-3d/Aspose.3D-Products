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
{{< blocks/products/pf/feature-page-section h2="Learn How To Set Up Mesh Geometry Data" >}}

<p>
In this tutorial, we'll learn how to set up mesh geometry data.
</p>

<p>
We will set the data for the color. We initialize an <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/imeshconvertible/">IMeshConvertible</a> object using the Torus class, initialize a node object, and add it to the scene. Finally, we initialize a <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/lambertmaterial/">LambertMaterial</a> object and set the color data. We can clearly see the changes in it.
</p>

<br />
{{< app/3d/tutorial >}}
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

