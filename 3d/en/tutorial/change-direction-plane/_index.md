---
title: Aspose.3D Change the direction of a Plane
weight: 7700
limit: 
description: Learn how to change the direction of a Plane
keywords: [3d scene, Plane, direction]
url: /tutorial/change-direction-plane
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Change the direction of a Plane" >}}

<p>
In this tutorial, we will start by using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a> to create a new scene, and then we will create a plane within the 3D scene. By changing the plane's direction using the Up property, we can clearly observe this change.

<br />
{{< app/3d/tutorial >}}
//ExSummary: Please check the following code to find out how to change the direction of a Plane, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to create a plane.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code demonstrates how to change the direction of a plane.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
//Create a plane.
var plane = new Plane(4,4);
var node = scene.RootNode.CreateChildNode(plane);

//ExStep:2-
//Change the direction of the plane
plane.Up = new Vector3(2, 2, 3);

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

