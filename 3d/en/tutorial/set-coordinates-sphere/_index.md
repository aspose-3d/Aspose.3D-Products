---
title: Aspose.3D set the coordinates of a sphere
weight: 7700
limit: 
description: Learn how to set the Coordinates of a Sphere
keywords: [3d scene, Coordinates, Sphere]
url: /tutorial/set-coordinates-sphere
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Set The Coordinates Of A Sphere" >}}

<p>
In this tutorial, we'll learn how to set the coordinates of a sphere.
</p>

<p>
We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>.Then we will create two spheres with different radii. We will set the coordinate attributes for one of the spheres, and we can clearly see the differences.
</p>

<br />
{{< app/3d/tutorial2 >}}
//ExSummary: Please check the following code to find out how to set the coordinates of a Sphere, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to set up a sphere with a radius of 1.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to set coordinate attributes for a sphere.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
// Set a sphere with a radius of 1 (Using Radius property you can get or set radius of Sphere)
scene.RootNode.CreateChildNode(new Sphere() { Radius = 1 }).Transform.Translation = new Vector3(-4, 0, 0);

//ExStep:2-
// Set the coordinates of the sphere
scene.RootNode.CreateChildNode(new Sphere() { Radius = 1.5,ThetaStart=1,ThetaLength=7, PhiLength = 5, PhiStart = 2 }).Transform.Translation = new Vector3(2, 0, 0);

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

