﻿---
title: Java를 통해 ASE을 3DS로 변환 
weight: 770
url: /ko/java/conversion/ase-to-3ds/ 
description: ASE 형식을 3DS 파일로 변환하는 샘플 Java 변환 코드. 이 예제 코드를 사용하여 웹 또는 데스크톱 Java 기반 애플리케이션 내에서 ASE을 3DS로 변환합니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java를 통해 ASE을 3DS로 변환" h2="3D 모델링 소프트웨어 없이 Java 라이브러리를 사용하여 ASE에서 3DS로 변환" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Java를 사용하여 ASE을 3DS로 변환하는 방법" %}}

 ASE을 3DS로 렌더링하기 위해 다음을 사용합니다.
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

{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 ASE을 3DS로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Java 프로그래머는 몇 줄의 코드로 ASE 파일을 3DS로 쉽게 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Scene 클래스의 생성자를 통해 ASE 파일 로드1. 3dsSaveOptions의 인스턴스 만들기1. 고급 변환을 위한 3DS 특정 속성 설정1. Scene.save 메소드 호출1. 3dsSaveOptions의 파일 확장자 및 개체가 3DS인 출력 경로를 전달합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Java 변환 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 JSP/JSF 애플리케이션 및 데스크톱 애플리케이션용 Java Runtime Environment와 호환되는 OS.- Maven에서 직접 최신 버전의 Aspose.3D for Java을(를) 받으십시오.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ASE에서 3DS로 Java 전환 소스 코드" offSpacer="" %}}

```cs
// Scene의 객체에 ASE 로드 
Scene document = new Scene("template.ase");
// 3dsSaveOptions의 인스턴스 생성 
Discreet3dsSaveOptions options = new Discreet3dsSaveOptions();
// ASE을 3DS로 저장 
document.save("output.3ds", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="ASE에서 3DS로의 전환 라이브 데모" sectionDescription="[ASE을(를) 3DS(으)로 변환](https://products.aspose.app/3d/conversion/ase-to-3ds) 지금 바로 라이브 데모 웹사이트를 방문하세요. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API을(를) 다운로드할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ASE 파일을 업로드하기만 하면 즉시 3DS(으)로 변환됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 다운로드 링크가 나옵니다." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 장면 조작 라이브러리" %}}

 Aspose.3D은(는) 3D 파일을 로드, 수정 및 변환하는 CAD 및 Gameware API입니다. API는 독립 실행형이며 3D 모델링 또는 렌더링 소프트웨어가 필요하지 않습니다. Discreet3DS, WavefrontOBJ, STL(ASCII, 바이너리), Universal3D, FBX(ASCII, 바이너리), Collada, glTF, PLY, GLB, DirectX 및 기타 형식. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}

ASE 파일은 레이어, 프레임, 팔레트, 태그 및 설정이 포함된 2D 애니메이션 또는 그래픽입니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}

확장자가 3DS인 파일은 Autodesk 3D Studio에서 사용하는 3D Studio(DOS) 메시 파일 형식을 나타냅니다. Autodesk 3D Studio는 1990년대부터 3D 파일 형식 시장에 있었고 이제 3D 모델링, 애니메이션 및 렌더링 작업을 위해 3D Studio MAX로 발전했습니다. 3DS 파일은 장면 및 이미지의 3D 표현을 위한 데이터를 포함하며 3D 데이터 가져오기 및 내보내기에 널리 사용되는 파일 형식 중 하나입니다. 카메라 위치, 메시 데이터, 조명 정보, 뷰포트 구성, 스무딩 그룹 데이터, 비트맵 참조 및 속성과 같은 정보를 고려하여 장면을 렌더링하기 위한 정점 및 다각형을 만듭니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="ASE을(는) 아래 나열된 몇 가지를 포함하여 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-amf/" name="ASE ~ AMF" description="적층 제조 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-dae/" name="ASE ~ DAE" description="디지털 자산 교환" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-fbx/" name="ASE ~ FBX" description="3D 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-gltf/" name="ASE ~ GLTF" description="GL 전송 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-html/" name="ASE ~ HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-obj/" name="ASE ~ OBJ" description="3D 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-ply/" name="ASE ~ PLY" description="다각형 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-rvm/" name="ASE ~ RVM" description="AVEVA 플랜트 설계 모델" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-stl/" name="ASE ~ STL" description="교체 가능한 3D 표면 기하학" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-u3d/" name="ASE ~ U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}