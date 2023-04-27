---
title: Java 3D Преобразование форматов
url: /ru/java/conversion/
description: Преобразование форматов 3D amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x с помощью нескольких строк кода Java с помощью библиотеки Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D Преобразование форматов через Java" h2="Преобразование форматов файлов 3D без установки программного обеспечения 3D для моделирования и рендеринга для создания кроссплатформенных Java приложений." >}}

{{% blocks/products/pf/feature-page-summary %}}
Для создания, редактирования, управления и сохранения приложений с трехмерной графикой **Java 3D API** предоставляет методы высокого уровня для выполнения таких функций без установки какого-либо 3D программного обеспечения для моделирования и рендеринга. Немногие из них создают сетку из различных трехмерных геометрических фигур, создают файл сцены 3D, настраивают нормали или UV на кубе, форматируют элементы, добавляют свойство анимации и многое другое. 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Преобразование файла 3D в другие форматы" %}}
Процесс преобразования прост. Просто загрузите исходный файл 3D, используя [Класс сцены](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene)Поскольку сцена — это объект верхнего уровня, имеющий узлы, геометрию, текстуры, материалы, анимацию, позы, подсцены и т. д. Создайте соответствующие [Сохранить параметры](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) такие как AmfSaveOptions, ColladaSaveOptions, Discreet3dsSaveOptions, DracoSaveOptions, FbxSaveOptions, GltfSaveOptions, RvmSaveOptions, StlSaveOptions, U3dSaveOptions и т. д., и установите соответствующие свойства. Наконец, вызовите метод сохранения с выходным файлом и создайте объект параметров сохранения целевого формата. Кроме того, с помощью API программисты могут даже сохранить сцену 3D как HTML.


{{% blocks/products/pf/feature-page-code h3="Код Java для преобразования AMF в 3DS" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Преобразование сцены 3D в HTML через Java" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
