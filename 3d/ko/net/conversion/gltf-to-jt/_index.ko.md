﻿---
title: C#를 통해 GLTF을 JT로 변환 
weight: 530
url: /ko/net/conversion/gltf-to-jt/ 
description: GLTF에서 JT로의 C# 변환을 위한 샘플 코드. VB.NET, Asp.NET 또는 모든 .NET 기반 애플리케이션 내에서 배치 GLTF 파일을 JT로 변환하는 API 예제 코드를 사용합니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#를 통해 GLTF을 JT로 변환" h2="3D 모델링 및 렌더링 소프트웨어 없이 GLTF을 JT로 렌더링합니다." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#를 사용하여 GLTF을 JT로 변환하는 방법" %}}

 GLTF을(를) JT(으)로 변환하기 위해 다음을 사용합니다.
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API은(는) C# 플랫폼용으로 기능이 풍부하고 강력하며 사용하기 쉬운 문서 조작 및 변환API입니다. 열려있는
 [누겟](https://www.nuget.org/packages/aspose.3d) 
 패키지 관리자, 검색
 Aspose.3D 
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="패키지 관리자 콘솔 명령" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#를 통해 GLTF을 JT로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 프로그래머는 몇 줄의 코드로 GLTF 파일을 쉽게 로드하고 JT로 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Scene 클래스의 생성자를 통해 GLTF 파일 로드1. JT 형식으로 Scene.Save 메서드를 호출합니다.1. 지정된 경로에서 결과 JT 파일 확인
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 변환 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Mono 호환 OS.- Microsoft Visual Studio와 같은 개발 환경.- Aspose.3D for .NET 프로젝트에서 참조되는 DLL입니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="이 샘플 코드는 GLTF에서 JT로의 C# 전환을 보여줍니다." offSpacer="" %}}

```cs
// 소스 GLTF 파일 로드
Scene scene = new Scene("sourceFile.gltf");
// 3D 장면을 Siemens JT 형식의 파일로 변환
scene.Save("output.jt", FileFormat.SiemensJT9)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="GLTF을(를) JT(으)로 변환하는 무료 앱" sectionDescription="라이브 데모를 확인하십시오. [GLTF에서 JT로의 전환](https://products.aspose.app/3d/conversion/gltf-to-jt) 다음과 같은 혜택이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 아무것도 다운로드하거나 설정할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" GLTF 파일을 업로드하고 \"변환\" 버튼을 누르기만 하면 됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 결과 JT 파일에 대한 다운로드 링크를 즉시 얻을 수 있습니다." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 모델링 및 렌더링 소프트웨어 없이 3D 파일을 조작하는 3D 파일 처리 라이브러리. 3D API는 Discreet3DS, WavefrontOBJ, FBX(ASCII, 바이너리), STL(ASCII, 바이너리), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco 파일 형식 등 개발자는 3D 문서 형식의 내용을 쉽게 생성, 읽기, 변환, 수정 및 제어할 수 있습니다.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF(GL 전송 형식)은 3D 모델 정보를 JSON 형식으로 저장하는 3D 파일 형식입니다. JSON을 사용하면 3D 자산의 크기와 이러한 자산의 압축을 풀고 사용하는 데 필요한 런타임 처리가 최소화됩니다. 애플리케이션별 3D 장면 및 모델의 효율적인 전송 및 로드를 위해 채택되었습니다. glTF는 Khronos Group 3D Formats Working Group에서 개발했으며 제작자는 3D의 JPEG로도 설명합니다. 이 형식은 제작 워크플로를 간소화하고 업계 전반에 걸쳐 콘텐츠를 상호 운용할 수 있도록 하는 3D 콘텐츠 도구 및 서비스에 대한 확장 가능한 공통 게시 형식을 정의합니다. glTF 파일 형식을 만든 목적은 제작 워크플로를 간소화하고 업계 전반에 걸쳐 콘텐츠를 상호 운용할 수 있도록 하는 3D 콘텐츠 도구 및 서비스에 대해 확장 가능하고 공통된 게시 형식을 정의하는 것이었습니다. WebGL 및 기타 API를 사용하는 애플리케이션의 런타임 처리를 최소화합니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="jt" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}
JT(Jupiter Tessellation)은 Siemens PLM Software에서 개발한 효율적이고 유연한 업계 중심의 ISO 표준화 3D 데이터 형식입니다. 항공 우주, 자동차 산업 및 중장비의 기계 CAD 도메인은 JT를 가장 선도적인 3D 시각화 형식으로 사용합니다.
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="GLTF을(는) 아래 나열된 몇 가지를 포함하여 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-glb/" name="GLTF ~ GLB" description="바이너리 GL 전송 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-pdf/" name="GLTF ~ PDF" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-fbx/" name="GLTF ~ FBX" description="Autodesk FBX 교환 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-stl/" name="GLTF ~ STL" description="광조형 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-obj/" name="GLTF ~ OBJ" description="Wavefront 3D 개체 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-3ds/" name="GLTF ~ 3DS" description="3D 스튜디오 장면" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-dae/" name="GLTF ~ DAE" description="디지털 자산 교환 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-u3d/" name="GLTF ~ U3D" description="Universal 3D 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-ply/" name="GLTF ~ PLY" description="다각형 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-drc/" name="GLTF ~ DRC" description="Google Draco 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-rvm/" name="GLTF ~ RVM" description="아베바 RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-jt/" name="GLTF ~ JT" description="JT CAD 파일 열기" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-amf/" name="GLTF ~ AMF" description="적층 제조 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-html/" name="GLTF ~ HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-usd/" name="GLTF ~ USD" description="범용 장면 설명 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/gltf-to-usdz/" name="GLTF ~ USDZ" description="범용 장면 설명 압축 형식" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}