---
title: Aspose.3D File format convert
weight: 7700
limit: 
description: Learn how to do use Aspose.3D to convert 3D file's format
keywords: [3d scene, format, convert]
url: /tutorial/format-convert
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}

//ExSummary: Please check the following code to find out how to deduplicate the mesh and try to reuse existing data like control point, normals as much as possible, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to prepare a sample scene
//ExStepSummary:1: The following code shows how to open the 3D file
//ExStepSummary:2: The following code shows how to resave it to different format
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;
using Aspose.ThreeD.Profiles;
using Aspose.ThreeD.Utilities;


//We prepare a sample 3D file with a simple mesh
(new Scene(new Box())).Save("test-input.fbx");

//ExStep:1-
// Load a FBX file 
var scene = Scene.FromFile("test-input.fbx"); 

//ExStep:2-
// Save the FBX file into a USD file
scene.Save("test-output.usd");

//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to use `Scene.FromFile` to load a 3D scene from file, and use `Scene.Save` to save it to file.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}