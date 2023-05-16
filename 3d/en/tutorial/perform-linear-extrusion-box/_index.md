---
title: Aspose.3D Create box with material
weight: 7700
limit: 
description: Learn how to use center and slices property to perform linear extrusion in a Box
keywords: [3d scene, Box, linear extrusion,profile]
url: /tutorial/perform-linear-extrusion-box
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Perform Linear Extrusion In A Box" >}}

<p>
In this tutorial, we will create two box objects and then <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/linearextrusion/">linear extrusion</a> them. We will perform this series of operations by using the center and slices property. Finally, by comparing the box objects in the scene, the differences can be clearly seen.
</p>

<br />
{{< app/3d/tutorial >}}
//ExSummary: Please review the following code that demonstrates how to use center and slices property to perform linear extrusion in a Box. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The following code demonstrates how to create two box objects.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates the effect of linear extrusion on the left box.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code demonstrates the effect of linear extrusion on the right box, and compares it with the left box.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//Create a new 3D scene
Scene scene = new Scene();

// Initialize the base profile to be extruded
var profile = new RectangleShape()
{
    RoundingRadius = 0.3
};

// Create left node
var left = scene.RootNode.CreateChildNode();
left.CreateChildNode(new Box(0.01, 3, 3));

// Create right node
var right = scene.RootNode.CreateChildNode();
right.CreateChildNode(new Box(0.01, 3, 3));
right.Transform.Translation = new Vector3(5, 0, 0);

//ExStep:1-
//Perform linear extrusion on left node using center and slices property
left.CreateChildNode(new LinearExtrusion(profile, 3) { Center = false, Slices = 3 });

//ExStep:2-
// Perform linear extrusion on left node using center and slices property
right.CreateChildNode(new LinearExtrusion(profile, 3) { Center = true, Slices = 3 });

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

