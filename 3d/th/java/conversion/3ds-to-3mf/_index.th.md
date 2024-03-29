﻿---
title: แปลง 3DS เป็น 3MF ผ่าน Java 
weight: 810
url: /th/java/conversion/3ds-to-3mf/ 
description: ตัวอย่างโค้ดการแปลง Java สำหรับรูปแบบ 3DS เป็นไฟล์ 3MF ใช้โค้ดตัวอย่างนี้เพื่อแปลง 3DS เป็น 3MF ภายในแอปพลิเคชันบนเว็บหรือเดสก์ท็อป Java
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง 3DS เป็น 3MF ผ่าน Java" h2="การแปลง 3DS เป็น 3MF โดยใช้ไลบรารี Java โดยไม่มีซอฟต์แวร์การสร้างแบบจำลอง 3D ใดๆ" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="3MF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง 3DS เป็น 3MF โดยใช้ Java" %}}

 เพื่อแสดง 3DS เป็น 3MF เราจะใช้
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API ซึ่งเป็นแพลตฟอร์มการแปลง API for Java ที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
 และติดตั้งภายในโปรเจ็กต์ที่ใช้ Maven โดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml

{{% blocks/products/pf/agp/code-block title="ที่เก็บ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การพึ่งพา" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-3d</artifactId>
<version>version of aspose-3d API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง 3DS เป็น 3MF ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

 โปรแกรมเมอร์ Java สามารถแปลงไฟล์ 3DS เป็น 3MF ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ 3DS ผ่านตัวสร้างของ Scene class1. สร้างอินสแตนซ์ของ U3dSaveOptions1. ตั้งค่า 3MF คุณสมบัติเฉพาะสำหรับการแปลงขั้นสูง1. วิธีการโทร Scene.save1. ส่งเส้นทางเอาต์พุตด้วย 3MF นามสกุลไฟล์ & อ็อบเจ็กต์ของ U3dSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ด Conversion Java ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป- รับเวอร์ชันล่าสุดของ Aspose.3D for Java โดยตรงจาก Maven
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="3DS ถึง 3MF Java รหัสแหล่งที่มาของการแปลง" offSpacer="" %}}

```cs
// โหลด 3DS ในวัตถุของ Scene 
Scene document = new Scene("template.3ds");
// สร้างอินสแตนซ์ของ U3dSaveOptions 
U3dSaveOptions options = new U3dSaveOptions();
// บันทึก 3DS เป็น 3MF 
document.save("output.3mf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="3DS ถึง 3MF การสาธิตการแปลงสด" sectionDescription="[แปลง 3DS เป็น 3MF](https://products.aspose.app/3d/conversion/3ds-to-3mf) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ 3DS ของคุณ ไฟล์จะถูกแปลงเป็น 3MF ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D ไลบรารีการจัดการฉาก" %}}

 Aspose.3D เป็น CAD และ Gameware API ในการโหลด แก้ไข และแปลงไฟล์ 3D API เป็นแบบสแตนด์อโลนและไม่จำเป็นต้องมี 3D ซอฟต์แวร์สร้างแบบจำลองหรือเรนเดอร์ใดๆ สามารถใช้ API สำหรับ Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX และรูปแบบอื่นๆ 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}

ไฟล์ที่มีนามสกุล 3DS หมายถึงรูปแบบไฟล์ตาข่าย 3D Studio (DOS) ที่ใช้โดย Autodesk 3D Studio Autodesk 3D Studio อยู่ใน 3D ตลาดรูปแบบไฟล์ตั้งแต่ปี 1990 และตอนนี้ได้พัฒนาเป็น 3D Studio MAX สำหรับการทำงานกับ 3D การสร้างแบบจำลอง แอนิเมชัน และการแสดงผล ไฟล์ 3DS มีข้อมูลสำหรับการแสดงฉากและภาพ 3D และเป็นหนึ่งในรูปแบบไฟล์ยอดนิยมสำหรับการนำเข้าและส่งออกข้อมูล 3D โดยจะพิจารณาข้อมูลต่างๆ เช่น ตำแหน่งของกล้อง ข้อมูลตาข่าย ข้อมูลการจัดแสง การกำหนดค่าวิวพอร์ต ข้อมูลกลุ่มที่ราบรื่น การอ้างอิงบิตแมป และแอตทริบิวต์เพื่อสร้างจุดยอดและรูปหลายเหลี่ยมสำหรับการแสดงฉาก


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}

3MF, 3D รูปแบบการผลิต ถูกใช้โดยแอปพลิเคชันเพื่อแสดงโมเดลอ็อบเจ็กต์ 3D ให้กับแอปพลิเคชัน แพลตฟอร์ม บริการ และเครื่องพิมพ์อื่นๆ ที่หลากหลาย สร้างขึ้นเพื่อหลีกเลี่ยงข้อจำกัดและปัญหาในรูปแบบไฟล์ 3D อื่นๆ เช่น STL สำหรับการทำงานกับเครื่องพิมพ์ 3D เวอร์ชันล่าสุด 3MF ค่อนข้างเป็นรูปแบบไฟล์ใหม่ที่ได้รับการพัฒนาและเผยแพร่โดยกลุ่ม 3MF มีเนื้อหาเพียงพอที่จะอธิบายแบบจำลอง เก็บข้อมูลภายใน สี และคุณลักษณะอื่นๆ ที่ทำให้ขยายได้เพื่อรองรับนวัตกรรมใหม่ในการพิมพ์ 3D


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง 3DS เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-amf/" name="3DS ถึง AMF" description="รูปแบบการผลิตสารเติมแต่ง" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-dae/" name="3DS ถึง DAE" description="การแลกเปลี่ยนสินทรัพย์ดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-fbx/" name="3DS ถึง FBX" description="3D รูปแบบ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-gltf/" name="3DS ถึง GLTF" description="รูปแบบการส่ง GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-html/" name="3DS ถึง HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-obj/" name="3DS ถึง OBJ" description="3D รูปแบบไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-ply/" name="3DS ถึง PLY" description="รูปแบบไฟล์รูปหลายเหลี่ยม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-rvm/" name="3DS ถึง RVM" description="โมเดลการออกแบบโรงงาน AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3ds-to-stl/" name="3DS ถึง STL" description="เปลี่ยนได้ 3D เรขาคณิตพื้นผิว" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}