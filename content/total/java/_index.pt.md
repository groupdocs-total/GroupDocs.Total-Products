---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: pt
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
head_title: "Suíte completa de automação de documentos para aplicativos Java"
head_description: "GroupDocs.Total for Java é uma biblioteca abrangente de automação de documentos feita sob medida para desenvolvedores Java, oferecendo uma ampla gama de funcionalidades para lidar com diversos formatos de documentos, como PDF, Word, Excel, Imagem, HTML, Diagrama e muito mais."

############################# Header ############################
title: "Simplifique a automação de documentos<br> em seus projetos Java"
description: "Aprimore os recursos de automação de documentos: converta, visualize, compare, edite e assine facilmente mais de 200 formatos de arquivo."
words:
  for: "for"

actions:
  main: "Download grátis do Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-total/"
  alt: "Licenciamento"
  alt_link: "https://purchase.groupdocs.com/pricing/total/java"
  title: "Pronto para começar?"
  description: "Experimente os recursos do GroupDocs.Total gratuitamente ou solicite uma licença"

release:
  title: "Versão {0} lançada"
  notes: "Veja o que é novo"
  downloads: "Transferências"
  link: "https://releases.groupdocs.com/total/java/release-notes/latest/"

code:
  title: "Mesclar e visualizar arquivos do Word em Java"
  more: "Mais exemplos"
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
    // Carregue o arquivo DOCX de origem 
    Merger merger = new Merger("sample1.docx");
    
    // Adicione outro arquivo DOCX para mesclar
    merger.join("sample2.docx");

    // Mesclar arquivos DOCX e salvar o resultado
    merger.save("merged.docx");
    
    // Carregar arquivo DOCX mesclado no visualizador
    try (Viewer viewer = new Viewer("merged.docx"))
    {
      // Defina opções de saída HTML, um arquivo por página
      HtmlViewOptions viewOptions =   
      HtmlViewOptions.forEmbeddedResources("page{0}.html");
          
      // Renderize DOCX para HTML com recursos incorporados        
      viewer.view(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total em resumo"
  description: "Automatize a visualização de arquivos, converta, edite, compare, pesquise, coloque marcas d'água e outros fluxos de trabalho em aplicativos Java"
  features:
    # feature loop
    - title: "Combine o poder de vários produtos GroupDocs em uma solução única e abrangente"
      content: | 
        Você pode usar recursos de diferentes produtos GroupDocs para criar uma abordagem personalizada que atenda às suas necessidades específicas.
        <br><br>
        Por exemplo, você pode converter um arquivo Word em PDF e adicionar uma assinatura digital. Ou preencha os dados de um modelo de documento de um banco de dados ou extraia texto de uma imagem e depois traduza-o para outro idioma.
        <br><br>
        As possibilidades são infinitas!
          
    # feature loop
    - title: "Domine a diversidade de formatos de arquivo"
      content: "GroupDocs.Total for Java desbloqueia a compatibilidade com mais de 200 formatos de arquivo, permitindo processar documentos de todos os tipos populares. Desde formatos de escritório como Word e Excel até imagens, códigos e arquivos criptografados, nós ajudamos você."

    # feature loop
    - title: "Suporte multiplataforma"
      content: "Liberte-se das limitações da plataforma. GroupDocs.Total oferece compatibilidade entre plataformas, permitindo que você forneça desempenho ideal e disponibilidade de solução para usuários em qualquer sistema onde o Java possa ser instalado."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independência de plataforma"
  description: "GroupDocs.Total for Java suporta os seguintes sistemas operacionais, estruturas e gerenciadores de pacotes"
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
  title: "Formatos de arquivo suportados"
  description: |
    GroupDocs.Total for Java oferece suporte a operações com os seguintes [formatos de arquivo](https://docs.groupdocs.com/total/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument e formatos de texto
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
        ### Imagens, gráficos e diagramas
        * **Imagens rasterizadas:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Outro        
        * **Rede:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Arquivos:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Outro:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Recursos do GroupDocs.Total"
  description: "Gerencie, renderize e converta de forma abrangente PDFs e documentos do Office"

  items:
    # feature loop
    - icon: "viewer"
      title: "Extensa visualização de arquivos"
      content: "Visualização abrangente de documentos em mais de 180 formatos, incluindo HTML, imagens e PDF."

    # feature loop
    - icon: "conversion"
      title: "Conversão de formato"
      content: "Conversão perfeita entre vários formatos de documentos sem ferramentas externas."

    # feature loop
    - icon: "annotation"
      title: "Anotação interativa"
      content: "Recursos avançados de anotação para elementos de texto e imagem em documentos."

    # feature loop
    - icon: "comparison"
      title: "Comparação de conteúdo"
      content: "Comparação precisa de documentos, destacando diferenças de conteúdo e estilo."

    # feature loop
    - icon: "signature"
      title: "Flexibilidade de Assinatura"
      content: "Opções versáteis de assinatura, incluindo texto, imagem e assinaturas digitais."

    # feature loop
    - icon: "assembly"
      title: "Criação de documentos baseados em modelos"
      content: "Geração automatizada de documentos a partir de modelos e fontes de dados externas."

    # feature loop
    - icon: "metadata"
      title: "Gerenciamento de metadados"
      content: "Acesso e manipulação robustos de metadados para controle aprimorado de documentos."

    # feature loop
    - icon: "search"
      title: "Busca Avançada"
      content: "Funcionalidade de pesquisa poderosa com suporte para algoritmos difusos e sinônimos."

    # feature loop
    - icon: "watermark"
      title: "Controle de marca d’água"
      content: "Gerenciamento fácil de marcas d'água de documentos, oferecendo recursos de personalização e extração."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Amostras de código"
  description: "Alguns cenários do mundo real de GroupDocs.Total para uso de Java"
  items:
    # code sample loop
    - title: "Proteja e organize contratos: aplique marcas d'água e gerencie metadados em arquivo DOCX"
      content: |
        Proteja e organize seus documentos do Word de maneira eficiente com este exemplo de código abrangente. O exemplo abaixo permite que você implemente gerenciamento robusto de marcas d'água e metadados em seu fluxo de trabalho de contrato para maior segurança e gerenciamento de informações. Ele demonstra como: <br><br>
        <b>Aplicar uma marca d'água personalizada:</b> Adicione uma marca d'água de destaque 'Rascunho do contrato' ao documento para maior clareza e proteção visual. [Personalize a marca d'água](https://docs.groupdocs.com/watermark/java/adding-text-watermarks/) com opções de fonte, cor, opacidade e alinhamento. <br><br>
        <b>Aprimorar metadados:</b> [Modifique facilmente os metadados do documento](https://docs.groupdocs.com/metadata/java/working-with-metadata-in-word-processing-documents/) para incluir detalhes essenciais como autor, horário de criação, empresa, categoria, e palavras-chave para melhor organização e capacidade de pesquisa.
       
        {{< landing/code title="Java">}}
        ```java {style=abap}  
        import com.groupdocs.metadata.Metadata;
        import com.groupdocs.watermark.Watermark;
        import com.groupdocs.watermark.Watermark.Common;
        import com.groupdocs.watermark.Options.HtmlViewOptions;
        
        // Carregue seu documento em marca d'água
        Watermarker watermarker = new Watermarker("contract.docx");
        
        // Defina o texto e a fonte desejados para a marca d'água
        TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 36));
          
        // Escolha a cor da fonte e a opacidade, rotação e alinhamentos do texto
        watermark.setForegroundColor(Color.getRed());                                                            
        watermark.setHorizontalAlignment(HorizontalAlignment.Center);                                            
        watermark.setVerticalAlignment(VerticalAlignment.Center);                               

        // Aplicar a marca d'água
        watermarker.add(watermark);
        
        // Salve o documento resultante
        watermarker.save("watermarked-contract.docx");
        
        Metadata metadata = new Metadata("watermarked-contract.docx");        
        WordProcessingRootPackage root = metadata.getRootPackageGeneric();

        // Atualizar propriedades de metadados do documento
        root.getDocumentProperties().setAuthor("Name Surname");
        root.getDocumentProperties().setCreatedTime(new Date());
        root.getDocumentProperties().setCompany("Company Name");
        root.getDocumentProperties().setCategory("Work materials");
        root.getDocumentProperties().setKeywords("contract, watermarked");

        // Salvar documento com metadados atualizados
        metadata.save("contract-final.docx");                
        ```
        {{< /landing/code >}}

    # code sample loop
    - title: "Redação simplificada de documentos"
      content: |
        <b>Cenário:</b> Um grande escritório de advocacia frequentemente processa diversos documentos contendo informações confidenciais de clientes que devem ser editadas antes de serem compartilhadas com terceiros ou para divulgação pública. A redação manual dessas informações confidenciais pode ser tediosa, demorada e propensa a erros humanos. Para garantir eficiência, precisão e conformidade com as regulamentações de proteção de dados, o escritório de advocacia busca uma solução automatizada para agilizar o processo de redação de documentos. 
        
        <br>

        <b>Solução:</b>
        GroupDocs.Total automatiza o processo, acionando a redação ao receber um documento. Além disso, [opções flexíveis](https://docs.groupdocs.com/redaction/java/text-redactions/) permitem a personalização, permitindo definir regras, escolher modos de redação (por exemplo, blecaute, substituir por asteriscos) e especificar seções ou páginas específicas para redação. Por fim, [saída amigável](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) gera documentos editados em formato PDF para fácil compartilhamento e revisão, enquanto segurança e auditabilidade aprimoradas garantem todo o o processo é documentado para conformidade e responsabilidade. 
        <br><br>
        Esta solução abrangente capacita profissionais jurídicos e outras organizações a reduzir significativamente o tempo e os custos de redação, minimizar o erro humano e lidar consistentemente com informações confidenciais com confiança.        
              
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.redaction.Redaction;
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Carregar documento com dados privados no redator 
        Redactor redactor = new Redactor("customer-info.docx");
        
        // Configure e personalize opções de redação 
        redactor.apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
        
        // Aplicar redações e salvar o resultado 
        redactor.save();

        // Carregar arquivo editado para revisão 
        Viewer viewer = new Viewer("customer-info.docx");
        
        // Configure o PDF como formato de visualização desejado       
        PdfViewOptions viewOptions = new PdfViewOptions("redacted-info.pdf");

        // Salvar documento em PDF      
        viewer.view(viewOptions);        
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Avaliações de produtos GroupDocs"
# description: "Não acredite apenas na nossa palavra. Veja o que outros desenvolvedores dizem sobre nossas APIs"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Excelente atendimento e excelentes produtos. Eles foram extremamente úteis e receptivos durante o processo de implementação do GroupDocs.Viewer para .NET, não posso recomendá-los o suficiente."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Depois de implementar e usar GroupDocs.Viewer for Java no projeto parece estar funcionando muito bem. Eu testei com muitos documentos e até agora tudo bem. Tudo o que joguei nele é renderizado perfeitamente e parece tão bom quanto em um visualizador de PDF ou MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---