﻿---
title: Lihat DRC Format Berkas melalui .NET 
url: /id/net/viewer/drc/ 
description: C# kode sumber untuk memuat, merender, dan menampilkan DRC dokumen pada .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin Platforms.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="DRC Penampil Berkas for .NET" h2="Render file DRC tanpa perangkat lunak pemodelan dan rendering 3D apa pun." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Cara Melihat DRC Berkas Menggunakan C#" %}}

Untuk melihat DRC file, kami akan menggunakan <a href="/3d/net/">Aspose.3D for .NET</a> API yang kaya fitur, canggih, dan mudah digunakan API untuk C# platform yang akan digunakan dengan Pemirsa mana pun. Membuka <a href="https://www.nuget.org/packages/aspose.3d">NuGet</a> manajer paket, cari <b>Aspose.3D</b> dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Perintah Konsol Manajer Paket" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Melihat DRC melalui C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D memudahkan pengembang untuk melihat file DRC hanya dengan beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file DRC melalui konstruktor kelas Scene1. Buat instance Html5SaveOptions1. Setel properti untuk pemformatan lanjutan1. Panggil metode Scene.Save dengan objek Html5SaveOptions1. Periksa file HTML yang dihasilkan di browser default

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET didukung di semua sistem operasi utama. Pastikan saja Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin Platforms- Lingkungan pengembangan seperti Microsoft Visual Studio- Aspose.3D for .NET dirujuk dalam proyek Anda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kode untuk melihat DRC" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// memuat DRC adegan melalui instance Adegan
var scene = new ThreeD.Scene("template.drc");
// buat objek Html5SaveOptions dan atur properti untuk pemformatan
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // matikan jaringan
    ShowGrid = false,
    // matikan antarmuka pengguna
    ShowUI = false
};

// simpan 3D adegan sebagai HTML5
scene.Save(output, options);
// memuat hasil HTML di browser default
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.3D adalah CAD dan Gameware API untuk memuat, memodifikasi, dan mengonversi file 3D. API berdiri sendiri dan tidak memerlukan perangkat lunak pemodelan atau rendering 3D apa pun. Seseorang dapat dengan mudah menggunakan API untuk Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX, dan format lainnya.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplikasi Gratis untuk Dilihat DRC" sectionDescription="Periksa demo langsung kami untuk [Lihat DRC](https://products.aspose.app/3d/viewer/drc) dengan manfaat sebagai berikut." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh atau mengatur apa pun" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis atau mengkompilasi kode" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file DRC dan tekan tombol \"Lihat\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Unduh file DRC dari tautan, jika diperlukan" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
File dengan ekstensi .drc adalah format file 3D terkompresi yang dibuat dengan perpustakaan Google Draco. Google menawarkan Draco sebagai perpustakaan sumber terbuka untuk mengompresi dan mendekompresi jerat geometris 3D dan awan titik, serta meningkatkan penyimpanan dan transmisi grafik 3D. Ini mengkodekan data input dan menyimpannya sebagai file .drc. Di pihak penerima, API membaca file .drc dan dapat menampilkannya sebagai file PLY atau OBJ. File keluaran terkompresi memungkinkan pengguna mengunduh aplikasi lebih cepat dan menyediakan pemuatan grafis 3D dengan cepat di browser.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Penampil yang Didukung Lainnya" subTitle="Menggunakan C#, Seseorang juga dapat melihat banyak format file lainnya termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Studio DOS Mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D Format Manufaktur" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Format Manufaktur Aditif" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="File Animasi 2D" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Pertukaran Aset Digital" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="Menggambar Format Pertukaran" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D Representasi Biner File" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="Format Transmisi GL" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="File Tesselasi Jupiter" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D Format Berkas" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Format File Poligon" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="Model Desain Tanaman AVEVA" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="3D Geometri Permukaan yang Dapat Dipertukarkan" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Bahasa Pemodelan Realitas Virtual" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="x" description="Gambar Model Langsung" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="Format Pengarsipan" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}