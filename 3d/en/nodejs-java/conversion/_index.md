---
title: Node.js via Java 3D Formats Conversion
url: /nodejs-java/conversion/
description: Convert 3D formats amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x with few lines of Node.js code via Java library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D Formats Conversion Via Node.js" h2="Convert 3D file formats without any 3D modeling and rendering software installation to build Node.js applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
For creating, editing, manipulating and saving three-dimensional graphics applications, **Node.js via Java API** provides high level of methods to do such features without installation of any 3D modeling and rendering software. Few are build the mesh of different three-dimensional geometric shapes, create a 3D scene file, set up normals or UV on the Cube, format elements, add animation property and more. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert 3D File to different formats" %}}
Conversion process is simple. Just load the source 3D file using [Scene class](https://reference.aspose.com/3d/nodejs-java/aspose.threed/scene/). As scene is a top-level object having the nodes, geometries, textures, materials, animation, poses, sub-scenes etc. Create the relevant the [Save options](https://reference.aspose.com/3d/nodejs-java/aspose.threed/saveoptions/) such as AmfSaveOptions, ColladaSaveOptions, Discreet3dsSaveOptions, DracoSaveOptions, FbxSaveOptions, GltfSaveOptions, RvmSaveOptions, StlSaveOptions, U3dSaveOptions etc and set the properties accordingly. Finally call the save method with output file and created target format save options object. Further more, Using the API programmers can even save 3D scene as HTML.


{{% blocks/products/pf/feature-page-code h3="Convert 3D Scene to HTML via Node.js" %}}

{{< highlight java >}}

var aspose = aspose || {};

aspose.threed = require("aspose.threed");

// Initialize a scene
var scene = new aspose.threed.Scene();

scene.getRootNode().createChildNode(new aspose.threed.Cylinder());

var opt =new aspose.threed.Html5SaveOptions();
// Turn off the grid
opt.setShowGrid(false);
//Turn off the user interface
opt.setShowUI(false);

scene.save("html5SaveOption.html");

{{< /highlight >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="3ds-to-obj 3ds-to-stl 3ds-to-drc 3ds-to-rvm 3ds-to-usdz" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
