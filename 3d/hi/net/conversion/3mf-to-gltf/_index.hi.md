﻿---
title: C# के माध्यम से 3MF को GLTF में बदलें 
url: /hi/net/conversion/3mf-to-gltf/ 
description: 3MF से GLTF C# रूपांतरण के लिए नमूना कोड। बैच 3MF फ़ाइलों के लिए GLTF VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन में रूपांतरण के लिए API उदाहरण कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# के माध्यम से 3MF को GLTF में बदलें" h2="बिना किसी 3D मॉडलिंग और रेंडरिंग सॉफ़्टवेयर के 3MF को GLTF के रूप में प्रस्तुत करें।" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3MF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके 3MF को GLTF में कैसे बदलें" %}}

 3MF को GLTF में बदलने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से 3MF को GLTF में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 कोड की कुछ ही पंक्तियों में .NET प्रोग्रामर आसानी से 3MF फ़ाइलों को GLTF में लोड और परिवर्तित कर सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें 3MF फ़ाइल1. AmfSaveOptions का एक उदाहरण बनाएँ1. उन्नत रूपांतरण के लिए GLTF विशिष्ट गुण सेट करें1. दृश्य को कॉल करें। विधि सहेजें1. GLTF फ़ाइल एक्सटेंशन और GltfSaveOptions के ऑब्जेक्ट के साथ आउटपुट पथ पास करें1. परिणामी GLTF फ़ाइल को निर्दिष्ट पथ पर जांचें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 .NET रूपांतरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Mono के साथ संगत OS।- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास पर्यावरण।- Aspose.3D for .NET DLL आपके प्रोजेक्ट में संदर्भित है।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="यह नमूना कोड 3MF से GLTF C# रूपांतरण दिखाता है" offSpacer="" %}}

```cs
// सीन के ऑब्जेक्ट में 3MF लोड करें 
var document = new Aspose.ThreeD.Scene("template.3mf");
// GltfSaveOptions का एक उदाहरण बनाएं 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions();
// 3MF को GLTF के रूप में सहेजें 
document.Save("output.gltf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="3MF को GLTF में बदलने के लिए निःशुल्क ऐप" sectionDescription="इसके लिए हमारे लाइव डेमो देखें [3MF से GLTF रूपांतरण](https://products.aspose.app/3d/conversion/3mf-to-gltf) निम्नलिखित लाभों के साथ।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी 3MF फ़ाइल अपलोड करें और \"कन्वर्ट\" बटन दबाएं।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको परिणामी GLTF फ़ाइल के लिए तुरंत डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 बिना किसी मॉडलिंग और रेंडरिंग सॉफ्टवेयर के 3D फाइलों में हेरफेर करने के लिए एक 3D फाइल प्रोसेसिंग लाइब्रेरी। 3D API Discreet3DS, WavefrontOBJ, FBX (ASCII, बाइनरी), STL (ASCII, बाइनरी), Universal3D, Collada, glTF, GLB, का समर्थन करता है। PLY, DirectX, Google Draco फ़ाइल स्वरूप और बहुत कुछ। डेवलपर 3D दस्तावेज़ स्वरूपों के सार को आसानी से बना सकते हैं, पढ़ सकते हैं, रूपांतरित कर सकते हैं, संशोधित कर सकते हैं और नियंत्रित कर सकते हैं।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}
3MF, 3D निर्माण प्रारूप, अनुप्रयोगों द्वारा विभिन्न प्रकार के अन्य अनुप्रयोगों, प्लेटफार्मों, सेवाओं और प्रिंटरों को 3D ऑब्जेक्ट मॉडल प्रस्तुत करने के लिए उपयोग किया जाता है। इसे 3D प्रिंटर के नवीनतम संस्करणों के साथ काम करने के लिए STL जैसे अन्य 3D फ़ाइल स्वरूपों में सीमाओं और समस्याओं से बचने के लिए बनाया गया था। 3MF अपेक्षाकृत एक नया फ़ाइल स्वरूप है जिसे 3MF संघ द्वारा विकसित और प्रकाशित किया गया है। यह एक मॉडल का पूरी तरह से वर्णन करने के लिए पर्याप्त है, आंतरिक जानकारी, रंग और अन्य विशेषताओं को बनाए रखता है जो इसे 3D प्रिंटिंग में नए नवाचारों का समर्थन करने के लिए एक्स्टेंसिबल बनाता है। प्रारूप एक्स्टेंसिबल है, व्यापक रूप से अपनाया जा सकता है और अन्य व्यापक रूप से उपयोग किए जाने वाले फ़ाइल स्वरूपों के साथ समस्याओं से मुक्त है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="gltf" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (जीएल ट्रांसमिशन प्रारूप) एक 3D फ़ाइल स्वरूप है जो JSON प्रारूप में 3D मॉडल जानकारी संग्रहीत करता है। JSON का उपयोग 3D संपत्तियों के आकार और उन संपत्तियों को अनपैक करने और उपयोग करने के लिए आवश्यक रनटाइम प्रोसेसिंग दोनों को कम करता है। इसे अनुप्रयोगों द्वारा 3D दृश्यों और मॉडलों के कुशल संचरण और लोडिंग के लिए अपनाया गया था। glTF को ख्रोनोस ग्रुप 3D फॉर्मेट वर्किंग ग्रुप द्वारा विकसित किया गया था और इसके रचनाकारों द्वारा इसे 3D के जेपीईजी के रूप में भी वर्णित किया गया है। यह प्रारूप 3D सामग्री टूल और सेवाओं के लिए एक एक्स्टेंसिबल, सामान्य प्रकाशन प्रारूप को परिभाषित करता है जो ऑथरिंग वर्कफ़्लो को सुव्यवस्थित करता है और पूरे उद्योग में सामग्री के इंटरऑपरेबल उपयोग को सक्षम बनाता है। glTF फ़ाइल स्वरूप के निर्माण के पीछे उद्देश्य 3D सामग्री टूल और सेवाओं के लिए एक एक्स्टेंसिबल, सामान्य प्रकाशन प्रारूप को परिभाषित करना था जो ऑथरिंग वर्कफ़्लोज़ को सुव्यवस्थित करना चाहिए और पूरे उद्योग में सामग्री के इंटरऑपरेबल उपयोग को सक्षम करना चाहिए। यह वेबजीएल और अन्य एपीआई का उपयोग करके अनुप्रयोगों द्वारा रनटाइम प्रोसेसिंग को कम करता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप 3MF को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-3ds/" name="3MF से 3DS" description="3D स्टूडियो डॉस मेश" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-amf/" name="3MF से AMF" description="योजक विनिर्माण प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-dae/" name="3MF से DAE" description="डिजिटल एसेट एक्सचेंज" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-fbx/" name="3MF से FBX" description="3D प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-html/" name="3MF से HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-obj/" name="3MF से OBJ" description="3D फ़ाइल स्वरूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-pdf/" name="3MF से PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-ply/" name="3MF से PLY" description="बहुभुज फ़ाइल स्वरूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-rvm/" name="3MF से RVM" description="अवेवा प्लांट डिजाइन मॉडल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-stl/" name="3MF से STL" description="विनिमेय 3D भूतल ज्यामिति" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-u3d/" name="3MF से U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}