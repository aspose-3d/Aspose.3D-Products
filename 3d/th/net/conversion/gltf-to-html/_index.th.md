﻿---
title: แปลง GLTF เป็น HTML ผ่าน C# 
url: /th/net/conversion/gltf-to-html/ 
description: โค้ดตัวอย่างสำหรับการแปลง GLTF ถึง HTML C# ใช้ API โค้ดตัวอย่างสำหรับแบตช์ GLTF ไฟล์เป็น HTML การแปลงภายใน VB.NET, Asp.NET หรือแอปพลิเคชันตาม .NET ใดๆ
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง GLTF เป็น HTML ผ่าน C#" h2="แสดงผล GLTF เป็น HTML โดยไม่ต้องใช้ซอฟต์แวร์สร้างแบบจำลองและการแสดงผล 3D" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง GLTF เป็น HTML โดยใช้ C#" %}}

 ในการแปลง GLTF เป็น HTML เราจะใช้
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง GLTF เป็น HTML ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

 โปรแกรมเมอร์ .NET สามารถโหลดและแปลงไฟล์ GLTF เป็น HTML ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ GLTF ผ่านตัวสร้างของ Scene class1. สร้างอินสแตนซ์ของ AmfSaveOptions1. ตั้งค่า HTML คุณสมบัติเฉพาะสำหรับการแปลงขั้นสูง1. เรียกวิธี Scene.Save1. ส่งเส้นทางเอาต์พุตด้วย HTML นามสกุลไฟล์ & อ็อบเจ็กต์ของ Html5SaveOptions1. ตรวจสอบไฟล์ผลลัพธ์ HTML ที่เส้นทางที่ระบุ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ด Conversion .NET ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio- Aspose.3D for .NET DLL ที่อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่างนี้แสดงการแปลง GLTF ถึง HTML C#" offSpacer="" %}}

```cs
// โหลด GLTF ในวัตถุของ Scene 
var document = new Aspose.ThreeD.Scene("template.gltf");
// สร้างอินสแตนซ์ของ Html5SaveOptions 
var options = new Aspose.ThreeD.Formats.Html5SaveOptions();
// บันทึก GLTF เป็น HTML 
document.Save("output.html", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="แอปฟรีสำหรับแปลง GLTF เป็น HTML" sectionDescription="ตรวจสอบการสาธิตสดของเราสำหรับ [GLTF เป็น HTML แปลง](https://products.aspose.app/3d/conversion/gltf-to-html) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไร" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ GLTF ของคุณแล้วกดปุ่ม \"แปลง\"" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงก์ดาวน์โหลดสำหรับไฟล์ผลลัพธ์ HTML ทันที" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D ไลบรารีการประมวลผลไฟล์เพื่อจัดการไฟล์ 3D โดยไม่ต้องใช้ซอฟต์แวร์สร้างแบบจำลองและแสดงผล 3D API รองรับ Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, รูปแบบไฟล์ PLY, DirectX, Google Draco และอีกมากมาย นักพัฒนาสามารถสร้าง อ่าน แปลง แก้ไข และควบคุมเนื้อหาของรูปแบบเอกสาร 3D รูปแบบได้อย่างง่ายดาย



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (รูปแบบการส่ง GL) เป็นรูปแบบไฟล์ 3D ที่เก็บข้อมูลรุ่น 3D ในรูปแบบ JSON การใช้ JSON ช่วยลดทั้งขนาดของสินทรัพย์ 3D และการประมวลผลรันไทม์ที่จำเป็นในการแกะและใช้เนื้อหาเหล่านั้น มันถูกนำไปใช้สำหรับการส่งและการโหลด 3D ฉากและแบบจำลองอย่างมีประสิทธิภาพโดยแอปพลิเคชัน glTF ได้รับการพัฒนาโดย Khronos Group 3D Formats Working Group และได้รับการอธิบายว่าเป็น JPEG ของ 3D โดยผู้สร้าง รูปแบบกำหนดรูปแบบการเผยแพร่ทั่วไปที่ขยายได้สำหรับเครื่องมือและบริการเนื้อหา 3D ที่ปรับปรุงเวิร์กโฟลว์การเขียนให้คล่องตัวและเปิดใช้งานการใช้เนื้อหาที่ทำงานร่วมกันได้ทั่วทั้งอุตสาหกรรม จุดประสงค์เบื้องหลังการสร้างรูปแบบไฟล์ glTF คือการกำหนดรูปแบบการเผยแพร่ทั่วไปที่ขยายได้สำหรับเครื่องมือและบริการเนื้อหา 3D ที่ควรปรับปรุงเวิร์กโฟลว์การเขียนและเปิดใช้งานการใช้เนื้อหาที่ทำงานร่วมกันได้ทั่วทั้งอุตสาหกรรม ลดการประมวลผลรันไทม์โดยแอปพลิเคชันโดยใช้ WebGL และ API อื่นๆ

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="html" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (Hyper Text Markup Language) เป็นส่วนขยายสำหรับหน้าเว็บที่สร้างขึ้นสำหรับแสดงในเบราว์เซอร์ HTML เป็นที่รู้จักในฐานะภาษาของเว็บ ได้พัฒนาข้อกำหนดของข้อกำหนดข้อมูลใหม่เพื่อแสดงเป็นส่วนหนึ่งของหน้าเว็บ ตัวแปรล่าสุดเรียกว่า HTML 5 ซึ่งให้ความยืดหยุ่นอย่างมากในการทำงานกับภาษา หน้า HTML จะได้รับจากเซิร์ฟเวอร์ซึ่งมีการโฮสต์ไว้ หรือสามารถโหลดจากระบบภายในได้เช่นกัน หน้า HTML แต่ละหน้าประกอบด้วยองค์ประกอบ HTML เช่น แบบฟอร์ม ข้อความ รูปภาพ แอนิเมชั่น ลิงก์ ฯลฯ องค์ประกอบเหล่านี้แสดงโดยแท็ก เช่น img, a, p และอื่นๆ อีกหลายอย่างซึ่งแต่ละแท็กมีจุดเริ่มต้นและจุดสิ้นสุด . นอกจากนี้ยังสามารถฝังแอปพลิเคชันที่เขียนด้วยภาษาสคริปต์ เช่น JavaScript และสไตล์ชีต (CSS) สำหรับการแสดงเค้าโครงโดยรวม

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}