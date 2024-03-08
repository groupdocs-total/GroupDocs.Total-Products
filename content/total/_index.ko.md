---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Total"
product_tag: "total"

############################# Head ############################
head_title: "문서 자동화 API | 온프레미스 API 및 온라인 서비스"
head_description: "문서 조작을 쉽고 무료로 자동화하세요"

############################# Header ##########################
title: "올인원 제품군을 통한 마스터 문서 자동화"
description: |
  단 몇 줄의 코드만으로 반복적인 문서 작업을 단순화하고 워크플로우를 간소화하세요. 강력한 API를 사용하면 쉽게 통합할 수 있으므로 인프라가 아닌 혁신에 집중할 수 있습니다.

  변환, 서명, 보기, 주석 달기 등 최소한의 코드로 모든 문서 작업을 완료하세요. Word에서 PDF, Excel에서 이미지까지 모든 것을 원활하게 처리합니다. 코드는 적고 영향력은 커집니다.

  문서 작업을 자동화하고, 효율성을 높이며, 빛처럼 빠른 통합으로 빠르게 움직일 수 있습니다. 시간과 자원을 절약하고 비즈니스에 정말로 중요한 것에 집중하세요.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "플랫폼을 선택하세요"
  title: "지원되는 플랫폼"
  description: "GroupDocs.Total 라이브러리는 다음 운영 체제 및 프레임워크를 지원합니다."
  details_link_title: "더 알아보기"
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
        - content: "200개 이상의 파일 형식"
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
        - content: "200개 이상의 파일 형식"
          rows: "1"
        # features loop
        - content:  "Eclipse <br> NetBeans <br> IntelliJ Idea"
          rows: "3"

############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Total의 기능 세트"
  description: "모든 개별 GroupDocs 제품의 기능을 한 지붕 아래 통합하고 타사 소프트웨어 없이 모든 문서 작업을 관리하는 단일 솔루션입니다."

  items:
    # feature loop
    - icon: "view"
      title: "문서 및 이미지 보기"
      content: "파일을 렌더링하여 HTML, PDF, PNG 및 JPEG 형식으로 볼 수 있습니다."

    # feature loop
    - icon: "convert"
      title: "형식 간 변환"
      content: "다양한 소스의 파일을 다양한 대상 형식으로 변환합니다."

    # feature loop
    - icon: "merge"
      title: "여러 파일을 하나로 병합"
      content: "여러 PDF, Office 및 기타 항목을 하나의 문서로 원활하게 결합합니다."
    
    # feature loop
    - icon: "settings"
      title: "더 많은 제품 및 기능"
      content: "비교, e-sing, 검색, 워터마크 등 모든 GroupDocs 문서 자동화 API 세트를 살펴보세요!"


############################# Code samples ############################
# code_samples:
#   enable: true
#   title: "GroupDocs.전체 코드 샘플"
#   description: "C#, Java, TypeScript의 일반적인 GroupDocs.Total 작업의 일부 사용 사례"
#   items:
#     # code sample loop
#     - title: "DOCX 파일을 PDF로 렌더링하는 방법"
#       content: |
#        Microsoft Word나 기타 소프트웨어를 설치하지 않고도 DOCX 문서를 PDF로 렌더링할 수 있습니다. 웹 애플리케이션이든 데스크탑 애플리케이션이든 관계없이 애플리케이션 내에서 DOCX 파일을 쉽게 로드하고 볼 수 있습니다. 다음은 DOCX 파일을 PDF로 렌더링하는 방법의 예입니다.
#       samples:
#         - language: "C#"
#           color: "blue"
#           content: |
#             ```csharp {style=abap}   
#             // 렌더링할 DOCX 파일 로드
#             using (Viewer viewer = new Viewer("sample.docx"))
#             {
#               // DOCX를 PDF 파일로 렌더링
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
#             // 렌더링할 DOCX 파일 로드
#             try (Viewer viewer = new Viewer("sample.docx")) {
#                 // DOCX를 PDF 파일로 렌더링
#                 PdfViewOptions viewOptions = new PdfViewOptions();
#                 viewer.view(viewOptions);
#             }
#             ```
#         - language: "TypeScript"
#           color: "green"
#           content: |
#             ```javascript {style=abap}  
#             // 렌더링할 DOCX 파일 로드
#             const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
#             // DOCX를 PDF 파일로 렌더링
#             const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
#             viewer.view(viewOptions)
#             ```


