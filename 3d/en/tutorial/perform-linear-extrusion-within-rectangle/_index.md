---
title: Aspose.3D Perform linear extrusion within a rectangle
weight: 7700
limit: 
description: Learn how to Perform linear extrusion within a Rectangle
keywords: [3d scene, Rectangle, linear extrusion]
url: /tutorial/perform-linear-extrusion-within-rectangle
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Perform linear extrusion within a rectangle" >}}

<p>
In this tutorial, we will create two rectangles in the scene. We will apply linear extrusion with distortion and slicing attributes to one of the rectangles using the left-side node. For the other rectangle, we will apply linear extrusion with distortion, slicing, and directional attributes using the right-side node. By comparing them, we can clearly observe the differences between the different attributes.
</p>

<br />
{{< app/3d/tutorial >}}
//ExSummary: Please check the following code to find out how to perform linear extrusion within a rectangle, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene and create node locations.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows performing linear extrusion on the left node using twist and slice attributes.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows performing linear extrusion on the right node using twist, slice, and orientation properties.
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

// Create a scene 
Scene scene = new Scene();

// Create left node
var left = scene.RootNode.CreateChildNode();
left.Transform.Translation = new Vector3(-4, -3,-4);

// Create right node
var right = scene.RootNode.CreateChildNode();
right.Transform.Translation = new Vector3(1,-3,-4);

//ExStep:1-
// Direction property defines the direction of the extrusion.
// Perform linear extrusion on left node using twist and slices property
left.CreateChildNode(new LinearExtrusion(profile, 7) { Twist = 360, Slices = 100 });

//ExStep:2-
// Perform linear extrusion on right node using twist, slices, and direction property
right.CreateChildNode(new LinearExtrusion(profile, 7) { Twist = 360, Slices = 100, Direction = new Vector3(0.7, 0.4, 0.7) });

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

