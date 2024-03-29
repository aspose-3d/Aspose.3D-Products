﻿---
title: Java를 통해 DXF을 PDF로 변환 
url: /ko/java/conversion/dxf-to-pdf/ 
description: DXF 형식을 PDF 파일로 변환하는 샘플 Java 변환 코드. 이 예제 코드를 사용하여 웹 또는 데스크톱 Java 기반 애플리케이션 내에서 DXF을 PDF로 변환합니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java를 통해 DXF을 PDF로 변환" h2="3D 모델링 소프트웨어 없이 Java 라이브러리를 사용하여 DXF에서 PDF로 변환" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Java를 사용하여 DXF을 PDF로 변환하는 방법" %}}

 DXF을 PDF로 렌더링하기 위해 다음을 사용합니다.
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API는 기능이 풍부하고 강력하며 사용하기 쉬운 전환 API for Java 플랫폼입니다. 에서 직접 최신 버전을 다운로드할 수 있습니다.
 [메이븐](https://repository.aspose.com/3d/) 
 다음 구성을 pom.xml에 추가하여 Maven 기반 프로젝트 내에 설치합니다.

{{% blocks/products/pf/agp/code-block title="저장소" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="의존" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 DXF을 PDF로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Java 프로그래머는 몇 줄의 코드로 DXF 파일을 PDF로 쉽게 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Scene 클래스의 생성자를 통해 DXF 파일 로드1. PdfSaveOptions의 인스턴스 만들기1. 고급 변환을 위한 PDF 특정 속성 설정1. Scene.save 메소드 호출1. PDF 파일 확장자와 PdfSaveOptions 개체를 사용하여 출력 경로를 전달합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Java 변환 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 JSP/JSF 애플리케이션 및 데스크톱 애플리케이션용 Java Runtime Environment와 호환되는 OS.- Maven에서 직접 최신 버전의 Aspose.3D for Java을(를) 받으십시오.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DXF에서 PDF로 Java 전환 소스 코드" offSpacer="" %}}

```cs
// Scene의 객체에 DXF 로드 
Scene document = new Scene("template.dxf");
// PdfSaveOptions의 인스턴스 만들기 
AmfSaveOptions options = new PdfSaveOptions();
// DXF을 PDF로 저장 
document.save("output.pdf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DXF에서 PDF로의 전환 라이브 데모" sectionDescription="[DXF을(를) PDF(으)로 변환](https://products.aspose.app/3d/conversion/dxf-to-pdf) 지금 바로 라이브 데모 웹사이트를 방문하세요. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API을(를) 다운로드할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" DXF 파일을 업로드하기만 하면 즉시 PDF(으)로 변환됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 다운로드 링크가 나옵니다." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 장면 조작 라이브러리" %}}

 Aspose.3D은(는) 3D 파일을 로드, 수정 및 변환하는 CAD 및 Gameware API입니다. API는 독립 실행형이며 3D 모델링 또는 렌더링 소프트웨어가 필요하지 않습니다. Discreet3DS, WavefrontOBJ, STL(ASCII, 바이너리), Universal3D, FBX(ASCII, 바이너리), Collada, glTF, PLY, GLB, DirectX 및 기타 형식. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}

DXF, 도면 교환 형식 또는 도면 교환 형식은 AutoCAD 도면 파일의 태그가 지정된 데이터 표현입니다. 파일의 각 요소에는 그룹 코드라는 접두어 정수 번호가 있습니다. 이 그룹 코드는 실제로 뒤에 오는 요소를 나타내고 주어진 개체 유형에 대한 데이터 요소의 의미를 나타냅니다. DXF을 사용하면 도면 파일에서 거의 모든 사용자 지정 정보를 표현할 수 있습니다. DXF 파일 형식은 AutoCAD와 다른 응용프로그램 간의 데이터 상호 운용성을 위해 Autodesk에서 CAD 데이터 파일 형식으로 개발했습니다. 따라서 DXF 파일 형식 상호 운용성 사양에 따라 데이터를 다른 형식에서 DXF AutoCAD로 가져올 수 있습니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

휴대용 문서 형식(PDF)은 1990년대에 Adobe에서 만든 문서 유형입니다. 이 파일 형식의 목적은 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제와 독립적인 형식으로 문서 및 기타 참조 자료를 표시하기 위한 표준을 도입하는 것입니다. PDF 파일은 확장 프로그램/플러그인을 통해 Chrome, Safari, Firefox와 같은 대부분의 최신 브라우저뿐만 아니라 Adobe Acrobat Reader/Writer에서도 열 수 있습니다. 상업적으로 사용 가능한 대부분의 소프트웨어 제품군은 추가 소프트웨어 구성 요소 없이도 문서를 PDF 파일 형식으로 변환할 수 있습니다. 따라서 PDF 파일 형식은 텍스트, 이미지, 하이퍼링크, 양식 필드, 리치 미디어, 디지털 서명, 첨부 파일, 메타데이터, 지리 공간 기능 및 소스의 일부가 될 수 있는 3D 개체와 같은 정보를 포함할 수 있는 완전한 기능을 가지고 있습니다. 문서.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="DXF을(는) 아래 나열된 몇 가지를 포함하여 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-3ds/" name="DXF ~ 3DS" description="3D 스튜디오 DOS 메시" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-amf/" name="DXF ~ AMF" description="적층 제조 형식" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ase/" name="DXF ~ ASE" description="2D 애니메이션 파일" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-dae/" name="DXF ~ DAE" description="디지털 자산 교환" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-fbx/" name="DXF ~ FBX" description="3D 형식" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-gltf/" name="DXF ~ GLTF" description="GL 전송 형식" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-html/" name="DXF ~ HTML" description="하이퍼 텍스트 마크업 언어" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-obj/" name="DXF ~ OBJ" description="3D 파일 형식" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ply/" name="DXF ~ PLY" description="다각형 파일 형식" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-rvm/" name="DXF ~ RVM" description="AVEVA 플랜트 설계 모델" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-stl/" name="DXF ~ STL" description="교체 가능한 3D 표면 기하학" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-u3d/" name="DXF ~ U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}