﻿---
title: .NET के माध्यम से GLB फ़ाइल स्वरूपों से एसेट निकालें 
weight: 830
url: /hi/net/extractor/glb/ 
description: .NET फ्रेमवर्क, .NET कोर, Mono पर GLB दस्तावेज़ों से एक्सट्रैक्ट एसेट लोड करने, रेंडर करने और जोड़ने के लिए C# स्रोत कोड।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="GLB से C# के माध्यम से संपत्तियां निकालें" h2="सर्वर-साइड API का उपयोग करके GLB फ़ाइलों से एसेट निकालने के लिए अपने स्वयं के .NET ऐप्स बनाएं।" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="GLB फ़ाइल का उपयोग करके C# से एसेट कैसे निकालें" %}}

 GLB फ़ाइल से एसेट निकालने के लिए, हम उपयोग करेंगे
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान API है जो C# प्लेटफॉर्म के लिए एक्सट्रैक्ट एसेट के साथ उपयोग किया जाता है। खुला हुआ
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

{{% blocks/products/pf/agp/feature-section-col title="GLB से C# के माध्यम से संपत्ति निकालने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D केवल कोड की कुछ पंक्तियों के साथ GLB फ़ाइल से एसेट निकालना डेवलपर के लिए आसान बनाता है.

{{% /blocks/products/pf/agp/text %}}

- सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें GLB फ़ाइल- आउटपुट फ़ाइल स्वरूप के रूप में ज़िप फ़ाइल स्वरूप वस्तु बनाएँ- आर्काइव क्लास बनाएं और एक्सट्रैक्ट एसेट क्लास को हैंडल करें- एक्सट्रैक्ट मेथड को कॉल करें और फाइल को सेव करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Mono के साथ संगत OS- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल- Aspose.3D for .NET आपके प्रोजेक्ट में संदर्भित
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# कोड GLB से संपत्ति निकालने के लिए" offSpacer="" %}}

```cs

//स्रोत फ़ाइलें जिन्हें संपत्ति निकालने की आवश्यकता होती है
string file = "template.glb";
Scene scene = new Scene(file);  

//आउटपुट एक संपीड़ित फ़ाइल स्वरूप में है, और निर्देशिका मौजूदा फ़ोल्डर के नाम का प्रतिनिधित्व करती है
var zipOutput = Path.Combine("Directory", "OutputFile.zip");
using var output = new FileStream(zipOutput, FileMode.Create);
using var za = new Zip(output);

//एसेट एक्सट्रैक्शन ऑपरेशन करने के लिए एक्सट्रैक्ट मेथड को कॉल करें
Extract(scene,za,true);

//कॉल करने योग्य निकालने की विधि,पैरामीटर बनावट इंगित करती है: क्या बनावट को निकालना है
private void Extract(Scene scene, Zip za,bool texture)
{
    var extractor = new Extractor(za,texture);
    extractor.Extract(scene);
}

//एक संपीड़ित फ़ाइल प्रसंस्करण वर्ग बनाएँ
class Zip : IDisposable
{
    private ZipArchive archive;
    private HashSet<string> entries = new HashSet<string>();

    public Zip(Stream stream)
    {
        archive = new ZipArchive(stream, ZipArchiveMode.Create);
    }
    public void Dispose()
    {
        archive.Dispose();
    }

    public void Add(string fileName, byte[] content, bool enableCompression)
    {
        var entryName = PickName(fileName);
        var compressionLevel = enableCompression ? CompressionLevel.Fastest : CompressionLevel.NoCompression;
        var entry = archive.CreateEntry(entryName, compressionLevel);
        using var stream = entry.Open();
        stream.Write(content, 0, content.Length);
    }
    
    private string PickName(string fileName)
    {
        if (!entries.Contains(fileName))
        {
            entries.Add(fileName);
            return fileName;
        }
        var baseName = Path.GetFileNameWithoutExtension(fileName);
        var ext = Path.GetExtension(fileName);
        for (var idx = 2; ; idx++)
        {
            var newName = baseName + "_" + idx;
            if (!string.IsNullOrEmpty(ext))
                newName += ext;
            if (entries.Contains(newName))
                continue;
            entries.Add(newName);
            return newName;
        }
    }
}

//एसेट एक्सट्रैक्शन प्रोसेसिंग क्लास बनाएं
class Extractor
{
    private Zip zip;
    private bool texture;
    HashSet<A3DObject> visited = new HashSet<A3DObject>();
    public Extractor(Zip zip,bool texture)
    {
        this.zip = zip;
        this.texture = texture;
    }

    private bool CanVisit(A3DObject obj)
    {
        if (visited.Contains(obj))
            return false;
        visited.Add(obj);
        return true;
    }
    public void Extract(Scene scene)
    {
        if (scene.Library != null && scene.Library.Count > 0)
        {
            foreach (var obj in scene.Library)
            {
                Visit(obj);
            }
        }
        VisitNode(scene.RootNode);
    }
    private void VisitNode(Node node)
    {
        if (!CanVisit(node))
            return;
        if (texture)
        {
            foreach (var mat in node.Materials)
            {
                VisitMaterial(mat);
            }
        }

        foreach (var entity in node.Entities)
        {
            if (entity is Mesh)
                Save((Mesh)entity, node.Name);
        }
        
        foreach (var child in node.ChildNodes)
        {
            VisitNode(child);
        }
    }
    private void VisitMaterial(Material mat)
    {
        if (!CanVisit(mat))
            return;
        if (!texture)
            return;
        foreach (var tslot in mat)
        {
            if (tslot.Texture is Texture)
            {
                Save((Texture)tslot.Texture);
            }
        }
    }
    private void Visit(A3DObject obj)
    {
        if (texture && obj is Texture)
        {
            Save((Texture)obj);
        }
        else if (obj is Mesh)
        {
            Save((Mesh)obj, null);
        }
        else if (obj is Node)
        {
            VisitNode((Node)obj);
        }
    }
    private void Save(Mesh mesh, string? nodeName)
    {
        if (!CanVisit(mesh))
            return;
        Scene scene = new Scene(mesh);
        using (var ms = new MemoryStream())
        {
            scene.Save(ms, FileFormat.FBX7400ASCII);
            var name = nodeName;
            if (string.IsNullOrEmpty(name))
                name = mesh.Name;
            if (string.IsNullOrEmpty(name))
                name = "mesh";
            var ext = ".fbx";
            zip.Add(name + ext, ms.ToArray(), true);
        }
    }
    private void Save(Texture tex)
    {
        if (tex.Content == null || !CanVisit(tex))
            return;
        var fileName = tex.FileName != null ? Path.GetFileName(tex.FileName) : null;
        zip.Add(fileName, tex.Content, false);
    }
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="लगभग Aspose.3D for .NET API" %}}

 Aspose.3D एक CAD और गेमवेयर API है जो 3D फाइलों को लोड, संशोधित और परिवर्तित करता है। API एक स्टैंडअलोन है और इसके लिए किसी भी 3D मॉडलिंग या रेंडरिंग सॉफ़्टवेयर की आवश्यकता नहीं है। Discreet3DS, WavefrontOBJ, STL (ASCII, बाइनरी), Universal3D, FBX (ASCII, बाइनरी), Collada, glTF, PLY, के लिए कोई आसानी से API का उपयोग कर सकता है। GLB, DirectX और अधिक प्रारूप। 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="GLB से संपत्ति निकालने के लिए निःशुल्क ऐप" sectionDescription="हमारे लाइव डेमो की जांच करें [निकालने वाला GLB](https://products.aspose.app/3d/extractor/glb) निम्नलिखित लाभों के साथ।" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोड लिखने या संकलित करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस GLB फ़ाइल अपलोड करें और \"निकालें\" बटन दबाएं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" यदि आवश्यक हो, तो लिंक से GLB फ़ाइल डाउनलोड करें" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB जीएल ट्रांसमिशन फ़ॉर्मेट (glTF) में सहेजे गए 3D मॉडल का बाइनरी फ़ाइल स्वरूप प्रतिनिधित्व है। बाइनरी प्रारूप में 3D मॉडल जैसे नोड पदानुक्रम, कैमरा, सामग्री, एनिमेशन और मेश के बारे में जानकारी। यह बाइनरी फॉर्मेट glTF एसेट (JSON, .bin और इमेज) को बाइनरी ब्लॉब में स्टोर करता है। यह फ़ाइल आकार में वृद्धि के मुद्दे से भी बचता है जो glTF के मामले में होता है। GLB फ़ाइल स्वरूप के परिणामस्वरूप कॉम्पैक्ट फ़ाइल आकार, तेज़ लोडिंग, पूर्ण 3D दृश्य प्रतिनिधित्व, और आगे के विकास के लिए एक्स्टेंसिबिलिटी होती है। प्रारूप मॉडल/gltf-बाइनरी को MIME प्रकार के रूप में उपयोग करता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="प्रारूपों से संपत्ति निकालने के लिए अन्य समर्थित ऐप" subTitle="C# का उपयोग करके, कोई भी व्यक्ति सहित कई अन्य फ़ाइल स्वरूपों से संपत्तियां निकाल सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3mf/" name="3MF" description="3D निर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/amf/" name="AMF" description="योजक विनिर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ase/" name="ASE" description="2डी एनिमेशन फाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/dae/" name="DAE" description="डिजिटल एसेट एक्सचेंज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/dxf/" name="DXF" description="ड्राइंग इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/fbx/" name="FBX" description="3D प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3ds/" name="3DS" description="3D स्टूडियो मेश फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/gltf/" name="GLTF" description="जीएल ट्रांसमिशन प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/jt/" name="JT" description="बृहस्पति टेसेलेशन फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/obj/" name="OBJ" description="3D फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ply/" name="PLY" description="बहुभुज फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/rvm/" name="RVM" description="अवेवा प्लांट डिजाइन मॉडल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/stl/" name="STL" description="विनिमेय 3D भूतल ज्यामिति" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/vrml/" name="VRML" description="आभासी वास्तविकता मॉडलिंग भाषा" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/x/" name="एक्स" description="DirectX मॉडल छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usd/" name="USD" description="यूनिवर्सल सीन विवरण" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usdz/" name="USDZ" description="यूनिवर्सल सीन विवरण जिप आर्काइव" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}