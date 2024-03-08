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

{{< app/3d/tutorial-example >}}


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
//ExLinkCategory: API References
//ExLink: Scene:https://reference.aspose.com/3d/net/aspose.threed/scene/
//ExLink: RectangleShape:https://reference.aspose.com/3d/net/aspose.threed.profiles/rectangleshape/
//ExLink: Transform:https://reference.aspose.com/3d/net/aspose.threed/transform/
//ExLink: LinearExtrusion:https://reference.aspose.com/3d/net/aspose.threed.entities/linearextrusion/
//ExLink: Vector3:https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/
//ExLinkCategory: Documents
//ExLink: Working with Linear Extrusion:https://docs.aspose.com/3d/net/working-with-linear-extrusion/
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we will create two rectangles in the scene. We will apply <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/linearextrusion/">linear extrusion</a> with distortion and slicing attributes to one of the rectangles using the left-side node. For the other rectangle, we will apply linear extrusion with distortion, slicing, and directional attributes using the right-side node. By comparing them, we can clearly observe the differences between the different attributes.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)


{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
