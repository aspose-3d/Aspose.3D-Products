﻿---
title: แปลง PLY TO OBJ Via Java 
weight: 880
url: /th/java/conversion/ply-to-obj/ 
description: ตัวอย่าง Java รหัสการแปลงสำหรับ PLY รูปแบบเป็น OBJ ไฟล์ใช้โค้ดตัวอย่างนี้เพื่อแปลง PLY เป็น OBJ ภายในเว็บหรือเดสก์ท็อป Java
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง PLY TO OBJ Via Java" h2="PLY ถึง OBJ การแปลงโดยใช้ไลบรารี Java โดยไม่มีซอฟต์แวร์แบบจำลอง 3D" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="How to convert PLY TO OBJ การใช้ Java" %}}

 เพื่อแสดงผล PLY ถึง OBJ เราจะใช้
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API ซึ่งเป็นคุณลักษณะที่อุดมไปด้วยที่มีประสิทธิภาพและง่ายต่อการใช้การแปลง API for Java แพลตฟอร์มคุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
 [MAVEN](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 และติดตั้งภายในโครงการ MAVEN ของคุณโดยการเพิ่มการกำหนดค่าต่อไปนี้ไปยัง POM.XML.

{{% blocks/products/pf/agp/code-block title="พื้นที่เก็บข้อมูล" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </URL>
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

{{% blocks/products/pf/agp/feature-section-col title="Steps TO convert PLY TO OBJ Via Java [ตัวอย่าง]" %}}

{{% blocks/products/pf/agp/text %}}

 Java โปรแกรมเมอร์สามารถแปลง PLY ไฟล์เป็น OBJ ในเพียงไม่กี่บรรทัดของรหัส

{{% /blocks/products/pf/agp/text %}}

1. โหลด PLY ไฟล์ผ่านตัวสร้างชั้นฉาก1. สร้างอินสแตนซ์ของ objsaveoptions1. ตั้งค่า OBJ คุณสมบัติเฉพาะสำหรับการแปลงขั้นสูง1. ฉากโทร.บันทึกวิธีการ1. ผ่านเส้นทางเอาต์พุตด้วย OBJ นามสกุลไฟล์และวัตถุของ objsaveoptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนที่จะใช้รหัสการแปลง Java โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับสภาพแวดล้อมรันไทม์ Java สำหรับแอพพลิเคชัน JSP/JSF และแอพพลิเคชันเดสก์ท็อป- รับเวอร์ชั่นล่าสุด Aspose.3D for Java โดยตรงจาก MAVEN
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PLY ถึง OBJ Java รหัสแหล่งที่มาของการแปลง" offSpacer="" %}}

```cs
// โหลด PLY ในวัตถุของฉาก 
Scene document = new Scene("template.ply");
// สร้างอินสแตนซ์ของ objsaveoptions 
ObjSaveOptions options = new ObjSaveOptions();
// บันทึก PLY เป็น OBJ 
document.save("output.obj", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PLY TO OBJ Conversion การสาธิตสด" sectionDescription="[แปลง PLY TO OBJ](https://products.aspose.app/3d/conversion/ply-to-obj) ขณะนี้โดยการเยี่ยมชมเว็บไซต์สาธิตสดของเราการสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงแค่อัปโหลดไฟล์ PLY ของคุณก็จะถูกแปลงทันทีเป็น OBJ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D ห้องสมุดการจัดการฉาก" %}}

 Aspose.3D เป็น CAD และ gameware API ในการโหลดแก้ไขและแปลง 3D ไฟล์ API เป็นแบบสแตนด์อโลนและไม่ต้องใช้ใดๆ 3D การสร้างแบบจำลองหรือซอฟต์แวร์การแสดงผลหนึ่งสามารถใช้ API สำหรับ Discreet3DS, WavefrontOBJ, STL (ASCII, binary), Universal3D, FBX (ASCII, binary), Collada, glTF, PLY, GLB, DirectX และรูปแบบอื่นๆ 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}

PLY, รูปแบบไฟล์รูปหลายเหลี่ยมหมายถึงรูปแบบไฟล์ 3D ที่จัดเก็บวัตถุกราฟิกที่อธิบายว่าเป็นชุดของรูปหลายเหลี่ยมวัตถุประสงค์ของรูปแบบไฟล์นี้คือการสร้างประเภทไฟล์ที่ง่ายและง่ายซึ่งโดยทั่วไปเพียงพอที่จะเป็นประโยชน์สำหรับรูปแบบต่างๆ PLY รูปแบบไฟล์มาเป็น ASCII เช่นเดียวกับรูปแบบไบนารีสำหรับการเก็บรักษาที่มีขนาดกะทัดรัดและสำหรับการประหยัดและการโหลดอย่างรวดเร็วรูปแบบไฟล์ถูกใช้โดยการใช้งานที่แตกต่างกันซึ่งให้การสนับสนุนการอ่านไฟล์ 3D


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

OBJ ไฟล์จะถูกใช้โดยโปรแกรม visualizer ขั้นสูง Wavefront เพื่อกำหนดและจัดเก็บวัตถุทางเรขาคณิตการส่งข้อมูลทางเรขาคณิตย้อนหลังและไปข้างหน้าทำได้ผ่านไฟล์ OBJ รูปทรงเรขาคณิตทั้งสองเหลี่ยมเช่นจุดเส้นจุดยอดพื้นผิวใบหน้าและรูปทรงเรขาคณิตแบบอิสระ (เส้นโค้งและพื้นผิว) ได้รับการสนับสนุนโดยรูปแบบ OBJ รูปแบบนี้ไม่สนับสนุนภาพเคลื่อนไหวหรือข้อมูลที่เกี่ยวข้องกับแสงสว่างและตำแหน่งของฉากไฟล์ OBJ มักเป็นผลิตภัณฑ์สิ้นสุดของกระบวนการสร้างแบบจำลอง 3D ที่สร้างขึ้นโดย CAD (Computer Aided DESIGN) คำสั่งซื้อเริ่มต้นในการจัดเก็บจุดยอดคือทวนเข็มนาฬิกาหลีกเลี่ยงการประกาศที่ชัดเจนของ normals ใบหน้าแม้ว่าไฟล์ OBJ จะประกาศข้อมูลขนาดในบรรทัดความคิดเห็นแต่ยังไม่มีการประกาศหน่วยสำหรับพิกัด OBJ


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงที่สนับสนุนอื่นๆ" subTitle="PLY ลงในรูปแบบไฟล์อื่นๆอีกมากมายรวมทั้งไม่กี่รายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-3ds/" name="PLY TO 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-amf/" name="PLY TO AMF" description="รูปแบบการผลิตสารเติมแต่ง" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-ase/" name="PLY TO ASE" description="วิธีด้วย.2D ไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-dae/" name="PLY TO DAE" description="การแลกเปลี่ยนสินทรัพย์ดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-fbx/" name="PLY TO FBX" description="3D รูปแบบ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-gltf/" name="PLY TO GLTF" description="รูปแบบการส่ง GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-html/" name="PLY TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-rvm/" name="PLY TO RVM" description="Aveva รุ่น Plant Design" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-stl/" name="PLY TO STL" description="เปลี่ยนได้ 3D เรขาคณิตพื้นผิว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-u3d/" name="PLY TO U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}