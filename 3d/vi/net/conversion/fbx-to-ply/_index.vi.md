﻿---
title: Chuyển đổi FBX sang PLY qua C# 
weight: 2600
url: /vi/net/conversion/fbx-to-ply/ 
description: Mã mẫu cho chuyển đổi FBX thành PLY C#. Sử dụng API mã mẫu cho hàng loạt tệp FBX để chuyển đổi PLY trong VB .NET, Asp .NET hoặc bất kỳ ứng dụng dựa trên .NET nào.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi FBX sang PLY qua C#" h2="Hiển thị FBX dưới dạng PLY mà không có bất kỳ 3D phần mềm kết xuất và mô hình hóa nào." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PLY" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển đổi FBX thành PLY bằng cách sử dụng C#" %}}

 Để chuyển đổi FBX thành PLY, chúng tôi sẽ sử dụng
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

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi FBX thành PLY qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET người lập trình có thể dễ dàng tải và chuyển đổi FBX tệp thành PLY chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp FBX qua hàm tạo của lớp Scene1. Tạo một phiên bản của PlySaveOptions1. Đặt PLY thuộc tính cụ thể cho chuyển đổi nâng cao1. Gọi phương thức Scene.Save1. Chuyển đường dẫn đầu ra với PLY phần mở rộng tệp & đối tượng của PlySaveOptions1. Kiểm tra tệp PLY kết quả tại đường dẫn được chỉ định
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã chuyển đổi .NET, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc một hệ điều hành tương thích với .NET Framework, .NET Core, Mono.- Môi trường phát triển như Microsoft Visual Studio.- Aspose.3D for .NET DLL được tham chiếu trong dự án của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã mẫu này hiển thị Chuyển đổi FBX sang PLY C#" offSpacer="" %}}

```cs
// tải FBX trong một đối tượng của Scene 
var document = new Aspose.ThreeD.Scene("template.fbx");
// tạo một phiên bản của PlySaveOptions 
var options = new Aspose.ThreeD.Formats.PlySaveOptions();
// lưu FBX dưới dạng PLY 
document.Save("output.ply", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ứng dụng miễn phí để chuyển đổi FBX sang PLY" sectionDescription="Kiểm tra các bản trình diễn trực tiếp của chúng tôi cho [Chuyển đổi FBX thành PLY](https://products.aspose.app/3d/conversion/fbx-to-ply) với những lợi ích sau đây." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hoặc thiết lập bất cứ thứ gì." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp FBX của bạn và nhấn nút \"Chuyển đổi\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Bạn sẽ ngay lập tức nhận được liên kết tải xuống cho tệp PLY kết quả." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D Thư viện xử lý tệp để thao tác 3D tệp mà không cần bất kỳ phần mềm kết xuất và mô hình hóa nào. 3D API hỗ trợ Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, Định dạng tệp PLY, DirectX, Google Draco và hơn thế nữa. Các nhà phát triển có thể tạo, đọc, chuyển đổi, sửa đổi và kiểm soát nội dung của 3D các định dạng tài liệu một cách dễ dàng.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, là một định dạng tệp 3D phổ biến được Kaydara phát triển ban đầu cho MotionBuilder. Nó được Autodesk Inc mua lại vào năm 2006 và hiện là một trong những định dạng trao đổi 3D chính được nhiều 3D công cụ sử dụng. FBX có sẵn ở cả định dạng tệp nhị phân và ASCII. Định dạng được thiết lập để cung cấp khả năng tương tác giữa các ứng dụng tạo nội dung kỹ thuật số. Có nhiều công cụ có sẵn để chuyển đổi từ / sang FBX định dạng tệp.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ply" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}
PLY, Định dạng Tệp Đa giác, đại diện cho 3D định dạng tệp lưu trữ các đối tượng đồ họa được mô tả như một tập hợp các đa giác. Mục đích của định dạng tệp này là thiết lập một loại tệp đơn giản và dễ dàng, đủ chung để hữu ích cho nhiều loại mô hình. Định dạng tệp PLY có dạng ASCII cũng như định dạng Binary để lưu trữ nhỏ gọn và lưu và tải nhanh chóng. Định dạng tệp được sử dụng bởi các ứng dụng khác nhau cung cấp hỗ trợ cho việc đọc tệp 3D.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi FBX thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-3ds/" name="FBX ĐẾN 3DS" description="3D Lưới Studio DOS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-amf/" name="FBX ĐẾN AMF" description="Định dạng sản xuất phụ gia" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-dae/" name="FBX ĐẾN DAE" description="Trao đổi tài sản kỹ thuật số" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-html/" name="FBX ĐẾN HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-obj/" name="FBX ĐẾN OBJ" description="3D Định dạng Tệp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-pdf/" name="FBX ĐẾN PDF" description="Định dạng tài liệu di động" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-rvm/" name="FBX ĐẾN RVM" description="Mô hình thiết kế nhà máy AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-stl/" name="FBX ĐẾN STL" description="Hình học bề mặt 3D có thể hoán đổi cho nhau" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-u3d/" name="FBX ĐẾN U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}