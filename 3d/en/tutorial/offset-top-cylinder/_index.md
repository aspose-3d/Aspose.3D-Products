---
title: Aspose.3D Offset the top of a cylinder
weight: 7700
limit: 
description: Learn how to offset the top of a Cylinder
keywords: [3d scene, Cylinder, offset]
url: /tutorial/offset-top-cylinder
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Offset The Top OF A Cylinder" >}}

<p>
In this tutorial, we will create two cylinders in a 3D scene. We will offset the top of one of the cylinders using the OffsetTop property. By creating a regular cylinder for comparison, we can clearly see the differences.
</p>

<p>
We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>. Then we will create a cylinder with a top offset and a regular cylinder for visual comparison.
</p>

<br />
{{< app/3d/tutorial2 >}}
//ExSummary: Please check the following code to find out how to offset the top of a cylinder, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to create a regular cylinder in a scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code demonstrates how to offset the top of a cylinder in a scene.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Entities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
// Initialize cylinder
var cylinder1 = new Cylinder(2, 2, 2, 20, 1, false);

// Create ChildNode
scene.RootNode.CreateChildNode(cylinder1).Transform.Translation = new Vector3(5, 0, 0);

//ExStep:2-
// Intialze second cylinder
var cylinder2 = new Cylinder(2, 2, 2, 20, 1, false);

// Set OffsetTop
cylinder2.OffsetTop = new Vector3(4, 0, 0);

// Create ChildNode
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

