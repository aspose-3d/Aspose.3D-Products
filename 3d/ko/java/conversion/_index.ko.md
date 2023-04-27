---
title: Java 3D 형식 변환
url: /ko/java/conversion/
description: Java 라이브러리를 통해 몇 줄의 Java 코드로 3D 형식 amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x를 변환합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D Java을 통한 형식 변환" h2="3D 모델링 및 렌더링 소프트웨어 설치 없이 3D 파일 형식을 변환하여 플랫폼 간 Java 애플리케이션을 빌드합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}
3차원 그래픽 애플리케이션을 생성, 편집, 조작 및 저장하기 위해 **Java 3D API**는 3D 모델링 및 렌더링 소프트웨어를 설치하지 않고도 이러한 기능을 수행할 수 있는 높은 수준의 방법을 제공합니다. 다양한 3차원 기하학적 모양의 메쉬를 만들고, 3D 장면 파일을 만들고, 큐브에 법선 또는 UV를 설정하고, 요소의 형식을 지정하고, 애니메이션 속성을 추가하는 등의 작업은 거의 없습니다. 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="3D 파일을 다른 형식으로 변환" %}}
변환 과정은 간단합니다. 다음을 사용하여 소스 3D 파일을 로드하기만 하면 됩니다. [장면 클래스](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene)장면은 노드, 지오메트리, 텍스처, 재질, 애니메이션, 포즈, 하위 장면 등이 있는 최상위 개체이므로 관련 생성 [저장 옵션](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) AmfSaveOptions, ColladaSaveOptions, Discreet3dsSaveOptions, DracoSaveOptions, FbxSaveOptions, GltfSaveOptions, RvmSaveOptions, StlSaveOptions, U3dSaveOptions 등을 선택하고 그에 따라 속성을 설정합니다. 마지막으로 출력 파일과 생성된 대상 형식 저장 옵션 개체로 save 메서드를 호출합니다. 또한 API 프로그래머를 사용하면 3D 장면을 HTML로 저장할 수도 있습니다.


{{% blocks/products/pf/feature-page-code h3="AMF에서 3DS로의 변환을 위한 Java 코드" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java를 통해 3D 장면을 HTML로 변환" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
