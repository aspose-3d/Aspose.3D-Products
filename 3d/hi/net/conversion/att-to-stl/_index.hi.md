﻿---
title: C# के माध्यम से ATT को STL में बदलें 
url: /hi/net/conversion/att-to-stl/ 
description: ATT से STL C# रूपांतरण के लिए नमूना कोड। बैच ATT फ़ाइलों के लिए STL VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन में रूपांतरण के लिए API उदाहरण कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# के माध्यम से ATT को STL में बदलें" h2="बिना किसी 3D मॉडलिंग और रेंडरिंग सॉफ़्टवेयर के ATT को STL के रूप में प्रस्तुत करें।" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ATT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके ATT को STL में कैसे बदलें" %}}

 ATT को STL में बदलने के लिए, हम उपयोग करेंगे
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API जो C# प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ हेरफेर और रूपांतरण API है। खुला हुआ
 [नुगेट](https://www.nuget.org/packages/aspose.3d) 
 पैकेज मैनेजर, खोजें
 Aspose.3D 
 और स्थापित करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="पैकेज मैनेजर कंसोल कमांड" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से ATT को STL में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 कोड की कुछ ही पंक्तियों में .NET प्रोग्रामर आसानी से ATT फ़ाइलों को STL में लोड और परिवर्तित कर सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें ATT फ़ाइल1. AmfSaveOptions का एक उदाहरण बनाएँ1. उन्नत रूपांतरण के लिए STL विशिष्ट गुण सेट करें1. दृश्य को कॉल करें। विधि सहेजें1. STL फ़ाइल एक्सटेंशन और StlSaveOptions के ऑब्जेक्ट के साथ आउटपुट पथ पास करें1. परिणामी STL फ़ाइल को निर्दिष्ट पथ पर जांचें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 .NET रूपांतरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Mono के साथ संगत OS।- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास पर्यावरण।- Aspose.3D for .NET DLL आपके प्रोजेक्ट में संदर्भित है।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="यह नमूना कोड ATT से STL C# रूपांतरण दिखाता है" offSpacer="" %}}

```cs
// सीन के ऑब्जेक्ट में ATT लोड करें 
var document = new Aspose.ThreeD.Scene("template.att");
// StlSaveOptions का एक उदाहरण बनाएं 
var options = new Aspose.ThreeD.Formats.StlSaveOptions();
// ATT को STL के रूप में सहेजें 
document.Save("output.stl", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="ATT को STL में बदलने के लिए निःशुल्क ऐप" sectionDescription="इसके लिए हमारे लाइव डेमो देखें [ATT से STL रूपांतरण](https://products.aspose.app/3d/conversion/att-to-stl) निम्नलिखित लाभों के साथ।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी ATT फ़ाइल अपलोड करें और \"कन्वर्ट\" बटन दबाएं।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको परिणामी STL फ़ाइल के लिए तुरंत डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 बिना किसी मॉडलिंग और रेंडरिंग सॉफ्टवेयर के 3D फाइलों में हेरफेर करने के लिए एक 3D फाइल प्रोसेसिंग लाइब्रेरी। 3D API Discreet3DS, WavefrontOBJ, FBX (ASCII, बाइनरी), STL (ASCII, बाइनरी), Universal3D, Collada, glTF, GLB, का समर्थन करता है। PLY, DirectX, Google Draco फ़ाइल स्वरूप और बहुत कुछ। डेवलपर 3D दस्तावेज़ स्वरूपों के सार को आसानी से बना सकते हैं, पढ़ सकते हैं, रूपांतरित कर सकते हैं, संशोधित कर सकते हैं और नियंत्रित कर सकते हैं।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ATT" readMoreLink="/{{att_url}}" >}}
{{att}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="stl" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, स्टीरियोलिथोग्राफी के लिए संक्षिप्त नाम, एक विनिमेय फ़ाइल स्वरूप है जो 3-आयामी सतह ज्यामिति का प्रतिनिधित्व करता है। फ़ाइल प्रारूप कई क्षेत्रों में इसका उपयोग पाता है जैसे कि रैपिड प्रोटोटाइप, 3D प्रिंटिंग और कंप्यूटर-एडेड मैन्युफैक्चरिंग। यह एक सतह को छोटे त्रिभुजों की एक श्रृंखला के रूप में दर्शाता है, जिसे पहलू के रूप में जाना जाता है, जहां प्रत्येक पहलू को लंबवत दिशा और त्रिभुज के शिखर का प्रतिनिधित्व करने वाले तीन बिंदुओं द्वारा वर्णित किया जाता है। परिणामी डेटा का उपयोग अनुप्रयोगों द्वारा फैबर द्वारा बनाए जाने वाले 3D आकार के क्रॉस सेक्शन को निर्धारित करने के लिए किया जाता है। रंग, बनावट या अन्य सामान्य CAD मॉडल विशेषताओं के प्रतिनिधित्व के लिए STL फ़ाइल स्वरूप में कोई जानकारी उपलब्ध नहीं है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}