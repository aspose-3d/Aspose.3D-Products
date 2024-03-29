﻿---
title: Ubah AMF menjadi FBX melalui Java 
weight: 3460
url: /id/java/conversion/amf-to-fbx/ 
description: Contoh Java kode konversi untuk format AMF ke file FBX. Gunakan kode contoh ini untuk mengonversi AMF ke FBX dalam aplikasi berbasis Web atau Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ubah AMF menjadi FBX melalui Java" h2="Konversi AMF ke FBX menggunakan pustaka Java tanpa perangkat lunak pemodelan 3D apa pun." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="AMF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi AMF ke FBX Menggunakan Java" %}}

 Untuk merender AMF menjadi FBX, kami akan menggunakan
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API yang merupakan platform API for Java konversi yang kaya fitur, canggih, dan mudah digunakan. Anda dapat mengunduh versi terbarunya langsung dari
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
 dan instal dalam proyek berbasis Maven Anda dengan menambahkan konfigurasi berikut ke pom.xml.

{{% blocks/products/pf/agp/code-block title="Gudang" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repositori.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ketergantungan" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengonversi AMF ke FBX melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java pemrogram dapat dengan mudah mengonversi berkas AMF menjadi FBX hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file AMF melalui konstruktor kelas Scene1. Buat instance dari FbxSaveOptions1. Tetapkan FBX properti khusus untuk konversi lanjutan1. Metode panggilan Scene.save1. Lewati jalur keluaran dengan FBX ekstensi file & objek FbxSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan Java kode konversi, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.- Dapatkan versi terbaru Aspose.3D for Java langsung dari Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="AMF ke FBX Java Kode Sumber Konversi" offSpacer="" %}}

```cs
// memuat AMF dalam objek Scene 
Scene document = new Scene("template.amf");
// buat instance FbxSaveOptions 
FbxSaveOptions options = new FbxSaveOptions();
// simpan AMF sebagai FBX 
document.save("output.fbx", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="AMF ke FBX Demo Konversi Langsung" sectionDescription="[Ubah AMF menjadi FBX](https://products.aspose.app/3d/conversion/amf-to-fbx) sekarang dengan mengunjungi situs web Demo Langsung kami. Demo langsung memiliki manfaat sebagai berikut" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file AMF Anda, itu akan langsung dikonversi menjadi FBX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anda akan mendapatkan tautan unduhan." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Pustaka Manipulasi Adegan" %}}

 Aspose.3D adalah CAD dan Gameware API untuk memuat, memodifikasi, dan mengonversi file 3D. API berdiri sendiri dan tidak memerlukan perangkat lunak pemodelan atau rendering 3D apa pun. Seseorang dapat dengan mudah menggunakan API untuk Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX, dan format lainnya. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="AMF" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}

Format file Manufaktur Aditif (AMF) mendefinisikan standar terbuka untuk deskripsi objek agar dapat digunakan oleh proses manufaktur aditif seperti 3D Printing. Program CAD menggunakan format file AMF dengan memanfaatkan informasi seperti geometri, warna, dan bahan objek. AMF berbeda dari format STL karena lateral tidak mendukung warna, material, kisi, dan konstelasi.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}

FBX, FilmBox, adalah format berkas 3D populer yang awalnya dikembangkan oleh Kaydara untuk MotionBuilder. Itu diakuisisi oleh Autodesk Inc pada tahun 2006 dan sekarang menjadi salah satu format pertukaran 3D utama seperti yang digunakan oleh banyak alat 3D. FBX tersedia dalam format file biner dan ASCII. Format ini dibuat untuk menyediakan interoperabilitas antara aplikasi pembuatan konten digital. Ada banyak alat yang tersedia untuk konversi dari/ke format file FBX.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi yang Didukung Lainnya" subTitle="Anda juga dapat mengonversi AMF ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-3ds/" name="AMF KE 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-dae/" name="AMF KE DAE" description="Pertukaran Aset Digital" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-gltf/" name="AMF KE GLTF" description="Format Transmisi GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-html/" name="AMF KE HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-obj/" name="AMF KE OBJ" description="3D Format Berkas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-ply/" name="AMF KE PLY" description="Format File Poligon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-rvm/" name="AMF KE RVM" description="Model Desain Tanaman AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-stl/" name="AMF KE STL" description="3D Geometri Permukaan yang Dapat Dipertukarkan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/amf-to-u3d/" name="AMF KE U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}