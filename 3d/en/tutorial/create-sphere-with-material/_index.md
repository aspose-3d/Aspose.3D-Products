---
title: Aspose.3D Create sphere with material 
weight: 7700
limit: 
description: Learn how to create a 3D scene with a Sphere object and has material definition.
keywords: [3d scene, sphere, pbr material]
url: /tutorial/create-sphere-with-material
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Create Sphere with material" >}}


<p>
In this tutorial, we'll create a sphere in a 3D file and apply material to it. <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/">Materials</a> are a powerful feature of the 3D, and adding materials to them can make your scene more visually appealing and attractive.
</p>

<p>
We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a> and create a sphere. Then we'll customize its radius. Finally we'll attach this sphere to the scene.
</p>

<br />
{{< app/3d/tutorial >}}
//ExSummary: Please check the following code to find out how to create a sphere and attach it to a scene, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene
//ExStepSummary:1: The following code shows how to create a new sphere and customize its radius.
//ExStepSummary:2: The following code shows how to create a material and apply it to the sphere's node
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;

//Create a new 3D scene
var scene = new Scene();

//ExStep:1-
//Create a new sphere and attach it to scene
var sphere = new Sphere();
sphere.Radius = 10;
var node = scene.RootNode.CreateChildNode(sphere);

//ExStep:2-
//create a new material and apply it to the node
var material = new PbrMaterial();
material.Albedo = new Vector3(0, 1, 0);
node.Material = material;

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

