﻿---
title: C# के माध्यम से U3D को OBJ में बदलें 
weight: 1820
url: /hi/net/conversion/u3d-to-obj/ 
description: U3D से OBJ C# रूपांतरण के लिए नमूना कोड। बैच U3D फ़ाइलों के लिए OBJ VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन में रूपांतरण के लिए API उदाहरण कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# के माध्यम से U3D को OBJ में बदलें" h2="बिना किसी 3D मॉडलिंग और रेंडरिंग सॉफ़्टवेयर के U3D को OBJ के रूप में प्रस्तुत करें।" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="U3D" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके U3D को OBJ में कैसे बदलें" %}}

 U3D को OBJ में बदलने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से U3D को OBJ में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 कोड की कुछ ही पंक्तियों में .NET प्रोग्रामर आसानी से U3D फ़ाइलों को OBJ में लोड और परिवर्तित कर सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें U3D फ़ाइल1. ObjSaveOptions का एक उदाहरण बनाएँ1. उन्नत रूपांतरण के लिए OBJ विशिष्ट गुण सेट करें1. दृश्य को कॉल करें। विधि सहेजें1. आउटपुट पथ को OBJ फ़ाइल एक्सटेंशन और ObjSaveOptions के ऑब्जेक्ट के साथ पास करें1. परिणामी OBJ फ़ाइल को निर्दिष्ट पथ पर जांचें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 .NET रूपांतरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Mono के साथ संगत OS।- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास पर्यावरण।- Aspose.3D for .NET DLL आपके प्रोजेक्ट में संदर्भित है।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="यह नमूना कोड U3D से OBJ C# रूपांतरण दिखाता है" offSpacer="" %}}

```cs
// सीन के ऑब्जेक्ट में U3D लोड करें 
var document = new Aspose.ThreeD.Scene("template.u3d");
// ObjSaveOptions का एक उदाहरण बनाएं 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// U3D को OBJ के रूप में सहेजें 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="U3D को OBJ में बदलने के लिए निःशुल्क ऐप" sectionDescription="इसके लिए हमारे लाइव डेमो देखें [U3D से OBJ रूपांतरण](https://products.aspose.app/3d/conversion/u3d-to-obj) निम्नलिखित लाभों के साथ।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी U3D फ़ाइल अपलोड करें और \"कन्वर्ट\" बटन दबाएं।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको परिणामी OBJ फ़ाइल के लिए तुरंत डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 बिना किसी मॉडलिंग और रेंडरिंग सॉफ्टवेयर के 3D फाइलों में हेरफेर करने के लिए एक 3D फाइल प्रोसेसिंग लाइब्रेरी। 3D API Discreet3DS, WavefrontOBJ, FBX (ASCII, बाइनरी), STL (ASCII, बाइनरी), Universal3D, Collada, glTF, GLB, का समर्थन करता है। PLY, DirectX, Google Draco फ़ाइल स्वरूप और बहुत कुछ। डेवलपर 3D दस्तावेज़ स्वरूपों के सार को आसानी से बना सकते हैं, पढ़ सकते हैं, रूपांतरित कर सकते हैं, संशोधित कर सकते हैं और नियंत्रित कर सकते हैं।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}
U3D (Universal 3D) 3D कंप्यूटर ग्राफ़िक्स के लिए एक संपीड़ित फ़ाइल स्वरूप और डेटा संरचना है। इसमें 3D मॉडल की जानकारी जैसे त्रिकोण जाल, प्रकाश व्यवस्था, छायांकन, गति डेटा, रेखाएं और रंग और संरचना के साथ बिंदु शामिल हैं। प्रारूप को अगस्त 2005 में ECMA-363 मानक के रूप में स्वीकार किया गया था। 3D PDF दस्तावेज़ U3D एम्बेड करने वाली वस्तुओं का समर्थन करते हैं और इसे Adobe Reader (संस्करण 7 और उसके बाद) में देखा जा सकता है। U3D प्रारूप को त्रि-आयामी डेटा भंडारण और विनिमय के लिए एक सार्वभौमिक मानक स्थापित करने के उद्देश्य से विकसित किया गया था। हालांकि, प्रारूप को इंटरचेंज प्रारूप के रूप में उपयोग किए जाने के बजाय 3D PDF के लिए एन्कोडिंग में इसका मुख्य उपयोग मिलता है। एक्रोबैट 3D समर्थित 3D फ़ाइल प्रकार को PDF में बदलने पर या तो U3D या PRC में कनवर्ट करता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
ज्यामितीय वस्तुओं को परिभाषित और संग्रहीत करने के लिए Wavefront के उन्नत विज़ुअलाइज़र एप्लिकेशन द्वारा OBJ फ़ाइलों का उपयोग किया जाता है। ज्यामितीय डेटा का बैकवर्ड और फॉरवर्ड ट्रांसमिशन OBJ फाइलों के माध्यम से संभव है। दोनों बहुभुज ज्यामिति जैसे बिंदु, रेखाएं, बनावट के कोने, फलक और मुक्त-रूप ज्यामिति (वक्र और सतह) OBJ प्रारूप द्वारा समर्थित हैं। यह प्रारूप एनीमेशन या प्रकाश और दृश्यों की स्थिति से संबंधित जानकारी का समर्थन नहीं करता है। एक OBJ फ़ाइल आमतौर पर CAD (कंप्यूटर एडेड डिज़ाइन) द्वारा उत्पन्न 3D मॉडलिंग प्रक्रिया का एक अंतिम उत्पाद है। चेहरे के मानदंडों की स्पष्ट घोषणा से बचने के लिए कोने को स्टोर करने का डिफ़ॉल्ट क्रम काउंटर-क्लॉकवाइज है। हालांकि OBJ फाइलें एक टिप्पणी पंक्ति में पैमाने की जानकारी की घोषणा करती हैं, फिर भी OBJ निर्देशांक के लिए कोई इकाई घोषित नहीं की गई है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप U3D को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-3ds/" name="U3D से 3DS" description="3D स्टूडियो डॉस मेश" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-amf/" name="U3D से AMF" description="योजक विनिर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-dae/" name="U3D से DAE" description="डिजिटल एसेट एक्सचेंज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-fbx/" name="U3D से FBX" description="3D प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-html/" name="U3D से HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-pdf/" name="U3D से PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-ply/" name="U3D से PLY" description="बहुभुज फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-rvm/" name="U3D से RVM" description="अवेवा प्लांट डिजाइन मॉडल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-stl/" name="U3D से STL" description="विनिमेय 3D भूतल ज्यामिति" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}