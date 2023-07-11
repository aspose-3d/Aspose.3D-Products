---
title: Aspose.3D Use Phong material to PBR material
weight: 7700
limit: 
description: Learn how to use Phong material to PBR material
keywords: [3d scene, Phong material, PBR material]
url: /tutorial/use-phong-material-to-pbr-material
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Use Phong Material To PBR Material" >}}

<p>
In this tutorial, we'll learn how to use phong material to pbr material.
</p>

<p>
We'll create a box object, add a Phong material to it, and attach the box to the scene. We will customize the material converter to convert <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/phongmaterial/">PhongMaterial</a> to <a href="https://reference.aspose.com/3d/net/aspose.threed.shading/pbrmaterial/">PbrMaterial</a>.
</p>

<br />
{{< app/3d/tutorial >}}
//ExSummary: Please review the following code that demonstrates how to use phong material to pbr material. You can make changes to the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to add the Phong material to the box.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to customize the material converter.
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
//Create a new box object
var box = new Box();

//Add Phong material to the box object
scene.RootNode.CreateChildNode("box1", box).Material = new PhongMaterial() { DiffuseColor = new Vector3(1, 0, 1) };

//ExStep:2-
//Create format options that need to be saved
GltfSaveOptions opt = new GltfSaveOptions(FileFormat.GLTF2);

//Custom material converter to convert PhongMaterial to PbrMaterial
opt.MaterialConverter = delegate (Material material)
{
    PhongMaterial m = (PhongMaterial)material;
    return new PbrMaterial() { Albedo = new Vector3(m.DiffuseColor.x, m.DiffuseColor.y, m.DiffuseColor.z) };
};

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial >}}
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