############################# Formats ############################
formats:
  enable: true
  title:  "200개 이상의 파일 형식 지원"
  description: "GroupDocs.Total은 가장 널리 사용되는 [파일 형식](https://docs.groupdocs.com/total/net/supported-document-formats/) 작업을 지원합니다."


############################# Metrics ############################

metrics:
  enable: true
  title: "심층적인 지표 및 통계적 통찰력"
  description: "당사의 성과, 영향 및 성장에 대한 포괄적인 지표와 통계적 통찰력을 제공하는 주요 수치에 대한 자세한 분석을 살펴보세요."

  items:
    # metrics loop
    - number: "200+"
      title: "지원되는 형식"
      content: "문서, 이미지, CAD 도면을 포함한 200개 이상의 파일 형식을 번거로움 없이 쉽게 볼 수 있습니다. 포괄적인 보기 솔루션을 사용하여 호환성 장벽을 허물고 다양한 파일에 쉽게 액세스하세요."
    # metrics loop
    - number: "550K"
      title: "NuGet 다운로드"
      content: "NuGet 패키지 솔루션은 수많은 프로젝트에 원활한 통합과 귀중한 기능을 제공하여 개발자 커뮤니티에서 신뢰할 수 있고 널리 채택되는 리소스가 되었습니다."

    # metrics loop
    - number: "10+"
      title: "도서관"
      content: "우리 제품에는 성능 최적화를 위한 고급 기능을 제공하는 10개 이상의 라이브러리가 포함되어 있습니다. 이러한 라이브러리는 비교할 수 없는 기능으로 다양한 개발 요구 사항을 충족하도록 설계되었습니다."
    
    # metrics loop
    - number: "100+"
      title: "행복한 고객"
      content: "전 세계에서 가장 상징적인 브랜드에 서비스를 제공합니다. 수백 명이 GroupDocs.Total을 좋아하는 이유를 알아보세요! 원활한 탐색, 편리한 공동작업, 비교할 수 없는 사용 편의성을 살펴보세요. 지금 가입하세요!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "우리의 행복한 고객"
  description: "GroupDocs 라이브러리는 전 세계적으로 유명하고 뛰어난 브랜드에서 사용됩니다."

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
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Total 기능을 무료로 사용해 보거나 라이선스를 요청하세요"

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
  title: "일반적인 질문과 우려 사항"
  description: "자주 묻는 질문(FAQ) 섹션에서 일반적인 문의에 대한 답변을 찾아 문의 사항과 우려 사항을 빠르게 해결하세요."

  items:
    #  loop
    - question: "GroupDocs.Total은 무엇이며 다른 GroupDocs 제품과 어떻게 다릅니까?"
      answer: |
        GroupDocs.Total은 모든 개별 GroupDocs 제품의 기능을 단일 패키지로 결합한 포괄적인 제품군입니다. 이는 여러 가지 장점을 제공합니다.: <br><br>
        <ul>
          <li>
            <b>통합된 기능:</b> 단일 API 내에서 보기, 변환, 병합, 주석, 서명 등을 포함한 모든 문서 처리 기능에 액세스할 수 있습니다. <br><br>
          </li>
          <li>
            <b>향상된 호환성:</b> GroupDocs.Total은 지원되는 모든 파일 형식과 플랫폼에서 일관되고 안정적인 성능을 보장하여 별도의 제품을 사용할 때 발생할 수 있는 호환성 문제를 제거합니다. <br><br>
          </li>
          <li>
            <b>최적화된 패키지 크기:</b> 이 제품군은 단일 컴팩트 패키지로 제공되므로 별도의 설치로 개별 제품을 사용하는 것에 비해 리소스 소비를 줄이고 애플리케이션에 대한 통합을 단순화합니다.
          </li>
        <ul>

    #  loop
    - question: "개별 GroupDocs 제품을 구매하는 대신 GroupDocs.Total을 선호하는 이유는 무엇입니까?"
      answer: |
        단일 GroupDocs.Total 라이센스를 구입하는 것은 일반적으로 두 개 이상의 개별 GroupDocs 제품에 대한 라이센스를 구입하는 것보다 비용이 저렴합니다. <br>
        이는 여러 가지 주요 이점을 제공합니다.: <br><br>
        <b>비용 절감:</b> GroupDocs.Total은 개별 제품 구매에 비해 상당한 할인 혜택을 제공하므로 예산을 더욱 늘릴 수 있습니다. <br><br>
        <b>단순화된 관리:</b> GroupDocs.Total을 사용하면 하나의 라이선스로 모든 것을 관리할 수 있으므로 다양한 제품에 대해 여러 라이선스를 추적하고 유지 관리할 필요가 없습니다. 이를 통해 관리 작업이 단순화되고 전체 비용이 절감됩니다. <br><br>
        문서 관리 요구 사항에 맞는 비용 효율적이고 기능이 풍부한 솔루션을 찾고 있다면 GroupDocs.Total이 완벽한 선택입니다.

    #  loop
    - question: "GroupDocs.Total을 시작하려면 어떻게 해야 하나요?"
      answer: |
        무료 평가판을 시작하여 기능을 살펴보고 귀하의 요구 사항을 충족하는지 확인할 수 있습니다. GroupDocs는 통합 및 개발을 시작하는 데 도움이 되는 다양한 [문서](https://docs.groupdocs.com/total/) 리소스와 [튜토리얼](https://groupdocs.github.io)도 제공합니다.
        
    #  loop
    - question: "GroupDocs.Total은 기술 지원을 제공합니까?"
      answer: |
        예, GroupDocs는 GroupDocs.Total을 통한 귀하의 성공을 보장하기 위해 포괄적인 기술 지원을 제공합니다. 그들은 두 가지 옵션이 있습니다: <br><br>
        <b>[무료 지원 포럼](https://forum.groupdocs.com):</b> 이 포럼을 통해 귀하의 질문에 답변하고 경험을 바탕으로 솔루션을 제공할 수 있는 GroupDocs 직원과 연결할 수 있습니다. 일반적인 문제와 일반 문의사항에 대한 훌륭한 리소스입니다. <br><br>
        <b>[유료 지원 헬프데스크](https://helpdesk.groupdocs.com):</b> 이 옵션은 우선순위에 따라 지원을 제공합니다. 복잡한 문제가 발생하거나 더 빠른 해결이 필요한 경우 유료 지원을 통해 맞춤형 지원과 더 빠른 응답 시간을 제공받을 수 있습니다. <br><br>
        무료 옵션과 유료 옵션을 모두 제공함으로써 GroupDocs는 다양한 요구 사항과 예산에 맞춰 GroupDocs.Total을 통해 성공하는 데 필요한 지원을 보장합니다.

    #  loop
    - question: "GroupDocs.Total에는 문서 조작을 위한 추가 소프트웨어가 필요합니까?"
      answer: |
        GroupDocs.Total은 독립형 제품군이며 보기, 변환, 주석 달기 또는 서명과 같은 기본적인 문서 조작 작업을 위한 추가 타사 소프트웨어가 필요하지 않습니다. 그러나 사용하는 특정 기능(예: 스캔한 문서의 OCR)에 따라 외부 라이브러리가 필요할 수도 있습니다.

############################# Cloud and Apps ############################

cloud_links:
  enable: true
  title: "GroupDocs.Total 솔루션"
  description: "클라우드 REST API와 무료 온라인 앱을 사용하여 애플리케이션의 문서 처리 성능을 강화하세요."

  items:
    #  loop
    - icon: "groupdocs_total-cloud"
      title: "GroupDocs.Total Cloud"
      link: "https://products.groupdocs.cloud/total"
      content: "애플리케이션에서 Microsoft Office, PDF 문서 처리를 효율적으로 자동화하는 강력한 클라우드 솔루션입니다."

    #  loop
    - icon: "groupdocs_total-apps"
      title: "GroupDocs.Total Online Apps"
      link: "https://products.groupdocs.app"
      content: "문서 콘텐츠를 보고 편집하고, 다양한 Microsoft Office, OpenOffice, 이미지 및 기타 널리 사용되는 파일 형식을 비교 및 ​​병합할 수 있는 무료 온라인 웹 앱입니다."    

    #  loop
    - icon: "groupdocs_total-windows"
      title: "GroupDocs.Total Windows"
      link: "https://products.groupdocs.app/total/windows"
      content: "모든 운영 체제에서 문서를 변환, 주석 달기, 비교, 서명, 조합, 구문 분석, 분류, 수정 및 검색할 수 있는 오프라인 앱입니다."   

---