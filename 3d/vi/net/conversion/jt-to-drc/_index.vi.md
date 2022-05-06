﻿---
title: Chuyển đổi JT sang DRC qua C# 
url: /vi/net/conversion/jt-to-drc/ 
description: Mã mẫu cho chuyển đổi JT thành DRC C#. Sử dụng API mã mẫu cho hàng loạt tệp JT để chuyển đổi DRC trong VB .NET, Asp .NET hoặc bất kỳ ứng dụng dựa trên .NET nào.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi JT sang DRC qua C#" h2="Hiển thị JT dưới dạng DRC mà không có bất kỳ 3D phần mềm kết xuất và mô hình hóa nào." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DRC" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển đổi JT thành DRC bằng cách sử dụng C#" %}}

 Để chuyển đổi JT thành DRC, chúng tôi sẽ sử dụng
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API là một nền tảng thao tác và chuyển đổi tài liệu API giàu tính năng, mạnh mẽ và dễ sử dụng API cho C#. Mở
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 quản lý gói, tìm kiếm
 Aspose.3D 
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Lệnh Bảng điều khiển Trình quản lý Gói" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi JT thành DRC qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET người lập trình có thể dễ dàng tải và chuyển đổi JT tệp thành DRC chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp JT qua hàm tạo của lớp Scene1. Tạo một phiên bản của AmfSaveOptions1. Đặt DRC thuộc tính cụ thể cho chuyển đổi nâng cao1. Gọi phương thức Scene.Save1. Chuyển đường dẫn đầu ra với DRC phần mở rộng tệp & đối tượng của DrcSaveOptions1. Kiểm tra tệp DRC kết quả tại đường dẫn được chỉ định
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã chuyển đổi .NET, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc một hệ điều hành tương thích với .NET Framework, .NET Core, Mono.- Môi trường phát triển như Microsoft Visual Studio.- Aspose.3D for .NET DLL được tham chiếu trong dự án của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã mẫu này hiển thị Chuyển đổi JT sang DRC C#" offSpacer="" %}}

```cs
// tải JT trong một đối tượng của Scene 
var document = new Aspose.ThreeD.Scene("template.jt");
// tạo một phiên bản của DrcSaveOptions 
var options = new Aspose.ThreeD.Formats.DrcSaveOptions();
// lưu JT dưới dạng DRC 
document.Save("output.drc", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ứng dụng miễn phí để chuyển đổi JT sang DRC" sectionDescription="Kiểm tra các bản trình diễn trực tiếp của chúng tôi cho [Chuyển đổi JT thành DRC](https://products.aspose.app/3d/conversion/jt-to-drc) với những lợi ích sau đây." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hoặc thiết lập bất cứ thứ gì." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp JT của bạn và nhấn nút \"Chuyển đổi\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Bạn sẽ ngay lập tức nhận được liên kết tải xuống cho tệp DRC kết quả." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D Thư viện xử lý tệp để thao tác 3D tệp mà không cần bất kỳ phần mềm kết xuất và mô hình hóa nào. 3D API hỗ trợ Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, Định dạng tệp PLY, DirectX, Google Draco và hơn thế nữa. Các nhà phát triển có thể tạo, đọc, chuyển đổi, sửa đổi và kiểm soát nội dung của 3D các định dạng tài liệu một cách dễ dàng.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JT" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}
JT (Jupiter Tessellation) là một định dạng dữ liệu hiệu quả, tập trung vào ngành và linh hoạt 3D được tiêu chuẩn hóa bởi Phần mềm PLM của Siemens. Các lĩnh vực CAD cơ khí của Hàng không vũ trụ, công nghiệp ô tô và Thiết bị nặng sử dụng JT làm định dạng hình ảnh hóa 3D hàng đầu của chúng. Định dạng JT là một biểu đồ cảnh hỗ trợ các thuộc tính và nút CAD cụ thể. Các kỹ thuật nén phức tạp được sử dụng để lưu trữ dữ liệu khía cạnh (tam giác). Định dạng này được cấu trúc để hỗ trợ các thuộc tính trực quan, thông tin sản phẩm và sản xuất (PMI) và Siêu dữ liệu. Có một sự hỗ trợ tốt cho việc phát trực tuyến nội dung không đồng bộ. Trong ngành cơ khí nặng, các chuyên gia sử dụng tệp JT trong các giải pháp CAD và chương trình phần mềm quản lý vòng đời sản phẩm (PLM) của họ để kiểm tra hình dạng của hàng hóa phức tạp.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="drc" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
Tệp có phần mở rộng .drc là định dạng tệp 3D nén được tạo bằng thư viện Google Draco. Google cung cấp Draco dưới dạng thư viện mã nguồn mở để nén và giải nén 3D lưới hình học và đám mây điểm, đồng thời cải thiện khả năng lưu trữ và truyền tải 3D đồ họa. Nó mã hóa dữ liệu đầu vào và lưu dưới dạng tệp .drc. Ở cuối nhận, API đọc các tệp .drc và có thể xuất các tệp này dưới dạng tệp PLY hoặc OBJ. Tệp đầu ra được nén cho phép người dùng tải xuống ứng dụng nhanh hơn và cung cấp khả năng tải nhanh đồ họa 3D trong các trình duyệt.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi JT thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-3ds/" name="JT ĐẾN 3DS" description="3D Lưới Studio DOS" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-amf/" name="JT ĐẾN AMF" description="Định dạng sản xuất phụ gia" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-dae/" name="JT ĐẾN DAE" description="Trao đổi tài sản kỹ thuật số" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-fbx/" name="JT ĐẾN FBX" description="3D Định dạng" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-html/" name="JT ĐẾN HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-obj/" name="JT ĐẾN OBJ" description="3D Định dạng Tệp" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-pdf/" name="JT ĐẾN PDF" description="Định dạng tài liệu di động" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-ply/" name="JT ĐẾN PLY" description="Định dạng tệp đa giác" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-rvm/" name="JT ĐẾN RVM" description="Mô hình thiết kế nhà máy AVEVA" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-stl/" name="JT ĐẾN STL" description="Hình học bề mặt 3D có thể hoán đổi cho nhau" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-u3d/" name="JT ĐẾN U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}