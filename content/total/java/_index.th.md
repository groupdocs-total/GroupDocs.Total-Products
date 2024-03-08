---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: th
product: "Total"
product_tag: "total"
platform: "Java"
platform_tag: "java"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
      
############################# Head ############################
head_title: "ชุดเอกสารอัตโนมัติแบบครบวงจรสำหรับแอปพลิเคชัน Java"
head_description: "GroupDocs.Total for Java คือไลบรารีระบบอัตโนมัติด้านเอกสารที่ครอบคลุมซึ่งปรับแต่งมาสำหรับนักพัฒนา Java โดยมีฟังก์ชันการทำงานที่หลากหลายเพื่อรองรับรูปแบบเอกสารที่หลากหลาย เช่น PDF, Word, Excel, รูปภาพ, HTML, ไดอะแกรม และอื่นๆ"

############################# Header ############################
title: "ลดความซับซ้อนของการทำงานอัตโนมัติของเอกสาร<br>ในโปรเจ็กต์ Java ของคุณ"
description: "ปรับปรุงความสามารถอัตโนมัติของเอกสาร: แปลง ดู เปรียบเทียบ แก้ไข และลงนามในรูปแบบไฟล์กว่า 200 รูปแบบได้อย่างง่ายดาย"
words:
  for: "for"

actions:
  main: "ดาวน์โหลดฟรี Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-total/"
  alt: "การออกใบอนุญาต"
  alt_link: "https://purchase.groupdocs.com/pricing/total/java"
  title: "พร้อมที่จะเริ่มต้นหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Total ฟรีหรือขอใบอนุญาต"

release:
  title: "เวอร์ชัน {0} เปิดตัวแล้ว"
  notes: "ดูว่ามีอะไรใหม่"
  downloads: "ดาวน์โหลด"
  link: "https://releases.groupdocs.com/total/java/release-notes/latest/"

