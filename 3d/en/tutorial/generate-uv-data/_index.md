---
title: Aspose.3D Generate uv data
weight: 7700
limit: 
description: Learn how to generate uv data
keywords: [3d scene, generate, uv,data]
url: /tutorial/generate-uv-data
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please review the following code that demonstrates how to generate uv data. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a pyramid in the scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2:The following code shows how to remove and manually add uv data.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
//since all primitive entities in Aspose.3D will have built in UV generation
var mesh = (new Pyramid()).ToMesh();

//put it to the scene
var node = scene.RootNode.CreateChildNode(mesh);
node.Transform.Translation = new Vector3(-1, -4, -4);

//ExStep:2-
//here we manually remove it to assume we have a mesh without UV data
 mesh.VertexElements.Remove(mesh.GetElement(VertexElementType.UV));

//then we can manually generate UV for it
var uv = PolygonModifier.GenerateUV(mesh);

//generated UV data is not associated with the mesh, we should manually do this
mesh.AddElement(uv);

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to generate uv data.

We will create a pyramid and place it in the scene. We will manually delete the <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/vertexelementtype/">uv</a> data, and then we will manually generate uv data for it. The generated uv data is not associated with the mesh, we should manually add to the mesh.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Generate UV](https://docs.aspose.com/3d/net/generate-uv/)
* [API Pyramid](https://reference.aspose.com/3d/net/aspose.threed.entities/pyramid/)
* [API Transform](https://reference.aspose.com/3d/net/aspose.threed/transform/)
* [API Vector3](https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/)
* [API PolygonModifier](https://reference.aspose.com/3d/net/aspose.threed.entities/polygonmodifier/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

