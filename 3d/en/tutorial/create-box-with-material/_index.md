---
title: Aspose.3D Create box with material
weight: 7700
limit: 
description: Learn how to create Box with material
keywords: [3d scene, Box, prb material]
url: /tutorial/create-box-with-material
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Create Box with material" >}}

<p>
In this tutorial, we will create a box in a 3D scene and apply materials to it. <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/">Materials</a> are a powerful feature of 3D, and adding materials to it can make the scene visually more attractive.
</p>

<p>
We'll start by creating a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a> and create a box. Then we will add metal materials to the box and make the surface rough. Finally, we will attach this box to the scene.
</p>

<br />
{{< app/3d/tutorial2 >}}
//ExSummary: Please check the following code to find out how to create a box and attach it to a scene, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a box in a scene.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to add metal material to the box and make its surface rough.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
//create a box to which the material will be applied
var boxNode = scene.RootNode.CreateChildNode("box", new Box());

//ExStep:2-
//initialize PBR material object
PbrMaterial mat = new PbrMaterial();

// an almost metal material
mat.MetallicFactor = 0.9;

// material surface is very rough
mat.RoughnessFactor = 0.4;

boxNode.Material = mat;

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

