﻿---
title: แปลง ASE เป็น U3D ผ่าน C# 
weight: 2170
url: /th/net/conversion/ase-to-u3d/ 
description: โค้ดตัวอย่างสำหรับการแปลง ASE ถึง U3D C# ใช้ API โค้ดตัวอย่างสำหรับแบตช์ ASE ไฟล์เป็น U3D การแปลงภายใน VB.NET, Asp.NET หรือแอปพลิเคชันตาม .NET ใดๆ
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง ASE เป็น U3D ผ่าน C#" h2="แสดงผล ASE เป็น U3D โดยไม่ต้องใช้ซอฟต์แวร์สร้างแบบจำลองและการแสดงผล 3D" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง ASE เป็น U3D โดยใช้ C#" %}}

 ในการแปลง ASE เป็น U3D เราจะใช้
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง ASE เป็น U3D ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

 โปรแกรมเมอร์ .NET สามารถโหลดและแปลงไฟล์ ASE เป็น U3D ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ ASE ผ่านตัวสร้างของ Scene class1. สร้างอินสแตนซ์ของ U3dSaveOptions1. ตั้งค่า U3D คุณสมบัติเฉพาะสำหรับการแปลงขั้นสูง1. เรียกวิธี Scene.Save1. ส่งเส้นทางเอาต์พุตด้วย U3D นามสกุลไฟล์ & อ็อบเจ็กต์ของ U3dSaveOptions1. ตรวจสอบไฟล์ผลลัพธ์ U3D ที่เส้นทางที่ระบุ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ด Conversion .NET ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio- Aspose.3D for .NET DLL ที่อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่างนี้แสดงการแปลง ASE ถึง U3D C#" offSpacer="" %}}

```cs
// โหลด ASE ในวัตถุของ Scene 
var document = new Aspose.ThreeD.Scene("template.ase");
// สร้างอินสแตนซ์ของ U3dSaveOptions 
var options = new Aspose.ThreeD.Formats.U3dSaveOptions();
// บันทึก ASE เป็น U3D 
document.Save("output.u3d", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="แอปฟรีสำหรับแปลง ASE เป็น U3D" sectionDescription="ตรวจสอบการสาธิตสดของเราสำหรับ [ASE เป็น U3D แปลง](https://products.aspose.app/3d/conversion/ase-to-u3d) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไร" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ ASE ของคุณแล้วกดปุ่ม \"แปลง\"" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงก์ดาวน์โหลดสำหรับไฟล์ผลลัพธ์ U3D ทันที" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D ไลบรารีการประมวลผลไฟล์เพื่อจัดการไฟล์ 3D โดยไม่ต้องใช้ซอฟต์แวร์สร้างแบบจำลองและแสดงผล 3D API รองรับ Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, รูปแบบไฟล์ PLY, DirectX, Google Draco และอีกมากมาย นักพัฒนาสามารถสร้าง อ่าน แปลง แก้ไข และควบคุมเนื้อหาของรูปแบบเอกสาร 3D รูปแบบได้อย่างง่ายดาย



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}
ไฟล์ ASE คือภาพเคลื่อนไหวหรือกราฟิก 2 มิติที่มีเลเยอร์ เฟรม จานสี แท็ก และการตั้งค่า

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="u3d" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}
U3D (Universal 3D) คือรูปแบบไฟล์บีบอัดและโครงสร้างข้อมูลสำหรับ 3D คอมพิวเตอร์กราฟิก ประกอบด้วยข้อมูลโมเดล 3D เช่น ตาข่ายสามเหลี่ยม การจัดแสง การแรเงา ข้อมูลการเคลื่อนไหว เส้นและจุดด้วยสีและโครงสร้าง รูปแบบนี้ได้รับการยอมรับเป็นมาตรฐาน ECMA-363 ในเดือนสิงหาคม 2548 เอกสาร 3D PDF รองรับการฝังวัตถุ U3D และสามารถดูได้ใน Adobe Reader (เวอร์ชัน 7 ขึ้นไป) รูปแบบ U3D ได้รับการพัฒนาโดยคำนึงถึงจุดมุ่งหมายเพื่อสร้างมาตรฐานสากลสำหรับการจัดเก็บและแลกเปลี่ยนข้อมูลสามมิติ อย่างไรก็ตาม รูปแบบพบว่าการใช้งานหลักในการเข้ารหัสสำหรับ 3D PDF แทนที่จะใช้เป็นรูปแบบการแลกเปลี่ยน Acrobat 3D แปลงประเภทไฟล์ 3D ที่สนับสนุนเป็น U3D หรือ PRC เมื่อแปลงเป็น PDF

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง ASE เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-3ds/" name="ASE ถึง 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-amf/" name="ASE ถึง AMF" description="รูปแบบการผลิตสารเติมแต่ง" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-dae/" name="ASE ถึง DAE" description="การแลกเปลี่ยนสินทรัพย์ดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-fbx/" name="ASE ถึง FBX" description="3D รูปแบบ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-html/" name="ASE ถึง HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-obj/" name="ASE ถึง OBJ" description="3D รูปแบบไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-pdf/" name="ASE ถึง PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-ply/" name="ASE ถึง PLY" description="รูปแบบไฟล์รูปหลายเหลี่ยม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-rvm/" name="ASE ถึง RVM" description="โมเดลการออกแบบโรงงาน AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-stl/" name="ASE ถึง STL" description="เปลี่ยนได้ 3D เรขาคณิตพื้นผิว" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}