﻿---
title: تحويل VRML إلى U3D عبر Java 
weight: 2880
url: /ar/java/conversion/vrml-to-u3d/ 
description: نموذج Java شفرة تحويل من تنسيق VRML إلى ملف U3D. استخدم رمز المثال هذا لتحويل VRML إلى U3D داخل أي تطبيق يستند إلى الويب أو سطح المكتب Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل VRML إلى U3D عبر Java" h2="VRML إلى U3D التحويل باستخدام مكتبة Java بدون أي 3D برامج تصميم." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="VRML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل VRML إلى U3D باستخدام Java" %}}

 من أجل تقديم VRML إلى U3D ، سنستخدم
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API نظام أساسي للتحويل غني بالميزات وقوي وسهل الاستخدام API for Java. يمكنك تنزيل أحدث إصدار مباشرة من
 [مخضرم](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 وقم بتثبيته في مشروعك المستند إلى Maven عن طريق إضافة التكوينات التالية إلى ملف pom.xml.

{{% blocks/products/pf/agp/code-block title="مخزن" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="الاعتماد" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="خطوات التحويل من VRML إلى U3D عبر Java" %}}

{{% blocks/products/pf/agp/text %}}

 يمكن للمبرمجين Java بسهولة تحويل VRML ملف إلى U3D في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1. تحميل ملف VRML عبر منشئ فئة المشهد1. قم بإنشاء مثيل U3dSaveOptions1. قم بتعيين U3D من الخصائص المحددة للتحويل المتقدم1. استدعاء طريقة Scene.save1. قم بتمرير مسار الإخراج مع U3D امتداد الملف وكائن U3dSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 قبل تشغيل شفرة التحويل Java ، تأكد من توفر المتطلبات الأساسية التالية لديك.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.- احصل على أحدث إصدار من Aspose.3D for Java مباشرة من Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="VRML إلى U3D Java شفرة مصدر التحويل" offSpacer="" %}}

```cs
// تحميل VRML في كائن من المشهد 
Scene document = new Scene("template.vrml");
// إنشاء مثيل U3dSaveOptions 
U3dSaveOptions options = new U3dSaveOptions();
// حفظ VRML باسم U3D 
document.save("output.u3d", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="VRML إلى U3D عروض توضيحية مباشرة للتحويلات" sectionDescription="[تحويل VRML إلى U3D](https://products.aspose.app/3d/conversion/vrml-to-u3d) الآن من خلال زيارة موقع Live Demos الخاص بنا ، حيث يتمتع العرض التوضيحي المباشر بالمزايا التالية" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي كود." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف VRML الخاص بك ، وسيتم تحويله على الفور إلى U3D." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" سوف تحصل على رابط التحميل." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D مكتبة معالجة المشهد" %}}

 Aspose.3D هو برنامج ألعاب CAD وألعاب API لتحميل وتعديل وتحويل ملفات 3D. API هو برنامج قائم بذاته ولا يتطلب أي 3D برامج عرض أو نماذج. يمكن للمرء بسهولة استخدام API لـ Discreet3DS ، WavefrontOBJ ، STL (ASCII ، ثنائي) ، Universal3D ، FBX (ASCII ، ثنائي) ، Collada ، glTF ، PLY ، GLB و DirectX والمزيد من التنسيقات. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="VRML" readMoreLink="https://docs.fileformat.com/3d/vrml/" >}}

لغة نمذجة الواقع الافتراضي (VRML) هي تنسيق ملف لتمثيل كائنات العالم التفاعلية 3D عبر شبكة الويب العالمية (www). يجد استخدامه في إنشاء تمثيلات ثلاثية الأبعاد للمشاهد المعقدة مثل الرسوم التوضيحية والتعريف وعروض الواقع الافتراضي. تم استبدال التنسيق بـ X3D. يمكن للعديد من تطبيقات 3D النمذجة حفظ الكائنات والمشاهد بتنسيق VRML.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}

U3D (Universal 3D) هو تنسيق ملف مضغوط وبنية بيانات لرسومات الكمبيوتر 3D. يحتوي على معلومات نموذجية 3D مثل شبكات المثلث والإضاءة والتظليل وبيانات الحركة والخطوط والنقاط ذات اللون والبنية. تم قبول التنسيق كمعيار ECMA-363 في أغسطس 2005. 3D PDF تدعم المستندات U3D تضمين الكائنات ويمكن عرضها في Adobe Reader (الإصدار 7 وما بعده). تم تطوير تنسيق U3D مع مراعاة الهدف المتمثل في وضع معيار عالمي لتخزين البيانات ثلاثية الأبعاد وتبادلها. ومع ذلك ، يجد التنسيق استخدامه الأساسي في تشفير 3D PDF بدلاً من استخدامه كتنسيق تبادل. يحول Acrobat 3D نوع ملف 3D مدعوم إما إلى U3D أو PRC عند التحويل إلى PDF.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل VRML إلى العديد من تنسيقات الملفات الأخرى بما في ذلك بعض التنسيقات المدرجة أدناه." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-3ds/" name="VRML إلى 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-amf/" name="VRML إلى AMF" description="تنسيق التصنيع الإضافي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-ase/" name="VRML إلى ASE" description="ملف الرسوم المتحركة ثنائي الأبعاد" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-dae/" name="VRML إلى DAE" description="تبادل الأصول الرقمية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-fbx/" name="VRML إلى FBX" description="3D تنسيق" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-gltf/" name="VRML إلى GLTF" description="تنسيق نقل GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-html/" name="VRML إلى HTML" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-obj/" name="VRML إلى OBJ" description="3D تنسيق الملف" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-ply/" name="VRML إلى PLY" description="تنسيق ملف مضلع" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-rvm/" name="VRML إلى RVM" description="نموذج تصميم مصنع AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/vrml-to-stl/" name="VRML إلى STL" description="قابلة للتبديل 3D هندسة السطح" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}