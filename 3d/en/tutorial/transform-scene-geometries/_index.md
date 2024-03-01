---
title: Aspose.3D Transform scene's geometries 
weight: 7700
limit: 
description: Learn how to transform scene's geometries.
keywords: [3d scene, transform, geometries]
url: /tutorial/transform-scene-geometries
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to transform scene's geometries, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a box and transform it.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to scale the box proportionally.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to perform Euler angle transformation on a box.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Entities;

//Create a new 3D scene
Scene scene = new Scene();

//Create a box and transform it
var box = new Box();
var tr = scene.RootNode.CreateChildNode(box).Transform;
tr.Translation = new Vector3(3, 0, 0);

//ExStep:1-
//Scale the box proportionally
tr.Scale = new Vector3(2, 2, 2);

//ExStep:2-
//Box Euler angle transformation
tr.EulerAngles = new Vector3(10, 17, 0);

//ExStep:0-
tr = scene.RootNode.CreateChildNode(box).Transform;
scene
//ExEnd
//ExLinkCategory: API References
//ExLink: Scene:https://reference.aspose.com/3d/net/aspose.threed/scene/
//ExLink: Vector3:https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/
//ExLink: Box:https://reference.aspose.com/3d/net/aspose.threed.entities/box/
//ExLink: Transform:https://reference.aspose.com/3d/net/aspose.threed/transform/
//ExLinkCategory: Documents
//ExLink: Scale geometries of a 3D Scene:https://docs.aspose.com/3d/net/scale-geometries-of-a-3d-scene/
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we will create a box in a 3D file and perform transformation operations. We will transform the box, scale it proportionally, and transform its Euler angles. Can enrich your various operations on 3D models.

We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a> and create a box. Then we will perform a series of transformation operations. Finally, we can see the entire transformation process of the box.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)


{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
