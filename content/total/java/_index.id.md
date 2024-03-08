---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: id
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
head_title: "Rangkaian otomatisasi dokumen lengkap untuk aplikasi Java"
head_description: "GroupDocs.Total untuk Java adalah pustaka otomatisasi dokumen komprehensif yang dirancang untuk pengembang Java, menawarkan beragam fungsi untuk menangani beragam format dokumen seperti PDF, Word, Excel, Gambar, HTML, Diagram, dan banyak lagi."

############################# Header ############################
title: "Sederhanakan otomatisasi dokumen<br> dalam proyek Java Anda"
description: "Tingkatkan kemampuan otomatisasi dokumen: dengan mudah mengonversi, melihat, membandingkan, mengedit, dan menandatangani lebih dari 200 format file dengan mudah."
words:
  for: "for"

actions:
  main: "Unduhan Maven Gratis"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-total/"
  alt: "Perizinan"
  alt_link: "https://purchase.groupdocs.com/pricing/total/java"
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Total secara gratis atau minta lisensi"

release:
  title: "Versi {0} dirilis"
  notes: "Lihat apa yang baru"
  downloads: "Unduhan"
  link: "https://releases.groupdocs.com/total/java/release-notes/latest/"

code:
  title: "Gabungkan dan lihat file Word di Java"
  more: "Lebih banyak contoh"
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
    // Muat file DOCX sumber 
    Merger merger = new Merger("sample1.docx");
    
    // Tambahkan file DOCX lain untuk digabungkan
    merger.join("sample2.docx");

    // Gabungkan file DOCX dan simpan hasilnya
    merger.save("merged.docx");
    
    // Muat file DOCX yang digabungkan ke dalam penampil
    try (Viewer viewer = new Viewer("merged.docx"))
    {
      // Tetapkan opsi HTML keluaran, satu file per halaman
      HtmlViewOptions viewOptions =   
      HtmlViewOptions.forEmbeddedResources("page{0}.html");
          
      // Render DOCX ke HTML dengan sumber daya tertanam        
      viewer.view(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Sekilas tentang GroupDocs.Total"
  description: "Mengotomatiskan tampilan file, mengonversi, mengedit, membandingkan, mencari, memberi tanda air, dan alur kerja lainnya dalam aplikasi Java"
  features:
    # feature loop
    - title: "Gabungkan kekuatan beberapa produk GroupDocs menjadi satu solusi komprehensif"
      content: | 
        Anda dapat menggunakan fitur produk GroupDocs yang berbeda untuk menciptakan pendekatan khusus yang memenuhi kebutuhan spesifik Anda.
        <br><br>
        Misalnya, Anda dapat mengonversi file Word ke PDF lalu menambahkan tanda tangan digital. Atau mengisi data templat dokumen dari database, atau mengekstrak teks dari gambar lalu menerjemahkannya ke bahasa lain.
        <br><br>
        Kemungkinannya tidak terbatas!
          
    # feature loop
    - title: "Kuasai keragaman format file"
      content: "GroupDocs.Total untuk Java membuka kompatibilitas dengan lebih dari 200 format file, memberdayakan Anda untuk memproses semua jenis dokumen populer. Dari format perkantoran seperti Word dan Excel hingga gambar, kode, dan file terenkripsi, kami siap membantu Anda."

    # feature loop
    - title: "Dukungan lintas platform"
      content: "Bebaskan diri Anda dari batasan platform. GroupDocs.Total menyediakan kompatibilitas lintas platform, memungkinkan Anda memberikan kinerja optimal dan ketersediaan solusi kepada pengguna di sistem mana pun di mana Java dapat diinstal."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independensi platform"
  description: "GroupDocs.Total untuk Java mendukung sistem operasi, kerangka kerja, dan manajer paket berikut"
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
  title: "Format file yang didukung"
  description: |
    GroupDocs.Total untuk Java mendukung operasi dengan berikut [format file](https://docs.groupdocs.com/total/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument dan format teks
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
        ### Gambar, Grafik & Diagram
        * **Gambar raster:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Lainnya        
        * **jaring:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Arsip:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Lainnya:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Total fitur"
  description: "Kelola, render, dan konversi PDF dan Dokumen Office secara komprehensif"

  items:
    # feature loop
    - icon: "viewer"
      title: "Melihat File Secara Luas"
      content: "Tampilan dokumen komprehensif untuk lebih dari 180 format, termasuk HTML, gambar, dan PDF."

    # feature loop
    - icon: "conversion"
      title: "Konversi Format"
      content: "Konversi mulus antara berbagai format dokumen tanpa alat eksternal."

    # feature loop
    - icon: "annotation"
      title: "Anotasi Interaktif"
      content: "Kemampuan anotasi tingkat lanjut untuk elemen teks dan gambar dalam dokumen."

    # feature loop
    - icon: "comparison"
      title: "Perbandingan Konten"
      content: "Perbandingan dokumen yang tepat, menyoroti perbedaan konten dan gaya."

    # feature loop
    - icon: "signature"
      title: "Fleksibilitas Tanda Tangan"
      content: "Opsi tanda tangan serbaguna, termasuk teks, gambar, dan tanda tangan digital."

    # feature loop
    - icon: "assembly"
      title: "Pembuatan Dokumen Berbasis Template"
      content: "Pembuatan dokumen otomatis dari templat dan sumber data eksternal."

    # feature loop
    - icon: "metadata"
      title: "Manajemen Metadata"
      content: "Akses dan manipulasi metadata yang kuat untuk meningkatkan kontrol dokumen."

    # feature loop
    - icon: "search"
      title: "Pencarian Lanjutan"
      content: "Fungsionalitas pencarian yang kuat dengan dukungan untuk algoritma fuzzy dan sinonim."

    # feature loop
    - icon: "watermark"
      title: "Kontrol Tanda Air"
      content: "Manajemen tanda air dokumen yang mudah, menawarkan fitur penyesuaian dan ekstraksi."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Contoh kode"
  description: "Beberapa skenario GroupDocs.Total dunia nyata untuk penggunaan Java"
  items:
    # code sample loop
    - title: "Amankan dan atur kontrak: Terapkan tanda air dan kelola metadata dalam file DOCX"
      content: |
        Lindungi dan atur dokumen Word Anda secara efisien dengan contoh kode komprehensif ini. Contoh di bawah ini memberdayakan Anda untuk menerapkan manajemen watermarking dan metadata yang kuat dalam alur kerja kontrak Anda untuk meningkatkan keamanan dan manajemen informasi. Ini menunjukkan cara: <br><br>
        <b>Terapkan Tanda Air Khusus:</b> Tambahkan tanda air 'Draf Kontrak' yang menonjol ke dokumen untuk kejelasan dan perlindungan visual. [Sesuaikan tanda air](https://docs.groupdocs.com/watermark/java/adding-text-watermarks/) dengan opsi font, warna, opacity, dan perataan. <br><br>
        <b>Tingkatkan Metadata:</b> [Ubah metadata dokumen dengan mudah](https://docs.groupdocs.com/metadata/java/working-with-metadata-in-word-processing-documents/) untuk menyertakan detail penting seperti penulis, waktu pembuatan, perusahaan, kategori, dan kata kunci untuk meningkatkan pengorganisasian dan kemudahan pencarian.
       
        {{< landing/code title="Java">}}
        ```java {style=abap}  
        import com.groupdocs.metadata.Metadata;
        import com.groupdocs.watermark.Watermark;
        import com.groupdocs.watermark.Watermark.Common;
        import com.groupdocs.watermark.Options.HtmlViewOptions;
        
        // Muat dokumen Anda ke dalam tanda air
        Watermarker watermarker = new Watermarker("contract.docx");
        
        // Atur teks dan font yang diinginkan untuk tanda air
        TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 36));
          
        // Pilih warna font dan opacity teks, rotasi dan perataan
        watermark.setForegroundColor(Color.getRed());                                                            
        watermark.setHorizontalAlignment(HorizontalAlignment.Center);                                            
        watermark.setVerticalAlignment(VerticalAlignment.Center);                               

        // Terapkan tanda air
        watermarker.add(watermark);
        
        // Simpan dokumen yang dihasilkan
        watermarker.save("watermarked-contract.docx");
        
        Metadata metadata = new Metadata("watermarked-contract.docx");        
        WordProcessingRootPackage root = metadata.getRootPackageGeneric();

        // Perbarui properti metadata dokumen
        root.getDocumentProperties().setAuthor("Name Surname");
        root.getDocumentProperties().setCreatedTime(new Date());
        root.getDocumentProperties().setCompany("Company Name");
        root.getDocumentProperties().setCategory("Work materials");
        root.getDocumentProperties().setKeywords("contract, watermarked");

        // Simpan dokumen dengan metadata yang diperbarui
        metadata.save("contract-final.docx");                
        ```
        {{< /landing/code >}}

    # code sample loop
    - title: "Redaksi Dokumen yang Efisien"
      content: |
        <b>Skenario:</b> Sebuah firma hukum besar sering kali memproses beragam dokumen yang berisi informasi rahasia klien yang harus disunting sebelum dibagikan kepada pihak ketiga atau untuk diungkapkan kepada publik. Menyunting informasi sensitif ini secara manual bisa jadi membosankan, memakan waktu, dan rentan terhadap kesalahan manusia. Untuk memastikan efisiensi, akurasi, dan kepatuhan terhadap peraturan perlindungan data, firma hukum ini mencari solusi otomatis untuk menyederhanakan proses redaksi dokumen. 
        
        <br>

        <b>Larutan:</b>
        GroupDocs.Total mengotomatiskan proses, memicu redaksi setelah menerima dokumen. Selain itu, [opsi fleksibel](https://docs.groupdocs.com/redaction/java/text-redactions/) memberdayakan penyesuaian dengan memungkinkan Anda menetapkan aturan, memilih mode redaksi (misalnya, mematikan lampu, mengganti dengan tanda bintang), dan menentukan bagian atau halaman tertentu untuk redaksi. Terakhir, [keluaran yang mudah digunakan](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) menghasilkan dokumen yang telah disunting dalam format PDF agar mudah dibagikan dan ditinjau, sementara peningkatan keamanan dan kemampuan audit memastikan keseluruhan proses didokumentasikan untuk kepatuhan dan akuntabilitas. 
        <br><br>
        Solusi komprehensif ini memberdayakan para profesional hukum dan organisasi lain untuk secara signifikan mengurangi waktu dan biaya redaksi, meminimalkan kesalahan manusia, dan secara konsisten menangani informasi sensitif dengan percaya diri.        
              
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.redaction.Redaction;
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Muat dokumen dengan data pribadi ke dalam redaksi 
        Redactor redactor = new Redactor("customer-info.docx");
        
        // Siapkan dan sesuaikan opsi redaksi 
        redactor.apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
        
        // Terapkan redaksi dan simpan hasilnya 
        redactor.save();

        // Muat file yang telah disunting untuk ditinjau 
        Viewer viewer = new Viewer("customer-info.docx");
        
        // Atur PDF sesuai format tampilan yang diinginkan       
        PdfViewOptions viewOptions = new PdfViewOptions("redacted-info.pdf");

        // Simpan dokumen ke dalam PDF      
        viewer.view(viewOptions);        
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Ulasan produk GroupDocs"
# description: "Jangan hanya percaya kata-kata kami begitu saja. Lihat apa yang dikatakan pengembang lain tentang API kami"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Pelayanan prima dan produk unggulan. Mereka sangat membantu dan responsif selama proses implementasi GroupDocs.Viewer untuk .NET, dan sangat merekomendasikannya."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Setelah mengimplementasikan dan menggunakan GroupDocs.Viewer untuk Java dalam proyek tersebut tampaknya berfungsi dengan baik. Saya telah menguji dengan banyak dokumen dan sejauh ini bagus. Semua yang saya berikan ditampilkan dengan baik dan terlihat sama bagusnya dengan penampil PDF atau MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---