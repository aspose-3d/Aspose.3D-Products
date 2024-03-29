﻿---
title: C#를 통해 PDF을 U3D로 변환 
weight: 610
url: /ko/net/conversion/pdf-to-u3d/ 
description: PDF에서 U3D로의 C# 변환을 위한 샘플 코드. VB.NET, Asp.NET 또는 모든 .NET 기반 애플리케이션 내에서 배치 PDF 파일을 U3D로 변환하는 API 예제 코드를 사용합니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#를 통해 PDF을 U3D로 변환" h2="3D 모델링 및 렌더링 소프트웨어 없이 PDF을 U3D로 렌더링합니다." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="C#를 사용하여 PDF을 U3D로 변환하는 방법" %}}

 PDF을(를) U3D(으)로 변환하기 위해 다음을 사용합니다.
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

{{% blocks/products/pf/agp/feature-section-col title="C#를 통해 PDF을 U3D로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 프로그래머는 몇 줄의 코드로 PDF 파일을 쉽게 로드하고 U3D로 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Scene 클래스의 생성자를 통해 PDF 파일 로드1. U3dSaveOptions의 인스턴스 생성1. 고급 변환을 위한 U3D 특정 속성 설정1. Scene.Save 메서드 호출1. U3dSaveOptions의 파일 확장자와 개체가 U3D인 출력 경로를 전달합니다.1. 지정된 경로에서 결과 U3D 파일 확인
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 변환 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Mono 호환 OS.- Microsoft Visual Studio와 같은 개발 환경.- Aspose.3D for .NET 프로젝트에서 참조되는 DLL입니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="이 샘플 코드는 PDF에서 U3D로의 C# 전환을 보여줍니다." offSpacer="" %}}

```cs
// Scene의 객체에 PDF 로드 
var document = new Aspose.ThreeD.Scene("template.pdf");
// U3dSaveOptions의 인스턴스 생성 
var options = new Aspose.ThreeD.Formats.U3dSaveOptions();
// PDF을 U3D로 저장 
document.Save("output.u3d", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="PDF을(를) U3D(으)로 변환하는 무료 앱" sectionDescription="라이브 데모를 확인하십시오. [PDF에서 U3D로의 전환](https://products.aspose.app/3d/conversion/pdf-to-u3d) 다음과 같은 혜택이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 아무것도 다운로드하거나 설정할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" PDF 파일을 업로드하고 \"변환\" 버튼을 누르기만 하면 됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 결과 U3D 파일에 대한 다운로드 링크를 즉시 얻을 수 있습니다." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 모델링 및 렌더링 소프트웨어 없이 3D 파일을 조작하는 3D 파일 처리 라이브러리. 3D API는 Discreet3DS, WavefrontOBJ, FBX(ASCII, 바이너리), STL(ASCII, 바이너리), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco 파일 형식 등 개발자는 3D 문서 형식의 내용을 쉽게 생성, 읽기, 변환, 수정 및 제어할 수 있습니다.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
휴대용 문서 형식(PDF)은 1990년대에 Adobe에서 만든 문서 유형입니다. 이 파일 형식의 목적은 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제와 독립적인 형식으로 문서 및 기타 참조 자료를 표시하기 위한 표준을 도입하는 것입니다. PDF 파일은 확장 프로그램/플러그인을 통해 Chrome, Safari, Firefox와 같은 대부분의 최신 브라우저뿐만 아니라 Adobe Acrobat Reader/Writer에서도 열 수 있습니다. 상업적으로 사용 가능한 대부분의 소프트웨어 제품군은 추가 소프트웨어 구성 요소 없이도 문서를 PDF 파일 형식으로 변환할 수 있습니다. 따라서 PDF 파일 형식은 텍스트, 이미지, 하이퍼링크, 양식 필드, 리치 미디어, 디지털 서명, 첨부 파일, 메타데이터, 지리 공간 기능 및 소스의 일부가 될 수 있는 3D 개체와 같은 정보를 포함할 수 있는 완전한 기능을 가지고 있습니다. 문서.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="u3d" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}
U3D(Universal 3D)은 3D 컴퓨터 그래픽용 압축 파일 형식 및 데이터 구조입니다. 여기에는 삼각형 메쉬, 조명, 음영, 모션 데이터, 색상 및 구조가 있는 선 및 점과 같은 3D 모델 정보가 포함됩니다. 형식은 2005년 8월에 ECMA-363 표준으로 승인되었습니다. 3D PDF 문서는 U3D 개체 임베딩을 지원하며 Adobe Reader(버전 7 이상)에서 볼 수 있습니다. U3D 형식은 3차원 데이터 저장 및 교환에 대한 보편적인 표준을 수립하는 것을 목표로 개발되었습니다. 그러나 형식은 교환 형식으로 사용되지 않고 3D PDF에 대한 인코딩에서 주요 활용을 찾습니다. Acrobat 3D은 지원되는 3D 파일 유형을 PDF으로 변환할 때 U3D 또는 PRC로 변환합니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="PDF을(는) 아래 나열된 몇 가지를 포함하여 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-3ds/" name="PDF ~ 3DS" description="3D 스튜디오 DOS 메시" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-amf/" name="PDF ~ AMF" description="적층 제조 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-dae/" name="PDF ~ DAE" description="디지털 자산 교환" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-fbx/" name="PDF ~ FBX" description="3D 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-html/" name="PDF ~ HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-obj/" name="PDF ~ OBJ" description="3D 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-ply/" name="PDF ~ PLY" description="다각형 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-rvm/" name="PDF ~ RVM" description="AVEVA 플랜트 설계 모델" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-stl/" name="PDF ~ STL" description="교체 가능한 3D 표면 기하학" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-u3d/" name="PDF ~ U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}