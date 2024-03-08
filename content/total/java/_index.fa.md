---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: fa
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
head_title: "مجموعه اتوماسیون اسناد یکپارچه برای برنامه های جاوا"
head_description: "GroupDocs.Total برای جاوا یک کتابخانه اتوماسیون اسناد جامع است که برای توسعه دهندگان جاوا طراحی شده است و طیف گسترده ای از عملکردها را برای مدیریت فرمت های اسناد مختلف مانند PDF، Word، Excel، Image، HTML، Diagram و غیره ارائه می دهد."

############################# Header ############################
title: "اتوماسیون سند<br> را در پروژه های جاوا خود ساده کنید"
description: "قابلیت‌های اتوماسیون اسناد را افزایش دهید: بیش از 200 فرمت فایل را بدون زحمت تبدیل، مشاهده، مقایسه، ویرایش و امضا کنید."
words:
  for: "for"

actions:
  main: "دانلود رایگان Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-total/"
  alt: "صدور مجوز"
  alt_link: "https://purchase.groupdocs.com/pricing/total/java"
  title: "برای شروع آماده اید؟"
  description: "ویژگی های GroupDocs.Total را به صورت رایگان امتحان کنید یا درخواست مجوز کنید"

release:
  title: "نسخه {0} منتشر شد"
  notes: "ببینید چه چیز جدیدی است"
  downloads: "دانلودها"
  link: "https://releases.groupdocs.com/total/java/release-notes/latest/"