code:
  title: "ผสานและดูไฟล์ Word ใน Java"
  more: "ตัวอย่างเพิ่มเติม"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-Java"
  install: |
    <dependencies>
      <dependency>
        <groupId>com.groupdocs</groupId>
        <artifactId>groupdocs-total</artifactId>
        <version>{0}</version>
      </dependency>
    </dependencies>

    <repositories>
      <repository>
        <id>repository.groupdocs.com</id>
        <name>GroupDocs Repository</name>
        <url>https://repository.groupdocs.com/repo/</url>
      </repository>
    </repositories>
  content: |
    ```java {style=abap}
    // โหลดไฟล์ DOCX ต้นฉบับ 
    Merger merger = new Merger("sample1.docx");
    
    // เพิ่มไฟล์ DOCX อื่นเพื่อรวม
    merger.join("sample2.docx");

    // รวมไฟล์ DOCX และบันทึกผลลัพธ์
    merger.save("merged.docx");
    
    // โหลดไฟล์ DOCX ที่ผสานแล้วลงในโปรแกรมดู
    try (Viewer viewer = new Viewer("merged.docx"))
    {
      // ตั้งค่าตัวเลือก HTML เอาต์พุต หนึ่งไฟล์ต่อหน้า
      HtmlViewOptions viewOptions =   
      HtmlViewOptions.forEmbeddedResources("page{0}.html");
          
      // เรนเดอร์ DOCX เป็น HTML ด้วยทรัพยากรที่ฝังอยู่        
      viewer.view(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total ได้อย่างรวดเร็ว"
  description: "ทำให้การดูไฟล์ แปลง แก้ไข เปรียบเทียบ ค้นหา ใส่ลายน้ำ และเวิร์กโฟลว์อื่นๆ ในแอปพลิเคชัน Java เป็นแบบอัตโนมัติ"
  features:
    # feature loop
    - title: "รวมพลังของผลิตภัณฑ์ GroupDocs หลายรายการไว้ในโซลูชันเดียวที่ครอบคลุม"
      content: | 
        คุณสามารถใช้คุณลักษณะของผลิตภัณฑ์ GroupDocs ต่างๆ เพื่อสร้างแนวทางที่ปรับแต่งให้ตรงตามความต้องการเฉพาะของคุณได้
        <br><br>
        ตัวอย่างเช่น คุณสามารถแปลงไฟล์ Word เป็น PDF แล้วเพิ่มลายเซ็นดิจิทัลได้ หรือเติมข้อมูลเทมเพลตเอกสารจากฐานข้อมูล หรือแยกข้อความจากรูปภาพแล้วแปลเป็นภาษาอื่น
        <br><br>
        ความเป็นไปได้ไม่มีที่สิ้นสุด!
          
    # feature loop
    - title: "ฝึกฝนความหลากหลายของรูปแบบไฟล์"
      content: "GroupDocs.Total สำหรับ Java ปลดล็อกความเข้ากันได้กับรูปแบบไฟล์มากกว่า 200 รูปแบบ ช่วยให้คุณสามารถประมวลผลเอกสารประเภทยอดนิยมทุกประเภท ตั้งแต่รูปแบบ Office เช่น Word และ Excel ไปจนถึงรูปภาพ โค้ด และไฟล์ที่เข้ารหัส เราช่วยคุณได้"

    # feature loop
    - title: "การสนับสนุนข้ามแพลตฟอร์ม"
      content: "ปลดปล่อยตัวเองจากข้อจำกัดของแพลตฟอร์ม GroupDocs.Total มีความเข้ากันได้ข้ามแพลตฟอร์ม ช่วยให้คุณสามารถมอบประสิทธิภาพและความพร้อมใช้งานของโซลูชันที่เหมาะสมที่สุดแก่ผู้ใช้บนระบบใดๆ ที่สามารถติดตั้ง Java ได้"

############################# Platforms ############################
platforms:
  enable: true
  title: "ความเป็นอิสระของแพลตฟอร์ม"
  description: "GroupDocs.Total สำหรับ Java รองรับระบบปฏิบัติการ เฟรมเวิร์ก และตัวจัดการแพ็คเกจต่อไปนี้"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"


############################# File formats ############################
formats:
  enable: true
  title: "รูปแบบไฟล์ที่รองรับ"
  description: |
    GroupDocs.Total สำหรับ Java รองรับการทำงานด้วย [รูปแบบไฟล์](https://docs.groupdocs.com/total/java/supported-document-formats/) ต่อไปนี้
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument และรูปแบบข้อความ
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### รูปภาพ กราฟิก และไดอะแกรม
        * **ภาพแรสเตอร์:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### อื่น        
        * **เว็บ:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **หอจดหมายเหตุ:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **อื่น:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Total คุณสมบัติทั้งหมด"
  description: "จัดการ เรนเดอร์ และแปลง PDF และเอกสาร Office อย่างครอบคลุม"

  items:
    # feature loop
    - icon: "viewer"
      title: "การดูไฟล์ที่กว้างขวาง"
      content: "การดูเอกสารที่ครอบคลุมมากกว่า 180 รูปแบบ รวมถึง HTML, รูปภาพ และ PDF"

    # feature loop
    - icon: "conversion"
      title: "การแปลงรูปแบบ"
      content: "การแปลงเอกสารรูปแบบต่างๆ ได้อย่างราบรื่นโดยไม่ต้องใช้เครื่องมือภายนอก"

    # feature loop
    - icon: "annotation"
      title: "คำอธิบายประกอบแบบโต้ตอบ"
      content: "ความสามารถในการใส่คำอธิบายประกอบขั้นสูงสำหรับองค์ประกอบข้อความและรูปภาพภายในเอกสาร"

    # feature loop
    - icon: "comparison"
      title: "การเปรียบเทียบเนื้อหา"
      content: "การเปรียบเทียบเอกสารที่แม่นยำ เน้นความแตกต่างในเนื้อหาและรูปแบบ"

    # feature loop
    - icon: "signature"
      title: "ความยืดหยุ่นของลายเซ็น"
      content: "ตัวเลือกลายเซ็นที่หลากหลาย รวมถึงข้อความ รูปภาพ และลายเซ็นดิจิทัล"

    # feature loop
    - icon: "assembly"
      title: "การสร้างเอกสารตามเทมเพลต"
      content: "การสร้างเอกสารอัตโนมัติจากเทมเพลตและแหล่งข้อมูลภายนอก"

    # feature loop
    - icon: "metadata"
      title: "การจัดการข้อมูลเมตา"
      content: "การเข้าถึงและการจัดการข้อมูลเมตาที่แข็งแกร่งเพื่อการควบคุมเอกสารที่ได้รับการปรับปรุง"

    # feature loop
    - icon: "search"
      title: "การค้นหาขั้นสูง"
      content: "ฟังก์ชันการค้นหาอันทรงพลังพร้อมรองรับอัลกอริธึมคลุมเครือและคำพ้องความหมาย"

    # feature loop
    - icon: "watermark"
      title: "การควบคุมลายน้ำ"
      content: "การจัดการลายน้ำเอกสารที่ง่ายดาย นำเสนอคุณสมบัติการปรับแต่งและการดึงข้อมูล"

############################# Code samples ############################
code_samples:
  enable: true
  title: "ตัวอย่างโค้ด"
  description: "สถานการณ์จริงบางประการของ GroupDocs.Total สำหรับการใช้งาน Java"
  items:
    # code sample loop
    - title: "รักษาความปลอดภัยและจัดระเบียบสัญญา: ใส่ลายน้ำและจัดการข้อมูลเมตาในไฟล์ DOCX"
      content: |
        ปกป้องและจัดระเบียบเอกสาร Word ของคุณอย่างมีประสิทธิภาพด้วยตัวอย่างโค้ดที่ครอบคลุมนี้ ตัวอย่างด้านล่างนี้ช่วยให้คุณสามารถใช้ลายน้ำและการจัดการข้อมูลเมตาที่มีประสิทธิภาพภายในขั้นตอนการทำงานของสัญญาของคุณเพื่อเพิ่มความปลอดภัยและการจัดการข้อมูล มันแสดงให้เห็นถึงวิธีการ: <br><br>
        <b>ใช้ลายน้ำแบบกำหนดเอง:</b> เพิ่มลายน้ำ 'ร่างสัญญา' ที่โดดเด่นลงในเอกสารเพื่อให้มองเห็นได้ชัดเจนและปกป้อง [ปรับแต่งลายน้ำ](https://docs.groupdocs.com/watermark/java/adding-text-watermarks/) พร้อมตัวเลือกแบบอักษร สี ความทึบ และการจัดตำแหน่ง <br><br>
        <b>ปรับปรุงข้อมูลเมตา:</b> [แก้ไขข้อมูลเมตาของเอกสาร](https://docs.groupdocs.com/metadata/java/working-with-metadata-in-word-processing-documents/) ได้อย่างง่ายดายเพื่อรวมรายละเอียดที่สำคัญ เช่น ผู้แต่ง เวลาในการสร้าง บริษัท หมวดหมู่ และคำหลักเพื่อปรับปรุงการจัดระเบียบและความสามารถในการค้นหา
       
        {{< landing/code title="Java">}}
        ```java {style=abap}  
        import com.groupdocs.metadata.Metadata;
        import com.groupdocs.watermark.Watermark;
        import com.groupdocs.watermark.Watermark.Common;
        import com.groupdocs.watermark.Options.HtmlViewOptions;
        
        // โหลดเอกสารของคุณลงในลายน้ำ
        Watermarker watermarker = new Watermarker("contract.docx");
        
        // ตั้งค่าข้อความและแบบอักษรที่ต้องการสำหรับลายน้ำ
        TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 36));
          
        // เลือกสีแบบอักษรและความทึบของข้อความ การหมุน และการจัดแนว
        watermark.setForegroundColor(Color.getRed());                                                            
        watermark.setHorizontalAlignment(HorizontalAlignment.Center);                                            
        watermark.setVerticalAlignment(VerticalAlignment.Center);                               

        // ใช้ลายน้ำ
        watermarker.add(watermark);
        
        // บันทึกเอกสารผลลัพธ์
        watermarker.save("watermarked-contract.docx");
        
        Metadata metadata = new Metadata("watermarked-contract.docx");        
        WordProcessingRootPackage root = metadata.getRootPackageGeneric();

        // อัปเดตคุณสมบัติข้อมูลเมตาของเอกสาร
        root.getDocumentProperties().setAuthor("Name Surname");
        root.getDocumentProperties().setCreatedTime(new Date());
        root.getDocumentProperties().setCompany("Company Name");
        root.getDocumentProperties().setCategory("Work materials");
        root.getDocumentProperties().setKeywords("contract, watermarked");

        // บันทึกเอกสารด้วยข้อมูลเมตาที่อัปเดต
        metadata.save("contract-final.docx");                
        ```
        {{< /landing/code >}}

    # code sample loop
    - title: "การเรียบเรียงเอกสารที่คล่องตัว"
      content: |
        <b>สถานการณ์:</b> สำนักงานกฎหมายขนาดใหญ่มักประมวลผลเอกสารที่หลากหลายซึ่งประกอบด้วยข้อมูลลูกค้าที่เป็นความลับ ซึ่งจะต้องแก้ไขก่อนที่จะแบ่งปันกับบุคคลที่สามหรือเพื่อการเปิดเผยต่อสาธารณะ การแก้ไขข้อมูลที่ละเอียดอ่อนนี้ด้วยตนเองอาจเป็นเรื่องที่น่าเบื่อ ใช้เวลานาน และมีแนวโน้มที่จะเกิดข้อผิดพลาดจากมนุษย์ เพื่อให้มั่นใจถึงประสิทธิภาพ ความถูกต้อง และการปฏิบัติตามกฎระเบียบด้านการปกป้องข้อมูล บริษัทกฎหมายจึงแสวงหาโซลูชันอัตโนมัติเพื่อปรับปรุงกระบวนการตรวจทานเอกสารให้มีประสิทธิภาพยิ่งขึ้น 
        
        <br>

        <b>สารละลาย:</b>
        GroupDocs.Total ดำเนินกระบวนการโดยอัตโนมัติ โดยจะกระตุ้นให้ดำเนินการแก้ไขเมื่อได้รับเอกสาร นอกจากนี้ [ตัวเลือกที่ยืดหยุ่น](https://docs.groupdocs.com/redaction/java/text-redactions/) ช่วยให้ปรับแต่งได้โดยอนุญาตให้คุณตั้งกฎ เลือกโหมดการเขียนทับ (เช่น ปิดทึบ แทนที่ด้วยเครื่องหมายดอกจัน) และระบุ ส่วนหรือหน้าเฉพาะสำหรับการเรียบเรียง สุดท้ายนี้ [เอาต์พุตที่เป็นมิตรกับผู้ใช้](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) จะสร้างเอกสารที่แก้ไขแล้วในรูปแบบ PDF เพื่อการแชร์และตรวจทานที่ง่ายดาย ในขณะที่การรักษาความปลอดภัยและการตรวจสอบที่ได้รับการปรับปรุงช่วยให้มั่นใจได้ว่าทั้งหมด กระบวนการได้รับการบันทึกไว้เพื่อการปฏิบัติตามและความรับผิดชอบ 
        <br><br>
        โซลูชันที่ครอบคลุมนี้ช่วยให้ผู้เชี่ยวชาญด้านกฎหมายและองค์กรอื่นๆ สามารถลดเวลาและค่าใช้จ่ายในการแก้ไขได้อย่างมาก ลดข้อผิดพลาดของมนุษย์ และจัดการข้อมูลที่ละเอียดอ่อนด้วยความมั่นใจอย่างสม่ำเสมอ        
              
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.redaction.Redaction;
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // โหลดเอกสารที่มีข้อมูลส่วนตัวลงในตัวแก้ไข 
        Redactor redactor = new Redactor("customer-info.docx");
        
        // ตั้งค่าและปรับแต่งตัวเลือกการเขียนทับ 
        redactor.apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
        
        // ใช้การแก้ไขและบันทึกผลลัพธ์ 
        redactor.save();

        // โหลดไฟล์ที่ถูกแก้ไขเพื่อตรวจสอบ 
        Viewer viewer = new Viewer("customer-info.docx");
        
        // ตั้งค่า PDF เป็นรูปแบบการดูที่ต้องการ       
        PdfViewOptions viewOptions = new PdfViewOptions("redacted-info.pdf");

        // บันทึกเอกสารเป็น PDF      
        viewer.view(viewOptions);        
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "บทวิจารณ์ผลิตภัณฑ์ GroupDocs"
# description: "อย่าเพิ่งเชื่อคำพูดของเรา ดูว่านักพัฒนารายอื่นพูดถึง API ของเราอย่างไร"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "บริการที่เป็นเลิศและผลิตภัณฑ์ที่เป็นเลิศ พวกเขามีประโยชน์และตอบสนองอย่างมากในระหว่างกระบวนการใช้งาน GroupDocs.Viewer สำหรับ .NET ไม่สามารถแนะนำได้มากพอ"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "หลังจากใช้งานและใช้งาน GroupDocs.Viewer สำหรับ Java ในโปรเจ็กต์แล้ว ดูเหมือนว่าจะทำงานได้ดีมาก ฉันได้ทดสอบกับเอกสารจำนวนมากและจนถึงตอนนี้ก็ดีมาก ทุกสิ่งที่ฉันใส่ลงไปนั้นเรนเดอร์ได้อย่างสวยงามและดูดีพอๆ กับในโปรแกรมดู PDF หรือ MS Word"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---