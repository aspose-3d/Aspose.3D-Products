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

{{< app/3d/tutorial-example >}}


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
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to set the rendering mode of geometry.

We'll create a cylinder and add a Phong <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/material/">material</a> to it so it changes. We will set the save object PdfSaveOptions. We will set the lighting scheme and rendering mode through the PdfSaveOptions object.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [Non-PBR to PBR Material Conversion](https://docs.aspose.com/3d/net/customize-non-pbr-to-pbr-materials-conversion-before-saving-3d-scenes-to-gltf-2-0-format/#non-pbr-to-pbr-material-conversion)
* [API Vector3](https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/)
* [API PhongMaterial](https://reference.aspose.com/3d/net/aspose.threed.shading/phongmaterial/)
* [API PdfSaveOptions](https://reference.aspose.com/3d/net/aspose.threed.formats/pdfsaveoptions/)
* [API PdfLightingScheme](https://reference.aspose.com/3d/net/aspose.threed.formats/pdflightingscheme/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

