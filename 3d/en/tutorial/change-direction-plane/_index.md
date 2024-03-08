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

{{< app/3d/tutorial-example >}}


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
//ExLinkCategory: API References
//ExLink: Scene:https://reference.aspose.com/3d/net/aspose.threed/scene/
//ExLink: Vector3:https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/
//ExLink: Plane:https://reference.aspose.com/3d/net/aspose.threed.entities/plane/
//ExLink: Up:https://reference.aspose.com/3d/net/aspose.threed.entities/plane/up/
//ExLinkCategory: Documents
//ExLink: Changing Plane Orientation:https://docs.aspose.com/3d/net/changing-plane-orientation/
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we will start by using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a> to create a new scene, and then we will create a plane within the 3D scene. By changing the plane's direction using the Up property, we can clearly observe this change.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)


{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

