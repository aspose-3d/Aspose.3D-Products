﻿---
title: Java를 통해 DAE을 JT로 변환
weight: 530
url: /ko/java/conversion/dae-to-jt/ 
description: DAE 형식을 JT 파일로 변환하는 샘플 Java 변환 코드. 이 예제 코드를 사용하여 웹 또는 데스크톱 Java 기반 애플리케이션 내에서 DAE을 JT로 변환합니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java를 통해 DAE을 JT로 변환" h2="3D 모델링 소프트웨어 없이 Java 라이브러리를 사용하여 DAE에서 JT로 변환" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="JT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DAE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Java를 사용하여 DAE을 JT로 변환하는 방법" %}}

 DAE을 JT로 렌더링하기 위해 다음을 사용합니다.
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

{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 DAE을 JT로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Java 프로그래머는 몇 줄의 코드로 DAE 파일을 JT로 쉽게 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Scene 클래스의 생성자를 통해 DAE 파일 로드1. JT 형식으로 Scene.save 메서드를 호출합니다.1. 지정된 경로에서 결과 JT 파일 확인
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Java 변환 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 JSP/JSF 애플리케이션 및 데스크톱 애플리케이션용 Java Runtime Environment와 호환되는 OS.- Maven에서 직접 최신 버전의 Aspose.3D for Java을(를) 받으십시오.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DAE에서 JT로 Java 전환 소스 코드" offSpacer="" %}}

```cs
// 소스 Collada DAE 파일 로드
Scene scene = new Scene("sourceFile.dae");
// 3D 장면을 Siemens JT 형식의 파일로 변환
scene.save("output.jt", FileFormat.SIEMENSJT9)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DAE에서 JT로의 전환 라이브 데모" sectionDescription="[DAE을(를) JT(으)로 변환](https://products.aspose.app/3d/conversion/dae-to-jt) 지금 바로 라이브 데모 웹사이트를 방문하세요. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API을(를) 다운로드할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" DAE 파일을 업로드하기만 하면 즉시 JT(으)로 변환됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 다운로드 링크가 나옵니다." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 장면 조작 라이브러리" %}}

 Aspose.3D은(는) 3D 파일을 로드, 수정 및 변환하는 CAD 및 Gameware API입니다. API는 독립 실행형이며 3D 모델링 또는 렌더링 소프트웨어가 필요하지 않습니다. USD, Discreet3DS, WavefrontOBJ, STL(ASCII, Binary), Universal3D, FBX(ASCII, Binary), Collada, glTF, PLY, GLB, DirectX 및 기타 형식. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}

DAE 파일은 대화형 3D 애플리케이션 간에 데이터를 교환하는 데 사용되는 디지털 자산 교환 파일 형식입니다. 이 파일 형식은 그래픽 소프트웨어 응용 프로그램 간의 디지털 자산 교환을 위한 개방형 표준 XML 스키마인 COLLADA(COLLAborative Design Activity) XML 스키마를 기반으로 합니다. ISO에서 공개 사양인 ISO/pAS 17506으로 채택했습니다. DAE 파일은 Adobe Photoshop, AutoDesk Maya, AutoDesk AutoCAD와 같은 애플리케이션 및 Aspose.CAD과 같은 API에서 열 수 있습니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JT" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}

JT(Jupiter Tessellation)은 Siemens PLM Software에서 개발한 효율적이고 유연한 업계 중심의 ISO 표준화 3D 데이터 형식입니다. 항공 우주, 자동차 산업 및 중장비의 기계 CAD 도메인은 JT를 가장 선도적인 3D 시각화 형식으로 사용합니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="DAE을(는) 아래 나열된 몇 가지를 포함하여 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-gltf/" name="DAE ~ GLTF" description="GL 전송 형식 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-glb/" name="DAE ~ GLB" description="바이너리 GL 전송 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-pdf/" name="DAE ~ PDF" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-fbx/" name="DAE ~ FBX" description="Autodesk FBX 교환 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-stl/" name="DAE ~ STL" description="광조형 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-obj/" name="DAE ~ OBJ" description="Wavefront 3D 개체 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-3ds/" name="DAE ~ 3DS" description="3D 스튜디오 장면" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-u3d/" name="DAE ~ U3D" description="Universal 3D 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-ply/" name="DAE ~ PLY" description="다각형 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-drc/" name="DAE ~ DRC" description="Google Draco 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-rvm/" name="DAE ~ RVM" description="아베바 RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-jt/" name="DAE ~ JT" description="JT CAD 파일 열기" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-amf/" name="DAE ~ AMF" description="적층 제조 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-html/" name="DAE ~ HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-usd/" name="DAE ~ USD" description="범용 장면 설명 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-usdz/" name="DAE ~ USDZ" description="범용 장면 설명 압축 형식" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}