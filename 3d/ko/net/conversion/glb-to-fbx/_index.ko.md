﻿---
title: C#를 통해 GLB을 FBX로 변환 
weight: 530
url: /ko/net/conversion/glb-to-fbx/ 
description: GLB에서 FBX로의 C# 변환을 위한 샘플 코드. VB.NET, Asp.NET 또는 모든 .NET 기반 애플리케이션 내에서 배치 GLB 파일을 FBX로 변환하는 API 예제 코드를 사용합니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#를 통해 GLB을 FBX로 변환" h2="3D 모델링 및 렌더링 소프트웨어 없이 GLB을 FBX로 렌더링합니다." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="C#를 사용하여 GLB을 FBX로 변환하는 방법" %}}

 GLB을(를) FBX(으)로 변환하기 위해 다음을 사용합니다.
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

{{% blocks/products/pf/agp/feature-section-col title="C#를 통해 GLB을 FBX로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 프로그래머는 몇 줄의 코드로 GLB 파일을 쉽게 로드하고 FBX로 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Scene 클래스의 생성자를 통해 GLB 파일 로드1. FBX 형식으로 Scene.Save 메서드를 호출합니다.1. 지정된 경로에서 결과 FBX 파일 확인
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 변환 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Mono 호환 OS.- Microsoft Visual Studio와 같은 개발 환경.- Aspose.3D for .NET 프로젝트에서 참조되는 DLL입니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="이 샘플 코드는 GLB에서 FBX로의 C# 전환을 보여줍니다." offSpacer="" %}}

```cs
// 소스 바이너리 GLTF 파일 로드
Scene scene = new Scene("sourceFile.glb");
// 3D 장면을 Autodesk FBX 형식의 파일로 변환
scene.Save("output.fbx", FileFormat.FBX7700Binary)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="GLB을(를) FBX(으)로 변환하는 무료 앱" sectionDescription="라이브 데모를 확인하십시오. [GLB에서 FBX로의 전환](https://products.aspose.app/3d/conversion/glb-to-fbx) 다음과 같은 혜택이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 아무것도 다운로드하거나 설정할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" GLB 파일을 업로드하고 \"변환\" 버튼을 누르기만 하면 됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 결과 FBX 파일에 대한 다운로드 링크를 즉시 얻을 수 있습니다." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 모델링 및 렌더링 소프트웨어 없이 3D 파일을 조작하는 3D 파일 처리 라이브러리. 3D API는 Discreet3DS, WavefrontOBJ, FBX(ASCII, 바이너리), STL(ASCII, 바이너리), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco 파일 형식 등 개발자는 3D 문서 형식의 내용을 쉽게 생성, 읽기, 변환, 수정 및 제어할 수 있습니다.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB은 GL 전송 형식(glTF)에 저장된 3D 모델의 바이너리 파일 형식 표현입니다. 노드 계층 구조, 카메라, 재질, 애니메이션 및 메시와 같은 3D 모델에 대한 정보(바이너리 형식). 이 바이너리 형식은 바이너리 blob에 glTF 자산(JSON, .bin 및 이미지)을 저장합니다. 또한 glTF의 경우에 발생하는 파일 크기 증가 문제를 방지합니다. GLB 파일 형식을 사용하면 파일 크기가 작고, 로드가 빠르고, 완전한 3D 장면 표현이 가능하고, 추가 개발을 위한 확장성이 있습니다. 형식은 MIME 유형으로 model/gltf-binary를 사용합니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="fbx" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox는 원래 Kaydara에서 MotionBuilder용으로 개발한 인기 있는 3D 파일 형식입니다. 2006년 Autodesk Inc에 인수되었으며 현재 많은 3D 도구에서 사용되는 주요 3D 교환 형식 중 하나입니다. FBX는 바이너리 및 ASCII 파일 형식으로 사용할 수 있습니다. 형식은 디지털 콘텐츠 생성 응용 프로그램 간의 상호 운용성을 제공하기 위해 설정되었습니다. FBX 파일 형식에서/로 변환하는 데 사용할 수 있는 도구가 많이 있습니다.
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="GLB을(는) 아래 나열된 몇 가지를 포함하여 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-gltf/" name="GLB ~ GLTF" description="GL 전송 형식 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-pdf/" name="GLB ~ PDF" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-fbx/" name="GLB ~ FBX" description="Autodesk FBX 교환 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-stl/" name="GLB ~ STL" description="광조형 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-obj/" name="GLB ~ OBJ" description="Wavefront 3D 개체 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-3ds/" name="GLB ~ 3DS" description="3D 스튜디오 장면" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-dae/" name="GLB ~ DAE" description="디지털 자산 교환 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-u3d/" name="GLB ~ U3D" description="Universal 3D 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-ply/" name="GLB ~ PLY" description="다각형 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-drc/" name="GLB ~ DRC" description="Google Draco 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-rvm/" name="GLB ~ RVM" description="아베바 RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-jt/" name="GLB ~ JT" description="JT CAD 파일 열기" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-amf/" name="GLB ~ AMF" description="적층 제조 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-html/" name="GLB ~ HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-usd/" name="GLB ~ USD" description="범용 장면 설명 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-usdz/" name="GLB ~ USDZ" description="범용 장면 설명 압축 형식" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
