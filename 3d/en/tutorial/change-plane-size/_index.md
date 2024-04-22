---
title: Aspose.3D Change the plane size
weight: 7700
limit: 
description: Learn how to Change the Plane size
keywords: [3d scene, change, size, Plane]
url: /tutorial/change-plane-size
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to change the plane size, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a plane in the scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to use the Length and Width attributes to change the plane size.
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
var plane = new Plane(3,3);
var node = scene.RootNode.CreateChildNode(plane);

//ExStep:2-
//Change the length of the plane
plane.Length = 6;

//Change the width of the plane
plane.Width=7;

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to change the plane size.

We first create a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>, and then create a plane in the 3D scene. We change the size of the plane through the Length and Width properties, and we can clearly observe this change.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Changing Plane Orientation](https://docs.aspose.com/3d/net/changing-plane-orientation/)
* [API Plane](https://reference.aspose.com/3d/net/aspose.threed.entities/plane/)
* [API Length](https://reference.aspose.com/3d/net/aspose.threed.entities/plane/length/)
* [API Width](https://reference.aspose.com/3d/net/aspose.threed.entities/plane/width/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

