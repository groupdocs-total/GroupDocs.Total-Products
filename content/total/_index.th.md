---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Total"
product_tag: "total"

############################# Head ############################
head_title: "API การทำงานอัตโนมัติของเอกสาร | On Premise API และบริการออนไลน์"
head_description: "จัดการเอกสารของคุณโดยอัตโนมัติอย่างง่ายดายและฟรี"

############################# Header ##########################
title: "จัดการเอกสารอัตโนมัติด้วยชุดโปรแกรมออลอินวัน"
description: |
  ลดความซับซ้อนของงานเอกสารที่ซ้ำซ้อน และปรับปรุงขั้นตอนการทำงานของคุณด้วยโค้ดเพียงไม่กี่บรรทัด API อันทรงพลังทำให้การบูรณาการทำได้อย่างง่ายดาย ช่วยให้คุณมุ่งเน้นไปที่นวัตกรรม ไม่ใช่โครงสร้างพื้นฐาน

  แปลง ลงนาม ดู ใส่คำอธิบายประกอบ - พิชิตงานเอกสารด้วยโค้ดที่น้อยที่สุด ตั้งแต่ Word ไปจนถึง PDF, Excel ไปจนถึงรูปภาพ จัดการทุกอย่างได้อย่างราบรื่น รหัสน้อยลง ผลกระทบที่มากขึ้น

  ทำงานเอกสารอัตโนมัติ เพิ่มประสิทธิภาพ และดำเนินการอย่างรวดเร็วด้วยการผสานรวมที่รวดเร็วปานสายฟ้า ประหยัดเวลาและทรัพยากร โดยมุ่งเน้นไปที่สิ่งที่สำคัญต่อธุรกิจของคุณอย่างแท้จริง

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "เลือกแพลตฟอร์มของคุณ"
  title: "แพลตฟอร์มที่รองรับ"
  description: "ไลบรารี GroupDocs.Total รองรับระบบปฏิบัติการและเฟรมเวิร์กต่อไปนี้"
  details_link_title: "เรียนรู้เพิ่มเติม"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Total for .NET"
      color: "blue"
      tag: "net"
      link: "/total/net/"
      features_link: "https://docs.groupdocs.com/total/net/system-requirements/"
      features:
        # features loop
        - content: ".NET Framework 4.6.2+  <br>  .NET Core 3.1  <br>  .NET 6+"
          rows: "3"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "ไฟล์มากกว่า 200 รูปแบบ"
          rows: "1"
        # features loop
        - content: "Visual Studio <br> VS Code <br> Rider"
          rows: "15"
    
    # supported_platforms loop
    - title: "Java"
      description: "GroupDocs.Total for Java"
      color: "red"
      tag: "java"
      link: "/total/java/"
      features_link: "https://docs.groupdocs.com/total/java/system-requirements/"
      features:
        # features loop
        - content: "J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"       
        # features loop
        - content: "ไฟล์มากกว่า 200 รูปแบบ"
          rows: "1"
        # features loop
        - content:  "Eclipse <br> NetBeans <br> IntelliJ Idea"
          rows: "3"

############################# Features ############################

features:
  enable: true
  title: "ชุดคุณลักษณะของ GroupDocs.Total"
  description: "โซลูชันเดียวที่รวมฟังก์ชันการทำงานของผลิตภัณฑ์ GroupDocs ทั้งหมดไว้ในที่เดียว และจัดการงานเอกสารต่างๆ โดยไม่ต้องใช้ซอฟต์แวร์จากภายนอก"

  items:
    # feature loop
    - icon: "view"
      title: "ดูเอกสารและรูปภาพ"
      content: "เรนเดอร์ไฟล์เพื่อดูในรูปแบบ HTML, PDF, PNG และ JPEG"

    # feature loop
    - icon: "convert"
      title: "แปลงระหว่างรูปแบบ"
      content: "แปลงไฟล์จากแหล่งต่าง ๆ เป็นรูปแบบเป้าหมายที่หลากหลาย"

    # feature loop
    - icon: "merge"
      title: "รวมหลายไฟล์เป็นไฟล์เดียว"
      content: "รวม PDF, Office และอื่นๆ หลายรายการไว้ในเอกสารเดียวได้อย่างราบรื่น"
    
    # feature loop
    - icon: "settings"
      title: "ผลิตภัณฑ์และคุณสมบัติเพิ่มเติม"
      content: "สำรวจชุด API การทำงานอัตโนมัติของเอกสาร GroupDocs ทั้งหมด: เปรียบเทียบ e-sing ค้นหา ลายน้ำ และอื่นๆ อีกมากมาย!"


