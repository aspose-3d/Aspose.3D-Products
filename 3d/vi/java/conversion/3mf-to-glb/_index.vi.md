﻿---
title: Chuyển đổi 3MF sang GLB qua Java
weight: 530
url: /vi/java/conversion/3mf-to-glb/ 
description: Mã chuyển đổi Java mẫu cho định dạng 3MF thành GLB tệp. Sử dụng mã ví dụ này để chuyển đổi 3MF thành GLB trong bất kỳ ứng dụng dựa trên Web hoặc Máy tính để bàn Java nào.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi 3MF sang GLB qua Java" h2="Chuyển đổi 3MF sang GLB bằng cách sử dụng thư viện Java mà không cần bất kỳ 3D phần mềm tạo mô hình nào." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3MF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển đổi 3MF thành GLB bằng cách sử dụng Java" %}}

 Để hiển thị 3MF thành GLB, chúng tôi sẽ sử dụng
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API là một nền tảng chuyển đổi API for Java giàu tính năng, mạnh mẽ và dễ sử dụng. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp từ
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
 và cài đặt nó trong dự án dựa trên Maven của bạn bằng cách thêm các cấu hình sau vào pom.xml.

{{% blocks/products/pf/agp/code-block title="Kho" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Sự phụ thuộc" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi 3MF thành GLB qua Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java lập trình viên có thể dễ dàng chuyển đổi tệp 3MF thành GLB chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp 3MF qua hàm tạo của lớp Scene1. Gọi phương thức Scene.save với định dạng của GLB.1. Kiểm tra tệp GLB kết quả tại đường dẫn được chỉ định
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã chuyển đổi Java, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với Java Môi trường thời gian chạy cho Ứng dụng JSP / JSF và Ứng dụng trên máy tính để bàn.- Tải phiên bản mới nhất của Aspose.3D for Java trực tiếp từ Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã nguồn chuyển đổi 3MF thành GLB Java" offSpacer="" %}}

```cs
// Tải tệp 3MF nguồn
Scene scene = new Scene("sourceFile.3mf");
// Chuyển đổi cảnh 3D thành tệp ở định dạng Nhị phân GLTF
scene.save("output.glb", FileFormat.GLTF2_BINARY)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="3MF thành GLB Bản trình diễn Trực tiếp Chuyển đổi" sectionDescription="[Chuyển đổi 3MF thành GLB](https://products.aspose.app/3d/conversion/3mf-to-glb) ngay bây giờ bằng cách truy cập trang web Demos Trực tiếp của chúng tôi. Bản demo trực tiếp có những lợi ích sau" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp 3MF của bạn, tệp sẽ được chuyển đổi ngay lập tức thành GLB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Bạn sẽ nhận được liên kết tải xuống." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Thư viện Thao tác Cảnh" %}}

 Aspose.3D là một CAD và Phần mềm trò chơi API để tải, sửa đổi và chuyển đổi 3D tệp. API là một phần mềm độc lập và không yêu cầu bất kỳ 3D phần mềm kết xuất hoặc mô hình hóa nào. Người ta có thể dễ dàng sử dụng API cho USD, Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX và các định dạng khác. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}

3MF, 3D Định dạng Sản xuất, được các ứng dụng sử dụng để hiển thị 3D mô hình đối tượng cho nhiều ứng dụng, nền tảng, dịch vụ và máy in khác. Nó được xây dựng để tránh những hạn chế và vấn đề ở các 3D định dạng tệp khác, như STL, để làm việc với các phiên bản mới nhất của máy in 3D. 3MF là một định dạng tệp tương đối mới đã được phát triển và xuất bản bởi tập đoàn 3MF. Nó đủ phong phú để mô tả đầy đủ một mô hình, giữ lại thông tin nội bộ, màu sắc và các đặc điểm khác giúp nó có thể mở rộng để hỗ trợ các cải tiến mới trong in 3D. Định dạng này có thể mở rộng, có thể được chấp nhận rộng rãi và không có các vấn đề xảy ra với các định dạng tệp được sử dụng rộng rãi khác.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}

GLB là đại diện định dạng tệp nhị phân của các mô hình 3D được lưu ở Định dạng Truyền GL (glTF). Thông tin về các mô hình 3D như hệ thống phân cấp nút, máy ảnh, vật liệu, hoạt ảnh và lưới ở định dạng nhị phân. Định dạng nhị phân này lưu trữ nội dung glTF (JSON, .bin và hình ảnh) trong một khối nhị phân. Nó cũng tránh vấn đề tăng kích thước tệp xảy ra trong trường hợp glTF. Định dạng tệp GLB dẫn đến kích thước tệp nhỏ gọn, tải nhanh, biểu diễn cảnh 3D hoàn chỉnh và khả năng mở rộng để phát triển thêm. Định dạng sử dụng model / gltf-binary làm kiểu MIME.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi 3MF thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-gltf/" name="3MF ĐẾN GLTF" description="Tệp định dạng truyền GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-glb/" name="3MF ĐẾN GLB" description="Định dạng truyền GL nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-pdf/" name="3MF ĐẾN PDF" description="Định dạng tài liệu di động" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-fbx/" name="3MF ĐẾN FBX" description="Tệp trao đổi Autodesk FBX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-stl/" name="3MF ĐẾN STL" description="Tệp in nổi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-obj/" name="3MF ĐẾN OBJ" description="Wavefront 3D Tệp Đối tượng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-3ds/" name="3MF ĐẾN 3DS" description="3D Cảnh Studio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-dae/" name="3MF ĐẾN DAE" description="Tệp trao đổi tài sản kỹ thuật số" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-u3d/" name="3MF ĐẾN U3D" description="Universal 3D Tệp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-ply/" name="3MF ĐẾN PLY" description="Định dạng tệp đa giác" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-drc/" name="3MF ĐẾN DRC" description="Google Draco Định dạng Tệp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-rvm/" name="3MF ĐẾN RVM" description="AVEVA RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-jt/" name="3MF ĐẾN JT" description="JT Mở CAD Tệp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-amf/" name="3MF ĐẾN AMF" description="Tệp sản xuất phụ gia" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-html/" name="3MF ĐẾN HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-usd/" name="3MF ĐẾN USD" description="Định dạng mô tả cảnh phổ quát" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-usdz/" name="3MF ĐẾN USDZ" description="Định dạng nén mô tả cảnh phổ quát" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}