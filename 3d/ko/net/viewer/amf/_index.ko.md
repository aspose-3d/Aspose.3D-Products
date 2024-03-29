﻿---
title: .NET을(를) 통해 AMF 파일 형식 보기 
weight: 1900
url: /ko/net/viewer/amf/ 
description: C# 소스 코드는 .NET Framework, .NET Core, Mono에서 AMF 문서를 로드, 렌더링 및 표시합니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="AMF 파일 뷰어 for .NET" h2="3D 모델링 및 렌더링 소프트웨어 없이 AMF 파일을 렌더링합니다." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="AMF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="AMF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="C#을 사용하여 AMF 파일을 보는 방법" %}}

 AMF 파일을 보기 위해 다음을 사용합니다.
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API은(는) 모든 뷰어와 함께 사용할 수 있는 C# 플랫폼을 위한 풍부하고 강력하며 사용하기 쉬운 API입니다. 열려있는
 [누겟](https://www.nuget.org/packages/aspose.3d) 
 패키지 관리자, 검색
 **Aspose.3D** 
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="패키지 관리자 콘솔 명령" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#을(를) 통해 AMF을(를) 보는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D을 사용하면 개발자가 몇 줄의 코드로 AMF 파일을 쉽게 볼 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Scene 클래스의 생성자를 통해 AMF 파일 로드1. Html5SaveOptions의 인스턴스 만들기1. 고급 서식 속성 설정1. Html5SaveOptions 개체로 Scene.Save 메서드를 호출합니다.1. 기본 브라우저에서 결과 HTML 파일 확인
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET은(는) 모든 주요 운영 체제에서 지원됩니다. 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Mono 호환 OS- Microsoft Visual Studio와 같은 개발 환경- 프로젝트에서 참조된 Aspose.3D for .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="AMF을(를) 볼 C# 코드" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// Scene 인스턴스를 통해 AMF 장면 로드
var scene = new ThreeD.Scene("template.amf");
// Html5SaveOptions의 개체를 만들고 서식 속성을 설정합니다.
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // 그리드를 끄다
    ShowGrid = false,
    // 사용자 인터페이스 끄기
    ShowUI = false
};

// 3D 장면을 HTML5로 저장
scene.Save(output, options);
// 기본 브라우저에서 결과 HTML 로드
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.3D for .NET API 정보" %}}

 Aspose.3D은(는) 3D 파일을 로드, 수정 및 변환하는 CAD 및 Gameware API입니다. API는 독립 실행형이며 3D 모델링 또는 렌더링 소프트웨어가 필요하지 않습니다. Discreet3DS, WavefrontOBJ, STL(ASCII, 바이너리), Universal3D, FBX(ASCII, 바이너리), Collada, glTF, PLY, GLB, DirectX 및 기타 형식. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="볼 수 있는 무료 앱 AMF" sectionDescription="라이브 데모를 확인하려면 [보기 AMF](https://products.aspose.app/3d/viewer/amf) 다음과 같은 혜택이 있습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 아무것도 다운로드하거나 설정할 필요가 없습니다" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성하거나 컴파일할 필요가 없습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" AMF 파일을 업로드하고 \"보기\" 버튼을 누르십시오." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" 필요한 경우 링크에서 AMF 파일 다운로드" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="AMF" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}
적층 제조 파일 형식(AMF)은 3D 인쇄와 같은 적층 제조 프로세스에서 활용하기 위해 개체 설명에 대한 공개 표준을 정의합니다. CAD 프로그램은 개체의 기하학, 색상 및 재질과 같은 정보를 사용하여 AMF 파일 형식을 사용합니다. AMF는 측면이 색상, 재료, 격자 및 성좌를 지원하지 않기 때문에 STL 형식과 다릅니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 뷰어 형식" subTitle="C#을(를) 사용하면 다음을 비롯한 많은 다른 파일 형식도 볼 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D 스튜디오 DOS 메시" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D 제조 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="2D 애니메이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="디지털 자산 교환" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="도면 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D 파일 이진 표현" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="GL 전송 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="목성 테셀레이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="다각형 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="AVEVA 플랜트 설계 모델" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="교체 가능한 3D 표면 기하학" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="가상 현실 모델링 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="엑스" description="DirectX 모델 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP 보관 형식" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}