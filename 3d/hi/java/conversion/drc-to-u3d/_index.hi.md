﻿---
title: Java के माध्यम से DRC को U3D में बदलें 
url: /hi/java/conversion/drc-to-u3d/ 
description: DRC प्रारूप से U3D फ़ाइल के लिए नमूना Java रूपांतरण कोड। किसी भी वेब या डेस्कटॉप Java आधारित एप्लिकेशन में DRC को U3D में बदलने के लिए इस उदाहरण कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java के माध्यम से DRC को U3D में बदलें" h2="बिना किसी 3D मॉडलिंग सॉफ़्टवेयर के Java लाइब्रेरी का उपयोग करके DRC से U3D रूपांतरण।" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके DRC को U3D में कैसे बदलें" %}}

 DRC से U3D को रेंडर करने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="Java के माध्यम से DRC को U3D में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 कोड की कुछ ही पंक्तियों में Java प्रोग्रामर आसानी से DRC फ़ाइल को U3D में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें DRC फ़ाइल1. U3dSaveOptions का एक उदाहरण बनाएं1. उन्नत रूपांतरण के लिए U3D विशिष्ट गुण सेट करें1. कॉल सीन.सेव मेथड1. U3D फ़ाइल एक्सटेंशन और U3dSaveOptions के ऑब्जेक्ट के साथ आउटपुट पथ पास करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Java रूपांतरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या एक संगत OS जिसमें Java JSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश है।- मावेन से सीधे Aspose.3D for Java का नवीनतम संस्करण प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DRC से U3D Java रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// सीन के ऑब्जेक्ट में DRC लोड करें 
Scene document = new Scene("template.drc");
// U3dSaveOptions का एक उदाहरण बनाएं 
AmfSaveOptions options = new U3dSaveOptions();
// DRC को U3D के रूप में सहेजें 
document.save("output.u3d", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DRC से U3D रूपांतरण लाइव प्रदर्शन" sectionDescription="[DRC को U3D में बदलें](https://products.aspose.app/3d/conversion/drc-to-u3d) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी DRC फ़ाइल अपलोड करें, यह तुरंत U3D में परिवर्तित हो जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D सीन मैनिपुलेशन लाइब्रेरी" %}}

 Aspose.3D एक CAD और गेमवेयर API है जो 3D फाइलों को लोड, संशोधित और परिवर्तित करता है। API एक स्टैंडअलोन है और इसके लिए किसी भी 3D मॉडलिंग या रेंडरिंग सॉफ़्टवेयर की आवश्यकता नहीं है। Discreet3DS, WavefrontOBJ, STL (ASCII, बाइनरी), Universal3D, FBX (ASCII, बाइनरी), Collada, glTF, PLY, के लिए कोई आसानी से API का उपयोग कर सकता है। GLB, DirectX और अधिक प्रारूप। 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}

.drc एक्सटेंशन वाली फ़ाइल एक संपीड़ित 3D फ़ाइल स्वरूप है जिसे Google Draco लाइब्रेरी के साथ बनाया गया है। Google Draco को ओपन सोर्स लाइब्रेरी के रूप में 3D जियोमेट्रिक मेश और पॉइंट क्लाउड्स को कंप्रेस और डीकंप्रेस करने की पेशकश करता है, और 3D ग्राफिक्स के स्टोरेज और ट्रांसमिशन को बेहतर बनाता है। यह इनपुट डेटा को एन्कोड करता है और इसे .drc फ़ाइल के रूप में सहेजता है। प्राप्त करने के अंत में, API .drc फ़ाइलें पढ़ता है और इन्हें PLY या OBJ फ़ाइलों के रूप में आउटपुट कर सकता है। संपीड़ित आउटपुट फ़ाइल उपयोगकर्ताओं को ऐप्स को तेज़ी से डाउनलोड करने और ब्राउज़रों में 3D ग्राफिक्स की त्वरित लोडिंग प्रदान करने में सक्षम बनाती है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}

U3D (Universal 3D) 3D कंप्यूटर ग्राफ़िक्स के लिए एक संपीड़ित फ़ाइल स्वरूप और डेटा संरचना है। इसमें 3D मॉडल की जानकारी जैसे त्रिकोण जाल, प्रकाश व्यवस्था, छायांकन, गति डेटा, रेखाएं और रंग और संरचना के साथ बिंदु शामिल हैं। प्रारूप को अगस्त 2005 में ECMA-363 मानक के रूप में स्वीकार किया गया था। 3D PDF दस्तावेज़ U3D एम्बेड करने वाली वस्तुओं का समर्थन करते हैं और इसे Adobe Reader (संस्करण 7 और उसके बाद) में देखा जा सकता है। U3D प्रारूप को त्रि-आयामी डेटा भंडारण और विनिमय के लिए एक सार्वभौमिक मानक स्थापित करने के उद्देश्य से विकसित किया गया था। हालांकि, प्रारूप को इंटरचेंज प्रारूप के रूप में उपयोग किए जाने के बजाय 3D PDF के लिए एन्कोडिंग में इसका मुख्य उपयोग मिलता है। एक्रोबैट 3D समर्थित 3D फ़ाइल प्रकार को PDF में बदलने पर या तो U3D या PRC में कनवर्ट करता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}