############################# Code samples ############################
# code_samples:
#   enable: true
#   title: "GroupDocs.ตัวอย่างโค้ดทั้งหมด"
#   description: "กรณีการใช้งานบางส่วนของการดำเนินการ GroupDocs.Total ทั่วไปใน C#, Java, TypeScript"
#   items:
#     # code sample loop
#     - title: "วิธีเรนเดอร์ไฟล์ DOCX เป็น PDF"
#       content: |
#        เรนเดอร์เอกสาร DOCX เป็น PDF โดยไม่ต้องติดตั้ง Microsoft Word หรือซอฟต์แวร์อื่นๆ โหลดและดูไฟล์ DOCX ภายในแอปพลิเคชันของคุณได้อย่างง่ายดาย ไม่ว่าจะเป็นแอปพลิเคชันบนเว็บหรือเดสก์ท็อป ต่อไปนี้คือตัวอย่างวิธีเรนเดอร์ไฟล์ DOCX เป็น PDF:
#       samples:
#         - language: "C#"
#           color: "blue"
#           content: |
#             ```csharp {style=abap}   
#             // โหลดไฟล์ DOCX เพื่อเรนเดอร์
#             using (Viewer viewer = new Viewer("sample.docx"))
#             {
#               // เรนเดอร์ DOCX เป็นไฟล์ PDF
#               PdfViewOptions viewOptions = new PdfViewOptions();
#               viewer.View(viewOptions);
#             }
#             ```
#         - language: "Java"
#           color: "red"
#           content: |
#             ```java {style=abap}   
#             import com.groupdocs.viewer.Viewer;
#             import com.groupdocs.viewer.options.PdfViewOptions;
#             // ...
#             // โหลดไฟล์ DOCX เพื่อเรนเดอร์
#             try (Viewer viewer = new Viewer("sample.docx")) {
#                 // เรนเดอร์ DOCX เป็นไฟล์ PDF
#                 PdfViewOptions viewOptions = new PdfViewOptions();
#                 viewer.view(viewOptions);
#             }
#             ```
#         - language: "TypeScript"
#           color: "green"
#           content: |
#             ```javascript {style=abap}  
#             // โหลดไฟล์ DOCX เพื่อเรนเดอร์
#             const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
#             // เรนเดอร์ DOCX เป็นไฟล์ PDF
#             const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
#             viewer.view(viewOptions)
#             ```


############################# Formats ############################
formats:
  enable: true
  title:  "รองรับไฟล์มากกว่า 200 รูปแบบ"
  description: "GroupDocs.Total รองรับการทำงานด้วย [รูปแบบไฟล์](https://docs.groupdocs.com/total/net/supported-document-formats/) ยอดนิยมที่สุด"


############################# Metrics ############################

metrics:
  enable: true
  title: "ตัวชี้วัดเชิงลึกและข้อมูลเชิงลึกทางสถิติ"
  description: "เจาะลึกรายละเอียดตัวเลขหลักของเรา โดยให้ตัวชี้วัดที่ครอบคลุมและข้อมูลเชิงลึกทางสถิติเกี่ยวกับความสำเร็จ ผลกระทบ และการเติบโตของเรา"

  items:
    # metrics loop
    - number: "200+"
      title: "รูปแบบที่รองรับ"
      content: "ดูไฟล์มากกว่า 200 รูปแบบได้อย่างง่ายดาย รวมถึงเอกสาร รูปภาพ และแบบร่าง CAD โดยไม่ยุ่งยาก ทำลายอุปสรรคด้านความเข้ากันได้และเข้าถึงไฟล์ที่หลากหลายได้อย่างง่ายดายด้วยโซลูชันการรับชมที่ครอบคลุมของเรา"
    # metrics loop
    - number: "550K"
      title: "ดาวน์โหลด NuGet"
      content: "โซลูชันแพ็คเกจ NuGet ของเราได้กลายเป็นทรัพยากรที่เชื่อถือได้และนำไปใช้อย่างกว้างขวางในชุมชนนักพัฒนา โดยให้การบูรณาการที่ราบรื่นและฟังก์ชันการทำงานที่มีคุณค่าสำหรับโครงการนับไม่ถ้วน"

    # metrics loop
    - number: "10+"
      title: "ห้องสมุด"
      content: "ผลิตภัณฑ์ของเราประกอบด้วยไลบรารีมากกว่า 10 แห่งที่นำเสนอคุณลักษณะขั้นสูงเพื่อเพิ่มประสิทธิภาพการทำงาน ไลบรารีเหล่านี้ได้รับการออกแบบมาเพื่อตอบสนองความต้องการในการพัฒนาที่แตกต่างกันด้วยความสามารถที่เหนือชั้น"
    
    # metrics loop
    - number: "100+"
      title: "ลูกค้ามีความสุข"
      content: "ให้บริการแบรนด์ที่โดดเด่นที่สุดทั่วโลก ค้นพบว่าทำไมคนนับร้อยถึงรัก GroupDocs.Total! สำรวจการนำทางที่ราบรื่น การทำงานร่วมกันที่สะดวกสบาย และความสะดวกในการใช้งานที่เหนือชั้น เข้าร่วมเดี๋ยวนี้!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "ลูกค้าที่มีความสุขของเรา"
  description: "ห้องสมุด GroupDocs ได้รับการว่าจ้างจากแบรนด์ที่มีชื่อเสียงและโดดเด่นระดับโลกทั่วโลก"

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"



