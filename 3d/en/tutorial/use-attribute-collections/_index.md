---
title: Aspose.3D Use 3d attribute collections
weight: 7700
limit: 
description: Learn how to use 3d Attribute collections
keywords: [3d scene, use, Attribute, collections]
url: /tutorial/use-attribute-collections
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn How To Use 3D Attribute Collections" >}}

<p>
In this tutorial, we'll learn how to use 3d attribute collections.
</p>

<p>
We first create a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>, and then create a cylinder in the 3D scene. We create a material object, we use the PropertyCollection object to collect the properties of the material object, and then take out the properties according to the name. We can clearly see the changes in the material.
</p>

<br />
{{< app/3d/tutorial2 >}}
//ExSummary: Please check the following code to find out how to use 3d attribute collections, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Create a cylinder in the scene and place the attributes of the node in the PropertyCollection object.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Put the properties of the material in the PropertyCollection object and get the value from it through the property name.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
//Create a cylinder in the scene
var cylinder = new Cylinder();
var node = scene.RootNode.CreateChildNode(cylinder);

//Put the node properties into a PropertyCollection object
PropertyCollection props = node.Properties;

//ExStep:2-
//Create material objects
var material = new PbrMaterial();

//Put material object properties into a PropertyCollection object
PropertyCollection props2 = material.Properties;

//Using material properties from PropertyCollection object
props2["Albedo"] = new Vector3(0, 2, 2);

//Use node properties from PropertyCollection object
props["Material"] = material;

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

