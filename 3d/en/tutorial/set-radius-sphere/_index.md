---
title: Aspose.3D Set the radius of a sphere
weight: 7700
limit: 
description: Learn how to set the radius of a Sphere
keywords: [3d scene, Sphere, radius]
url: /tutorial/set-radius-sphere
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to set the radius of a Sphere, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code demonstrates how to set up a sphere with a radius of 1.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code demonstrates how to set up a sphere with a radius of 1.5 for comparison.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
// Set Sphere Radius (Using Radius property you can get or set radius of Sphere)
scene.RootNode.CreateChildNode(new Sphere() { Radius = 1 }).Transform.Translation = new Vector3(-4, 0, 0);

//ExStep:2-
// Set the sphere radius to 1.5
scene.RootNode.CreateChildNode(new Sphere() { Radius = 1.5 }).Transform.Translation = new Vector3(2, 0, 0);

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we will create two spheres in a 3D scene and modify their sizes using the Radius property. By comparing them, we can clearly see the difference in sphere sizes.

We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>. Then we will create two spheres with different radii for visual comparison.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Working with Radius of Sphere](https://docs.aspose.com/3d/net/working-with-radius-of-sphere/)
* [API Transform](https://reference.aspose.com/3d/net/aspose.threed/transform/)
* [API Vector3](https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/)
* [API Radius](https://reference.aspose.com/3d/net/aspose.threed.entities/sphere/radius/)
* [API Sphere](https://reference.aspose.com/3d/net/aspose.threed.entities/sphere/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