code:
  title: "ادغام و مشاهده فایل های Word در جاوا"
  more: "نمونه های بیشتر"
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
    // فایل منبع DOCX را بارگیری کنید 
    Merger merger = new Merger("sample1.docx");
    
    // یک فایل DOCX دیگر برای ادغام اضافه کنید
    merger.join("sample2.docx");

    // فایل های DOCX را ادغام کنید و نتیجه را ذخیره کنید
    merger.save("merged.docx");
    
    // فایل DOCX ادغام شده را در بیننده بارگیری کنید
    try (Viewer viewer = new Viewer("merged.docx"))
    {
      // گزینه های خروجی HTML را تنظیم کنید، یک فایل در هر صفحه
      HtmlViewOptions viewOptions =   
      HtmlViewOptions.forEmbeddedResources("page{0}.html");
          
      // DOCX را با منابع جاسازی شده به HTML ارائه دهید        
      viewer.view(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total در یک نگاه"
  description: "مشاهده فایل ها، تبدیل، ویرایش، مقایسه، جستجو، واترمارک و سایر گردش های کاری در برنامه های جاوا را به صورت خودکار انجام دهید"
  features:
    # feature loop
    - title: "قدرت چندین محصول GroupDocs را در یک راه حل واحد و جامع ترکیب کنید"
      content: | 
        می توانید از ویژگی های محصولات مختلف GroupDocs برای ایجاد یک رویکرد سفارشی که نیازهای خاص شما را برآورده می کند استفاده کنید.
        <br><br>
        به عنوان مثال، می توانید یک فایل Word را به PDF تبدیل کنید و سپس یک امضای دیجیتال اضافه کنید. یا داده های الگوی سند را از یک پایگاه داده پر کنید، یا متنی را از یک تصویر استخراج کنید و سپس آن را به زبان دیگری ترجمه کنید.
        <br><br>
        امکانات بی پایان هستند!
          
    # feature loop
    - title: "تسلط بر تنوع فرمت های فایل"
      content: "GroupDocs.Total برای جاوا سازگاری با بیش از 200 فرمت فایل را باز می کند و به شما امکان می دهد اسناد از همه نوع محبوب را پردازش کنید. از فرمت‌های آفیس مانند Word و Excel گرفته تا تصاویر، کدها و فایل‌های رمزگذاری‌شده، ما شما را تحت پوشش قرار داده‌ایم."

    # feature loop
    - title: "پشتیبانی از پلتفرم های مختلف"
      content: "خود را از محدودیت های پلت فرم رها کنید. GroupDocs.Total سازگاری بین پلتفرم ها را فراهم می کند و به شما این امکان را می دهد که عملکرد بهینه و در دسترس بودن راه حل را برای کاربران در هر سیستمی که جاوا قابل نصب است ارائه دهید."

############################# Platforms ############################
platforms:
  enable: true
  title: "استقلال سکو"
  description: "GroupDocs.Total برای جاوا از سیستم عامل ها، چارچوب ها و مدیران بسته های زیر پشتیبانی می کند"
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
  title: "فرمت های فایل پشتیبانی شده"
  description: |
    GroupDocs.Total برای جاوا از عملیات با قالب‌های فایل زیر پشتیبانی می‌کند [formats](https://docs.groupdocs.com/total/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### مایکروسافت آفیس، OpenDocument و فرمت های متنی
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
        ### تصاویر، گرافیک و نمودارها
        * **تصاویر شطرنجی:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### دیگر        
        * **وب:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **آرشیوها:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **دیگر:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "ویژگی های GroupDocs.Total"
  description: "PDF و اسناد آفیس را به طور جامع مدیریت، رندر و تبدیل کنید"

  items:
    # feature loop
    - icon: "viewer"
      title: "مشاهده گسترده فایل"
      content: "مشاهده اسناد جامع برای بیش از 180 فرمت، از جمله HTML، تصاویر و PDF."

    # feature loop
    - icon: "conversion"
      title: "تبدیل فرمت"
      content: "تبدیل یکپارچه بین فرمت های اسناد مختلف بدون ابزار خارجی."

    # feature loop
    - icon: "annotation"
      title: "حاشیه نویسی تعاملی"
      content: "قابلیت های حاشیه نویسی پیشرفته برای عناصر متن و تصویر در اسناد."

    # feature loop
    - icon: "comparison"
      title: "مقایسه محتوا"
      content: "مقایسه اسناد دقیق، برجسته کردن تفاوت ها در محتوا و سبک."

    # feature loop
    - icon: "signature"
      title: "انعطاف پذیری امضا"
      content: "گزینه های همه کاره امضا، از جمله متن، تصویر، و امضای دیجیتال."

    # feature loop
    - icon: "assembly"
      title: "ایجاد سند مبتنی بر الگو"
      content: "تولید خودکار اسناد از الگوها و منابع داده خارجی."

    # feature loop
    - icon: "metadata"
      title: "مدیریت فراداده"
      content: "دسترسی قوی به ابرداده و دستکاری برای کنترل پیشرفته سند."

    # feature loop
    - icon: "search"
      title: "جستجوی پیشرفته"
      content: "قابلیت جستجوی قدرتمند با پشتیبانی از الگوریتم های فازی و مترادف."

    # feature loop
    - icon: "watermark"
      title: "کنترل واترمارک"
      content: "مدیریت بدون زحمت واترمارک سند، ارائه ویژگی های سفارشی سازی و استخراج."

############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه کد"
  description: "برخی از سناریوهای دنیای واقعی GroupDocs.Total برای استفاده از جاوا"
  items:
    # code sample loop
    - title: "ایمن و سازماندهی قراردادها: اعمال واترمارک و مدیریت متادیتا در فایل DOCX"
      content: |
        با این مثال کد جامع، اسناد Word خود را به طور موثر محافظت و سازماندهی کنید. نمونه زیر به شما این امکان را می دهد که برای افزایش امنیت و مدیریت اطلاعات، مدیریت واترمارک و ابرداده قوی را در جریان کاری قرارداد خود پیاده سازی کنید. این نشان می دهد که چگونه: <br><br>
        <b>یک واترمارک سفارشی اعمال کنید:</b> رای وضوح بصری و محافظت، یک علامت برجسته پیش نویس قرارداد به سند اضافه کنید. سفارشی کردن واترمارک[watermark](https://docs.groupdocs.com/watermark/java/adding-text-watermarks/) با گزینه‌های فونت، رنگ، کدورت و تراز. <br><br>
        <b>افزایش متادیتا:</b> [metadata](https://docs.groupdocs.com/metadata/java/working-with-metadata-in-word-processing-documents/) تا شامل جزئیات ضروری مانند نویسنده، زمان ایجاد، شرکت، دسته، و کلمات کلیدی برای بهبود سازماندهی و قابلیت جستجو.
       
        {{< landing/code title="Java">}}
        ```java {style=abap}  
        import com.groupdocs.metadata.Metadata;
        import com.groupdocs.watermark.Watermark;
        import com.groupdocs.watermark.Watermark.Common;
        import com.groupdocs.watermark.Options.HtmlViewOptions;
        
        // سند خود را در واترمارکر بارگذاری کنید
        Watermarker watermarker = new Watermarker("contract.docx");
        
        // متن و فونت مورد نظر را برای واترمارک تنظیم کنید
        TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 36));
          
        // رنگ فونت و کدورت متن، چرخش و ترازها را انتخاب کنید
        watermark.setForegroundColor(Color.getRed());                                                            
        watermark.setHorizontalAlignment(HorizontalAlignment.Center);                                            
        watermark.setVerticalAlignment(VerticalAlignment.Center);                               

        // واترمارک را اعمال کنید
        watermarker.add(watermark);
        
        // سند حاصل را ذخیره کنید
        watermarker.save("watermarked-contract.docx");
        
        Metadata metadata = new Metadata("watermarked-contract.docx");        
        WordProcessingRootPackage root = metadata.getRootPackageGeneric();

        // ویژگی های ابرداده سند را به روز کنید
        root.getDocumentProperties().setAuthor("Name Surname");
        root.getDocumentProperties().setCreatedTime(new Date());
        root.getDocumentProperties().setCompany("Company Name");
        root.getDocumentProperties().setCategory("Work materials");
        root.getDocumentProperties().setKeywords("contract, watermarked");

        // سند را با ابرداده به روز ذخیره کنید
        metadata.save("contract-final.docx");                
        ```
        {{< /landing/code >}}

    # code sample loop
    - title: "ویرایش ساده سند"
      content: |
        <b>سناریو:</b> یک شرکت حقوقی بزرگ اغلب اسناد مختلفی را پردازش می کند که حاوی اطلاعات محرمانه مشتری است که باید قبل از به اشتراک گذاشتن با اشخاص ثالث یا برای افشای عمومی ویرایش شوند. ویرایش دستی این اطلاعات حساس می تواند خسته کننده، زمان بر و مستعد خطای انسانی باشد. برای اطمینان از کارایی، دقت و انطباق با مقررات حفاظت از داده ها، شرکت حقوقی به دنبال راه حلی خودکار برای ساده کردن فرآیند ویرایش اسناد است. 
        
        <br>

        <b>راه حل:</b>
        GroupDocs.Total فرآیند را خودکار می کند و پس از دریافت سند، ویرایش را آغاز می کند. علاوه بر این، گزینه‌های انعطاف‌پذیر [redaction](https://docs.groupdocs.com/redaction/java/text-redactions/)  [pdf](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) اسناد ویرایش شده را در قالب PDF برای اشتراک‌گذاری و بررسی آسان تولید می‌کند، در حالی که امنیت و قابلیت ممیزی بهبودیافته تضمین کننده کل است. فرآیند برای انطباق و پاسخگویی مستند شده است. 
        <br><br>
        این راه حل جامع به متخصصان حقوقی و سایر سازمان ها قدرت می دهد تا زمان و هزینه های ویرایش را به میزان قابل توجهی کاهش دهند، خطای انسانی را به حداقل برسانند و به طور مداوم اطلاعات حساس را با اطمینان مدیریت کنند.        
              
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.redaction.Redaction;
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // سند را با داده های خصوصی در ویرایشگر بارگیری کنید 
        Redactor redactor = new Redactor("customer-info.docx");
        
        // راه اندازی و سفارشی کردن گزینه های ویرایش 
        redactor.apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
        
        // ویرایش ها را اعمال کنید و نتیجه را ذخیره کنید 
        redactor.save();

        // فایل ویرایش شده را برای بررسی بارگیری کنید 
        Viewer viewer = new Viewer("customer-info.docx");
        
        // PDF را با فرمت مشاهده دلخواه تنظیم کنید       
        PdfViewOptions viewOptions = new PdfViewOptions("redacted-info.pdf");

        // سند را در PDF ذخیره کنید      
        viewer.view(viewOptions);        
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "بررسی محصولات GroupDocs"
# description: "فقط حرف ما را قبول نکنید. ببینید سایر توسعه دهندگان در مورد API های ما چه می گویند"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "خدمات عالی و محصولات عالی. آنها در طول فرآیند اجرای GroupDocs.Viewer برای دات نت بسیار مفید و پاسخگو بودند، نمی توان آنها را به اندازه کافی توصیه کرد."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "پس از پیاده سازی و استفاده از GroupDocs.Viewer برای جاوا در پروژه، به نظر می رسد که بسیار خوب کار می کند. من با مدارک زیادی تست کردم و تا الان خیلی خوبه. هر چیزی که به آن پرتاب کرده‌ام به خوبی رندر می‌شود و به همان خوبی در یک نمایشگر PDF یا MS Word به نظر می‌رسد."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---