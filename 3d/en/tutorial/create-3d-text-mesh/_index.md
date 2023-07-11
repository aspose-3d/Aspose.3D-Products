---
title: Aspose.3D Create 3D text mesh
weight: 7700
limit: 
description: Learn how to create 3D text object with material
keywords: [3d scene, text, font, extrusion]
url: /tutorial/create-3d-text-mesh
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Create 3D Text Mesh" >}}

<p>
In this tutorial, we'll learn how to extrude a text profile into a 3D mesh.
</p>

<p>
We'll start by creating a new font instance from file and create a text profile from a string using this font. Then we extrude the text profile into a mesh with a thickness, finally we'll add a material to the mesh. 
</p>

<br />
{{< app/3d/tutorial2 >}}
//ExSummary: Please check the following code to find out how to create a box and attach it to a scene, you can modify the code and run it directly in your browser.
//ExFile: NotoSans-Regular.ttf:/3d/tutorial/NotoSans-Regular.ttf
//ExStepSummary:0: The following code shows how to create a font instance from bytes.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a text profile.
//ExStepImage:1:step-1.png
//ExStepSummary:2: The following code shows how create a mesh by extruding the text profile with a thickness.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;
using Aspose.ThreeD.Profiles;
using Aspose.ThreeD.Utilities;


//Read bytes from font file
var bytes = File.ReadAllBytes("NotoSans-Regular.ttf");
//Parse the font from bytes
var font = FontFile.Parse(bytes);

//Create an empty scene
var scene = new Scene();

//ExStep:1-
//Create a text profile
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;

//ExStep:2-
//Extrude the text profile with a thickness
var mesh = new LinearExtrusion(text, 1).ToMesh();
var ven = PolygonModifier.GenerateNormal(mesh);
mesh.AddElement(ven);
//Create a scene with the mesh and rotate it
var textNode = scene.RootNode.CreateChildNode(mesh);
textNode.Transform.EulerAngles = new Vector3(180, 0, 0);

//initialize PBR material object
PbrMaterial mat = new PbrMaterial();
mat.MetallicFactor = 0.9;
mat.RoughnessFactor = 0.4;
textNode.Material = mat;

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

