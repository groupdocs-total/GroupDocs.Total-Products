---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Total"
product_tag: "total"

############################# Head ############################
head_title: "ドキュメント自動化 API |オンプレミス API とオンライン サービス"
head_description: "文書操作を簡単かつ無料で自動化します"

############################# Header ##########################
title: "オールインワン スイートによるマスター ドキュメント自動化"
description: |
  わずか数行のコードで、反復的なドキュメント タスクを簡素化し、ワークフローを合理化します。強力な API により統合が簡単になり、インフラストラクチャではなくイノベーションに集中できるようになります。

  変換、署名、表示、注釈付け - 最小限のコードであらゆるドキュメントのタスクを完了します。 Word から PDF、Excel から画像まで、あらゆるものをシームレスに処理します。コードが少ないほど、効果は大きくなります。

  超高速の統合により、文書タスクを自動化し、効率を高め、迅速に行動します。ビジネスにとって本当に重要なことに集中して、時間とリソースを節約します。

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "プラットフォームを選択してください"
  title: "サポートされているプラ​​ットフォーム"
  description: "GroupDocs.Total ライブラリは、次のオペレーティング システムとフレームワークをサポートしています。"
  details_link_title: "もっと詳しく知る"
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
        - content: "200 以上のファイル形式"
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
        - content: "200 以上のファイル形式"
          rows: "1"
        # features loop
        - content:  "Eclipse <br> NetBeans <br> IntelliJ Idea"
          rows: "3"

############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Total の機能セット"
  description: "すべての個別の GroupDocs 製品の機能を 1 つ屋根の下で統合し、サードパーティ ソフトウェアを使用せずにあらゆるドキュメント タスクを管理する単一のソリューション。"

  items:
    # feature loop
    - icon: "view"
      title: "ドキュメントと画像を表示する"
      content: "ファイルをレンダリングして、HTML、PDF、PNG、JPEG 形式で表示します。"

    # feature loop
    - icon: "convert"
      title: "形式間の変換"
      content: "ファイルをさまざまなソースからさまざまなターゲット形式に変換します。"

    # feature loop
    - icon: "merge"
      title: "複数のファイルを 1 つに結合する"
      content: "複数の PDF、Office などを 1 つのドキュメントにシームレスに結合します。"
    
    # feature loop
    - icon: "settings"
      title: "その他の製品と機能"
      content: "比較、電子歌唱、検索、透かしなど、GroupDocs ドキュメント自動化 API のすべてのセットを探索してください。"


############################# Code samples ############################
# code_samples:
#   enable: true
#   title: "GroupDocs.Total コード サンプル"
#   description: "C#、Java、TypeScript での典型的な GroupDocs.Total 操作の使用例"
#   items:
#     # code sample loop
#     - title: "DOCX ファイルを PDF にレンダリングする方法"
#       content: |
#        Microsoft Word やその他のソフトウェアをインストールしなくても、DOCX ドキュメントを PDF にレンダリングできます。 Web アプリケーションでもデスクトップ アプリケーションでも、アプリケーション内で DOCX ファイルを簡単にロードして表示できます。以下は、DOCX ファイルを PDF にレンダリングする方法の例です。
#       samples:
#         - language: "C#"
#           color: "blue"
#           content: |
#             ```csharp {style=abap}   
#             // レンダリングするDOCXファイルをロードします
#             using (Viewer viewer = new Viewer("sample.docx"))
#             {
#               // DOCX を PDF ファイルにレンダリングする
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
#             // レンダリングするDOCXファイルをロードします
#             try (Viewer viewer = new Viewer("sample.docx")) {
#                 // DOCX を PDF ファイルにレンダリングする
#                 PdfViewOptions viewOptions = new PdfViewOptions();
#                 viewer.view(viewOptions);
#             }
#             ```
#         - language: "TypeScript"
#           color: "green"
#           content: |
#             ```javascript {style=abap}  
#             // レンダリングするDOCXファイルをロードします
#             const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
#             // DOCX を PDF ファイルにレンダリングする
#             const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
#             viewer.view(viewOptions)
#             ```


