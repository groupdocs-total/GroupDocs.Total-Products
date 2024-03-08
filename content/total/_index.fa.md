---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Total"
product_tag: "total"

############################# Head ############################
head_title: "APIهای اتوماسیون اسناد | در مورد APIهای Premise و خدمات آنلاین"
head_description: "دستکاری اسناد خود را به راحتی و رایگان انجام دهید"

############################# Header ##########################
title: "اتوماسیون اسناد اصلی با مجموعه همه کاره"
description: |
  کارهای تکراری سند را ساده کنید و گردش کار خود را تنها با چند خط کد ساده کنید. APIهای قدرتمند، ادغام را بدون دردسر می کنند و به شما قدرت می دهند تا بر نوآوری تمرکز کنید، نه زیرساخت.

  تبدیل، امضا، مشاهده، حاشیه نویسی - هر کار سندی را با حداقل کد غلبه کنید. از Word گرفته تا PDF، Excel گرفته تا تصاویر، همه چیز را یکپارچه مدیریت کنید. کد کمتر، تاثیر بیشتر.

  کارهای سند را خودکار کنید، کارایی را افزایش دهید و با یکپارچه سازی با سرعت رعد و برق سریع حرکت کنید. صرفه جویی در زمان و منابع، تمرکز بر آنچه واقعا برای کسب و کار شما مهم است.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "پلتفرم خود را انتخاب کنید"
  title: "پلتفرم های پشتیبانی شده"
  description: "کتابخانه GroupDocs.Total از سیستم عامل ها و چارچوب های زیر پشتیبانی می کند"
  details_link_title: "بیشتر بدانید"
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
        - content: "بیش از 200 فرمت فایل"
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
        - content: "بیش از 200 فرمت فایل"
          rows: "1"
        # features loop
        - content:  "Eclipse <br> NetBeans <br> IntelliJ Idea"
          rows: "3"

############################# Features ############################

features:
  enable: true
  title: "مجموعه ویژگی های GroupDocs.Total"
  description: "راه حل واحدی که عملکرد همه محصولات GroupDocs را زیر یک سقف یکپارچه می کند و هر کار سندی را بدون نرم افزار شخص ثالث مدیریت می کند."

  items:
    # feature loop
    - icon: "view"
      title: "مشاهده اسناد و تصاویر"
      content: "فایل ها را برای مشاهده آنها در فرمت های HTML، PDF، PNG و JPEG رندر کنید."

    # feature loop
    - icon: "convert"
      title: "تبدیل بین فرمت ها"
      content: "تبدیل فایل ها از منابع مختلف به فرمت های هدف مختلف."

    # feature loop
    - icon: "merge"
      title: "ادغام چندین فایل در یک"
      content: "به طور یکپارچه چندین PDF، Office و موارد دیگر را در یک سند واحد ترکیب کنید."
    
    # feature loop
    - icon: "settings"
      title: "محصولات و ویژگی های بیشتر"
      content: "تمام مجموعه APIهای اتوماسیون اسناد GroupDocs را کاوش کنید: مقایسه، آواز الکترونیکی، جستجو، واترمارک و موارد دیگر!"


############################# Code samples ############################
# code_samples:
#   enable: true
#   title: "نمونه های کد GroupDocs.Total"
#   description: "برخی از موارد از عملیات معمولی GroupDocs.Total در C#، Java، TypeScript استفاده می کنند"
#   items:
#     # code sample loop
#     - title: "نحوه رندر فایل های DOCX به PDF"
#       content: |
#        اسناد DOCX را بدون نصب Microsoft Word یا سایر نرم افزارها به PDF ارائه دهید. به راحتی فایل های DOCX را در برنامه خود بارگیری و مشاهده کنید، چه یک برنامه وب یا دسکتاپ. در اینجا مثالی از نحوه ارائه یک فایل DOCX به PDF آورده شده است:
#       samples:
#         - language: "C#"
#           color: "blue"
#           content: |
#             ```csharp {style=abap}   
#             // فایل DOCX را برای رندر بارگیری کنید
#             using (Viewer viewer = new Viewer("sample.docx"))
#             {
#               // DOCX را به یک فایل PDF رندر کنید
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
#             // فایل DOCX را برای رندر بارگیری کنید
#             try (Viewer viewer = new Viewer("sample.docx")) {
#                 // DOCX را به یک فایل PDF رندر کنید
#                 PdfViewOptions viewOptions = new PdfViewOptions();
#                 viewer.view(viewOptions);
#             }
#             ```
#         - language: "TypeScript"
#           color: "green"
#           content: |
#             ```javascript {style=abap}  
#             // فایل DOCX را برای رندر بارگیری کنید
#             const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
#             // DOCX را به یک فایل PDF رندر کنید
#             const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
#             viewer.view(viewOptions)
#             ```


