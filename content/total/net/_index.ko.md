---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ko
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
head_title: ".NET 애플리케이션을 위한 올인원 문서 자동화 라이브러리"
head_description: "GroupDocs.Total for .NET은 .NET 개발자를 위한 올인원 문서 자동화 API 제품군으로, PDF, Word, Excel, 이미지, HTML, 다이어그램 등을 포함한 다양한 문서 형식 작업을 위한 포괄적인 도구 세트를 제공합니다. ."

############################# Header ##########################
title: ".NET 앱에서<br> 문서 자동화를 간소화하세요"
description: "문서 자동화 잠금 해제: 200개 이상의 형식을 쉽게 변환하고, 보고, 비교하고, 편집하고 서명합니다."
words:
  for: "for"

actions:
  main: "무료 NuGet 다운로드"
  main_link: "https://www.nuget.org/packages/GroupDocs.Total"
  alt: "라이선스"
  alt_link: "https://purchase.groupdocs.com/pricing/total/net"
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Total 기능을 무료로 사용해 보거나 라이선스를 요청하세요"

release:
  title: "버전 {0} 출시됨"
  notes: "새로운 소식 보기"
  downloads: "다운로드"
  link: "https://releases.groupdocs.com/total/net/release-notes/latest/"

code:
  title: "C#에서 Word 파일 병합 및 보기"
  more: "더 많은 예시"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-.NET"
  install: "dotnet add package GroupDocs.Total"
  content: |
    ```csharp {style=abap} 
    // 소스 DOCX 파일 로드
    using (Merger merger = new Merger("sample1.docx"))
    {
        // 병합할 다른 DOCX 파일 추가
        merger.Join("sample2.docx");

        // DOCX 파일을 병합하고 결과를 저장합니다.
        merger.Save("merged.docx");
    }

    // 병합된 DOCX 파일을 뷰어에 로드
    using (var viewer = new Viewer("merged.docx"))
    {
        // 출력 HTML 옵션 설정(페이지당 파일 1개)
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // 포함된 리소스를 사용하여 DOCX를 HTML로 렌더링        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total 개요"
  description: ".NET 애플리케이션에서 파일 보기, 변환, 편집, 비교, 검색, 워터마킹 및 기타 워크플로우를 자동화합니다."
  features:
    # feature loop
    - title: "여러 GroupDocs 제품의 강력한 기능을 하나의 포괄적인 솔루션으로 결합"
      content: | 
        다양한 GroupDocs 제품의 기능을 사용하여 특정 요구 사항에 맞는 사용자 정의 접근 방식을 만들 수 있습니다.
        <br><br>
        예를 들어 Word 파일을 PDF로 변환한 다음 디지털 서명을 추가할 수 있습니다. 또는 데이터베이스에서 문서 템플릿 데이터를 채우거나 이미지에서 텍스트를 추출한 다음 다른 언어로 번역하세요.
        <br><br>
        가능성은 무궁무진합니다!
          
    # feature loop
    - title: "다양한 파일 형식을 마스터하세요"
      content: ".NET용 GroupDocs.Total은 200개 이상의 파일 형식과의 호환성을 보장하므로 널리 사용되는 모든 유형의 문서를 처리할 수 있습니다. Word 및 Excel과 같은 사무용 형식부터 이미지, 코드, 암호화된 파일까지 모든 것을 다룹니다."

    # feature loop
    - title: "크로스 플랫폼 지원"
      content: "플랫폼 제한에서 벗어나세요. GroupDocs.Total은 플랫폼 간 호환성을 제공하므로 .NET을 설치할 수 있는 모든 시스템의 사용자에게 최적의 성능과 솔루션 가용성을 제공할 수 있습니다."

############################# Platforms ############################
platforms:
  enable: true
  title: "플랫폼 독립성"
  description: ".NET용 GroupDocs.Total은 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다."
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
  title: "지원되는 파일 형식"
  description: |
    .NET용 GroupDocs.Total은 다음 [파일 형식](https://docs.groupdocs.com/total/net/supported-document-formats/)을 사용한 작업을 지원합니다.
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument 및 텍스트 형식
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
        ### 이미지, 그래픽 및 다이어그램
        * **래스터 이미지:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### 다른        
        * **편물:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **아카이브:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **다른:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Total 전체 기능"
  description: "PDF 및 Office 문서를 종합적으로 관리, 렌더링 및 변환합니다."

  items:
    # feature loop
    - icon: "viewer"
      title: "광범위한 파일 보기"
      content: "HTML, 이미지, PDF를 포함한 180개 이상의 형식에 대한 포괄적인 문서 보기입니다."

    # feature loop
    - icon: "conversion"
      title: "형식 변환"
      content: "외부 도구 없이 다양한 문서 형식 간의 원활한 변환."

    # feature loop
    - icon: "annotation"
      title: "대화형 주석"
      content: "문서 내의 텍스트 및 이미지 요소에 대한 고급 주석 기능입니다."

    # feature loop
    - icon: "comparison"
      title: "콘텐츠 비교"
      content: "내용과 스타일의 차이를 강조하여 정확한 문서 비교."

    # feature loop
    - icon: "signature"
      title: "시그니처 유연성"
      content: "텍스트, 이미지, 디지털 서명을 포함한 다양한 서명 옵션."

    # feature loop
    - icon: "assembly"
      title: "템플릿 기반 문서 생성"
      content: "템플릿 및 외부 데이터 소스에서 자동 문서 생성."

    # feature loop
    - icon: "metadata"
      title: "메타데이터 관리"
      content: "향상된 문서 제어를 위한 강력한 메타데이터 액세스 및 조작."

    # feature loop
    - icon: "search"
      title: "고급 검색"
      content: "퍼지 및 동의어 알고리즘을 지원하는 강력한 검색 기능."

    # feature loop
    - icon: "watermark"
      title: "워터마크 제어"
      content: "사용자 정의 및 추출 기능을 제공하는 간편한 문서 워터마크 관리."

############################# Code samples ############################
code_samples:
  enable: true
  title: "코드 샘플"
  description: ".NET 사용을 위한 GroupDocs.Total의 일부 실제 시나리오"
  items:
    # code sample loop
    - title: "계약서 보호 및 구성: DOCX 파일에서 워터마크를 적용하고 메타데이터를 관리합니다."
      content: |
        이 포괄적인 코드 예제를 사용하여 Word 문서를 효율적으로 보호하고 구성하세요. 아래 샘플을 사용하면 보안 및 정보 관리 강화를 위해 계약 워크플로 내에서 강력한 워터마킹 및 메타데이터 관리를 구현할 수 있습니다. 다음 방법을 보여줍니다. <br><br>
        <b>사용자 정의 워터마크 적용:</b> 시각적 명확성과 보호를 위해 문서에 눈에 띄는 '계약 초안' 워터마크를 추가합니다. 글꼴, 색상, 불투명도, 정렬 옵션을 사용하여 [워터마크를 사용자 정의](https://docs.groupdocs.com/watermark/net/basic-usage/customize/)하세요. <br><br>
        <b>메타데이터 향상:</b> 작성자, 생성 시간, 회사, 카테고리, 키워드 등 필수 세부정보를 포함하도록 쉽게 [문서 메타데이터 수정](https://docs.groupdocs.com/metadata/net/working-with-metadata-in-wordprocessing-documents/) 향상된 구성 및 검색 가능성을 위해.
       
        {{< landing/code title="C#">}}
        ```csharp {style=abap}  
        using GroupDocs.Metadata;
        using GroupDocs.Watermark;
        using GroupDocs.Watermark.Common;
        using GroupDocs.Watermark.Watermarks;
        
        // 문서를 워터마커에 로드
        using (Watermarker watermarker = new Watermarker("contract.docx"))
        {
            // 워터마크에 원하는 텍스트와 글꼴을 설정하세요.
            TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 60, FontStyle.Bold));
            
            // 글꼴 색상과 텍스트 불투명도, 회전 및 정렬을 선택하세요.
            watermark.ForegroundColor = Color.DarkGreen;
            watermark.Opacity = 0.5;
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            
            // 워터마크 적용
            watermarker.Add(watermark);
            
            // 결과 문서를 저장
            watermarker.Save("watermarked-contract.docx");
        }

        using (Metadata metadata = new Metadata("watermarked-contract.docx"))
        {
          var root = metadata.GetRootPackage<WordProcessingRootPackage>();

          // 문서 메타데이터 속성 업데이트
          root.DocumentProperties.Author = "Name Surname";
          root.DocumentProperties.CreatedTime = DateTime.Now;
          root.DocumentProperties.Company = "Company Name";
          root.DocumentProperties.Category = "Work materials";
          root.DocumentProperties.Keywords = "contract, watermarked";

          // 업데이트된 메타데이터로 문서 저장
          metadata.Save("contract-final.docx");
        }        
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "간소화된 문서 편집"
      content: |
        <b>대본:</b> 대형 법률 회사는 제3자와 공유하거나 공개하기 전에 수정해야 하는 고객 기밀 정보가 포함된 다양한 문서를 자주 처리합니다. 이러한 민감한 정보를 수동으로 수정하는 것은 지루하고 시간이 많이 걸리며 인적 오류가 발생하기 쉽습니다. 효율성, 정확성, 데이터 보호 규정 준수를 보장하기 위해 법률 회사는 문서 편집 프로세스를 간소화하는 자동화된 솔루션을 찾고 있습니다. 
        
        <br>

        <b>해결책:</b>
        GroupDocs.Total은 프로세스를 자동화하여 문서 수신 시 수정을 시작합니다. 또한 [유연한 옵션](https://docs.groupdocs.com/redaction/net/text-redactions/)을 사용하면 규칙을 설정하고 수정 모드(예: 중단, 별표로 대체)를 선택하고 지정할 수 있어 맞춤설정이 가능합니다. 교정할 특정 섹션이나 페이지. 마지막으로 [사용자 친화적인 출력](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)은 손쉬운 공유 및 검토를 위해 PDF 형식으로 수정된 문서를 생성하는 동시에 향상된 보안 및 감사 기능을 통해 전체 문서를 보장합니다. 규정 준수 및 책임에 대해 프로세스가 문서화됩니다. 
        <br><br>
        이 포괄적인 솔루션을 통해 법률 전문가 및 기타 조직은 수정 시간과 비용을 크게 줄이고 인적 오류를 최소화하며 민감한 정보를 자신 있게 일관되게 처리할 수 있습니다.        
              
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Redaction;
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;

        // 개인 데이터가 포함된 문서를 교정기에 로드 
        using (Redactor redactor = new Redactor("customer-info.docx"))
        {
          // 교정 옵션 설정 및 사용자 정의 
          redactor.Apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
          // 교정 적용 및 결과 저장 
          redactor.Save();
        }

        // 검토를 위해 수정된 파일 로드 
        using (var viewer = new Viewer("customer-info.docx"))
        {
          // PDF를 원하는 보기 형식으로 설정       
          var viewOptions = new PdfViewOptions("redacted-info.pdf");

          // 문서를 PDF로 저장      
          viewer.View(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs 제품 리뷰"
# description: "우리의 말만 받아들이지 마십시오. 다른 개발자가 우리 API에 대해 어떻게 말하는지 확인하세요."

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "우수한 서비스와 우수한 제품. .NET용 GroupDocs.Viewer 구현 프로세스 동안 매우 도움이 되고 응답이 빨랐기 때문에 충분히 추천할 수는 없습니다."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "프로젝트에서 Java용 GroupDocs.Viewer를 구현하고 사용한 후에는 매우 잘 작동하는 것으로 보입니다. 나는 많은 문서를 가지고 테스트해 보았는데 지금까지는 아주 좋았다. 내가 던진 모든 것은 PDF 뷰어나 MS Word에서와 마찬가지로 멋지게 렌더링되고 보기에도 좋습니다."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---