---
title: Aspose.3D Deduplicate mesh data
weight: 7700
limit: 
description: Learn how to do optimize and deduplicate mesh data
keywords: [3d scene, mesh, optimization, deduplicate]
url: /tutorial/deduplicate-mesh-data
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}

//ExSummary: Please check the following code to find out how to deduplicate the mesh and try to reuse existing data like control point, normals as much as possible, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a scene with a box mesh.
//ExStepSummary:1: The following code shows how to deduplicate control points, vertex data.
//ExPostExecuteCommand:shading:wireframe
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;
using Aspose.ThreeD.Profiles;
using Aspose.ThreeD.Utilities;


//This feature has trial limits, turn the exception off temporarily(limits will not be lifted).
TrialException.SuppressTrialException = true;

var scene = new Scene();

//Here create a scene without using Boolean, the scene actually contains two meshes but overlapped together:
var box = new Box().ToMesh();
Console.WriteLine($"There're {box.ControlPoints.Count} control points for unoptimized box mesh.");

//ExStep:0-0
scene.RootNode.CreateChildNode(box);

//ExStep:1-

//Now we use `Optimize` to deduplicate the control points.
var optimized = box.Optimize(false);
Console.WriteLine($"There're {optimized.ControlPoints.Count} control points for optimized box mesh.");
scene.RootNode.CreateChildNode(optimized);



//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to use `Mesh.Optimize` to deduplicate control points and vertex element like normals, texture coordinates.

We'll start by creating one mesh, then we deduplicate by using `Mesh.Optimize` method, in each step we'll print the number of control points to output.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [API Optimize](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/doboolean)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}