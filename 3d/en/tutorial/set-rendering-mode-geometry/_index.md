---
title: Aspose.3D Set the Rendering mode of geometry
weight: 7700
limit: 
description: Learn how to set the Rendering mode of geometry
keywords: [3d scene, Rendering, geometry]
url: /tutorial/set-rendering-mode-geometry
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Set The Rendering Mode Of Geometry" >}}

<p>
In this tutorial, we'll learn how to set the rendering mode of geometry.
</p>

<p>
We'll create a cylinder and add a Phong <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/material/">material</a> to it so it changes. We will set the save object PdfSaveOptions. We will set the lighting scheme and rendering mode through the PdfSaveOptions object.
</p>

<br />
{{< app/3d/tutorial2 >}}
//ExSummary: Please review the following code that demonstrates how to set the rendering mode of geometry. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to create a cylinder in the scene and add a material.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to set the lighting scheme and rendering mode.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Formats;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
//Define material objects
var material = new PhongMaterial();
material.DiffuseColor = new Vector3(1, 2, 1);

// Create a cylinder child node
 scene.RootNode.CreateChildNode("cylinder", new Cylinder()).Material = material;

//ExStep:2-
//Set save options
PdfSaveOptions opt = new PdfSaveOptions();

//Set up a lighting scheme
opt.LightingScheme = PdfLightingScheme.CAD;

// Set rendering mode
opt.RenderMode = PdfRenderMode.ShadedIllustration;

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

