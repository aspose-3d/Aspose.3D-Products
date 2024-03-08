---
title: Aspose.3D Triangulate a 3D mesh
weight: 7700
limit: 
description: Learn how to triangulate a 3D mesh
keywords: [3d scene, triangulate]
url: /tutorial/triangulate-3d-mesh
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to triangulate an ordinal mesh, you can modify the code and run it directly in your browser.
//ExPostExecuteCommand:shading:wireframe
//ExStart
//ExStepSummary:0: Prepare an ordinal mesh, you can see this cylinder is made of quadrangles.
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;
using Aspose.ThreeD.Profiles;
using Aspose.ThreeD.Utilities;


var mesh = new Cylinder().ToMesh();

//ExStep:1-1
//ExStepSummary:1: The following code shows how to triangulate an ordinal mesh
//Triangulate this quadrangle-based mesh to triangle-based 
mesh = mesh.Triangulate();


//ExStep:0-
var scene = new Scene(mesh);

//Render the cylinder
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to triangulate a 3D mesh.

We'll start by creating a new cylinder mesh. Then we triangulate the mesh and render it in wireframe.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [API Mesh](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/)
* [API Mesh.Triangulate](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/triangulate/)
* [API PolygonModifier.Triangulate](https://reference.aspose.com/3d/net/aspose.threed.entities/polygonmodifier/triangulate/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}