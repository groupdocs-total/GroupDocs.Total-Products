---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Total"
product_tag: "total"

############################# Head ############################
head_title: "API Otomatisasi Dokumen | API Lokal dan layanan online"
head_description: "Otomatiskan manipulasi dokumen Anda dengan mudah dan gratis"

############################# Header ##########################
title: "Otomatisasi dokumen utama dengan rangkaian lengkap"
description: |
  Sederhanakan tugas dokumen yang berulang dan sederhanakan alur kerja Anda hanya dengan beberapa baris kode. API yang kuat membuat integrasi menjadi mudah, memberdayakan Anda untuk fokus pada inovasi, bukan infrastruktur.

  Konversi, tanda tangani, lihat, anotasi - taklukkan tugas dokumen apa pun dengan kode minimal. Dari Word hingga PDF, Excel hingga gambar, tangani semuanya dengan lancar. Lebih sedikit kode, dampak lebih besar.

  Otomatiskan tugas dokumen, tingkatkan efisiensi, dan bergerak cepat dengan integrasi secepat kilat. Hemat waktu dan sumber daya, dengan fokus pada hal yang benar-benar penting bagi bisnis Anda.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Pilih platform Anda"
  title: "Platform yang didukung"
  description: "Pustaka GroupDocs.Total mendukung sistem operasi dan kerangka kerja berikut"
  details_link_title: "Belajarlah lagi"
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
        - content: "200+ format file"
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
        - content: "200+ format file"
          rows: "1"
        # features loop
        - content:  "Eclipse <br> NetBeans <br> IntelliJ Idea"
          rows: "3"

############################# Features ############################

features:
  enable: true
  title: "Kumpulan fitur GroupDocs.Total"
  description: "Solusi tunggal yang menyatukan fungsionalitas semua produk GroupDocs individual dalam satu atap dan mengelola tugas dokumen apa pun tanpa perangkat lunak pihak ketiga."

  items:
    # feature loop
    - icon: "view"
      title: "Lihat dokumen dan gambar"
      content: "Render file untuk melihatnya dalam format HTML, PDF, PNG, dan JPEG."

    # feature loop
    - icon: "convert"
      title: "Konversi antar format"
      content: "Ubah file dari sumber berbeda ke berbagai format target."

    # feature loop
    - icon: "merge"
      title: "Gabungkan beberapa file menjadi satu"
      content: "Gabungkan beberapa PDF, Office, dan lainnya dengan mulus ke dalam satu dokumen."
    
    # feature loop
    - icon: "settings"
      title: "Lebih banyak produk dan fitur"
      content: "Jelajahi seluruh rangkaian API otomatisasi dokumen GroupDocs: bandingkan, e-sing, pencarian, tanda air, dan banyak lagi!"


############################# Code samples ############################
# code_samples:
#   enable: true
#   title: "GroupDocs.Total contoh kode"
#   description: "Beberapa kasus penggunaan operasi GroupDocs.Total tipikal di C#, Java, TypeScript"
#   items:
#     # code sample loop
#     - title: "Cara merender file DOCX ke PDF"
#       content: |
#        Render dokumen DOCX ke PDF tanpa menginstal Microsoft Word atau perangkat lunak lain. Memuat dan melihat file DOCX dengan mudah dalam aplikasi Anda, baik itu aplikasi web atau desktop. Berikut adalah contoh cara merender file DOCX ke PDF:
#       samples:
#         - language: "C#"
#           color: "blue"
#           content: |
#             ```csharp {style=abap}   
#             // Muat file DOCX untuk dirender
#             using (Viewer viewer = new Viewer("sample.docx"))
#             {
#               // Render DOCX ke file PDF
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
#             // Muat file DOCX untuk dirender
#             try (Viewer viewer = new Viewer("sample.docx")) {
#                 // Render DOCX ke file PDF
#                 PdfViewOptions viewOptions = new PdfViewOptions();
#                 viewer.view(viewOptions);
#             }
#             ```
#         - language: "TypeScript"
#           color: "green"
#           content: |
#             ```javascript {style=abap}  
#             // Muat file DOCX untuk dirender
#             const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
#             // Render DOCX ke file PDF
#             const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
#             viewer.view(viewOptions)
#             ```


