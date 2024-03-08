---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: fa
product: "Total"
product_tag: "total"
platform: ".NET"
platform_tag: "net"

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
head_title: "کتابخانه اتوماسیون اسناد یکپارچه برای برنامه های NET"
head_description: "GroupDocs.Total for .NET یک مجموعه API اتوماسیون اسناد یکپارچه برای توسعه دهندگان دات نت است که مجموعه ای جامع از ابزارها را برای کار با فرمت های اسناد مختلف از جمله PDF، Word، Excel، Image، HTML، Diagram و غیره ارائه می دهد. ."

############################# Header ##########################
title: "اتوماسیون سند<br> را در برنامه‌های NET خود ساده کنید"
description: "باز کردن قفل خودکار اسناد: تبدیل، مشاهده و مقایسه، ویرایش و امضا بین بیش از 200 فرمت به راحتی."
words:
  for: "for"

actions:
  main: "دانلود رایگان NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Total"
  alt: "صدور مجوز"
  alt_link: "https://purchase.groupdocs.com/pricing/total/net"
  title: "برای شروع آماده اید؟"
  description: "ویژگی های GroupDocs.Total را به صورت رایگان امتحان کنید یا درخواست مجوز کنید"

release:
  title: "نسخه {0} منتشر شد"
  notes: "ببینید چه چیز جدیدی است"
  downloads: "دانلودها"
  link: "https://releases.groupdocs.com/total/net/release-notes/latest/"