############################# Formats ############################
formats:
  enable: true
  title:  "بیش از 200 فرمت فایل پشتیبانی می شود"
  description: "GroupDocs.Total از عملیات با محبوب ترین پشتیبانی می کند [formats](https://docs.groupdocs.com/total/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "معیارهای عمیق و بینش آماری"
  description: "در تجزیه و تحلیل دقیق ارقام کلیدی ما غوطه ور شوید و معیارهای جامع و بینش آماری را در مورد دستاوردها، تأثیر و رشد ما ارائه دهید."

  items:
    # metrics loop
    - number: "200+"
      title: "فرمت های پشتیبانی شده"
      content: "به راحتی بیش از 200 فرمت فایل از جمله اسناد، تصاویر و نقشه های CAD را بدون دردسر مشاهده کنید. با راه حل جامع مشاهده ما موانع سازگاری را بشکنید و بدون زحمت به فایل های مختلف دسترسی پیدا کنید."
    # metrics loop
    - number: "550K"
      title: "دانلودهای NuGet"
      content: "راه حل بسته NuGet ما به یک منبع قابل اعتماد و پذیرفته شده در جامعه توسعه دهندگان تبدیل شده است که یکپارچه سازی یکپارچه و عملکرد ارزشمند را برای پروژه های بی شماری فراهم می کند."

    # metrics loop
    - number: "10+"
      title: "کتابخانه ها"
      content: "محصول ما شامل بیش از 10 کتابخانه است که ویژگی های پیشرفته ای را برای بهینه سازی عملکرد ارائه می دهد. این کتابخانه ها برای برآوردن نیازهای مختلف توسعه با قابلیت های بی نظیر طراحی شده اند."
    
    # metrics loop
    - number: "100+"
      title: "مشتریان خوشحال"
      content: "ارائه خدمات به نمادین ترین مارک ها در سراسر جهان. کشف کنید که چرا صدها نفر GroupDocs.Total را دوست دارند! ناوبری بدون درز، همکاری راحت و سهولت استفاده بی نظیر را کاوش کنید. همین الان ملحق شوید، همین الان بپیوندید!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "مشتریان خوشحال ما"
  description: "کتابخانه های GroupDocs توسط برندهای مشهور و برجسته جهانی در سراسر جهان به کار گرفته می شوند."

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
  title: "برای شروع آماده اید؟"
  description: "ویژگی های GroupDocs.Total را به صورت رایگان امتحان کنید یا درخواست مجوز کنید"

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
  title: "سوالات و نگرانی های رایج"
  description: "پاسخ سوالات متداول را در بخش سوالات متداول ما بیابید تا به سرعت سوالات و نگرانی های خود را برطرف کنید."

  items:
    #  loop
    - question: "GroupDocs.Total چیست و چه تفاوتی با سایر محصولات GroupDocs دارد؟"
      answer: |
        GroupDocs.Total یک مجموعه جامع است که عملکردهای همه محصولات GroupDocs را در یک بسته واحد ترکیب می کند. این چندین مزیت را ارائه می دهد: <br><br>
        <ul>
          <li>
            <b>ویژگی های یکپارچه:</b> شما به تمام قابلیت‌های پردازش سند، از جمله مشاهده، تبدیل، ادغام، حاشیه‌نویسی، امضا و موارد دیگر در یک API دسترسی دارید. <br><br>
          </li>
          <li>
            <b>سازگاری پیشرفته:</b> GroupDocs.Total عملکرد سازگار و قابل اعتماد را در تمام قالب‌ها و پلتفرم‌های فایل پشتیبانی‌شده تضمین می‌کند و مشکلات سازگاری را که ممکن است هنگام استفاده از محصولات جداگانه ایجاد شود، حذف می‌کند. <br><br>
          </li>
          <li>
            <b>اندازه های بسته بندی بهینه شده:</b> این مجموعه به‌عنوان یک بسته فشرده و منفرد ارائه می‌شود که مصرف منابع را کاهش می‌دهد و ادغام با برنامه‌های شما را در مقایسه با استفاده از محصولات جداگانه با نصب‌های جداگانه ساده‌تر می‌کند.
          </li>
        <ul>

    #  loop
    - question: "چرا باید GroupDocs.Total را به جای خرید تک تک محصولات GroupDocs ترجیح داد؟"
      answer: |
        خرید یک مجوز GroupDocs.Total معمولاً کمتر از خرید مجوز برای دو یا چند محصول جداگانه GroupDocs هزینه دارد. <br>
        این به چندین مزیت کلیدی برای شما ترجمه می شود: <br><br>
        <b>صرفه جویی در هزینه:</b> GroupDocs.Total در مقایسه با خرید محصولات جداگانه، تخفیف قابل توجهی ارائه می دهد و به شما امکان می دهد بودجه خود را بیشتر افزایش دهید. <br><br>
        <b>مدیریت ساده شده:</b> با GroupDocs.Total، همه چیز را تحت یک مجوز مدیریت می‌کنید و نیازی به پیگیری و نگهداری چندین مجوز برای محصولات مختلف را از بین می‌برید. این کار وظایف اداری شما را ساده می کند و هزینه های کلی را کاهش می دهد. <br><br>
        اگر به دنبال راه حلی مقرون به صرفه و با ویژگی های غنی برای نیازهای مدیریت اسناد خود هستید، GroupDocs.Total انتخاب مناسبی است.

    #  loop
    - question: "چگونه می توانم با GroupDocs.Total شروع کنم؟"
      answer: |
        می توانید با یک آزمایش رایگان شروع کنید تا ویژگی ها را بررسی کنید و ببینید که آیا نیازهای شما را برآورده می کند یا خیر. GroupDocs همچنین منابع [documentation](https://docs.groupdocs.com/total/) وآموزش‌های[tutorials](https://groupdocs.github.io) مختلفی را برای کمک به شما برای شروع یکپارچه‌سازی و توسعه ارائه می‌کند.
        
    #  loop
    - question: "آیا GroupDocs.Total پشتیبانی فنی ارائه می دهد؟"
      answer: |
        بله، GroupDocs پشتیبانی فنی جامعی را برای اطمینان از موفقیت شما با GroupDocs.Total ارائه می دهد. آنها دو گزینه دارند: <br><br>
        <b>[تالار گفتمان پشتیبانی رایگان](https://forum.groupdocs.com):</b> این انجمن به شما امکان می دهد با کارکنان GroupDocs ارتباط برقرار کنید، آنها می توانند به سؤالات شما پاسخ دهند و بر اساس تجربه خود راه حل ارائه دهند. این یک منبع عالی برای مسائل رایج و سوالات عمومی است. <br><br>
        <b>[پشتیبانی پشتیبانی پولی](https://helpdesk.groupdocs.com):</b> این گزینه پشتیبانی را بر اساس اولویت ارائه می دهد. اگر با مسائل پیچیده‌ای مواجه شدید یا به حل‌های سریع‌تر نیاز دارید، پشتیبانی پولی کمک شخصی و زمان‌های پاسخ سریع‌تر را ارائه می‌دهد. <br><br>
        با ارائه گزینه‌های رایگان و پولی، GroupDocs نیازها و بودجه‌های مختلف را برآورده می‌کند و تضمین می‌کند که از پشتیبانی لازم برای پیشرفت با GroupDocs.Total برخوردار هستید.

    #  loop
    - question: "آیا GroupDocs.Total به نرم افزار اضافی برای دستکاری سند نیاز دارد؟"
      answer: |
        GroupDocs.Total یک مجموعه مستقل است و برای کارهای اساسی دستکاری سند مانند مشاهده، تبدیل، حاشیه نویسی یا امضا نیازی به نرم افزار شخص ثالث اضافی ندارد. با این حال، بسته به ویژگی های خاصی که استفاده می کنید (به عنوان مثال، OCR برای اسناد اسکن شده)، ممکن است به کتابخانه های خارجی نیاز باشد.

############################# Cloud and Apps ############################

cloud_links:
  enable: true
  title: "GroupDocs.Total راه حل"
  description: "با Cloud REST API و برنامه‌های آنلاین رایگان، پردازش اسناد را در برنامه‌های خود افزایش دهید"

  items:
    #  loop
    - icon: "groupdocs_total-cloud"
      title: "GroupDocs.Total Cloud"
      link: "https://products.groupdocs.cloud/total"
      content: "راه حل های ابری قوی برای خودکارسازی کارآمد پردازش مایکروسافت آفیس، سند PDF در برنامه های شما."

    #  loop
    - icon: "groupdocs_total-apps"
      title: "GroupDocs.Total Online Apps"
      link: "https://products.groupdocs.app"
      content: "برنامه های وب آنلاین رایگان برای مشاهده و ویرایش محتوای اسناد، مقایسه و ادغام مختلف Microsoft Office، OpenOffice، تصاویر و سایر فرمت های فایل محبوب."    

    #  loop
    - icon: "groupdocs_total-windows"
      title: "GroupDocs.Total Windows"
      link: "https://products.groupdocs.app/total/windows"
      content: "برنامه های آفلاین برای تبدیل، حاشیه نویسی، مقایسه، امضا، جمع آوری، تجزیه، طبقه بندی، ویرایش و جستجوی اسناد در هر سیستم عامل."   

---