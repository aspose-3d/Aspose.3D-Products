﻿---
title: C# के माध्यम से GLTF को RVM में बदलें 
url: /hi/net/conversion/gltf-to-rvm/ 
description: GLTF से RVM C# रूपांतरण के लिए नमूना कोड। बैच GLTF फ़ाइलों के लिए RVM VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन में रूपांतरण के लिए API उदाहरण कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# के माध्यम से GLTF को RVM में बदलें" h2="बिना किसी 3D मॉडलिंग और रेंडरिंग सॉफ़्टवेयर के GLTF को RVM के रूप में प्रस्तुत करें।" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="RVM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके GLTF को RVM में कैसे बदलें" %}}

 GLTF को RVM में बदलने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से GLTF को RVM में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 कोड की कुछ ही पंक्तियों में .NET प्रोग्रामर आसानी से GLTF फ़ाइलों को RVM में लोड और परिवर्तित कर सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें GLTF फ़ाइल1. AmfSaveOptions का एक उदाहरण बनाएँ1. उन्नत रूपांतरण के लिए RVM विशिष्ट गुण सेट करें1. दृश्य को कॉल करें। विधि सहेजें1. RVM फ़ाइल एक्सटेंशन और RvmSaveOptions के ऑब्जेक्ट के साथ आउटपुट पथ पास करें1. परिणामी RVM फ़ाइल को निर्दिष्ट पथ पर जांचें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 .NET रूपांतरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Mono के साथ संगत OS।- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास पर्यावरण।- Aspose.3D for .NET DLL आपके प्रोजेक्ट में संदर्भित है।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="यह नमूना कोड GLTF से RVM C# रूपांतरण दिखाता है" offSpacer="" %}}

```cs
// सीन के ऑब्जेक्ट में GLTF लोड करें 
var document = new Aspose.ThreeD.Scene("template.gltf");
// RvmSaveOptions का एक उदाहरण बनाएँ 
var options = new Aspose.ThreeD.Formats.RvmSaveOptions();
// GLTF को RVM के रूप में सहेजें 
document.Save("output.rvm", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="GLTF को RVM में बदलने के लिए निःशुल्क ऐप" sectionDescription="इसके लिए हमारे लाइव डेमो देखें [GLTF से RVM रूपांतरण](https://products.aspose.app/3d/conversion/gltf-to-rvm) निम्नलिखित लाभों के साथ।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी GLTF फ़ाइल अपलोड करें और \"कन्वर्ट\" बटन दबाएं।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको परिणामी RVM फ़ाइल के लिए तुरंत डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 बिना किसी मॉडलिंग और रेंडरिंग सॉफ्टवेयर के 3D फाइलों में हेरफेर करने के लिए एक 3D फाइल प्रोसेसिंग लाइब्रेरी। 3D API Discreet3DS, WavefrontOBJ, FBX (ASCII, बाइनरी), STL (ASCII, बाइनरी), Universal3D, Collada, glTF, GLB, का समर्थन करता है। PLY, DirectX, Google Draco फ़ाइल स्वरूप और बहुत कुछ। डेवलपर 3D दस्तावेज़ स्वरूपों के सार को आसानी से बना सकते हैं, पढ़ सकते हैं, रूपांतरित कर सकते हैं, संशोधित कर सकते हैं और नियंत्रित कर सकते हैं।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (जीएल ट्रांसमिशन प्रारूप) एक 3D फ़ाइल स्वरूप है जो JSON प्रारूप में 3D मॉडल जानकारी संग्रहीत करता है। JSON का उपयोग 3D संपत्तियों के आकार और उन संपत्तियों को अनपैक करने और उपयोग करने के लिए आवश्यक रनटाइम प्रोसेसिंग दोनों को कम करता है। इसे अनुप्रयोगों द्वारा 3D दृश्यों और मॉडलों के कुशल संचरण और लोडिंग के लिए अपनाया गया था। glTF को ख्रोनोस ग्रुप 3D फॉर्मेट वर्किंग ग्रुप द्वारा विकसित किया गया था और इसके रचनाकारों द्वारा इसे 3D के जेपीईजी के रूप में भी वर्णित किया गया है। यह प्रारूप 3D सामग्री टूल और सेवाओं के लिए एक एक्स्टेंसिबल, सामान्य प्रकाशन प्रारूप को परिभाषित करता है जो ऑथरिंग वर्कफ़्लो को सुव्यवस्थित करता है और पूरे उद्योग में सामग्री के इंटरऑपरेबल उपयोग को सक्षम बनाता है। glTF फ़ाइल स्वरूप के निर्माण के पीछे उद्देश्य 3D सामग्री टूल और सेवाओं के लिए एक एक्स्टेंसिबल, सामान्य प्रकाशन प्रारूप को परिभाषित करना था जो ऑथरिंग वर्कफ़्लोज़ को सुव्यवस्थित करना चाहिए और पूरे उद्योग में सामग्री के इंटरऑपरेबल उपयोग को सक्षम करना चाहिए। यह वेबजीएल और अन्य एपीआई का उपयोग करके अनुप्रयोगों द्वारा रनटाइम प्रोसेसिंग को कम करता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="rvm" readMoreLink="https://docs.fileformat.com/3d/rvm/" >}}
RVM डेटा फ़ाइलें AVEVA PDMS से संबंधित हैं। RVM फ़ाइल AVEVA प्लांट डिज़ाइन मैनेजमेंट सिस्टम मॉडल है। AVEVA की प्लांट डिज़ाइन मैनेजमेंट सिस्टम (PDMS) परियोजनाओं के प्रबंधन के लिए डेटा-केंद्रित तकनीक का उपयोग करते हुए सबसे लोकप्रिय 3D डिज़ाइन सिस्टम है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}