---
title: Aspose.3D Create mesh from linear extrusion
weight: 7700
limit: 
description: Learn how to create a mesh using linear extrusion on a 2D shape
keywords: [3d scene, linear extrusion, profile, shape]
url: /tutorial/split-mesh-using-sub-materials
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Split Mesh Using sub materials" >}}

<p>
In this tutorial, we'll create a mesh from a <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/box/">box</a> and then manually assign sub material id for each polygon through a <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/vertexelementmaterial/">VertexElementMaterial</a>. Next we will <a href="https://reference.aspose.com/3d/net/aspose.threed.entities/polygonmodifier/splitmesh/">split</a> the mesh into sub meshes using Aspose.3D's builtin algorithm. Finally, we will display the sub meshes on the 3D view.

</p>

<br />
{{< app/3d/tutorial2 >}}
//ExSummary: Please review the following code that demonstrates how to split a mesh by sub material id. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The code below demonstrates how to create a new 3D scene with a box mesh.
//ExStepImage:0:step-0.png
//ExStepSummary:1: The following code demonstrates how to use sub material to split the box mesh.
//ExStepImage:1:step-0.png
//ExStepSummary:2: The following code demonstrates how to use different transform to see different sub mesh.
//ExStepImage:2:step-2.png
//ExStart
//ExStep:0-

using Aspose.ThreeD;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Profiles;

//Create a new 3D scene 
var scene = new Scene();
var mesh = (new Box()).ToMesh();
//ExStep:0-0
//Attach the mesh to the scene to we can see it
scene.RootNode.CreateChildNode(mesh);

//ExStep:1-
//Create a material vertex element so we can manually assign material id to different polygons
var materials = mesh.CreateElement(VertexElementType.Material) as VertexElementMaterial;
materials.Indices.Add(0);
materials.Indices.Add(0);
materials.Indices.Add(0);
materials.Indices.Add(1);
materials.Indices.Add(1);
materials.Indices.Add(1);
//Default value is MappingMode.AllSame, we need to map the sub material id by polygon.
//then the first sub mesh is from polygon 0,1,2, and second sub mesh is from polygon 3,4,5
materials.MappingMode = MappingMode.Polygon;

var meshes = PolygonModifier.SplitMesh(mesh, SplitMeshPolicy.CloneData);

//ExStep:1-1
//attach two sub meshes to different nodes so we can see them, but it looks like there's only one mesh.
scene.RootNode.CreateChildNode(meshes[0]);
scene.RootNode.CreateChildNode(meshes[1]);

//ExStep:2-2
//Make each sub mesh to use different translation, then we can see two meshes.
scene.RootNode.CreateChildNode(meshes[0]).Transform.Translation = new Vector3(0, 1, 0);
scene.RootNode.CreateChildNode(meshes[1]).Transform.Translation = new Vector3(0, -1, 0);


//ExStep:0-
scene

//ExEnd


{{< /app/3d/tutorial2 >}}
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

