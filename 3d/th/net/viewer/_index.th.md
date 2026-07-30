---
title: ตัวอย่างรูปแบบ 3 มิติ C#
url: /th/net/viewer/
description: ดูรูปแบบ 3 มิติ 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x ผ่านไลบรารี .NET โดยใช้โค้ด C# ไม่กี่บรรทัด
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="ตัวแสดงรูปแบบ 3 มิติผ่าน C#" h2="ดูรูปแบบเอกสาร 3 มิติโดยไม่มีซอฟต์แวร์สร้างแบบจำลองและเรนเดอร์ 3 มิติเพื่อสร้างแอปพลิเคชัน .NET แบบข้ามแพลตฟอร์ม" >}}

{{% blocks/products/pf/feature-page-summary %}}
นักพัฒนาสามารถใช้ไลบรารีกราฟิก 3 มิติเพื่ออ่าน สร้าง แปลง ปรับปรุง และควบคุมเนื้อหาในรูปแบบ 3 มิติได้อย่างง่ายดาย รูปแบบต่างๆ ที่รองรับโดย API ได้แก่ WavefrontOBJ, Discreet3DS, STL (ASCII, Binary), FBX (ASCII, Binary), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco formats เป็นต้น กระบวนการดูนั้นง่ายมาก โหลดไฟล์ต้นทางผ่านอินสแตนซ์ของ [scene class](https://apireference.aspose.com/3d/net/aspose.threed/scene) และเรียกใช้เมธอด Save พร้อมกับพารามิเตอร์รูปแบบเอาต์พุตที่เกี่ยวข้อง

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="ดู Scene 3 มิติไปยังรูปแบบต่างๆ" %}}
นักพัฒนาสามารถดูไฟล์ 3 มิติได้อย่างง่ายดายผ่านกระบวนการเดียวกันที่ระบุไว้ข้างต้น ลองพิจารณาตัวอย่างเช่น **3DS to HTML5 viewing** โหลดไฟล์ 3DS ผ่านอ็อบเจ็กต์ scene class สร้างตัวเลือกบันทึกโดยใช้ [Html5SaveOptions ](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5SaveOptions) เพื่อสร้างตัวเลือกบันทึก และเรียกใช้เมธอดบันทึก scene พร้อมกับอาร์กิวเมนต์พาธไฟล์เอาต์พุตและตัวเลือก html5 API มีคลาสตัวเลือกที่เหมาะสมสำหรับการบันทึกลงในคลาสที่เกี่ยวข้อง เช่น [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) และอื่นๆ นี่คือรายการรูปแบบ [viewer 3 มิติ](https://apireference.aspose.com/3d/net/aspose.threed.formats) ทั้งหมด

{{% blocks/products/pf/feature-page-code h3="Code C# สำหรับ 3DS to HTML5 Viewer" %}}

{{< gist "aspose-3d-gists" "9563193e834f0087b554c83130fcf7c7" "Examples-CSharp-Viewer-products.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Viewer" >}}
{{< /blocks/products/pf/feature-page-wrap >}}