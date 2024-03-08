---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ja
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
head_title: "Java アプリケーション用のオールインワンのドキュメント自動化スイート"
head_description: "GroupDocs.Total for Java は、Java 開発者向けに調整された包括的なドキュメント自動化ライブラリであり、PDF、Word、Excel、画像、HTML、図などのさまざまなドキュメント形式を処理するための幅広い機能を提供します。"

############################# Header ############################
title: "Java プロジェクトでのドキュメントの自動化を簡素化<br>"
description: "ドキュメント自動化機能の強化: 200 を超えるファイル形式を簡単に変換、表示、比較、編集、署名できます。"
words:
  for: "for"

actions:
  main: "Maven の無料ダウンロード"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-total/"
  alt: "ライセンス"
  alt_link: "https://purchase.groupdocs.com/pricing/total/java"
  title: "始める準備はできていますか?"
  description: "GroupDocs.Total の機能を無料で試すか、ライセンスをリクエストしてください"

release:
  title: "バージョン {0} がリリースされました"
  notes: "新機能を見る"
  downloads: "ダウンロード"
  link: "https://releases.groupdocs.com/total/java/release-notes/latest/"

code:
  title: "Java で Word ファイルを結合して表示する"
  more: "他の例"
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
    // ソースDOCXファイルをロードします 
    Merger merger = new Merger("sample1.docx");
    
    // マージする別の DOCX ファイルを追加します
    merger.join("sample2.docx");

    // DOCX ファイルをマージし、結果を保存します
    merger.save("merged.docx");
    
    // マージされた DOCX ファイルをビューアにロードします
    try (Viewer viewer = new Viewer("merged.docx"))
    {
      // 出力 HTML オプションを設定します (ページごとに 1 つのファイル)
      HtmlViewOptions viewOptions =   
      HtmlViewOptions.forEmbeddedResources("page{0}.html");
          
      // 埋め込みリソースを使用して DOCX を HTML にレンダリングします        
      viewer.view(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total の概要"
  description: "Java アプリケーションでのファイルの表示、変換、編集、比較、検索、透かし入れなどのワークフローを自動化します。"
  features:
    # feature loop
    - title: "複数の GroupDocs 製品の機能を 1 つの包括的なソリューションに統合します"
      content: | 
        さまざまな GroupDocs 製品の機能を使用して、特定のニーズを満たすカスタマイズされたアプローチを作成できます。
        <br><br>
        たとえば、Word ファイルを PDF に変換し、デジタル署名を追加できます。または、データベースからドキュメント テンプレート データを入力するか、画像からテキストを抽出して別の言語に翻訳します。
        <br><br>
        可能性は無限大！
          
    # feature loop
    - title: "多様なファイル形式をマスターする"
      content: "GroupDocs.Total for Java は、200 を超えるファイル形式との互換性を解除し、一般的なすべての種類のドキュメントを処理できるようにします。 Word や Excel などのオフィス形式から、画像、コード、暗号化されたファイルまで、あらゆるものをカバーします。"

    # feature loop
    - title: "クロスプラットフォームのサポート"
      content: "プラットフォームの制限から解放されます。 GroupDocs.Total はクロスプラットフォーム互換性を提供し、Java がインストールできるあらゆるシステム上のユーザーに最適なパフォーマンスとソリューションの可用性を提供できます。"

############################# Platforms ############################
platforms:
  enable: true
  title: "プラットフォームの独立性"
  description: "GroupDocs.Total for Java は、次のオペレーティング システム、フレームワーク、パッケージ マネージャーをサポートしています。"
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
  title: "サポートされているファイル形式"
  description: |
    GroupDocs.Total for Java は、次の [ファイル形式](https://docs.groupdocs.com/total/java/supported-document-formats/) での操作をサポートします。
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office、OpenDocument、およびテキスト形式
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
        ### 画像、グラフィック、図表
        * **ラスター画像:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### 他の        
        * **ウェブ:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **アーカイブ:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **他の:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Total 総合機能"
  description: "PDF と Office ドキュメントを包括的に管理、レンダリング、変換します"

  items:
    # feature loop
    - icon: "viewer"
      title: "広範なファイル表示"
      content: "HTML、画像、PDF を含む 180 を超える形式の包括的なドキュメント表示。"

    # feature loop
    - icon: "conversion"
      title: "フォーマット変換"
      content: "外部ツールを使用せずに、さまざまなドキュメント形式間でシームレスに変換します。"

    # feature loop
    - icon: "annotation"
      title: "インタラクティブな注釈"
      content: "ドキュメント内のテキストおよび画像要素に対する高度な注釈機能。"

    # feature loop
    - icon: "comparison"
      title: "内容の比較"
      content: "文書を正確に比較し、内容とスタイルの違いを強調します。"

    # feature loop
    - icon: "signature"
      title: "署名の柔軟性"
      content: "テキスト、画像、デジタル署名などの多彩な署名オプション。"

    # feature loop
    - icon: "assembly"
      title: "テンプレートベースのドキュメント作成"
      content: "テンプレートと外部データ ソースからのドキュメントの自動生成。"

    # feature loop
    - icon: "metadata"
      title: "メタデータ管理"
      content: "強化されたドキュメント管理のための堅牢なメタデータ アクセスと操作。"

    # feature loop
    - icon: "search"
      title: "高度な検索"
      content: "ファジーアルゴリズムと同義語アルゴリズムをサポートする強力な検索機能。"

    # feature loop
    - icon: "watermark"
      title: "ウォーターマーク制御"
      content: "文書の透かしを簡単に管理し、カスタマイズ機能と抽出機能を提供します。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "コードサンプル"
  description: "GroupDocs.Total for Java の使用に関するいくつかの実際のシナリオ"
  items:
    # code sample loop
    - title: "契約の保護と整理: ウォーターマークを適用し、DOCX ファイル内のメタデータを管理します"
      content: |
        この包括的なコード例を使用して、Word 文書を効率的に保護および整理します。以下のサンプルを使用すると、契約ワークフロー内に堅牢な透かしとメタデータ管理を実装して、セキュリティと情報管理を強化できます。以下の方法を示します。 <br><br>
        <b>カスタム透かしを適用する:</b> 視覚的な明瞭さと保護のために、文書に目立つ「契約草案」の透かしを追加します。 [ウォーターマークをカスタマイズ](https://docs.groupdocs.com/watermark/java/adding-text-watermarks/) フォント、色、不透明度、配置のオプションを使用します。 <br><br>
        <b>メタデータの強化:</b> 簡単に[ドキュメントのメタデータを変更](https://docs.groupdocs.com/metadata/java/working-with-metadata-in-word-processing-documents/)して、作成者、作成時間、会社、カテゴリなどの重要な詳細を含めることができます。およびキーワードにより、整理と検索性が向上します。
       
        {{< landing/code title="Java">}}
        ```java {style=abap}  
        import com.groupdocs.metadata.Metadata;
        import com.groupdocs.watermark.Watermark;
        import com.groupdocs.watermark.Watermark.Common;
        import com.groupdocs.watermark.Options.HtmlViewOptions;
        
        // 文書をウォーターマーカーにロードします
        Watermarker watermarker = new Watermarker("contract.docx");
        
        // ウォーターマークに必要なテキストとフォントを設定します
        TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 36));
          
        // フォントの色とテキストの不透明度、回転と配置を選択します
        watermark.setForegroundColor(Color.getRed());                                                            
        watermark.setHorizontalAlignment(HorizontalAlignment.Center);                                            
        watermark.setVerticalAlignment(VerticalAlignment.Center);                               

        // 透かしを適用する
        watermarker.add(watermark);
        
        // 結果のドキュメントを保存する
        watermarker.save("watermarked-contract.docx");
        
        Metadata metadata = new Metadata("watermarked-contract.docx");        
        WordProcessingRootPackage root = metadata.getRootPackageGeneric();

        // ドキュメントのメタデータのプロパティを更新する
        root.getDocumentProperties().setAuthor("Name Surname");
        root.getDocumentProperties().setCreatedTime(new Date());
        root.getDocumentProperties().setCompany("Company Name");
        root.getDocumentProperties().setCategory("Work materials");
        root.getDocumentProperties().setKeywords("contract, watermarked");

        // 更新されたメタデータを含むドキュメントを保存する
        metadata.save("contract-final.docx");                
        ```
        {{< /landing/code >}}

    # code sample loop
    - title: "合理化されたドキュメントの編集"
      content: |
        <b>シナリオ:</b> 大手法律事務所では、顧客の機密情報を含むさまざまな文書を頻繁に処理しており、第三者と共有したり一般に公開したりする前に編集する必要があります。この機密情報を手動で編集するのは面倒で時間がかかり、人的ミスが発生しやすい可能性があります。効率性、正確性、データ保護規制への準拠を確保するために、この法律事務所は文書編集プロセスを合理化する自動化ソリューションを求めています。 
        
        <br>

        <b>解決:</b>
        GroupDocs.Total はプロセスを自動化し、ドキュメントの受信時に編集をトリガーします。さらに、[柔軟なオプション](https://docs.groupdocs.com/redaction/java/text-redactions/) により、ルールを設定し、編集モード (ブラックアウト、アスタリスクで置換など) を選択し、指定することができるため、カスタマイズが可能になります。編集対象の特定のセクションまたはページ。最後に、[ユーザーフレンドリーな出力](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) は、共有とレビューが容易なように編集されたドキュメントを PDF 形式で生成します。また、強化されたセキュリティと監査可能性により、セキュリティ全体が保証されます。プロセスはコンプライアンスと説明責任のために文書化されます。 
        <br><br>
        この包括的なソリューションにより、法律専門家やその他の組織は編集時間とコストを大幅に削減し、人的エラーを最小限に抑え、機密情報を一貫して自信を持って処理できるようになります。        
              
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.redaction.Redaction;
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // プライベートデータを含むドキュメントをリダクターにロードする 
        Redactor redactor = new Redactor("customer-info.docx");
        
        // 編集オプションの設定とカスタマイズ 
        redactor.apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
        
        // 墨消しを適用して結果を保存する 
        redactor.save();

        // 編集したファイルをレビューのためにロードする 
        Viewer viewer = new Viewer("customer-info.docx");
        
        // PDFを希望の表示形式に設定します       
        PdfViewOptions viewOptions = new PdfViewOptions("redacted-info.pdf");

        // 文書を PDF に保存      
        viewer.view(viewOptions);        
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs 製品のレビュー"
# description: "私たちの言葉をそのまま鵜呑みにしないでください。他の開発者の API についての意見をご覧ください"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "優れたサービスと優れた製品。これらは、GroupDocs.Viewer for .NET の実装プロセス中に非常に役に立ち、迅速に対応してくれましたが、あまりお勧めできません。"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "プロジェクトに Java 用 GroupDocs.Viewer を実装して使用した後、非常にうまく動作しているように見えます。多くのドキュメントを使用してテストしましたが、これまでのところ良好です。私が投げたものはすべてうまくレンダリングされ、PDF ビューアや MS Word と同じくらい見栄えがよくなります。"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---