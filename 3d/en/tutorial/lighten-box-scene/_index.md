---
title: Aspose.3D Lighten boxes in a scene
weight: 7700
limit: 
description: Learn how to lighten Boxes in a scene
keywords: [3d scene, Box, lighten]
url: /tutorial/lighten-box-scene
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To lighten Boxes in a scene" >}}

<p>
In this tutorial, we will create two different boxes by setting the CastShadows and ReceiveShadows properties. We will light up the boxes in the scene by creating a Light object.
</p>

<p>
We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>.  Then we will create two boxes with different attributes, and finally we will light them up.
</p>

<br />
{{< app/3d/tutorial >}}
//ExSummary: Please check the following code to find out how to lighten boxes in a scene, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to create two boxes with different properties in a scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code demonstrates how to illuminate a box in the scene.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Shading;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
// Create a box don't cast shadows
Mesh m1 = (new Box()).ToMesh();
m1.CastShadows = false;
Node box1 = scene.RootNode.CreateChildNode("box1", m1);
box1.Transform.Translation = new Vector3(-1, 4, 4);

//Create a box that don't receive shadow but cast shadows
Mesh m2 = (new Box()).ToMesh();
m2.ReceiveShadows = false;
Node box2 = scene.RootNode.CreateChildNode("box2", m2);
box2.Transform.Translation = new Vector3(2, 4, 4);

//ExStep:2-
//Create a Light object to light up the box
Camera camera = new Camera();
camera.NearPlane = 0.1;
scene.RootNode.CreateChildNode("camera", camera);
Light light;
scene.RootNode.CreateChildNode("light", light = new Light()
{
    NearPlane = 0.1,
    CastShadows = true,
    Color = new Vector3(0,30,40)
}).Transform.Translation = new Vector3(9.4785, 5, 3.18);
light.LookAt = Vector3.Origin;
light.Falloff = 90;

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

