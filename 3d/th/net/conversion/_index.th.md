---
title: C# 3D การแปลงรูปแบบ
url: /th/net/conversion/
description: แปลง 3D รูปแบบ 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x ด้วยโค้ด C# สองสามบรรทัดผ่านไลบรารี .NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D รูปแบบการแปลงผ่าน C#" h2="แปลงรูปแบบเอกสาร 3D โดยไม่มีซอฟต์แวร์สร้างแบบจำลองและการแสดงผล 3D ใดๆ เพื่อสร้างแอปพลิเคชัน .NET ข้ามแพลตฟอร์ม" >}}

{{% blocks/products/pf/feature-page-summary %}}
นักพัฒนาสามารถอ่าน สร้าง แปลง อัปเดต และควบคุมเนื้อหาของรูปแบบ 3D ได้อย่างง่ายดายโดยใช้ไลบรารีกราฟิก 3D รูปแบบที่รองรับบางส่วนโดย API ได้แก่ WavefrontOBJ, Discreet3DS, STL (ASCII, Binary), FBX (ASCII, Binary), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco รูปแบบและอีกมากมาย ขั้นตอนการแปลงทำได้ง่ายเหมือนกับการโหลดไฟล์ต้นฉบับผ่านอินสแตนซ์ของ [ฉากคลาส](https://apireference.aspose.com/3d/net/aspose.threed/scene)และเรียกเมธอด Save ด้วยพารามิเตอร์รูปแบบเอาต์พุตที่เกี่ยวข้อง

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แปลง 3D ฉากเป็นรูปแบบต่างๆ" %}}
นักพัฒนาซอฟต์แวร์สามารถแปลง 3D ฉากได้อย่างง่ายดายโดยใช้กระบวนการเดียวกับที่แสดงด้านบน พิจารณาตัวอย่างบางส่วน เช่น **FBX ถึง OBJ การแปลง** โหลดไฟล์ FBX ผ่านวัตถุ Scene Class สร้างตัวเลือกการบันทึกโดยใช้ [ObjSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/objsaveoptions) และเรียกวิธีบันทึกฉากที่มีเส้นทางไฟล์เอาต์พุตและตัวเลือก obj เป็นพารามิเตอร์ API มีคลาสตัวเลือกที่เหมาะสมสำหรับการบันทึกลงในคลาสที่เกี่ยวข้อง เช่น [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxsaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) และอื่น ๆ. นี่คือรายการทั้งหมดสำหรับ 3D [รูปแบบการแปลง](https://apireference.aspose.com/3d/net/aspose.threed.formats) ตัวเลือก. นอกจากนี้ นักพัฒนายังสามารถบันทึกฉาก 3D ลงใน PDF ได้อย่างง่ายดาย

{{% blocks/products/pf/feature-page-code h3="C# โค้ดสำหรับการแปลง FBX ถึง OBJ" %}}

{{< gist "aspose-com-gists" "ed8b7177c365be75c2bf8d3e668f113a" "convert-fbx-to-obj.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับแปลง 3D ฉากเป็น PDF" %}}

{{< gist "aspose-3d" "631532eeb21c3374f2ed" "Examples-CSharp-Loading-and-Saving-Save3DInPdf-Save3DInPdf.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
