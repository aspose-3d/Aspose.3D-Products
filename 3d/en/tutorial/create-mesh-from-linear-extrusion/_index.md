---
title: Aspose.3D Create mesh from linear extrusion
weight: 7700
limit: 
description: Learn how to create a mesh using linear extrusion on a 2D shape
keywords: [3d scene, linear extrusion, profile, shape]
url: /tutorial/create-mesh-from-linear-extrusion
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Create Mesh From Linear Extrusion" >}}

<p>
In this tutorial, we'll create a <a href="https://reference.aspose.com/3d/net/aspose.threed.profiles/profile/">2D profile</a> and then perform a <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/linearextrusion/">linear extrusion</a> on it to turn it into a 3D mesh. Next we will <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/polygonmodifier/generatenormal/">generate normal data</a> using Aspose.3D's builtin algorithm. Finally, we will add materials to the mesh to enhance its visual appeal.

</p>

<br />
{{< app/3d/tutorial2 >}}
//ExSummary: Please review the following code that demonstrates how to create a mesh using linear extrusion. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The code below demonstrates how to create a new 3D scene with a linear extrusion object.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to create a mesh from a linear extrusion object.
//ExStepImage:1:step-1.png
//ExStepSummary:2: The following code demonstrates how to generate normal data from a mesh.
//ExStepImage:2:step-3.png
//ExStepSummary:3: The following code demonstrates how to apply a material to a mesh object.
//ExStepImage:3:step-4.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Profiles;
//ExStep:3-
using Aspose.ThreeD.Shading;
//ExStep:0-

//Create a new 3D scene
var scene = new Scene();

//ExStep:0-0
var profile = new CShape();
//Perform linear extrusion from a C shape profile with length 5.
var extrusion = new LinearExtrusion(profile, 5);
// Create node to hold the result
var node = scene.RootNode.CreateChildNode(extrusion);

//ExStep:1-
var profile = new CShape();
//Perform linear extrusion from a C shape profile with length 5.
var extrusion = new LinearExtrusion(profile, 5);
//Convert linear extrusion to mesh
var mesh = extrusion.ToMesh();

//ExStep:2-
//Generate normal data and add it to the mesh
var ven =  PolygonModifier.GenerateNormal(mesh);
mesh.AddElement(ven);

//ExStep:1-
// Create node to hold the result
var node = scene.RootNode.CreateChildNode(mesh);

//ExStep:3-
//create a new material and apply it to the node
var material = new PbrMaterial();
material.Albedo = new Vector3(0, 1, 0);
node.Material = material;

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

