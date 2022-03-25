﻿---
title: Java 를 통해 PDF 에서 STL 로 변환 
url: /ko/java/conversion/pdf-to-stl/ 
description: PDF 형식의 Java 변환 코드를 STL 파일로 샘플링합니다. 이 예제 코드를 사용하여 모든 웹 또는 데스크톱 Java 기반 응용 프로그램 내에서 PDF 에서 STL 로 변환할 수 있습니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java 를 통해 PDF 에서 STL 로 변환" h2="3D 모델링 소프트웨어없이 Java 라이브러리를 사용하여 PDF ~ STL 변환." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Java 를 사용하여 PDF 에서 STL 로 변환하는 방법" %}}

 PDF 을 STL 로 렌더링하려면
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API 기능이 풍부하고 강력하며 사용하기 쉬운 변환 API for Java 플랫폼입니다. 최신 버전을 직접 다운로드 할 수 있습니다.
 [메이븐](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 Pom. Xml에 다음 구성을 추가하여 Maven 기반 프로젝트에 설치하십시오.

{{% blocks/products/pf/agp/code-block title="저장소" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="의존성" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Java 를 통해 PDF 에서 STL 로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Java 프로그래머는 몇 줄의 코드로 PDF 파일을 STL 로 쉽게 변환 할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. 장면 클래스의 생성자를 통해 PDF 파일을로드1. StlSaveOptions 인스턴스 만들기1. 고급 변환을위한 STL 특정 속성 설정1. 전화 장면. 저장 방법1. STL 파일 확장자 및 StlSaveOptions 객체를 사용하여 출력 경로를 전달합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Java 변환 코드를 실행하기 전에 다음과 같은 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft 창 또는 JSP/JSF 응용 프로그램 및 데스크톱 응용 프로그램에 대한 Java 런타임 환경과 호환되는 OS.- Maven에서 직접 Aspose.3D for Java 의 최신 버전을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PDF ~ STL Java 변환 소스 코드" offSpacer="" %}}

```cs
// 장면의 객체에 PDF 로드 
Scene document = new Scene("template.pdf");
// StlSaveOptions 인스턴스 만들기 
AmfSaveOptions options = new StlSaveOptions();
// PDF 을 STL 로 저장 
document.save("output.stl", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PDF ~ STL 변환 라이브 데모" sectionDescription="[PDF 에서 STL 로 변환](https://products.aspose.app/3d/conversion/pdf-to-stl) 라이브 데모 웹 사이트를 방문하여 지금. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API 을 다운로드할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" PDF 파일을 업로드하면 즉시 STL 로 변환됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 다운로드 링크를 얻을 수 있습니다." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 장면 조작 라이브러리" %}}

 Aspose.3D 은 CAD 및 Gameware API 로 3D 파일을 로드, 수정 및 변환합니다. API 는 독립형이며 3D 모델링 또는 렌더링 소프트웨어가 필요하지 않습니다. Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary) 에 API 를 쉽게 사용할 수 있습니다. Collada, glTF, PLY, GLB, DirectX 및 더 많은 형식. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

휴대용 문서 형식 (PDF) 은 어도비가 1990 년대에 다시 만든 문서 유형입니다. 이 파일 형식의 목적은 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제와 독립적 인 형식으로 문서 및 기타 참조 자료를 표현하는 표준을 도입하는 것이 었습니다. PDF 파일은 확장/플러그인을 통해 크롬, 사파리, 파이어 폭스와 같은 대부분의 최신 브라우저에서 어도비 곡예사 리더/라이터에서도 열 수 있습니다. 시판되는 대부분의 소프트웨어 제품군은 추가 소프트웨어 구성 요소의 요구 없이 문서를 PDF 파일 형식으로 변환 할 수도 있습니다. 따라서 PDF 파일 형식은 텍스트, 이미지, 하이퍼링크, 폼 필드, 리치 미디어, 디지털 서명, 첨부 파일, 메타데이터, 소스 문서의 일부로 될 수있는 지리 공간 기능 및 3D 개체.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}

Stereolithrography의 약어 인 STL 은 3 차원 표면 형상을 나타내는 교환 가능한 파일 형식입니다. 파일 형식은 빠른 프로토 타이핑, 3D 인쇄 및 컴퓨터 지원 제조와 같은 여러 분야에서 사용됩니다. 그것은 표면을 패싯으로 알려진 일련의 작은 삼각형으로 나타내며, 각 패싯은 수직 방향과 삼각형의 정점을 나타내는 3 개의 점으로 설명됩니다. 결과적인 데이터는 fabber에 의해 구축될 3D 형상의 단면을 결정하기 위해 애플리케이션에 의해 사용된다. STL 파일 형식으로 색상, 텍스처 또는 기타 일반적인 CAD 모델 속성을 표현할 수 있는 정보가 없습니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}