﻿---
title: แปลง USD เป็น OBJ ผ่าน Java
weight: 530
url: /th/java/conversion/usd-to-obj/ 
description: ตัวอย่างโค้ดการแปลง Java สำหรับรูปแบบ USD เป็นไฟล์ OBJ ใช้โค้ดตัวอย่างนี้เพื่อแปลง USD เป็น OBJ ภายในแอปพลิเคชันบนเว็บหรือเดสก์ท็อป Java
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง USD เป็น OBJ ผ่าน Java" h2="การแปลง USD เป็น OBJ โดยใช้ไลบรารี Java โดยไม่มีซอฟต์แวร์การสร้างแบบจำลอง 3D ใดๆ" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="USD" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง USD เป็น OBJ โดยใช้ Java" %}}

 เพื่อแสดง USD เป็น OBJ เราจะใช้
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง USD เป็น OBJ ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

 โปรแกรมเมอร์ Java สามารถแปลงไฟล์ USD เป็น OBJ ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ USD ผ่านตัวสร้างของ Scene class1. เรียกเมธอด Scene.save ด้วยรูปแบบของ OBJ1. ตรวจสอบไฟล์ผลลัพธ์ OBJ ที่เส้นทางที่ระบุ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ด Conversion Java ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป- รับเวอร์ชันล่าสุดของ Aspose.3D for Java โดยตรงจาก Maven
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="USD ถึง OBJ Java รหัสแหล่งที่มาของการแปลง" offSpacer="" %}}

```cs
// โหลดซอร์ส USD file
Scene scene = new Scene("sourceFile.usd");
// แปลง 3D ฉากเป็นไฟล์ใน Wavefront OBJ รูปแบบ
scene.save("output.obj", FileFormat.WAVEFRONTOBJ)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="USD ถึง OBJ การสาธิตการแปลงสด" sectionDescription="[แปลง USD เป็น OBJ](https://products.aspose.app/3d/conversion/usd-to-obj) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ USD ของคุณ ไฟล์จะถูกแปลงเป็น OBJ ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D ไลบรารีการจัดการฉาก" %}}

 Aspose.3D เป็น CAD และ Gameware API ในการโหลด แก้ไข และแปลงไฟล์ 3D API เป็นแบบสแตนด์อโลนและไม่จำเป็นต้องมี 3D ซอฟต์แวร์สร้างแบบจำลองหรือเรนเดอร์ใดๆ สามารถใช้ API สำหรับ USD, Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX และรูปแบบอื่นๆ 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="USD" readMoreLink="https://docs.fileformat.com/3d/usd/" >}}

ไฟล์ที่มีนามสกุล .usd เป็นรูปแบบไฟล์ Universal Scene Description ที่เข้ารหัสข้อมูลเพื่อวัตถุประสงค์ในการแลกเปลี่ยนข้อมูลและเพิ่มพูนระหว่างแอปพลิเคชันการสร้างเนื้อหาดิจิทัล พัฒนาโดย Pixar USD ให้ความสามารถในการแลกเปลี่ยนเนื้อหาองค์ประกอบ (เช่น โมเดล) หรือแอนิเมชั่น

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

OBJ ไฟล์ถูกใช้โดยแอปพลิเคชัน Advanced Visualizer ของ Wavefront เพื่อกำหนดและจัดเก็บวัตถุทางเรขาคณิต การส่งข้อมูลทางเรขาคณิตย้อนหลังและไปข้างหน้าทำได้ผ่านไฟล์ OBJ ทั้งรูปทรงหลายเหลี่ยม เช่น จุด เส้น จุดยอดพื้นผิว ใบหน้า และเรขาคณิตอิสระ (เส้นโค้งและพื้นผิว) ได้รับการสนับสนุนโดยรูปแบบ OBJ รูปแบบนี้ไม่รองรับภาพเคลื่อนไหวหรือข้อมูลที่เกี่ยวข้องกับแสงและตำแหน่งของฉาก ไฟล์ OBJ มักจะเป็นผลิตภัณฑ์สุดท้ายของกระบวนการสร้างแบบจำลอง 3D ที่สร้างโดย CAD (การออกแบบโดยใช้คอมพิวเตอร์ช่วย) ลำดับเริ่มต้นในการจัดเก็บจุดยอดคือทวนเข็มนาฬิกาเพื่อหลีกเลี่ยงการประกาศภาวะปกติของใบหน้าอย่างชัดเจน แม้ว่าไฟล์ OBJ จะประกาศข้อมูลมาตราส่วนในบรรทัดความคิดเห็น แต่ยังไม่มีการประกาศหน่วยสำหรับพิกัด OBJ


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง USD เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-gltf/" name="USD ถึง GLTF" description="ไฟล์รูปแบบการส่ง GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-glb/" name="USD ถึง GLB" description="รูปแบบการส่งไบนารี GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-pdf/" name="USD ถึง PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-fbx/" name="USD ถึง FBX" description="Autodesk FBX ไฟล์ Interchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-stl/" name="USD ถึง STL" description="ไฟล์ Stereolithography" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-obj/" name="USD ถึง OBJ" description="Wavefront 3D ไฟล์อ็อบเจ็กต์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-3ds/" name="USD ถึง 3DS" description="3D ฉากสตูดิโอ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-dae/" name="USD ถึง DAE" description="ไฟล์การแลกเปลี่ยนสินทรัพย์ดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-u3d/" name="USD ถึง U3D" description="Universal 3D ไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-ply/" name="USD ถึง PLY" description="รูปแบบไฟล์รูปหลายเหลี่ยม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-drc/" name="USD ถึง DRC" description="Google Draco รูปแบบไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-rvm/" name="USD ถึง RVM" description="อาวีว่า RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-jt/" name="USD ถึง JT" description="JT เปิด CAD ไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-amf/" name="USD ถึง AMF" description="ไฟล์การผลิตสารเติมแต่ง" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-html/" name="USD ถึง HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-usdz/" name="USD ถึง USDZ" description="คำอธิบายฉากสากล รูปแบบซิป" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}