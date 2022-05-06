﻿---
title: .NET के माध्यम से JT फ़ाइल स्वरूप देखें 
weight: 3090
url: /hi/net/viewer/jt/ 
description: .NET फ्रेमवर्क, .NET कोर, Mono पर JT दस्तावेज़ों को लोड करने, प्रस्तुत करने और प्रदर्शित करने के लिए C# स्रोत कोड।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="JT फ़ाइल व्यूअर for .NET" h2="बिना किसी 3D मॉडलिंग और रेंडरिंग सॉफ़्टवेयर के JT फ़ाइलें रेंडर करें." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JT" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="JT फ़ाइल का उपयोग करके C# कैसे देखें" %}}

 JT फ़ाइल देखने के लिए, हम उपयोग करेंगे
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API जो किसी भी व्यूअर के साथ उपयोग किए जाने वाले C# प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान API है। खुला हुआ
 [नुगेट](https://www.nuget.org/packages/aspose.3d) 
 पैकेज मैनेजर, खोजें
 ***** 
 और स्थापित करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="पैकेज मैनेजर कंसोल कमांड" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से JT देखने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D डेवलपर्स के लिए कोड की कुछ पंक्तियों के साथ JT फ़ाइल को देखना आसान बनाता है।

{{% /blocks/products/pf/agp/text %}}

1. सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें JT फ़ाइल1. Html5SaveOptions का एक उदाहरण बनाएं1. उन्नत स्वरूपण के लिए गुण सेट करें1. Html5SaveOptions के ऑब्जेक्ट के साथ Scene.Save विधि को कॉल करें1. परिणामी HTML फ़ाइल को डिफ़ॉल्ट ब्राउज़र में जांचें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Mono के साथ संगत OS- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल- Aspose.3D for .NET आपके प्रोजेक्ट में संदर्भित
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="देखने के लिए C# कोड JT" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// दृश्य के उदाहरण के माध्यम से JT दृश्य लोड करें
var scene = new ThreeD.Scene("template.jt");
// Html5SaveOptions का ऑब्जेक्ट बनाएं और फ़ॉर्मेटिंग के लिए गुण सेट करें
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // ग्रिड बंद करो
    ShowGrid = false,
    // यूजर इंटरफेस बंद करें
    ShowUI = false
};

// 3D दृश्य को HTML5 के रूप में सहेजें
scene.Save(output, options);
// परिणामी HTML को डिफ़ॉल्ट ब्राउज़र में लोड करें
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="लगभग Aspose.3D for .NET API" %}}

 Aspose.3D एक CAD और गेमवेयर API है जो 3D फाइलों को लोड, संशोधित और परिवर्तित करता है। API एक स्टैंडअलोन है और इसके लिए किसी भी 3D मॉडलिंग या रेंडरिंग सॉफ़्टवेयर की आवश्यकता नहीं है। Discreet3DS, WavefrontOBJ, STL (ASCII, बाइनरी), Universal3D, FBX (ASCII, बाइनरी), Collada, glTF, PLY, के लिए कोई आसानी से API का उपयोग कर सकता है। GLB, DirectX और अधिक प्रारूप। 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="देखने के लिए नि:शुल्क ऐप JT" sectionDescription="हमारे लाइव डेमो की जांच करें [देखें JT](https://products.aspose.app/3d/viewer/jt) निम्नलिखित लाभों के साथ।" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोड लिखने या संकलित करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस JT फ़ाइल अपलोड करें और \"देखें\" बटन दबाएं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" यदि आवश्यक हो, तो लिंक से JT फ़ाइल डाउनलोड करें" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JT" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}
JT (बृहस्पति टेसेलेशन) सीमेंस पीएलएम सॉफ्टवेयर द्वारा विकसित एक कुशल, उद्योग-केंद्रित और लचीला आईएसओ-मानकीकृत 3D डेटा प्रारूप है। एयरोस्पेस, ऑटोमोटिव उद्योग और भारी उपकरण के यांत्रिक CAD डोमेन अपने सबसे प्रमुख 3D विज़ुअलाइज़ेशन प्रारूप के रूप में JT का उपयोग करते हैं। JT प्रारूप एक दृश्य ग्राफ है जो विशिष्ट विशेषताओं और नोड्स का समर्थन करता है जो कि CAD विशिष्ट हैं। पहलू डेटा (त्रिकोण) को संग्रहीत करने के लिए परिष्कृत संपीड़न तकनीकों का उपयोग किया जाता है। यह प्रारूप दृश्य विशेषताओं, उत्पाद और निर्माण जानकारी (पीएमआई), और मेटाडेटा का समर्थन करने के लिए संरचित है। सामग्री की अतुल्यकालिक स्ट्रीमिंग के लिए एक अच्छा समर्थन है। भारी यांत्रिक उद्योग में, पेशेवर अपने CAD समाधान और उत्पाद जीवनचक्र प्रबंधन (पीएलएम) सॉफ़्टवेयर प्रोग्राम में JT फ़ाइल का उपयोग जटिल वस्तुओं की ज्यामिति की जांच करने के लिए करते हैं।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित दर्शक प्रारूप" subTitle="C# का उपयोग करके, कोई भी कई अन्य फ़ाइल स्वरूपों को भी देख सकता है, जिनमें शामिल हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D स्टूडियो डॉस मेश" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D निर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="योजक विनिर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="2डी एनिमेशन फाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="डिजिटल एसेट एक्सचेंज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="ड्राइंग इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D फ़ाइल बाइनरी प्रतिनिधित्व" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="जीएल ट्रांसमिशन प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="बहुभुज फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="अवेवा प्लांट डिजाइन मॉडल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="विनिमेय 3D भूतल ज्यामिति" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="आभासी वास्तविकता मॉडलिंग भाषा" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="एक्स" description="DirectX मॉडल छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP संग्रह प्रारूप" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}