code:
  title: "ادغام و مشاهده فایل های Word در سی شارپ"
  more: "نمونه های بیشتر"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-.NET"
  install: "dotnet add package GroupDocs.Total"
  content: |
    ```csharp {style=abap} 
    // فایل منبع DOCX را بارگیری کنید
    using (Merger merger = new Merger("sample1.docx"))
    {
        // یک فایل DOCX دیگر برای ادغام اضافه کنید
        merger.Join("sample2.docx");

        // فایل های DOCX را ادغام کنید و نتیجه را ذخیره کنید
        merger.Save("merged.docx");
    }

    // فایل DOCX ادغام شده را در بیننده بارگیری کنید
    using (var viewer = new Viewer("merged.docx"))
    {
        // گزینه های خروجی HTML را تنظیم کنید، یک فایل در هر صفحه
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // DOCX را با منابع جاسازی شده به HTML ارائه دهید        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total در یک نگاه"
  description: "مشاهده خودکار فایل ها، تبدیل، ویرایش، مقایسه، جستجو، واترمارک و سایر گردش های کاری در برنامه های NET"
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
      content: "GroupDocs.Total برای دات نت سازگاری با بیش از 200 فرمت فایل را باز می کند و به شما امکان می دهد اسناد همه نوع محبوب را پردازش کنید. از فرمت‌های آفیس مانند Word و Excel گرفته تا تصاویر، کدها و فایل‌های رمزگذاری‌شده، ما شما را تحت پوشش قرار داده‌ایم."

    # feature loop
    - title: "پشتیبانی از پلتفرم های مختلف"
      content: "خود را از محدودیت های پلت فرم رها کنید. GroupDocs.Total سازگاری بین پلتفرم را فراهم می کند و به شما این امکان را می دهد که عملکرد بهینه و در دسترس بودن راه حل را برای کاربران در هر سیستمی که .NET می تواند نصب شود ارائه دهید."

############################# Platforms ############################
platforms:
  enable: true
  title: "استقلال سکو"
  description: "GroupDocs.Total برای دات نت از سیستم عامل ها، فریم ورک ها و مدیران بسته های زیر پشتیبانی می کند"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "فرمت های فایل پشتیبانی شده"
  description: |
    GroupDocs.Total برای دات نت از عملیات با فرمت های فایل زیر پشتیبانی می کند [formats](https://docs.groupdocs.com/total/net/supported-document-formats/).
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
  description: "برخی از سناریوهای دنیای واقعی GroupDocs.Total برای استفاده از NET"
  items:
    # code sample loop
    - title: "ایمن و سازماندهی قراردادها: اعمال واترمارک و مدیریت متادیتا در فایل DOCX"
      content: |
        با این مثال کد جامع، اسناد Word خود را به طور موثر محافظت و سازماندهی کنید. نمونه زیر به شما این امکان را می دهد که برای افزایش امنیت و مدیریت اطلاعات، مدیریت واترمارک و ابرداده قوی را در جریان کاری قرارداد خود پیاده سازی کنید. این نشان می دهد که چگونه: <br><br>
        <b>یک واترمارک سفارشی اعمال کنید:</b> برای وضوح بصری و محافظت، یک علامت برجسته پیش نویس قرارداده سند اضافه کنید. سفارشی کردن واترمارک[watermark](https://docs.groupdocs.com/watermark/net/basic-usage/customize/) با گزینه‌های فونت، رنگ، کدورت و تراز. <br><br>
        <b>افزایش متادیتا:</b> به راحتی تغییر متادیتای سند[Word](https://docs.groupdocs.com/metadata/net/working-with-metadata-in-wordprocessing-documents/) تا شامل جزئیات ضروری مانند نویسنده، زمان ایجاد، شرکت، دسته و کلمات کلیدی شود. برای بهبود سازماندهی و قابلیت جستجو
       
        {{< landing/code title="C#">}}
        ```csharp {style=abap}  
        using GroupDocs.Metadata;
        using GroupDocs.Watermark;
        using GroupDocs.Watermark.Common;
        using GroupDocs.Watermark.Watermarks;
        
        // سند خود را در واترمارکر بارگذاری کنید
        using (Watermarker watermarker = new Watermarker("contract.docx"))
        {
            // متن و فونت مورد نظر را برای واترمارک تنظیم کنید
            TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 60, FontStyle.Bold));
            
            // رنگ فونت و کدورت متن، چرخش و ترازها را انتخاب کنید
            watermark.ForegroundColor = Color.DarkGreen;
            watermark.Opacity = 0.5;
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            
            // واترمارک را اعمال کنید
            watermarker.Add(watermark);
            
            // سند حاصل را ذخیره کنید
            watermarker.Save("watermarked-contract.docx");
        }

        using (Metadata metadata = new Metadata("watermarked-contract.docx"))
        {
          var root = metadata.GetRootPackage<WordProcessingRootPackage>();

          // ویژگی های ابرداده سند را به روز کنید
          root.DocumentProperties.Author = "Name Surname";
          root.DocumentProperties.CreatedTime = DateTime.Now;
          root.DocumentProperties.Company = "Company Name";
          root.DocumentProperties.Category = "Work materials";
          root.DocumentProperties.Keywords = "contract, watermarked";

          // سند را با ابرداده به روز ذخیره کنید
          metadata.Save("contract-final.docx");
        }        
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "ویرایش ساده سند"
      content: |
        <b>سناریو:</b> یک شرکت حقوقی بزرگ اغلب اسناد مختلفی را پردازش می کند که حاوی اطلاعات محرمانه مشتری است که باید قبل از به اشتراک گذاشتن با اشخاص ثالث یا برای افشای عمومی ویرایش شوند. ویرایش دستی این اطلاعات حساس می تواند خسته کننده، زمان بر و مستعد خطای انسانی باشد. برای اطمینان از کارایی، دقت و انطباق با مقررات حفاظت از داده ها، شرکت حقوقی به دنبال راه حلی خودکار برای ساده کردن فرآیند ویرایش اسناد است. 
        
        <br>

        <b>راه حل:</b>
        GroupDocs.Total فرآیند را خودکار می کند و پس از دریافت سند، ویرایش را آغاز می کند. علاوه بر این،گزینه‌های انعطاف‌پذیر [redaction](https://docs.groupdocs.com/redaction/net/text-redactions/) با اجازه دادن به شما برای تنظیم قوانین، انتخاب حالت‌های ویرایش (به عنوان مثال، خاموش کردن، جایگزینی با ستاره)، و مشخص کردن، سفارشی‌سازی را تقویت می‌کند. بخش ها یا صفحات خاص برای ویرایش. در نهایت، خروجی کاربرپسند[PDF](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) اسناد ویرایش شده را در قالب PDF برای اشتراک‌گذاری و بررسی آسان تولید می‌کند، در حالی که امنیت و قابلیت ممیزی بهبودیافته تضمین کننده کل است. فرآیند برای انطباق و پاسخگویی مستند شده است. 
        <br><br>
        این راه حل جامع به متخصصان حقوقی و سایر سازمان ها قدرت می دهد تا زمان و هزینه های ویرایش را به میزان قابل توجهی کاهش دهند، خطای انسانی را به حداقل برسانند و به طور مداوم اطلاعات حساس را با اطمینان مدیریت کنند.        
              
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Redaction;
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;

        // سند را با داده های خصوصی در ویرایشگر بارگیری کنید 
        using (Redactor redactor = new Redactor("customer-info.docx"))
        {
          // راه اندازی و سفارشی کردن گزینه های ویرایش 
          redactor.Apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
          // ویرایش ها را اعمال کنید و نتیجه را ذخیره کنید 
          redactor.Save();
        }

        // فایل ویرایش شده را برای بررسی بارگیری کنید 
        using (var viewer = new Viewer("customer-info.docx"))
        {
          // PDF را با فرمت مشاهده دلخواه تنظیم کنید       
          var viewOptions = new PdfViewOptions("redacted-info.pdf");

          // سند را در PDF ذخیره کنید      
          viewer.View(viewOptions);
        }
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