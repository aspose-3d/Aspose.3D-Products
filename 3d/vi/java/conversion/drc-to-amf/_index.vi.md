﻿---
title: Chuyển đổi DRC sang AMF qua Java 
url: /vi/java/conversion/drc-to-amf/ 
description: Mã chuyển đổi Java mẫu cho định dạng DRC thành AMF tệp. Sử dụng mã ví dụ này để chuyển đổi DRC thành AMF trong bất kỳ ứng dụng dựa trên Web hoặc Máy tính để bàn Java nào.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi DRC sang AMF qua Java" h2="Chuyển đổi DRC sang AMF bằng cách sử dụng thư viện Java mà không cần bất kỳ 3D phần mềm tạo mô hình nào." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="AMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển đổi DRC thành AMF bằng cách sử dụng Java" %}}

 Để hiển thị DRC thành AMF, chúng tôi sẽ sử dụng
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

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi DRC thành AMF qua Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java lập trình viên có thể dễ dàng chuyển đổi tệp DRC thành AMF chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp DRC qua hàm tạo của lớp Scene1. Tạo một phiên bản của AmfSaveOptions1. Đặt AMF thuộc tính cụ thể cho chuyển đổi nâng cao1. Gọi phương thức Scene.save1. Chuyển đường dẫn đầu ra với AMF phần mở rộng tệp & đối tượng của AmfSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã chuyển đổi Java, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với Java Môi trường thời gian chạy cho Ứng dụng JSP / JSF và Ứng dụng trên máy tính để bàn.- Tải phiên bản mới nhất của Aspose.3D for Java trực tiếp từ Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã nguồn chuyển đổi DRC thành AMF Java" offSpacer="" %}}

```cs
// tải DRC trong một đối tượng của Scene 
Scene document = new Scene("template.drc");
// tạo một phiên bản của AmfSaveOptions 
AmfSaveOptions options = new AmfSaveOptions();
// lưu DRC dưới dạng AMF 
document.save("output.amf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DRC thành AMF Bản trình diễn Trực tiếp Chuyển đổi" sectionDescription="[Chuyển đổi DRC thành AMF](https://products.aspose.app/3d/conversion/drc-to-amf) ngay bây giờ bằng cách truy cập trang web Demos Trực tiếp của chúng tôi. Bản demo trực tiếp có những lợi ích sau" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp DRC của bạn, tệp sẽ được chuyển đổi ngay lập tức thành AMF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Bạn sẽ nhận được liên kết tải xuống." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Thư viện Thao tác Cảnh" %}}

 Aspose.3D là một CAD và Phần mềm trò chơi API để tải, sửa đổi và chuyển đổi 3D tệp. API là một phần mềm độc lập và không yêu cầu bất kỳ 3D phần mềm kết xuất hoặc mô hình hóa nào. Người ta có thể dễ dàng sử dụng API cho Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX và các định dạng khác. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}

Tệp có phần mở rộng .drc là định dạng tệp 3D nén được tạo bằng thư viện Google Draco. Google cung cấp Draco dưới dạng thư viện mã nguồn mở để nén và giải nén 3D lưới hình học và đám mây điểm, đồng thời cải thiện khả năng lưu trữ và truyền tải 3D đồ họa. Nó mã hóa dữ liệu đầu vào và lưu dưới dạng tệp .drc. Ở cuối nhận, API đọc các tệp .drc và có thể xuất các tệp này dưới dạng tệp PLY hoặc OBJ. Tệp đầu ra được nén cho phép người dùng tải xuống ứng dụng nhanh hơn và cung cấp khả năng tải nhanh đồ họa 3D trong các trình duyệt.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="AMF" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}

Định dạng tệp Sản xuất Phụ gia (AMF) xác định các tiêu chuẩn mở cho mô tả đối tượng để được sử dụng bởi các quy trình sản xuất phụ gia chẳng hạn như 3D In. CAD chương trình sử dụng định dạng tệp AMF bằng cách sử dụng thông tin như hình học, màu sắc và chất liệu của các đối tượng. Định dạng AMF khác với định dạng STL vì hình bên không hỗ trợ màu sắc, vật liệu, mạng lưới và các chòm sao.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}