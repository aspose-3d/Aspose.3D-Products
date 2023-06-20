---
title: Aspose.3D Perform linear extrusion using twist offset
weight: 7700
limit: 
description: Learn how to Perform linear extrusion using twist offset
keywords: [3d scene, linear extrusion, twist offset]
url: /tutorial/perform-linear-extrusion-twist-offset
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Perform Linear Extrusion using Twist Offset" >}}

<p>
In this tutorial, we will create two rectangles in the scene. We will apply a <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/linearextrusion/">linear extrusion</a> to one of the rectangles using the TwistOffset property, allowing us to observe the changes to the rectangle caused by the current attribute. By comparing the two rectangles, we can clearly see the differences.
</p>

<br />
{{< app/3d/tutorial >}}
//ExSummary: Please review the following code that demonstrates how to Perform linear extrusion using Twist Offset. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The following code demonstrates how to create a new 3D scene and initialize a rectangle.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates performing linear extrusion on the left node using twist and slices property.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code demonstrates performing linear extrusion on the right node using twist, twist offset and slices property.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

// Initialize the base profile to be extruded
var profile = new RectangleShape()
{
    RoundingRadius = 0.3
};

//Create a scene 
Scene scene = new Scene();

//ExStep:1-
// Create left node
var left = scene.RootNode.CreateChildNode();
left.Transform.Translation = new Vector3(-5, -3,-4);

// Perform linear extrusion on left node using twist and slices property
left.CreateChildNode(new LinearExtrusion(profile, 7) { Twist = 360, Slices = 100 });

//ExStep:2-
// Create right node
var right = scene.RootNode.CreateChildNode();
right.Transform.Translation = new Vector3(3,-4,-4);

// TwistOffset property is the translate offset while rotating the extrusion.
//Perform linear extrusion on right node using twist, twist offset and slices property
right.CreateChildNode(new LinearExtrusion(profile, 7) { Twist = 360, Slices = 100, TwistOffset = new Vector3(2, 0, 0)});

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