############################# Actions ############################

actions:
  enable: true
  title: "พร้อมที่จะเริ่มต้นหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Total ฟรีหรือขอใบอนุญาต"

  items:
    #  loop
    - title: ".NET"
      link: "/total/net/"
      color: "blue"
        #  loop
    - title: "Java"
      link: "/total/java/"
      color: "red"


############################# Faq ############################

faq:
  enable: true
  title: "คำถามและข้อกังวลทั่วไป"
  description: "ค้นหาคำตอบสำหรับคำถามทั่วไปในส่วนคำถามที่พบบ่อยของเราเพื่อตอบข้อสงสัยและข้อกังวลของคุณอย่างรวดเร็ว"

  items:
    #  loop
    - question: "GroupDocs.Total คืออะไร และแตกต่างจากผลิตภัณฑ์ GroupDocs อื่นๆ อย่างไร"
      answer: |
        GroupDocs.Total เป็นชุดโปรแกรมที่ครอบคลุมที่รวมฟังก์ชันการทำงานของผลิตภัณฑ์ GroupDocs ทั้งหมดไว้ในแพ็คเกจเดียว สิ่งนี้มีข้อดีหลายประการ: <br><br>
        <ul>
          <li>
            <b>คุณสมบัติแบบครบวงจร:</b> คุณสามารถเข้าถึงความสามารถในการประมวลผลเอกสารทั้งหมด รวมถึงการดู การแปลง การรวม คำอธิบายประกอบ การลงนาม และอื่นๆ ภายใน API เดียว <br><br>
          </li>
          <li>
            <b>ความเข้ากันได้ที่เพิ่มขึ้น:</b> GroupDocs.Total รับประกันประสิทธิภาพที่สม่ำเสมอและเชื่อถือได้ในทุกรูปแบบไฟล์และแพลตฟอร์มที่รองรับ ขจัดปัญหาความเข้ากันได้ที่อาจเกิดขึ้นเมื่อใช้ผลิตภัณฑ์แยกกัน <br><br>
          </li>
          <li>
            <b>ขนาดบรรจุภัณฑ์ที่ปรับให้เหมาะสม:</b> ชุดนี้มาเป็นแพ็คเกจเดียวที่มีขนาดกะทัดรัด ช่วยลดการใช้ทรัพยากรและทำให้การรวมเข้ากับแอปพลิเคชันของคุณง่ายขึ้น เมื่อเทียบกับการใช้ผลิตภัณฑ์เดี่ยวที่มีการติดตั้งแยกกัน
          </li>
        <ul>

    #  loop
    - question: "เหตุใดจึงเลือก GroupDocs.Total แทนที่จะซื้อผลิตภัณฑ์ GroupDocs แต่ละรายการ"
      answer: |
        การซื้อสิทธิ์การใช้งาน GroupDocs เดียว โดยทั่วไปแล้วจะมีค่าใช้จ่ายน้อยกว่าการซื้อสิทธิ์การใช้งานสำหรับผลิตภัณฑ์ GroupDocs สองรายการขึ้นไป <br>
        สิ่งนี้แปลให้เกิดประโยชน์หลักหลายประการสำหรับคุณ: <br><br>
        <b>ประหยัดต้นทุน:</b> GroupDocs.Total มอบส่วนลดจำนวนมากเมื่อเปรียบเทียบกับการซื้อผลิตภัณฑ์แต่ละรายการ ช่วยให้คุณขยายงบประมาณได้มากขึ้น <br><br>
        <b>การจัดการที่ง่ายขึ้น:</b> ด้วย GroupDocs.Total คุณจะจัดการทุกอย่างภายใต้ใบอนุญาตเดียว ขจัดความจำเป็นในการติดตามและรักษาใบอนุญาตหลายใบสำหรับผลิตภัณฑ์ต่างๆ สิ่งนี้ทำให้งานธุรการของคุณง่ายขึ้นและลดต้นทุนโดยรวม <br><br>
        หากคุณกำลังมองหาโซลูชันที่คุ้มค่าและมีฟีเจอร์มากมายสำหรับความต้องการในการจัดการเอกสารของคุณ GroupDocs.Total เป็นตัวเลือกที่สมบูรณ์แบบ

    #  loop
    - question: "ฉันจะเริ่มต้นใช้งาน GroupDocs.Total ได้อย่างไร"
      answer: |
        คุณสามารถเริ่มต้นด้วยการทดลองใช้ฟรีเพื่อสำรวจฟีเจอร์ต่างๆ และดูว่าตรงตามความต้องการของคุณหรือไม่ GroupDocs ยังมี[เอกสารประกอบ](https://docs.groupdocs.com/total/) ทรัพยากรและ[บทช่วยสอน](https://groupdocs.github.io) มากมายเพื่อช่วยคุณเริ่มต้นใช้งานการผสานรวมและการพัฒนา
        
    #  loop
    - question: "GroupDocs.Total มีบริการช่วยเหลือด้านเทคนิคหรือไม่"
      answer: |
        ใช่ GroupDocs ให้การสนับสนุนทางเทคนิคที่ครอบคลุมเพื่อให้คุณมั่นใจถึงความสำเร็จกับ GroupDocs.Total พวกเขามีสองทางเลือก: <br><br>
        <b>[ฟอรั่มการสนับสนุนฟรี](https://forum.groupdocs.com):</b> ฟอรัมนี้ช่วยให้คุณเชื่อมต่อกับเจ้าหน้าที่ GroupDocs ซึ่งสามารถตอบคำถามของคุณและเสนอวิธีแก้ปัญหาตามประสบการณ์ของพวกเขา เป็นแหล่งข้อมูลที่ดีสำหรับปัญหาทั่วไปและการสอบถามข้อมูลทั่วไป <br><br>
        <b>[ฝ่ายช่วยเหลือสนับสนุนแบบชำระเงิน](https://helpdesk.groupdocs.com):</b> ตัวเลือกนี้จะให้การสนับสนุนตามลำดับความสำคัญ หากคุณพบปัญหาที่ซับซ้อนหรือต้องการการแก้ไขที่เร็วขึ้น การสนับสนุนแบบชำระเงินจะให้ความช่วยเหลือส่วนบุคคลและเวลาตอบกลับที่รวดเร็วยิ่งขึ้น <br><br>
        ด้วยการเสนอตัวเลือกทั้งแบบฟรีและมีค่าใช้จ่าย GroupDocs จึงตอบสนองความต้องการและงบประมาณที่แตกต่างกัน ทำให้มั่นใจได้ว่าคุณจะได้รับการสนับสนุนที่จำเป็นเพื่อให้ประสบความสำเร็จด้วย GroupDocs.Total

    #  loop
    - question: "GroupDocs.Total จำเป็นต้องมีซอฟต์แวร์เพิ่มเติมสำหรับการจัดการเอกสารหรือไม่"
      answer: |
        GroupDocs.Total เป็นชุดโปรแกรมแบบครบวงจรและไม่ต้องใช้ซอฟต์แวร์ของบริษัทอื่นเพิ่มเติมสำหรับงานการจัดการเอกสารขั้นพื้นฐาน เช่น การดู การแปลง การใส่คำอธิบายประกอบ หรือการเซ็นชื่อ อย่างไรก็ตาม ขึ้นอยู่กับคุณสมบัติเฉพาะที่คุณใช้ (เช่น OCR สำหรับเอกสารที่สแกน) อาจจำเป็นต้องใช้ไลบรารีภายนอก

############################# Cloud and Apps ############################

cloud_links:
  enable: true
  title: "GroupDocs โซลูชั่นแบบครบวงจร"
  description: "เพิ่มประสิทธิภาพการประมวลผลเอกสารในแอปพลิเคชันของคุณด้วย REST API บนระบบคลาวด์และแอปออนไลน์ฟรีของเรา"

  items:
    #  loop
    - icon: "groupdocs_total-cloud"
      title: "GroupDocs.Total Cloud"
      link: "https://products.groupdocs.cloud/total"
      content: "โซลูชันคลาวด์ที่แข็งแกร่งเพื่อประมวลผล Microsoft Office, เอกสาร PDF ในแอปพลิเคชันของคุณโดยอัตโนมัติอย่างมีประสิทธิภาพ"

    #  loop
    - icon: "groupdocs_total-apps"
      title: "GroupDocs.Total Online Apps"
      link: "https://products.groupdocs.app"
      content: "เว็บแอปออนไลน์ฟรีเพื่อดูและแก้ไขเนื้อหาเอกสาร เปรียบเทียบและรวม Microsoft Office, OpenOffice, รูปภาพ และรูปแบบไฟล์ยอดนิยมอื่นๆ"    

    #  loop
    - icon: "groupdocs_total-windows"
      title: "GroupDocs.Total Windows"
      link: "https://products.groupdocs.app/total/windows"
      content: "แอปออฟไลน์สำหรับแปลง ใส่คำอธิบายประกอบ เปรียบเทียบ ลงนาม ประกอบ แยกวิเคราะห์ จัดประเภท ตรวจทาน และค้นหาเอกสารบนระบบปฏิบัติการใดๆ"   

---