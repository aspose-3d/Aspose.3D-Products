﻿---
title: C#를 통해 GLTF을 USDZ로 변환 
url: /ko/net/conversion/gltf-to-usdz 
description: GLTF에서 USDZ로의 C# 변환을 위한 샘플 코드. VB.NET, Asp.NET 또는 모든 .NET 기반 애플리케이션 내에서 배치 GLTF 파일을 USDZ로 변환하는 API 예제 코드를 사용합니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#를 통해 GLTF을 USDZ로 변환" h2="3D 모델링 및 렌더링 소프트웨어 없이 GLTF을 USDZ로 렌더링합니다." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="USDZ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="C#를 사용하여 GLTF을 USDZ로 변환하는 방법" %}}

 GLTF을(를) USDZ(으)로 변환하기 위해 다음을 사용합니다.
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

{{% blocks/products/pf/agp/feature-section-col title="C#를 통해 GLTF을 USDZ로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 프로그래머는 몇 줄의 코드로 GLTF 파일을 쉽게 로드하고 USDZ로 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Scene 클래스의 생성자를 통해 GLTF 파일 로드1. AmfSaveOptions의 인스턴스 생성1. 고급 변환을 위한 USDZ 특정 속성 설정1. Scene.Save 메서드 호출1. U3dSaveOptions의 파일 확장자와 개체가 USDZ인 출력 경로를 전달합니다.1. 지정된 경로에서 결과 USDZ 파일 확인
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 변환 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Mono 호환 OS.- Microsoft Visual Studio와 같은 개발 환경.- Aspose.3D for .NET 프로젝트에서 참조되는 DLL입니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="이 샘플 코드는 GLTF에서 USDZ로의 C# 전환을 보여줍니다." offSpacer="" %}}

```cs
// Scene의 객체에 GLTF 로드 
var document = new Aspose.ThreeD.Scene("template.gltf");
// GLTF을 USDZ로 저장 
document.Save("output.usdz", Aspose.ThreeD.FileFormat.USDZ); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="GLTF을(를) USDZ(으)로 변환하는 무료 앱" sectionDescription="라이브 데모를 확인하십시오. [GLTF에서 USDZ로의 전환](https://products.aspose.app/3d/conversion/gltf-to-usdz) 다음과 같은 혜택이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 아무것도 다운로드하거나 설정할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" GLTF 파일을 업로드하고 \"변환\" 버튼을 누르기만 하면 됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 결과 USDZ 파일에 대한 다운로드 링크를 즉시 얻을 수 있습니다." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 모델링 및 렌더링 소프트웨어 없이 3D 파일을 조작하는 3D 파일 처리 라이브러리. 3D API는 Discreet3DS, WavefrontOBJ, FBX(ASCII, 바이너리), STL(ASCII, 바이너리), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco 파일 형식 등 개발자는 3D 문서 형식의 내용을 쉽게 생성, 읽기, 변환, 수정 및 제어할 수 있습니다.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF(GL 전송 형식)은 3D 모델 정보를 JSON 형식으로 저장하는 3D 파일 형식입니다. JSON을 사용하면 3D 자산의 크기와 이러한 자산의 압축을 풀고 사용하는 데 필요한 런타임 처리가 최소화됩니다. 애플리케이션별 3D 장면 및 모델의 효율적인 전송 및 로드를 위해 채택되었습니다. glTF는 Khronos Group 3D Formats Working Group에서 개발했으며 제작자는 3D의 JPEG로도 설명합니다. 이 형식은 제작 워크플로를 간소화하고 업계 전반에 걸쳐 콘텐츠를 상호 운용할 수 있도록 하는 3D 콘텐츠 도구 및 서비스에 대한 확장 가능한 공통 게시 형식을 정의합니다. glTF 파일 형식을 만든 목적은 제작 워크플로를 간소화하고 업계 전반에 걸쳐 콘텐츠를 상호 운용할 수 있도록 하는 3D 콘텐츠 도구 및 서비스에 대해 확장 가능하고 공통된 게시 형식을 정의하는 것이었습니다. WebGL 및 기타 API를 사용하는 애플리케이션의 런타임 처리를 최소화합니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="USDZ" readMoreLink="https://docs.fileformat.com/3d/usdz/" >}}
.usdz가 있는 파일은 압축되지 않고 암호화되지 않은 USD(Universal Scene Description) 파일 형식에 대한 아카이브이며 아카이브 내에 포함되어 실행되는 다른 형식(텍스처 및 애니메이션 등)의 파일을 포함하고 이를 대리합니다. 압축을 풀 필요 없이 USD 런타임으로 직접. USDZ 파일은 디자인이 패키지의 새로운 Ar 수준 추상화를 기반으로 하는 패키지입니다. Usdz는 IANA에 등록되었으며 모델의 미디어 유형 이름과 vnd.usd+zip의 하위 유형 이름을 가지며 자세한 내용은 IANA 등록 페이지에서 확인할 수 있습니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
