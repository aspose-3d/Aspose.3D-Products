---
title: Aspose.3D set the coordinates of a sphere
weight: 7700
limit: 
description: Learn how to set the Coordinates of a Sphere
keywords: [3d scene, Coordinates, Sphere]
url: /tutorial/set-coordinates-sphere
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to set the coordinates of a Sphere, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to set up a sphere with a radius of 1.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to set coordinate attributes for a sphere.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
// Set a sphere with a radius of 1 (Using Radius property you can get or set radius of Sphere)
scene.RootNode.CreateChildNode(new Sphere() { Radius = 1 }).Transform.Translation = new Vector3(-4, 0, 0);

//ExStep:2-
// Set the coordinates of the sphere
scene.RootNode.CreateChildNode(new Sphere() { Radius = 1.5,ThetaStart=1,ThetaLength=7, PhiLength = 5, PhiStart = 2 }).Transform.Translation = new Vector3(2, 0, 0);

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to set the coordinates of a sphere.

We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>.Then we will create two spheres with different radii. We will set the coordinate attributes for one of the spheres, and we can clearly see the differences.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Working with Radius of Sphere](https://docs.aspose.com/3d/net/working-with-radius-of-sphere/)
* [API Transform](https://reference.aspose.com/3d/net/aspose.threed/transform/)
* [API PhiLength](https://reference.aspose.com/3d/net/aspose.threed.entities/sphere/philength/)
* [API Radius](https://reference.aspose.com/3d/net/aspose.threed.entities/sphere/radius/)
* [API ThetaLength](https://reference.aspose.com/3d/net/aspose.threed.entities/sphere/thetalength/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

