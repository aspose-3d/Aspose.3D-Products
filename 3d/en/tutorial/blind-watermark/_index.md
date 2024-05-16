---
title: Aspose.3D Encode and decode blind watermark
weight: 7700
limit: 
description: Learn how to apply blind watermark on your 3D file.
keywords: [blind,watermark,encode,decode,password,copyright]
url: /tutorial/blind-watermark
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to change the direction of a Plane, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a sample box mesh
//ExStepSummary:1: The following code demonstrates how to encode blind watermark to the mesh
//ExStepSummary:2: The following code demonstrates how to decode blind watermark from mesh
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;


//Create a sample mesh used for encoding blind watermark
Mesh mesh = (new Box()).ToMesh();


//ExStep:1-
//Apply watermark, the utility will return a new mesh with invisible watermark applied.
mesh = Watermark.EncodeWatermark(mesh, "Copyright by Aspose.3D");
//Save the mesh to file, here we use STL to verify the watermark, which only saves position and normal data.
(new Scene(mesh)).Save("copyright.stl");

//ExStep:2-
//Now we decode the blind watermark from file

mesh = Scene.FromFile("copyright.stl").RootNode.ChildNodes[0].GetEntity<Mesh>();

//See if the watermark was applied correctly
var watermark = Watermark.DecodeWatermark(mesh);
Console.WriteLine($"Watermark in file: {watermark}");

//ExStep:0-
//visualize the mesh
new Scene(mesh)

//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}


Aspose.3D's blind watermark feature is an advanced tool designed for embedding hidden watermarks within 3D models, enhancing digital asset protection. This functionality allows users to insert imperceptible watermarks that do not alter the visual quality of the 3D content, ensuring that the ownership and copyright information are preserved. Ideal for industries dealing with sensitive 3D data, this feature provides a robust method for safeguarding intellectual property against unauthorized use and distribution, while maintaining the integrity and appearance of the original models.


In this tutorial, we will start by using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a> to create a new scene, and then we will create a sample mesh within the 3D scene. Then we encode blind watermark to the mesh and save it to file, later we decode the watermark from this file.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Watermark](https://products.aspose.app/3d/watermark)
* [3D Watermark Verification](https://products.aspose.app/3d/verify-watermark)
* [API Watermark](https://reference.aspose.com/3d/net/aspose.threed.utilities/watermark/)
* [API Mesh](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

