﻿---
title: Chuyển đổi DXF sang GLB qua C# 
weight: 530
url: /vi/net/conversion/dxf-to-glb/ 
description: Mã mẫu cho chuyển đổi DXF thành GLB C#. Sử dụng API mã mẫu cho hàng loạt tệp DXF để chuyển đổi GLB trong VB .NET, Asp .NET hoặc bất kỳ ứng dụng dựa trên .NET nào.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi DXF sang GLB qua C#" h2="Hiển thị DXF dưới dạng GLB mà không có bất kỳ 3D phần mềm kết xuất và mô hình hóa nào." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển đổi DXF thành GLB bằng cách sử dụng C#" %}}

 Để chuyển đổi DXF thành GLB, chúng tôi sẽ sử dụng
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

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi DXF thành GLB qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET người lập trình có thể dễ dàng tải và chuyển đổi DXF tệp thành GLB chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp DXF qua hàm tạo của lớp Scene1. Gọi phương thức Scene.Save với định dạng của GLB.1. Kiểm tra tệp GLB kết quả tại đường dẫn được chỉ định
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã chuyển đổi .NET, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc một hệ điều hành tương thích với .NET Framework, .NET Core, Mono.- Môi trường phát triển như Microsoft Visual Studio.- Aspose.3D for .NET DLL được tham chiếu trong dự án của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã mẫu này hiển thị Chuyển đổi DXF sang GLB C#" offSpacer="" %}}

```cs
// Tải tệp DXF nguồn
Scene scene = new Scene("sourceFile.dxf");
// Chuyển đổi cảnh 3D thành tệp ở định dạng Nhị phân GLTF
scene.Save("output.glb", FileFormat.GLTF2_Binary)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ứng dụng miễn phí để chuyển đổi DXF sang GLB" sectionDescription="Kiểm tra các bản trình diễn trực tiếp của chúng tôi cho [Chuyển đổi DXF thành GLB](https://products.aspose.app/3d/conversion/dxf-to-glb) với những lợi ích sau đây." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hoặc thiết lập bất cứ thứ gì." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp DXF của bạn và nhấn nút \"Chuyển đổi\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Bạn sẽ ngay lập tức nhận được liên kết tải xuống cho tệp GLB kết quả." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D Thư viện xử lý tệp để thao tác 3D tệp mà không cần bất kỳ phần mềm kết xuất và mô hình hóa nào. 3D API hỗ trợ Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, Định dạng tệp PLY, DirectX, Google Draco và hơn thế nữa. Các nhà phát triển có thể tạo, đọc, chuyển đổi, sửa đổi và kiểm soát nội dung của 3D các định dạng tài liệu một cách dễ dàng.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/3d/dxf/" >}}
DXF, Định dạng Trao đổi Bản vẽ, hoặc Định dạng Trao đổi Bản vẽ, là một biểu diễn dữ liệu được gắn thẻ của tệp bản vẽ AutoCAD. Mỗi phần tử trong tệp có một số nguyên tiền tố được gọi là mã nhóm. Mã nhóm này thực sự đại diện cho phần tử theo sau và cho biết ý nghĩa của phần tử dữ liệu đối với một kiểu đối tượng nhất định. DXF làm cho nó có thể thể hiện hầu hết tất cả thông tin do người dùng chỉ định trong một tệp bản vẽ.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="glb" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB là đại diện định dạng tệp nhị phân của các mô hình 3D được lưu ở Định dạng Truyền GL (glTF). Thông tin về các mô hình 3D như hệ thống phân cấp nút, máy ảnh, vật liệu, hoạt ảnh và lưới ở định dạng nhị phân. Định dạng nhị phân này lưu trữ nội dung glTF (JSON, .bin và hình ảnh) trong một khối nhị phân. Nó cũng tránh vấn đề tăng kích thước tệp xảy ra trong trường hợp glTF. Định dạng tệp GLB dẫn đến kích thước tệp nhỏ gọn, tải nhanh, biểu diễn cảnh 3D hoàn chỉnh và khả năng mở rộng để phát triển thêm. Định dạng sử dụng model / gltf-binary làm kiểu MIME.
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi DXF thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-gltf/" name="DXF ĐẾN GLTF" description="Tệp định dạng truyền GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-glb/" name="DXF ĐẾN GLB" description="Định dạng truyền GL nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-pdf/" name="DXF ĐẾN PDF" description="Định dạng tài liệu di động" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-fbx/" name="DXF ĐẾN FBX" description="Tệp trao đổi Autodesk FBX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-stl/" name="DXF ĐẾN STL" description="Tệp in nổi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-obj/" name="DXF ĐẾN OBJ" description="Wavefront 3D Tệp Đối tượng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-3ds/" name="DXF ĐẾN 3DS" description="3D Cảnh Studio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-dae/" name="DXF ĐẾN DAE" description="Tệp trao đổi tài sản kỹ thuật số" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-u3d/" name="DXF ĐẾN U3D" description="Universal 3D Tệp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-ply/" name="DXF ĐẾN PLY" description="Định dạng tệp đa giác" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-drc/" name="DXF ĐẾN DRC" description="Google Draco Định dạng Tệp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-rvm/" name="DXF ĐẾN RVM" description="AVEVA RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-jt/" name="DXF ĐẾN JT" description="JT Mở CAD Tệp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-amf/" name="DXF ĐẾN AMF" description="Tệp sản xuất phụ gia" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-html/" name="DXF ĐẾN HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-usd/" name="DXF ĐẾN USD" description="Định dạng mô tả cảnh phổ quát" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-usdz/" name="DXF ĐẾN USDZ" description="Định dạng nén mô tả cảnh phổ quát" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