############################# Formats ############################
formats:
  enable: true
  title:  "200+ format file didukung"
  description: "GroupDocs.Total mendukung pengoperasian dengan paling populer [format file](https://docs.groupdocs.com/total/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Metrik mendalam dan wawasan statistik"
  description: "Pelajari rincian angka-angka penting kami, yang memberikan metrik komprehensif dan wawasan statistik mengenai pencapaian, dampak, dan pertumbuhan kami."

  items:
    # metrics loop
    - number: "200+"
      title: "Format yang didukung"
      content: "Lihat lebih dari 200 format file termasuk dokumen, gambar, dan gambar CAD dengan mudah tanpa repot. Hancurkan hambatan kompatibilitas dan akses beragam file dengan mudah menggunakan solusi tampilan komprehensif kami."
    # metrics loop
    - number: "550K"
      title: "Unduhan NuGet"
      content: "Solusi paket NuGet kami telah menjadi sumber daya tepercaya dan diadopsi secara luas di komunitas pengembang, menyediakan integrasi tanpa batas dan fungsionalitas berharga untuk banyak proyek."

    # metrics loop
    - number: "10+"
      title: "Perpustakaan"
      content: "Produk kami mencakup 10+ perpustakaan, menawarkan fitur-fitur canggih untuk mengoptimalkan kinerja. Perpustakaan ini dirancang untuk memenuhi kebutuhan pengembangan yang berbeda dengan kemampuan yang tak tertandingi."
    
    # metrics loop
    - number: "100+"
      title: "Pelanggan yang senang"
      content: "Melayani merek paling ikonik di seluruh dunia. Temukan mengapa ratusan orang menyukai GroupDocs.Total! Jelajahi navigasi yang lancar, kolaborasi yang nyaman, dan kemudahan penggunaan yang tak tertandingi. Bergabung sekarang!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Pelanggan kami yang bahagia"
  description: "Perpustakaan GroupDocs digunakan oleh merek-merek terkenal dan terkemuka secara global di seluruh dunia."

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
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Total secara gratis atau minta lisensi"

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
  title: "Pertanyaan dan kekhawatiran umum"
  description: "Temukan jawaban atas pertanyaan umum di bagian FAQ kami untuk menjawab pertanyaan dan kekhawatiran Anda dengan cepat."

  items:
    #  loop
    - question: "Apa itu GroupDocs.Total, dan apa bedanya dengan produk GroupDocs lainnya?"
      answer: |
        GroupDocs.Total adalah rangkaian komprehensif yang menggabungkan fungsionalitas semua produk GroupDocs individual ke dalam satu paket. Hal ini menawarkan beberapa keuntungan: <br><br>
        <ul>
          <li>
            <b>Fitur terpadu:</b> Anda memiliki akses ke semua kemampuan pemrosesan dokumen, termasuk melihat, konversi, penggabungan, anotasi, penandatanganan, dan lainnya, dalam satu API. <br><br>
          </li>
          <li>
            <b>Kompatibilitas yang ditingkatkan:</b> GroupDocs.Total memastikan kinerja yang konsisten dan andal di semua format file dan platform yang didukung, menghilangkan masalah kompatibilitas yang mungkin timbul saat menggunakan produk terpisah. <br><br>
          </li>
          <li>
            <b>Ukuran paket yang dioptimalkan:</b> Suite ini hadir sebagai paket tunggal dan ringkas, mengurangi konsumsi sumber daya dan menyederhanakan integrasi ke dalam aplikasi Anda dibandingkan menggunakan produk individual dengan instalasi terpisah.
          </li>
        <ul>

    #  loop
    - question: "Mengapa lebih memilih GroupDocs.Total daripada membeli produk GroupDocs individual?"
      answer: |
        Membeli satu lisensi GroupDocs.Total biasanya lebih murah dibandingkan membeli lisensi untuk dua atau lebih produk GroupDocs individual. <br>
        Ini berarti beberapa manfaat utama bagi Anda: <br><br>
        <b>Penghematan biaya:</b> GroupDocs.Total menawarkan diskon yang signifikan dibandingkan dengan pembelian produk individual, memungkinkan Anda untuk memperluas anggaran Anda lebih jauh. <br><br>
        <b>Manajemen yang disederhanakan:</b> Dengan GroupDocs.Total, Anda mengelola semuanya dalam satu lisensi, sehingga menghilangkan kebutuhan untuk melacak dan memelihara banyak lisensi untuk produk berbeda. Ini menyederhanakan tugas administratif Anda dan mengurangi biaya keseluruhan. <br><br>
        Jika Anda mencari solusi hemat biaya dan kaya fitur untuk kebutuhan manajemen dokumen Anda, GroupDocs.Total adalah pilihan yang tepat.

    #  loop
    - question: "Bagaimana cara memulai GroupDocs.Total?"
      answer: |
        Anda dapat memulai dengan uji coba gratis untuk menjelajahi fitur-fiturnya dan melihat apakah fitur tersebut memenuhi kebutuhan Anda. GroupDocs juga menawarkan berbagai sumber daya [dokumentasi](https://docs.groupdocs.com/total/) dan [tutorial](https://groupdocs.github.io) untuk membantu Anda memulai integrasi dan pengembangan.
        
    #  loop
    - question: "Apakah GroupDocs.Total menawarkan dukungan teknis?"
      answer: |
        Ya, GroupDocs menawarkan dukungan teknis komprehensif untuk memastikan kesuksesan Anda dengan GroupDocs.Total. Mereka punya dua pilihan: <br><br>
        <b>[Forum Dukungan Gratis](https://forum.groupdocs.com):</b> Forum ini memungkinkan Anda terhubung dengan staf GroupDocs, yang dapat menjawab pertanyaan Anda dan menawarkan solusi berdasarkan pengalaman mereka. Ini adalah sumber yang bagus untuk masalah umum dan pertanyaan umum. <br><br>
        <b>[Pusat Bantuan Dukungan Berbayar](https://helpdesk.groupdocs.com):</b> Opsi ini memberikan dukungan berdasarkan prioritas. Jika Anda menghadapi masalah yang rumit atau memerlukan penyelesaian yang lebih cepat, dukungan berbayar menawarkan bantuan yang dipersonalisasi dan waktu respons yang lebih cepat. <br><br>
        Dengan menyediakan opsi gratis dan berbayar, GroupDocs memenuhi berbagai kebutuhan dan anggaran, memastikan Anda mendapatkan dukungan yang Anda perlukan untuk berkembang dengan GroupDocs.Total.

    #  loop
    - question: "Apakah GroupDocs.Total memerlukan software tambahan untuk manipulasi dokumen?"
      answer: |
        GroupDocs.Total adalah rangkaian mandiri dan tidak memerlukan perangkat lunak pihak ketiga tambahan untuk tugas manipulasi dokumen dasar seperti melihat, mengonversi, membuat anotasi, atau menandatangani. Namun, bergantung pada fitur spesifik yang Anda gunakan (misalnya OCR untuk dokumen yang dipindai), perpustakaan eksternal mungkin diperlukan.

############################# Cloud and Apps ############################

cloud_links:
  enable: true
  title: "GroupDocs.Solusi total"
  description: "Tingkatkan pemrosesan dokumen dalam aplikasi Anda dengan REST API cloud kami dan aplikasi online gratis"

  items:
    #  loop
    - icon: "groupdocs_total-cloud"
      title: "GroupDocs.Total Cloud"
      link: "https://products.groupdocs.cloud/total"
      content: "Solusi cloud yang kuat untuk mengotomatiskan pemrosesan Microsoft Office, dokumen PDF secara efisien di aplikasi Anda."

    #  loop
    - icon: "groupdocs_total-apps"
      title: "GroupDocs.Total Online Apps"
      link: "https://products.groupdocs.app"
      content: "Aplikasi web online gratis untuk melihat dan mengedit konten dokumen, membandingkan dan menggabungkan berbagai Microsoft Office, OpenOffice, gambar & format file populer lainnya."    

    #  loop
    - icon: "groupdocs_total-windows"
      title: "GroupDocs.Total Windows"
      link: "https://products.groupdocs.app/total/windows"
      content: "Aplikasi offline untuk mengonversi, membuat anotasi, membandingkan, menandatangani, merakit, mengurai, mengklasifikasikan, menyunting, dan mencari dokumen di sistem operasi apa pun."   

---