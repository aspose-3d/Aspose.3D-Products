﻿---
title: تحويل DRC إلى OBJ عبر C# 
url: /ar/net/conversion/drc-to-obj/ 
description: نموذج رمز للتحويل من DRC إلى OBJ C#. استخدم API رمز المثال لملفات الدُفعات DRC OBJ للتحويل داخل VB .NET أو Asp .NET أو أي تطبيق قائم على .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل DRC إلى OBJ عبر C#" h2="تجسيد DRC كـ OBJ بدون أي 3D برامج تصميم وعرض." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل DRC إلى OBJ باستخدام C#" %}}

 لتحويل DRC إلى OBJ ، سنستخدم
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API وهو نظام غني بالميزات وقوي وسهل الاستخدام لمعالجة المستندات وتحويلها API لـ C# النظام الأساسي. افتح
 [نوجيت](https://www.nuget.org/packages/aspose.3d) 
 مدير الحزم ، ابحث عن
 Aspose.3D 
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم مدير الحزم" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات التحويل من DRC إلى OBJ عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

 يمكن للمبرمجين .NET تحميل وتحويل ملفات DRC بسهولة إلى OBJ في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1. تحميل ملف DRC عبر منشئ فئة المشهد1. قم بإنشاء مثيل AmfSaveOptions1. قم بتعيين OBJ من الخصائص المحددة للتحويل المتقدم1. استدعاء طريقة Scene.Save1. قم بتمرير مسار الإخراج مع OBJ امتداد الملف وكائن ObjSaveOptions1. تحقق من الملف الناتج OBJ في المسار المحدد
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 قبل تشغيل شفرة التحويل .NET ، تأكد من توفر المتطلبات الأساسية التالية لديك.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework ، .NET Core ، Mono.- بيئة التطوير مثل Microsoft Visual Studio.- Aspose.3D for .NET DLL المشار إليه في مشروعك.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="يوضح نموذج الشفرة هذا التحويل من DRC إلى OBJ C#" offSpacer="" %}}

```cs
// تحميل DRC في كائن من المشهد 
var document = new Aspose.ThreeD.Scene("template.drc");
// إنشاء مثيل ObjSaveOptions 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// حفظ DRC باسم OBJ 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="تطبيق مجاني للتحويل من DRC إلى OBJ" sectionDescription="تحقق من العروض الحية لدينا ل [DRC إلى OBJ التحويل](https://products.aspose.app/3d/conversion/drc-to-obj) مع الفوائد التالية." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل أو إعداد أي شيء." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي كود." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف DRC واضغط على الزر \"تحويل\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ستحصل فورًا على رابط التنزيل للملف الناتج OBJ." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 مكتبة 3D معالجة الملفات لمعالجة 3D الملفات بدون أي برامج نمذجة وعرض. 3D API يدعم Discreet3DS ، WavefrontOBJ ، FBX (ASCII ، ثنائي) ، STL (ASCII ، ثنائي) ، Universal3D ، Collada ، glTF ، GLB ، PLY و DirectX و Google Draco تنسيقات الملفات والمزيد. يمكن للمطورين إنشاء محتوى تنسيقات المستندات وقراءتها وتحويلها وتعديلها والتحكم فيها بسهولة.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
الملف بامتداد .drc هو تنسيق ملف مضغوط 3D تم إنشاؤه باستخدام مكتبة Google Draco. Google تقدم Draco كمكتبة مفتوحة المصدر لضغط وفك ضغط 3D الشبكات الهندسية وسحب النقاط ، وتحسين تخزين ونقل 3D الرسومات. يقوم بترميز بيانات الإدخال وحفظها كملف .drc. في الطرف المستلم ، يقرأ API ملفات .drc ويمكنه إخراجها كملفات PLY أو OBJ. يتيح ملف الإخراج المضغوط للمستخدمين تنزيل التطبيقات بشكل أسرع وتوفير تحميل سريع للرسومات 3D في المتصفحات.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
يتم استخدام ملفات OBJ بواسطة تطبيق Visualizer المتقدم لـ Wavefront لتعريف الكائنات الهندسية وتخزينها. أصبح النقل الخلفي والأمامي للبيانات الهندسية ممكنًا من خلال ملفات OBJ. يتم دعم كل من الهندسة متعددة الأضلاع مثل النقاط والخطوط ورؤوس النسيج والوجوه والشكل الهندسي الحر (المنحنيات والأسطح) بواسطة تنسيق OBJ. لا يدعم هذا التنسيق الرسوم المتحركة أو المعلومات المتعلقة بالضوء وموضع المشاهد. عادةً ما يكون ملف OBJ منتجًا نهائيًا لعملية النمذجة 3D التي تم إنشاؤها بواسطة CAD (التصميم بمساعدة الكمبيوتر). الترتيب الافتراضي لتخزين القمم هو عكس اتجاه عقارب الساعة لتجنب الإعلان الصريح لقواعد الوجه. على الرغم من أن ملفات OBJ تعلن عن معلومات المقياس في سطر تعليق إلا أنه لم يتم الإعلان عن أي وحدات لإحداثيات OBJ.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}