############################# Formats ############################
formats:
  enable: true
  title:  "200 以上のファイル形式をサポート"
  description: "GroupDocs.Total は、最も一般的な [ファイル形式](https://docs.groupdocs.com/total/net/supported-document-formats/) での操作をサポートします。"


############################# Metrics ############################

metrics:
  enable: true
  title: "詳細な指標と統計的洞察"
  description: "当社の主要な数値を詳細に分析し、当社の業績、影響、成長に関する包括的な指標と統計的洞察を提供します。"

  items:
    # metrics loop
    - number: "200+"
      title: "サポートされている形式"
      content: "ドキュメント、画像、CAD 図面などの 200 を超えるファイル形式を手間なく簡単に表示できます。当社の包括的な表示ソリューションを使用すると、互換性の壁を打ち破り、さまざまなファイルに簡単にアクセスできます。"
    # metrics loop
    - number: "550K"
      title: "NuGetのダウンロード"
      content: "当社の NuGet パッケージ ソリューションは、開発者コミュニティで信頼され広く採用されているリソースとなり、無数のプロジェクトにシームレスな統合と貴重な機能を提供します。"

    # metrics loop
    - number: "10+"
      title: "図書館"
      content: "当社の製品には 10 以上のライブラリが含まれており、パフォーマンスを最適化する高度な機能を提供します。これらのライブラリは、比類のない機能でさまざまな開発ニーズを満たすように設計されています。"
    
    # metrics loop
    - number: "100+"
      title: "幸せな顧客"
      content: "世界中の最も象徴的なブランドにサービスを提供しています。なぜ何人もが GroupDocs.Total を愛しているのかを発見してください!シームレスなナビゲーション、便利なコラボレーション、比類のない使いやすさを体験してください。今すぐ参加してください！"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "幸せなお客様"
  description: "GroupDocs ライブラリは、世界中の世界的に有名な有名ブランドで採用されています。"

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
  title: "始める準備はできていますか?"
  description: "GroupDocs.Total の機能を無料で試すか、ライセンスをリクエストしてください"

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
  title: "よくある質問と懸念事項"
  description: "よくある質問への回答を FAQ セクションで見つけて、質問や懸念事項にすばやく対処します。"

  items:
    #  loop
    - question: "GroupDocs.Total とは何ですか?また、他の GroupDocs 製品との違いは何ですか?"
      answer: |
        GroupDocs.Total は、すべての個別の GroupDocs 製品の機能を 1 つのパッケージに結合した包括的なスイートです。これにはいくつかの利点があります: <br><br>
        <ul>
          <li>
            <b>統合された機能:</b> 単一の API 内で、表示、変換、結合、注釈、署名などを含むすべてのドキュメント処理機能にアクセスできます。 <br><br>
          </li>
          <li>
            <b>強化された互換性:</b> GroupDocs.Total は、サポートされているすべてのファイル形式とプラットフォームにわたって一貫した信頼性の高いパフォーマンスを保証し、別の製品を使用するときに発生する可能性のある互換性の問題を排除します。 <br><br>
          </li>
          <li>
            <b>最適化されたパッケージサイズ:</b> このスイートは単一のコンパクトなパッケージとして提供されるため、個別の製品を個別にインストールして使用する場合に比べて、リソースの消費が削減され、アプリケーションへの統合が簡素化されます。
          </li>
        <ul>

    #  loop
    - question: "個別の GroupDocs 製品を購入するのではなく、GroupDocs.Total を選択するのはなぜですか?"
      answer: |
        通常、単一の GroupDocs.Total ライセンスを購入する方が、2 つ以上の個別の GroupDocs 製品のライセンスを購入するよりも費用が安くなります。 <br>
        これは、あなたにとっていくつかの重要な利点となります: <br><br>
        <b>コスト削減:</b> GroupDocs.Total では、個別の製品を購入する場合と比べて大幅な割引が提供されているため、予算をさらに拡張することができます。 <br><br>
        <b>管理の簡素化:</b> GroupDocs.Total を使用すると、すべてを 1 つのライセンスで管理できるため、さまざまな製品の複数のライセンスを追跡および管理する必要がなくなります。これにより、管理タスクが簡素化され、全体的なコストが削減されます。 <br><br>
        ドキュメント管理のニーズを満たす、コスト効率が高く、機能が豊富なソリューションをお探しの場合は、GroupDocs.Total が最適な選択肢です。

    #  loop
    - question: "GroupDocs.Total を使い始めるにはどうすればよいですか?"
      answer: |
        無料トライアルから始めて機能を試し、ニーズを満たすかどうかを確認できます。 GroupDocs は、統合と開発を始めるのに役立つさまざまな [ドキュメント](https://docs.groupdocs.com/total/) リソースと [チュートリアル](https://groupdocs.github.io) も提供します。
        
    #  loop
    - question: "GroupDocs.Total は技術サポートを提供していますか?"
      answer: |
        はい、GroupDocs は、GroupDocs.Total を確実に成功させるための包括的な技術サポートを提供しています。彼らには2つの選択肢があります: <br><br>
        <b>[無料サポートフォーラム](https://forum.groupdocs.com):</b> このフォーラムでは、GroupDocs スタッフとつながり、質問に答え、経験に基づいたソリューションを提供できます。よくある問題や一般的な問い合わせに最適なリソースです。 <br><br>
        <b>[有料サポート ヘルプデスク](https://helpdesk.groupdocs.com):</b> このオプションは、優先的にサポートを提供します。複雑な問題が発生した場合、またはより迅速な解決が必要な場合は、有料サポートを利用すると、パーソナライズされた支援と迅速な応答時間が提供されます。 <br><br>
        GroupDocs は無料と有料の両方のオプションを提供することで、さまざまなニーズと予算に対応し、GroupDocs.Total で成功するために必要なサポートを確実に提供します。

    #  loop
    - question: "GroupDocs.Total はドキュメント操作に追加のソフトウェアを必要としますか?"
      answer: |
        GroupDocs.Total は自己完結型のスイートであり、表示、変換、注釈付け、署名などの基本的なドキュメント操作タスクに追加のサードパーティ ソフトウェアを必要としません。ただし、使用する特定の機能 (スキャンされたドキュメントの OCR など) によっては、外部ライブラリが必要になる場合があります。

############################# Cloud and Apps ############################

cloud_links:
  enable: true
  title: "GroupDocs.トータルソリューション"
  description: "当社のクラウド REST API と無料のオンライン アプリを使用して、アプリケーションでのドキュメント処理を強化します。"

  items:
    #  loop
    - icon: "groupdocs_total-cloud"
      title: "GroupDocs.Total Cloud"
      link: "https://products.groupdocs.cloud/total"
      content: "アプリケーションでの Microsoft Office、PDF ドキュメントの処理を効率的に自動化する堅牢なクラウド ソリューション。"

    #  loop
    - icon: "groupdocs_total-apps"
      title: "GroupDocs.Total Online Apps"
      link: "https://products.groupdocs.app"
      content: "ドキュメントのコンテンツを表示および編集したり、さまざまな Microsoft Office、OpenOffice、画像、その他の一般的なファイル形式を比較および結合したりできる、無料のオンライン Web アプリです。"    

    #  loop
    - icon: "groupdocs_total-windows"
      title: "GroupDocs.Total Windows"
      link: "https://products.groupdocs.app/total/windows"
      content: "あらゆるオペレーティング システム上でドキュメントの変換、注釈付け、比較、署名、組み立て、解析、分類、編集、検索を行うオフライン アプリ。"   

---