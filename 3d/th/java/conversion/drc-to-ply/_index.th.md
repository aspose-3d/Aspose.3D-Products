﻿---
title: แปลง DRC เป็น PLY ผ่าน Java 
url: /th/java/conversion/drc-to-ply/ 
description: ตัวอย่างโค้ดการแปลง Java สำหรับรูปแบบ DRC เป็นไฟล์ PLY ใช้โค้ดตัวอย่างนี้เพื่อแปลง DRC เป็น PLY ภายในแอปพลิเคชันบนเว็บหรือเดสก์ท็อป Java
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง DRC เป็น PLY ผ่าน Java" h2="การแปลง DRC เป็น PLY โดยใช้ไลบรารี Java โดยไม่มีซอฟต์แวร์การสร้างแบบจำลอง 3D ใดๆ" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="PLY" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง DRC เป็น PLY โดยใช้ Java" %}}

 เพื่อแสดง DRC เป็น PLY เราจะใช้
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API ซึ่งเป็นแพลตฟอร์มการแปลง API for Java ที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง DRC เป็น PLY ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

 โปรแกรมเมอร์ Java สามารถแปลงไฟล์ DRC เป็น PLY ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ DRC ผ่านตัวสร้างของ Scene class1. สร้างอินสแตนซ์ของ PlySaveOptions1. ตั้งค่า PLY คุณสมบัติเฉพาะสำหรับการแปลงขั้นสูง1. วิธีการโทร Scene.save1. ส่งเส้นทางเอาต์พุตด้วย PLY นามสกุลไฟล์ & อ็อบเจ็กต์ของ PlySaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ด Conversion Java ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป- รับเวอร์ชันล่าสุดของ Aspose.3D for Java โดยตรงจาก Maven
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DRC ถึง PLY Java รหัสแหล่งที่มาของการแปลง" offSpacer="" %}}

```cs
// โหลด DRC ในวัตถุของ Scene 
Scene document = new Scene("template.drc");
// สร้างอินสแตนซ์ของ PlySaveOptions 
AmfSaveOptions options = new PlySaveOptions();
// บันทึก DRC เป็น PLY 
document.save("output.ply", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DRC ถึง PLY การสาธิตการแปลงสด" sectionDescription="[แปลง DRC เป็น PLY](https://products.aspose.app/3d/conversion/drc-to-ply) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ DRC ของคุณ ไฟล์จะถูกแปลงเป็น PLY ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D ไลบรารีการจัดการฉาก" %}}

 Aspose.3D เป็น CAD และ Gameware API ในการโหลด แก้ไข และแปลงไฟล์ 3D API เป็นแบบสแตนด์อโลนและไม่จำเป็นต้องมี 3D ซอฟต์แวร์สร้างแบบจำลองหรือเรนเดอร์ใดๆ สามารถใช้ API สำหรับ Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX และรูปแบบอื่นๆ 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}

ไฟล์ที่มีนามสกุล .drc คือรูปแบบไฟล์บีบอัด 3D ที่สร้างด้วยไลบรารี Google Draco Google เสนอ Draco เป็นไลบรารีโอเพนซอร์สสำหรับบีบอัดและขยายขนาด 3D เรขาคณิตเมชและพอยต์คลาวด์ และปรับปรุงการจัดเก็บและการส่งผ่านของกราฟิก 3D โดยจะเข้ารหัสข้อมูลที่ป้อนเข้าและบันทึกเป็นไฟล์ .drc เมื่อสิ้นสุดการรับ API จะอ่านไฟล์ .drc และสามารถส่งออกไฟล์เหล่านี้เป็นไฟล์ PLY หรือ OBJ ไฟล์เอาต์พุตที่บีบอัดทำให้ผู้ใช้สามารถดาวน์โหลดแอปได้เร็วขึ้นและให้การโหลด 3D กราฟิกในเบราว์เซอร์ได้อย่างรวดเร็ว

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}

PLY รูปแบบไฟล์รูปหลายเหลี่ยม หมายถึง 3D รูปแบบไฟล์ที่เก็บอ็อบเจ็กต์กราฟิกที่อธิบายว่าเป็นคอลเล็กชันของรูปหลายเหลี่ยม จุดประสงค์ของรูปแบบไฟล์นี้คือเพื่อสร้างไฟล์ประเภทที่ง่ายและสะดวกซึ่งโดยทั่วไปจะมีประโยชน์สำหรับรุ่นต่างๆ รูปแบบไฟล์ PLY มาในรูปแบบ ASCII เช่นเดียวกับรูปแบบไบนารีสำหรับพื้นที่เก็บข้อมูลขนาดกะทัดรัด และสำหรับการบันทึกและโหลดอย่างรวดเร็ว รูปแบบไฟล์ถูกใช้โดยแอปพลิเคชันต่างๆ ที่สนับสนุนการอ่านไฟล์ 3D

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}