---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: uk
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
head_title: "Все в одній бібліотеці для автоматизації документів для .NET-додатків"
head_description: "GroupDocs.Total для .NET - це комплексний набір API для автоматизації документів для розробників .NET, що надає повний набір інструментів для роботи з різними форматами документів, включаючи PDF, Word, Excel, зображення, HTML, діаграми та багато іншого."

############################# Header ##########################
title: "Оптимізуйте автоматизацію документів<br> у ваших програмах на .NET"
description: "Налаштуйте автоматизацію документів: конвертуйте, переглядайте, порівнюйте, редагуйте та підписуйте файли більш ніж у 200 форматах легко."
words:
  for: "for"

actions:
  main: "Завантажити безкоштовно з NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Total"
  alt: "Ліцензування"
  alt_link: "https://purchase.groupdocs.com/pricing/total/net"
  title: "Готові розпочати?"
  description: "Спробуйте функції GroupDocs.Total безкоштовно або запросіть ліцензію"

release:
  title: "Версія {0}&nbsp;випущена"
  notes: "Дивіться, що нового"
  downloads: "Завантаження"
  link: "https://releases.groupdocs.com/total/net/release-notes/latest/"

code:
  title: "Об'єднання та перегляд файлів Word у C#"
  more: "Ще більше прикладів"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-.NET"
  install: "dotnet add package GroupDocs.Total"
  content: |
    ```csharp {style=abap} 
    // Завантажте вихідний файл DOCX
    using (Merger merger = new Merger("sample1.docx"))
    {
        // Додайте ще один файл DOCX для об'єднання
        merger.Join("sample2.docx");

        // Об'єднайте файли DOCX та збережіть результат
        merger.Save("merged.docx");
    }

    // Завантажте об'єднаний файл DOCX у вьювер
    using (var viewer = new Viewer("merged.docx"))
    {
        // Встановіть параметри виведення HTML, один файл на сторінку
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Перетворіть DOCX у HTML з вбудованими ресурсами        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Огляд GroupDocs.Total"
  description: "Автоматизуйте перегляд файлів, конвертування, редагування, порівняння, пошук, нанесення водяного знака та інші робочі процеси у програмах .NET"
  features:
    # feature loop
    - title: "Поєднайте силу кількох продуктів GroupDocs у єдине, комплексне рішення"
      content: | 
        Ви можете використовувати можливості різних продуктів GroupDocs для створення індивідуального підходу, який відповідає вашим конкретним потребам.
        <br><br>
        Наприклад, ви можете конвертувати файл Word у PDF, а потім додати цифровий підпис. Або заповнити шаблон документа даними з бази даних, або витягнути текст із зображення та перекласти його на іншу мову.
        <br><br>
        Можливості безмежні!
          
    # feature loop
    - title: "Майстер різноманітності форматів файлів"
      content: "GroupDocs.Total для .NET розблоковує сумісність з понад 200 форматами файлів, дозволяючи вам обробляти документи всіх популярних типів. Від офісних форматів, таких як Word та Excel, до зображень, коду та зашифрованих файлів - ми підтримуємо все."

    # feature loop
    - title: "Підтримка крос-платформеності"
      content: "Звільніть себе від обмежень платформи. GroupDocs.Total надає сумісність з різними платформами, що дозволяє вам забезпечити оптимальну продуктивність та доступність рішень для користувачів на будь-якій системі, де може бути встановлено .NET."

############################# Platforms ############################
platforms:
  enable: true
  title: "Незалежність від платформи"
  description: "GroupDocs.Total для .NET підтримує такі операційні системи, фреймворки та менеджери пакетів"
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
  title: "Підтримувані формати файлів"
  description: |
    GroupDocs.Total для .NET підтримує операції з такими [форматами файлів](https://docs.groupdocs.com/total/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Формати Microsoft Office, OpenDocument та текстові
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
        ### Зображення, графіка та діаграми
        * **Растрові зображення:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Інші        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Архіви:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Інші:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Функції GroupDocs.Total"
  description: "Комплексне керування, відображення та конвертація PDF-файлів та документів Office"

  items:
    # feature loop
    - icon: "viewer"
      title: "Широкі можливості перегляду файлів"
      content: "Комплексний перегляд документів більш ніж у 180 форматах, включаючи HTML, зображення та PDF."

    # feature loop
    - icon: "conversion"
      title: "Конвертація формату"
      content: "Безперервна конвертація між різними форматами документів без зовнішніх інструментів."

    # feature loop
    - icon: "annotation"
      title: "Інтерактивні анотації"
      content: "Розширені можливості анотації текстових та зображеннєвих елементів у документах."

    # feature loop
    - icon: "comparison"
      title: "Порівняння вмісту"
      content: "Точне порівняння документів, виділяючи відмінності в змісті та стилі."

    # feature loop
    - icon: "signature"
      title: "Гнучкість підпису"
      content: "Різноманітні опції підпису, включаючи текстовий, зображеннєвий та цифровий підписи."

    # feature loop
    - icon: "assembly"
      title: "Створення документів на основі шаблонів"
      content: "Автоматизоване створення документів за допомогою шаблонів та зовнішніх джерел даних."

    # feature loop
    - icon: "metadata"
      title: "Керування метаданими"
      content: "Надійний доступ до метаданих та їх маніпулювання для покращеного контролю над документами."

    # feature loop
    - icon: "search"
      title: "Розширений пошук"
      content: "Потужна функціональність пошуку з підтримкою нечіткості та синонімів."

    # feature loop
    - icon: "watermark"
      title: "Керування водяним знаком"
      content: "Легке керування водяним знаком у документах з можливістю налаштування та екстракції."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Приклади коду"
  description: "Деякі реальні сценарії використання GroupDocs.Total для .NET"
  items:
    # code sample loop
    - title: "Захищення та організація контрактів: Застосовувати водяні знаки та керувати метаданими у файлі DOCX"
      content: |
        Ефективно захистіть та організуйте ваші документи Word за допомогою цього комплексного прикладу коду. Наведений нижче приклад дозволяє вам впровадити міцне водяне знакування та керування метаданими в рамках вашого робочого процесу з контрактами для поліпшення безпеки та управління інформацією. Він показує, як: <br><br>
        <b>Застосування власного водяного знаку:</b> Додайте визначний водяний знак 'Contract Draft' до документа для візуальної ясності та захисту. [Налаштуйте водяний знак](https://docs.groupdocs.com/watermark/net/basic-usage/customize/) з опціями шрифту, кольору, прозорості та вирівнювання. <br><br>
        <b>Поліпшення метаданих:</b> Легко [змінюйте метадані документа](https://docs.groupdocs.com/metadata/net/working-with-metadata-in-wordprocessing-documents/), щоб додати важливі деталі, такі як автор, час створення, компанія, категорія та ключові слова для покращеного управління та пошукової доступності.
       
        {{< landing/code title="C#">}}
        ```csharp {style=abap}  
        using GroupDocs.Metadata;
        using GroupDocs.Watermark;
        using GroupDocs.Watermark.Common;
        using GroupDocs.Watermark.Watermarks;
        
        // Завантажте ваш документ до водяного знакувальника
        using (Watermarker watermarker = new Watermarker("contract.docx"))
        {
            // Встановіть бажаний текст та шрифт для водяного знаку
            TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 60, FontStyle.Bold));
            
            // Виберіть колір шрифту та прозорість тексту, обертання та вирівнювання
            watermark.ForegroundColor = Color.DarkGreen;
            watermark.Opacity = 0.5;
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            
            // Застосуйте водяний знак
            watermarker.Add(watermark);
            
            // Збережіть отриманий документ
            watermarker.Save("watermarked-contract.docx");
        }

        using (Metadata metadata = new Metadata("watermarked-contract.docx"))
        {
          var root = metadata.GetRootPackage<WordProcessingRootPackage>();

          // Оновіть властивості метаданих документа
          root.DocumentProperties.Author = "Name Surname";
          root.DocumentProperties.CreatedTime = DateTime.Now;
          root.DocumentProperties.Company = "Company Name";
          root.DocumentProperties.Category = "Work materials";
          root.DocumentProperties.Keywords = "contract, watermarked";

          // Збережіть документ із оновленими метаданими
          metadata.Save("contract-final.docx");
        }        
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Оптимізоване редактування документів"
      content: |
        <b>Сценарій:</b> Велика юридична фірма часто обробляє різноманітні документи, що містять конфіденційну інформацію клієнтів, яку необхідно видаляти перед наданням третім сторонам або для загального розголошення. Ручне видалення цієї конфіденційної інформації може бути нудним, затратним за часом і схильним до людських помилок. Для забезпечення ефективності, точності та відповідності з правилами захисту даних юридична фірма шукає автоматизоване рішення для оптимізації процесу редактування документів. 
        
        <br>

        <b>Рішення:</b>
        GroupDocs.Total автоматизує процес, спрацьовуючи на отримання документа. Крім того, [гнучкі опції](https://docs.groupdocs.com/redaction/net/text-redactions/) надають можливість налаштування, дозволяючи встановлювати правила, вибирати режими видалення (наприклад, чорне видалення, заміна зірочками) та вказувати певні розділи або сторінки для видалення. Нарешті, [користувацький вихід](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) генерує видалені документи у форматі PDF для легкого обміну та перегляду, тоді як покращена безпека та аудитабельність забезпечують документацію всього процесу з метою відповідності та відповідальності. 
        <br><br>
        Це комплексне рішення дозволяє юристам та іншим організаціям значно зменшити час та витрати на видалення, мінімізувати людські помилки та постійно обробляти конфіденційну інформацію з впевненістю.        
              
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Redaction;
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;

        // Завантажте документ із приватними даними до редактора 
        using (Redactor redactor = new Redactor("customer-info.docx"))
        {
          // Налаштуйте та налаштуйте параметри видалення 
          redactor.Apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
          // Застосуйте видалення та збережіть результат 
          redactor.Save();
        }

        // Завантажте видалений файл для перегляду 
        using (var viewer = new Viewer("customer-info.docx"))
        {
          // Налаштуйте PDF як бажаний формат перегляду       
          var viewOptions = new PdfViewOptions("redacted-info.pdf");

          // Збережіть документ у форматі PDF      
          viewer.View(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Відгуки про продукти GroupDocs"
# description: "Не просто вірте на слово. Подивіться, що кажуть інші розробники про наші API"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Чудовий сервіс і відмінні продукти. Вони були дуже корисні та оперативні під час процесу впровадження GroupDocs.Viewer для .NET, не можу висловити їм достатньо високої оцінки."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Після впровадження та використання GroupDocs.Viewer для Java у проекті виглядає, що все працює дуже добре. Я протестував з багатьма документами, і досі все працює гарно. Все, що я випробував, відображається красиво та виглядає так само добре, як і в переглядачі PDF або MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---