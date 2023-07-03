---
title: Aspose.3D Set the radius of a sphere
weight: 7700
limit: 
description: Learn how to set the radius of a Sphere
keywords: [3d scene, Sphere, radius]
url: /tutorial/set-radius-sphere
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Set the radius of a Sphere" >}}

<p>
In this tutorial, we will create two spheres in a 3D scene and modify their sizes using the Radius property. By comparing them, we can clearly see the difference in sphere sizes.
</p>

<p>
We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>. Then we will create two spheres with different radii for visual comparison.
</p>

<br />
{{< app/3d/tutorial >}}
//ExSummary: Please check the following code to find out how to set the radius of a Sphere, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to set up a sphere with a radius of 1.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code demonstrates how to set up a sphere with a radius of 1.5 for comparison.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
// Set Sphere Radius (Using Radius property you can get or set radius of Sphere)
scene.RootNode.CreateChildNode(new Sphere() { Radius = 1 }).Transform.Translation = new Vector3(-4, 0, 0);

//ExStep:2-
// Set the sphere radius to 1.5
scene.RootNode.CreateChildNode(new Sphere() { Radius = 1.5 }).Transform.Translation = new Vector3(2, 0, 0);

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

