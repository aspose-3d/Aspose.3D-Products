﻿---
title: Ubah OBJ menjadi STL melalui Java 
weight: 2860
url: /id/java/conversion/obj-to-stl/ 
description: Contoh Java kode konversi untuk format OBJ ke file STL. Gunakan kode contoh ini untuk mengonversi OBJ ke STL dalam aplikasi berbasis Web atau Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ubah OBJ menjadi STL melalui Java" h2="Konversi OBJ ke STL menggunakan pustaka Java tanpa perangkat lunak pemodelan 3D apa pun." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi OBJ ke STL Menggunakan Java" %}}

 Untuk merender OBJ menjadi STL, kami akan menggunakan
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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengonversi OBJ ke STL melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java pemrogram dapat dengan mudah mengonversi berkas OBJ menjadi STL hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file OBJ melalui konstruktor kelas Scene1. Buat instance StlSaveOptions1. Tetapkan STL properti khusus untuk konversi lanjutan1. Metode panggilan Scene.save1. Lewati jalur keluaran dengan STL ekstensi file & objek StlSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan Java kode konversi, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.- Dapatkan versi terbaru Aspose.3D for Java langsung dari Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OBJ ke STL Java Kode Sumber Konversi" offSpacer="" %}}

```cs
// memuat OBJ dalam objek Scene 
Scene document = new Scene("template.obj");
// buat instance StlSaveOptions 
StlSaveOptions options = new StlSaveOptions();
// simpan OBJ sebagai STL 
document.save("output.stl", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="OBJ ke STL Demo Konversi Langsung" sectionDescription="[Ubah OBJ menjadi STL](https://products.aspose.app/3d/conversion/obj-to-stl) sekarang dengan mengunjungi situs web Demo Langsung kami. Demo langsung memiliki manfaat sebagai berikut" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file OBJ Anda, itu akan langsung dikonversi menjadi STL." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anda akan mendapatkan tautan unduhan." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Pustaka Manipulasi Adegan" %}}

 Aspose.3D adalah CAD dan Gameware API untuk memuat, memodifikasi, dan mengonversi file 3D. API berdiri sendiri dan tidak memerlukan perangkat lunak pemodelan atau rendering 3D apa pun. Seseorang dapat dengan mudah menggunakan API untuk Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX, dan format lainnya. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

Berkas OBJ digunakan oleh aplikasi Visualizer Lanjutan Wavefront untuk mendefinisikan dan menyimpan objek geometris. Transmisi maju dan mundur data geometris dimungkinkan melalui file OBJ. Geometri poligonal seperti titik, garis, simpul tekstur, wajah, dan geometri bentuk bebas (kurva dan permukaan) didukung oleh format OBJ. Format ini tidak mendukung animasi atau informasi yang berkaitan dengan cahaya dan posisi pemandangan. File OBJ biasanya merupakan produk akhir dari proses pemodelan 3D yang dihasilkan oleh CAD (Desain Berbantuan Komputer). Urutan default untuk menyimpan simpul adalah berlawanan arah jarum jam menghindari deklarasi eksplisit wajah normal. Meskipun file OBJ mendeklarasikan informasi skala dalam baris komentar, namun belum ada unit yang dideklarasikan untuk koordinat OBJ.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}

STL, singkatan dari stereolithrography, adalah format file yang dapat dipertukarkan yang mewakili geometri permukaan 3 dimensi. Format file menemukan penggunaannya di beberapa bidang seperti pembuatan prototipe cepat, pencetakan 3D, dan manufaktur berbantuan komputer. Ini mewakili permukaan sebagai serangkaian segitiga kecil, yang dikenal sebagai segi, di mana setiap segi dijelaskan oleh arah tegak lurus dan tiga titik yang mewakili simpul segitiga. Data yang dihasilkan digunakan oleh aplikasi untuk menentukan penampang bentuk 3D yang akan dibangun oleh fabber. Tidak ada informasi yang tersedia dalam format file STL untuk representasi warna, tekstur, atau atribut model CAD umum lainnya.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi yang Didukung Lainnya" subTitle="Anda juga dapat mengonversi OBJ ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-3ds/" name="OBJ KE 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-amf/" name="OBJ KE AMF" description="Format Manufaktur Aditif" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-ase/" name="OBJ KE ASE" description="File Animasi 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-dae/" name="OBJ KE DAE" description="Pertukaran Aset Digital" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-fbx/" name="OBJ KE FBX" description="3D Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-gltf/" name="OBJ KE GLTF" description="Format Transmisi GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-html/" name="OBJ KE HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-obj/" name="OBJ KE OBJ" description="3D Format Berkas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-ply/" name="OBJ KE PLY" description="Format File Poligon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-rvm/" name="OBJ KE RVM" description="Model Desain Tanaman AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/obj-to-u3d/" name="OBJ KE U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}