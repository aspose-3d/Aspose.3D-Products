﻿---
title: แปลง PLY เป็น OBJ ผ่าน C# 
weight: 2060
url: /th/net/conversion/ply-to-obj/ 
description: โค้ดตัวอย่างสำหรับการแปลง PLY ถึง OBJ C# ใช้ API โค้ดตัวอย่างสำหรับแบตช์ PLY ไฟล์เป็น OBJ การแปลงภายใน VB.NET, Asp.NET หรือแอปพลิเคชันตาม .NET ใดๆ
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง PLY เป็น OBJ ผ่าน C#" h2="แสดงผล PLY เป็น OBJ โดยไม่ต้องใช้ซอฟต์แวร์สร้างแบบจำลองและการแสดงผล 3D" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง PLY เป็น OBJ โดยใช้ C#" %}}

 ในการแปลง PLY เป็น OBJ เราจะใช้
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API ซึ่งเป็นการจัดการและการแปลงเอกสารที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย API สำหรับแพลตฟอร์ม C# เปิด
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 package manager ค้นหา
 Aspose.3D 
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="คำสั่งคอนโซลตัวจัดการแพ็คเกจ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง PLY เป็น OBJ ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

 โปรแกรมเมอร์ .NET สามารถโหลดและแปลงไฟล์ PLY เป็น OBJ ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ PLY ผ่านตัวสร้างของ Scene class1. สร้างอินสแตนซ์ของ ObjSaveOptions1. ตั้งค่า OBJ คุณสมบัติเฉพาะสำหรับการแปลงขั้นสูง1. เรียกวิธี Scene.Save1. ส่งเส้นทางเอาต์พุตด้วย OBJ นามสกุลไฟล์ & อ็อบเจ็กต์ของ ObjSaveOptions1. ตรวจสอบไฟล์ผลลัพธ์ OBJ ที่เส้นทางที่ระบุ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ด Conversion .NET ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio- Aspose.3D for .NET DLL ที่อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่างนี้แสดงการแปลง PLY ถึง OBJ C#" offSpacer="" %}}

```cs
// โหลด PLY ในวัตถุของ Scene 
var document = new Aspose.ThreeD.Scene("template.ply");
// สร้างอินสแตนซ์ของ ObjSaveOptions 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// บันทึก PLY เป็น OBJ 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="แอปฟรีสำหรับแปลง PLY เป็น OBJ" sectionDescription="ตรวจสอบการสาธิตสดของเราสำหรับ [PLY เป็น OBJ แปลง](https://products.aspose.app/3d/conversion/ply-to-obj) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไร" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ PLY ของคุณแล้วกดปุ่ม \"แปลง\"" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงก์ดาวน์โหลดสำหรับไฟล์ผลลัพธ์ OBJ ทันที" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D ไลบรารีการประมวลผลไฟล์เพื่อจัดการไฟล์ 3D โดยไม่ต้องใช้ซอฟต์แวร์สร้างแบบจำลองและแสดงผล 3D API รองรับ Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, รูปแบบไฟล์ PLY, DirectX, Google Draco และอีกมากมาย นักพัฒนาสามารถสร้าง อ่าน แปลง แก้ไข และควบคุมเนื้อหาของรูปแบบเอกสาร 3D รูปแบบได้อย่างง่ายดาย



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}
PLY รูปแบบไฟล์รูปหลายเหลี่ยม หมายถึง 3D รูปแบบไฟล์ที่เก็บอ็อบเจ็กต์กราฟิกที่อธิบายว่าเป็นคอลเล็กชันของรูปหลายเหลี่ยม จุดประสงค์ของรูปแบบไฟล์นี้คือเพื่อสร้างไฟล์ประเภทที่ง่ายและสะดวกซึ่งโดยทั่วไปจะมีประโยชน์สำหรับรุ่นต่างๆ รูปแบบไฟล์ PLY มาในรูปแบบ ASCII เช่นเดียวกับรูปแบบไบนารีสำหรับพื้นที่เก็บข้อมูลขนาดกะทัดรัด และสำหรับการบันทึกและโหลดอย่างรวดเร็ว รูปแบบไฟล์ถูกใช้โดยแอปพลิเคชันต่างๆ ที่สนับสนุนการอ่านไฟล์ 3D

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
OBJ ไฟล์ถูกใช้โดยแอปพลิเคชัน Advanced Visualizer ของ Wavefront เพื่อกำหนดและจัดเก็บวัตถุทางเรขาคณิต การส่งข้อมูลทางเรขาคณิตย้อนหลังและไปข้างหน้าทำได้ผ่านไฟล์ OBJ ทั้งรูปทรงหลายเหลี่ยม เช่น จุด เส้น จุดยอดพื้นผิว ใบหน้า และเรขาคณิตอิสระ (เส้นโค้งและพื้นผิว) ได้รับการสนับสนุนโดยรูปแบบ OBJ รูปแบบนี้ไม่รองรับภาพเคลื่อนไหวหรือข้อมูลที่เกี่ยวข้องกับแสงและตำแหน่งของฉาก ไฟล์ OBJ มักจะเป็นผลิตภัณฑ์สุดท้ายของกระบวนการสร้างแบบจำลอง 3D ที่สร้างโดย CAD (การออกแบบโดยใช้คอมพิวเตอร์ช่วย) ลำดับเริ่มต้นในการจัดเก็บจุดยอดคือทวนเข็มนาฬิกาเพื่อหลีกเลี่ยงการประกาศภาวะปกติของใบหน้าอย่างชัดเจน แม้ว่าไฟล์ OBJ จะประกาศข้อมูลมาตราส่วนในบรรทัดความคิดเห็น แต่ยังไม่มีการประกาศหน่วยสำหรับพิกัด OBJ

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PLY เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-3ds/" name="PLY ถึง 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-amf/" name="PLY ถึง AMF" description="รูปแบบการผลิตสารเติมแต่ง" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-dae/" name="PLY ถึง DAE" description="การแลกเปลี่ยนสินทรัพย์ดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-fbx/" name="PLY ถึง FBX" description="3D รูปแบบ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-html/" name="PLY ถึง HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-pdf/" name="PLY ถึง PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-rvm/" name="PLY ถึง RVM" description="โมเดลการออกแบบโรงงาน AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-stl/" name="PLY ถึง STL" description="เปลี่ยนได้ 3D เรขาคณิตพื้นผิว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-u3d/" name="PLY ถึง U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}