---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: id
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
head_title: "Pustaka otomatisasi dokumen lengkap untuk aplikasi .NET"
head_description: "GroupDocs.Total for .NET adalah rangkaian API otomatisasi dokumen lengkap untuk pengembang .NET, menyediakan seperangkat alat komprehensif untuk bekerja dengan berbagai format dokumen, termasuk PDF, Word, Excel, Gambar, HTML, Diagram, dan banyak lagi ."

############################# Header ##########################
title: "Sederhanakan otomatisasi dokumen<br> di aplikasi .NET Anda"
description: "Buka kunci otomatisasi dokumen: konversi, lihat dan bandingkan, edit dan tandatangani di antara lebih dari 200 format dengan mudah."
words:
  for: "for"

actions:
  main: "Unduh NuGet Gratis"
  main_link: "https://www.nuget.org/packages/GroupDocs.Total"
  alt: "Perizinan"
  alt_link: "https://purchase.groupdocs.com/pricing/total/net"
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Total secara gratis atau minta lisensi"

release:
  title: "Versi {0} dirilis"
  notes: "Lihat apa yang baru"
  downloads: "Unduhan"
  link: "https://releases.groupdocs.com/total/net/release-notes/latest/"

code:
  title: "Gabungkan dan lihat file Word di C#"
  more: "Lebih banyak contoh"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-.NET"
  install: "dotnet add package GroupDocs.Total"
  content: |
    ```csharp {style=abap} 
    // Muat file DOCX sumber
    using (Merger merger = new Merger("sample1.docx"))
    {
        // Tambahkan file DOCX lain untuk digabungkan
        merger.Join("sample2.docx");

        // Gabungkan file DOCX dan simpan hasilnya
        merger.Save("merged.docx");
    }

    // Muat file DOCX yang digabungkan ke dalam penampil
    using (var viewer = new Viewer("merged.docx"))
    {
        // Tetapkan opsi HTML keluaran, satu file per halaman
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Render DOCX ke HTML dengan sumber daya tertanam        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Sekilas tentang GroupDocs.Total"
  description: "Otomatiskan tampilan file, konversi, edit, bandingkan, cari, tanda air, dan alur kerja lainnya dalam aplikasi .NET"
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
      content: "GroupDocs.Total untuk .NET membuka kompatibilitas dengan lebih dari 200 format file, memberdayakan Anda untuk memproses semua jenis dokumen populer. Dari format perkantoran seperti Word dan Excel hingga gambar, kode, dan file terenkripsi, kami siap membantu Anda."

    # feature loop
    - title: "Dukungan lintas platform"
      content: "Bebaskan diri Anda dari batasan platform. GroupDocs.Total menyediakan kompatibilitas lintas platform, memungkinkan Anda memberikan kinerja optimal dan ketersediaan solusi kepada pengguna di sistem mana pun di mana .NET dapat diinstal."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independensi platform"
  description: "GroupDocs.Total untuk .NET mendukung sistem operasi, kerangka kerja, dan manajer paket berikut"
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
  title: "Format file yang didukung"
  description: |
    GroupDocs.Total untuk .NET mendukung operasi dengan berikut [format file](https://docs.groupdocs.com/total/net/supported-document-formats/).
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
  description: "Beberapa skenario GroupDocs.Total dunia nyata untuk penggunaan .NET"
  items:
    # code sample loop
    - title: "Amankan dan atur kontrak: Terapkan tanda air dan kelola metadata dalam file DOCX"
      content: |
        Lindungi dan atur dokumen Word Anda secara efisien dengan contoh kode komprehensif ini. Contoh di bawah ini memberdayakan Anda untuk menerapkan manajemen watermarking dan metadata yang kuat dalam alur kerja kontrak Anda untuk meningkatkan keamanan dan manajemen informasi. Ini menunjukkan cara: <br><br>
        <b>Terapkan Tanda Air Khusus:</b> Tambahkan tanda air 'Draf Kontrak' yang menonjol ke dokumen untuk kejelasan dan perlindungan visual. [Sesuaikan tanda air](https://docs.groupdocs.com/watermark/net/basic-usage/customize/) dengan opsi font, warna, opacity, dan perataan. <br><br>
        <b>Tingkatkan Metadata:</b> [Ubah metadata dokumen dengan mudah](https://docs.groupdocs.com/metadata/net/working-with-metadata-in-wordprocessing-documents/) untuk menyertakan detail penting seperti penulis, waktu pembuatan, perusahaan, kategori, dan kata kunci untuk meningkatkan pengorganisasian dan kemampuan pencarian.
       
        {{< landing/code title="C#">}}
        ```csharp {style=abap}  
        using GroupDocs.Metadata;
        using GroupDocs.Watermark;
        using GroupDocs.Watermark.Common;
        using GroupDocs.Watermark.Watermarks;
        
        // Muat dokumen Anda ke dalam tanda air
        using (Watermarker watermarker = new Watermarker("contract.docx"))
        {
            // Atur teks dan font yang diinginkan untuk tanda air
            TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 60, FontStyle.Bold));
            
            // Pilih warna font dan opacity teks, rotasi dan perataan
            watermark.ForegroundColor = Color.DarkGreen;
            watermark.Opacity = 0.5;
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            
            // Terapkan tanda air
            watermarker.Add(watermark);
            
            // Simpan dokumen yang dihasilkan
            watermarker.Save("watermarked-contract.docx");
        }

        using (Metadata metadata = new Metadata("watermarked-contract.docx"))
        {
          var root = metadata.GetRootPackage<WordProcessingRootPackage>();

          // Perbarui properti metadata dokumen
          root.DocumentProperties.Author = "Name Surname";
          root.DocumentProperties.CreatedTime = DateTime.Now;
          root.DocumentProperties.Company = "Company Name";
          root.DocumentProperties.Category = "Work materials";
          root.DocumentProperties.Keywords = "contract, watermarked";

          // Simpan dokumen dengan metadata yang diperbarui
          metadata.Save("contract-final.docx");
        }        
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Redaksi Dokumen yang Efisien"
      content: |
        <b>Skenario:</b> Sebuah firma hukum besar sering kali memproses beragam dokumen yang berisi informasi rahasia klien yang harus disunting sebelum dibagikan kepada pihak ketiga atau untuk diungkapkan kepada publik. Menyunting informasi sensitif ini secara manual bisa jadi membosankan, memakan waktu, dan rentan terhadap kesalahan manusia. Untuk memastikan efisiensi, akurasi, dan kepatuhan terhadap peraturan perlindungan data, firma hukum ini mencari solusi otomatis untuk menyederhanakan proses redaksi dokumen. 
        
        <br>

        <b>Larutan:</b>
        GroupDocs.Total mengotomatiskan proses, memicu redaksi setelah menerima dokumen. Selain itu, [opsi fleksibel](https://docs.groupdocs.com/redaction/net/text-redactions/) memberdayakan penyesuaian dengan memungkinkan Anda menetapkan aturan, memilih mode redaksi (misalnya, mematikan lampu, mengganti dengan tanda bintang), dan menentukan bagian atau halaman tertentu untuk redaksi. Terakhir, [keluaran yang mudah digunakan](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) menghasilkan dokumen yang telah disunting dalam format PDF agar mudah dibagikan dan ditinjau, sementara peningkatan keamanan dan kemampuan audit memastikan keseluruhan proses didokumentasikan untuk kepatuhan dan akuntabilitas. 
        <br><br>
        Solusi komprehensif ini memberdayakan para profesional hukum dan organisasi lain untuk secara signifikan mengurangi waktu dan biaya redaksi, meminimalkan kesalahan manusia, dan secara konsisten menangani informasi sensitif dengan percaya diri.        
              
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Redaction;
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;

        // Muat dokumen dengan data pribadi ke dalam redaksi 
        using (Redactor redactor = new Redactor("customer-info.docx"))
        {
          // Siapkan dan sesuaikan opsi redaksi 
          redactor.Apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
          // Terapkan redaksi dan simpan hasilnya 
          redactor.Save();
        }

        // Muat file yang telah disunting untuk ditinjau 
        using (var viewer = new Viewer("customer-info.docx"))
        {
          // Atur PDF sesuai format tampilan yang diinginkan       
          var viewOptions = new PdfViewOptions("redacted-info.pdf");

          // Simpan dokumen ke dalam PDF      
          viewer.View(viewOptions);
        }
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