---
title: ดึงข้อมูล Assets ในรูปแบบ 3D C#
url: /th/net/extractor/
description: ดึง Assets จากรูปแบบ 3 มิติ 3ds 3mf amf ase att dae dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x ผ่านไลบรารี .NET โดยใช้โค้ด C# เพียงไม่กี่บรรทัด
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="ดึงข้อมูลจากรูปแบบ 3 มิติผ่าน C#" h2="ดึงข้อมูลจากรูปแบบเอกสาร 3 มิติโดยไม่ต้องใช้ซอฟต์แวร์สร้างแบบจำลองและเรนเดอร์ 3 มิติเพื่อสร้างแอปพลิเคชัน .NET แบบข้ามแพลตฟอร์ม" >}}

{{% blocks/products/pf/feature-page-summary %}}
นักพัฒนาสามารถใช้ไลบรารี 3 มิติเพื่อดึงข้อมูลไฟล์ 3 มิติได้อย่างง่ายดาย รูปแบบต่างๆ ที่รองรับโดย API ได้แก่ WavefrontOBJ, Discreet3DS, STL (ASCII, Binary), FBX (ASCII, Binary), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco formats เป็นต้น กระบวนการดึงข้อมูลนั้นง่าย เพียงโหลดไฟล์ต้นทางผ่านอินสแตนซ์ของ [scene class](https://apireference.aspose.com/3d/net/aspose.threed/scene), สร้างคลาส archive และจัดการคลาสการดึงข้อมูลสินทรัพย์ และเรียกใช้ วิธี Save สำหรับพารามิเตอร์รูปแบบเอาต์พุตที่เกี่ยวข้อง

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section  h2="ดึงข้อมูลจาก Scene 3 มิติไปยังรูปแบบต่างๆ" %}}
นักพัฒนาสามารถดึงข้อมูลจากไฟล์ 3 มิติได้อย่างง่ายดายผ่านกระบวนการเดียวกันที่ระบุไว้ข้างต้น ลองพิจารณาตัวอย่างเช่น **3DS to FBX Extractor** โหลดไฟล์ 3DS ผ่านออบเจ็กต์ scene class สร้างตัวเลือกบันทึกด้วย [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions) เพื่อสร้างตัวเลือกบันทึก และเรียกใช้เมธอดบันทึก scene พร้อมกับอาร์กิวเมนต์พาธไฟล์เอาต์พุตและตัวเลือก fbx API มีคลาสตัวเลือกที่เหมาะสมสำหรับการบันทึกไปยังคลาสที่เกี่ยวข้อง เช่น [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) และอื่นๆ นี่คือรายการรูปแบบ [ตัวดึงข้อมูล](https://apireference.aspose.com/3d/net/aspose.threed.formats) 3 มิติทั้งหมด

{{% blocks/products/pf/feature-page-code h3="โค้ด C# สำหรับ 3DS to FBX ดึงข้อมูลสินทรัพย์" %}}

{{< gist "aspose-3d-gists" "9563193e834f0087b554c83130fcf7c7" "Examples-CSharp-Extractor-products.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Extractor" >}}
{{< /blocks/products/pf/feature-page-wrap >}}