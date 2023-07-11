---
title: Aspose.3D Shear the bottom of a Cylinder
weight: 7700
limit: 
description: Learn how to shear the bottom of a Cylinder
keywords: [3d scene, Cylinder, shear]
url: /tutorial/shear-bottom-cylinder
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To shear the bottom of a Cylinder" >}}

<p>
In this tutorial, we will create two cylinders in a 3D scene. We will use the ShearBottom property to shear the bottom of one of the cylinders. By creating a regular cylinder for comparison, we can clearly see the differences.
</p>

<p>
We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>. Then, we will create a cylinder with a sheared bottom and a regular cylinder for visual comparison.
</p>

<br />
{{< app/3d/tutorial2 >}}
//ExSummary: Please check the following code to find out how to shear the bottom of a cylinder, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to create a regular cylinder in a scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code demonstrates how to shear the bottom of a cylinder in a scene.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Entities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
// Create cylinder 1
var cylinder1 = new Cylinder(2, 2, 2, 20, 1, false);

// Add cylinder to without a ShearBottom to the scene
scene.RootNode.CreateChildNode(cylinder1).Transform.Translation = new Vector3(2, 0, 0);

//ExStep:2-
// Create cylinder 2
var cylinder2 = new Cylinder(2, 2, 3, 20, 1, false);

// Customized shear bottom for cylinder 2
cylinder2.ShearBottom = new Vector2(0, 0.83);

// Add cylinder 2 to the scene
scene.RootNode.CreateChildNode(cylinder2).Transform.Translation = new Vector3(-4, 0, 0);

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

