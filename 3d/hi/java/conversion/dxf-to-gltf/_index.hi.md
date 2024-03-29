﻿---
title: Java के माध्यम से DXF को GLTF में बदलें 
weight: 2080
url: /hi/java/conversion/dxf-to-gltf/ 
description: DXF प्रारूप से GLTF फ़ाइल के लिए नमूना Java रूपांतरण कोड। किसी भी वेब या डेस्कटॉप Java आधारित एप्लिकेशन में DXF को GLTF में बदलने के लिए इस उदाहरण कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java के माध्यम से DXF को GLTF में बदलें" h2="बिना किसी 3D मॉडलिंग सॉफ़्टवेयर के Java लाइब्रेरी का उपयोग करके DXF से GLTF रूपांतरण।" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके DXF को GLTF में कैसे बदलें" %}}

 DXF से GLTF को रेंडर करने के लिए, हम उपयोग करेंगे
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान रूपांतरण API for Java प्लेटफॉर्म है। आप इसका नवीनतम संस्करण सीधे से डाउनलोड कर सकते हैं
 [मावेना](https://repository.aspose.com/3d/) 
 और pom.xml में निम्नलिखित कॉन्फ़िगरेशन जोड़कर इसे अपने मावेन-आधारित प्रोजेक्ट में स्थापित करें।

{{% blocks/products/pf/agp/code-block title="कोष" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="निर्भरता" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Java के माध्यम से DXF को GLTF में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 कोड की कुछ ही पंक्तियों में Java प्रोग्रामर आसानी से DXF फ़ाइल को GLTF में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें DXF फ़ाइल1. GltfSaveOptions का एक उदाहरण बनाएं1. उन्नत रूपांतरण के लिए GLTF विशिष्ट गुण सेट करें1. कॉल सीन.सेव मेथड1. GLTF फ़ाइल एक्सटेंशन और GltfSaveOptions के ऑब्जेक्ट के साथ आउटपुट पथ पास करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Java रूपांतरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या एक संगत OS जिसमें Java JSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश है।- मावेन से सीधे Aspose.3D for Java का नवीनतम संस्करण प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DXF से GLTF Java रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// सीन के ऑब्जेक्ट में DXF लोड करें 
Scene document = new Scene("template.dxf");
// GltfSaveOptions का एक उदाहरण बनाएं 
GltfSaveOptions options = new GltfSaveOptions();
// DXF को GLTF के रूप में सहेजें 
document.save("output.gltf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DXF से GLTF रूपांतरण लाइव प्रदर्शन" sectionDescription="[DXF को GLTF में बदलें](https://products.aspose.app/3d/conversion/dxf-to-gltf) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी DXF फ़ाइल अपलोड करें, यह तुरंत GLTF में परिवर्तित हो जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D सीन मैनिपुलेशन लाइब्रेरी" %}}

 Aspose.3D एक CAD और गेमवेयर API है जो 3D फाइलों को लोड, संशोधित और परिवर्तित करता है। API एक स्टैंडअलोन है और इसके लिए किसी भी 3D मॉडलिंग या रेंडरिंग सॉफ़्टवेयर की आवश्यकता नहीं है। Discreet3DS, WavefrontOBJ, STL (ASCII, बाइनरी), Universal3D, FBX (ASCII, बाइनरी), Collada, glTF, PLY, के लिए कोई आसानी से API का उपयोग कर सकता है। GLB, DirectX और अधिक प्रारूप। 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}

DXF, ड्रॉइंग इंटरचेंज फॉर्मेट, या ड्रॉइंग एक्सचेंज फॉर्मेट, ऑटोकैड ड्राइंग फाइल का एक टैग किया गया डेटा प्रतिनिधित्व है। फ़ाइल में प्रत्येक तत्व में एक उपसर्ग पूर्णांक संख्या होती है जिसे समूह कोड कहा जाता है। यह समूह कोड वास्तव में उस तत्व का प्रतिनिधित्व करता है जो किसी दिए गए ऑब्जेक्ट प्रकार के लिए डेटा तत्व के अर्थ का अनुसरण करता है और इंगित करता है। DXF ड्राइंग फ़ाइल में लगभग सभी उपयोगकर्ता-निर्दिष्ट जानकारी का प्रतिनिधित्व करना संभव बनाता है। DXF फ़ाइल स्वरूप ऑटोडेस्क द्वारा ऑटोकैड और अन्य अनुप्रयोगों के बीच डेटा अंतरसंचालनीयता के लिए CAD डेटा फ़ाइल स्वरूप के रूप में विकसित किया गया था। इस प्रकार, डेटा को अन्य प्रारूपों से DXF में ऑटोकैड में आयात किया जा सकता है, जैसा कि DXF फ़ाइल प्रारूप इंटरऑपरेबिलिटी विनिर्देशों के अनुसार होता है।


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF (जीएल ट्रांसमिशन प्रारूप) एक 3D फ़ाइल स्वरूप है जो JSON प्रारूप में 3D मॉडल जानकारी संग्रहीत करता है। JSON का उपयोग 3D संपत्तियों के आकार और उन संपत्तियों को अनपैक करने और उपयोग करने के लिए आवश्यक रनटाइम प्रोसेसिंग दोनों को कम करता है। इसे अनुप्रयोगों द्वारा 3D दृश्यों और मॉडलों के कुशल संचरण और लोडिंग के लिए अपनाया गया था। glTF को ख्रोनोस ग्रुप 3D फॉर्मेट वर्किंग ग्रुप द्वारा विकसित किया गया था और इसके रचनाकारों द्वारा इसे 3D के जेपीईजी के रूप में भी वर्णित किया गया है। यह प्रारूप 3D सामग्री टूल और सेवाओं के लिए एक एक्स्टेंसिबल, सामान्य प्रकाशन प्रारूप को परिभाषित करता है जो ऑथरिंग वर्कफ़्लो को सुव्यवस्थित करता है और पूरे उद्योग में सामग्री के इंटरऑपरेबल उपयोग को सक्षम बनाता है। glTF फ़ाइल स्वरूप के निर्माण के पीछे उद्देश्य 3D सामग्री टूल और सेवाओं के लिए एक एक्स्टेंसिबल, सामान्य प्रकाशन प्रारूप को परिभाषित करना था जो ऑथरिंग वर्कफ़्लोज़ को सुव्यवस्थित करना चाहिए और पूरे उद्योग में सामग्री के इंटरऑपरेबल उपयोग को सक्षम करना चाहिए। यह वेबजीएल और अन्य एपीआई का उपयोग करके अनुप्रयोगों द्वारा रनटाइम प्रोसेसिंग को कम करता है।


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप DXF को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-3ds/" name="DXF से 3DS" description="3D स्टूडियो डॉस मेश" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-amf/" name="DXF से AMF" description="योजक विनिर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ase/" name="DXF से ASE" description="2डी एनिमेशन फाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-dae/" name="DXF से DAE" description="डिजिटल एसेट एक्सचेंज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-fbx/" name="DXF से FBX" description="3D प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-html/" name="DXF से HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-obj/" name="DXF से OBJ" description="3D फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ply/" name="DXF से PLY" description="बहुभुज फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-rvm/" name="DXF से RVM" description="अवेवा प्लांट डिजाइन मॉडल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-stl/" name="DXF से STL" description="विनिमेय 3D भूतल ज्यामिति" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-u3d/" name="DXF से U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}