---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Total"
product_tag: "total"

############################# Head ############################
head_title: "APIs de automação de documentos | APIs locais e serviços online"
head_description: "Automatize a manipulação de seus documentos de forma fácil e gratuita"

############################# Header ##########################
title: "Domine a automação de documentos com um pacote completo"
description: |
  Simplifique tarefas repetitivas de documentos e agilize seus fluxos de trabalho com apenas algumas linhas de código. APIs poderosas facilitam a integração, permitindo que você se concentre na inovação e não na infraestrutura.

  Converta, assine, visualize, anote - conquiste qualquer tarefa de documento com o mínimo de código. Do Word ao PDF, do Excel às imagens, lide com tudo perfeitamente. Menos código, maior impacto.

  Automatize tarefas documentais, aumente a eficiência e aja rapidamente com integração extremamente rápida. Economize tempo e recursos, concentrando-se no que realmente importa para o seu negócio.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Escolha sua plataforma"
  title: "Plataformas suportadas"
  description: "A biblioteca GroupDocs.Total suporta os seguintes sistemas operacionais e estruturas"
  details_link_title: "Saber mais"
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
        - content: "Mais de 200 formatos de arquivo"
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
        - content: "Mais de 200 formatos de arquivo"
          rows: "1"
        # features loop
        - content:  "Eclipse <br> NetBeans <br> IntelliJ Idea"
          rows: "3"

############################# Features ############################

features:
  enable: true
  title: "Conjunto de recursos do GroupDocs.Total"
  description: "Solução única que unifica a funcionalidade de todos os produtos GroupDocs individuais sob o mesmo teto e gerencia qualquer tarefa documental sem software de terceiros."

  items:
    # feature loop
    - icon: "view"
      title: "Ver documentos e imagens"
      content: "Renderize arquivos para visualizá-los nos formatos HTML, PDF, PNG e JPEG."

    # feature loop
    - icon: "convert"
      title: "Converter entre formatos"
      content: "Transforme arquivos de diferentes fontes em vários formatos de destino."

    # feature loop
    - icon: "merge"
      title: "Mesclar vários arquivos em um"
      content: "Combine perfeitamente vários PDFs, Office e outros em um único documento."
    
    # feature loop
    - icon: "settings"
      title: "Mais produtos e recursos"
      content: "Explore todo o conjunto de APIs de automação de documentos GroupDocs: compare, e-sing, pesquise, marca d'água e muito mais!"


############################# Code samples ############################
# code_samples:
#   enable: true
#   title: "Amostras de código GroupDocs.Total"
#   description: "Alguns casos de uso de operações GroupDocs.Total típicas em C#, Java, TypeScript"
#   items:
#     # code sample loop
#     - title: "Como renderizar arquivos DOCX em PDF"
#       content: |
#        Renderize documentos DOCX em PDF sem o Microsoft Word ou outro software instalado. Carregue e visualize facilmente arquivos DOCX em seu aplicativo, seja ele um aplicativo da web ou de desktop. Aqui está um exemplo de como renderizar um arquivo DOCX em PDF:
#       samples:
#         - language: "C#"
#           color: "blue"
#           content: |
#             ```csharp {style=abap}   
#             // Carregar arquivo DOCX para renderizar
#             using (Viewer viewer = new Viewer("sample.docx"))
#             {
#               // Renderizar DOCX em um arquivo PDF
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
#             // Carregar arquivo DOCX para renderizar
#             try (Viewer viewer = new Viewer("sample.docx")) {
#                 // Renderizar DOCX em um arquivo PDF
#                 PdfViewOptions viewOptions = new PdfViewOptions();
#                 viewer.view(viewOptions);
#             }
#             ```
#         - language: "TypeScript"
#           color: "green"
#           content: |
#             ```javascript {style=abap}  
#             // Carregar arquivo DOCX para renderizar
#             const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
#             // Renderizar DOCX em um arquivo PDF
#             const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
#             viewer.view(viewOptions)
#             ```


############################# Formats ############################
formats:
  enable: true
  title:  "Mais de 200 formatos de arquivo suportados"
  description: "GroupDocs.Total suporta operações com os mais populares [formatos de arquivo](https://docs.groupdocs.com/total/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Métricas detalhadas e insights estatísticos"
  description: "Mergulhe em uma análise detalhada de nossos principais números, fornecendo métricas abrangentes e insights estatísticos sobre nossas conquistas, impacto e crescimento."

  items:
    # metrics loop
    - number: "200+"
      title: "Formatos suportados"
      content: "Visualize facilmente mais de 200 formatos de arquivo, incluindo documentos, imagens e desenhos CAD, sem complicações. Quebre barreiras de compatibilidade e acesse diversos arquivos sem esforço com nossa solução de visualização abrangente."
    # metrics loop
    - number: "550K"
      title: "Downloads do NuGet"
      content: "Nossa solução de pacote NuGet se tornou um recurso confiável e amplamente adotado na comunidade de desenvolvedores, fornecendo integração perfeita e funcionalidades valiosas para inúmeros projetos."

    # metrics loop
    - number: "10+"
      title: "Bibliotecas"
      content: "Nosso produto inclui mais de 10 bibliotecas, oferecendo recursos avançados para otimizar o desempenho. Essas bibliotecas são projetadas para atender a diferentes necessidades de desenvolvimento com recursos incomparáveis."
    
    # metrics loop
    - number: "100+"
      title: "Clientes satisfeitos"
      content: "Servindo as marcas mais icônicas do mundo. Descubra por que centenas de pessoas adoram o GroupDocs.Total! Explore navegação perfeita, colaboração conveniente e facilidade de uso incomparável. Entrar!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Nossos clientes satisfeitos"
  description: "As bibliotecas GroupDocs são empregadas por marcas renomadas e distintas em todo o mundo."

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
  title: "Pronto para começar?"
  description: "Experimente os recursos do GroupDocs.Total gratuitamente ou solicite uma licença"

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
  title: "Perguntas e preocupações comuns"
  description: "Encontre respostas para perguntas comuns em nossa seção de perguntas frequentes para responder rapidamente às suas dúvidas e preocupações."

  items:
    #  loop
    - question: "O que é GroupDocs.Total e como ele difere de outros produtos GroupDocs?"
      answer: |
        GroupDocs.Total é um pacote abrangente que combina as funcionalidades de todos os produtos GroupDocs individuais em um único pacote. Isto oferece diversas vantagens: <br><br>
        <ul>
          <li>
            <b>Recursos unificados:</b> Você tem acesso a todos os recursos de processamento de documentos, incluindo visualização, conversão, mesclagem, anotação, assinatura e muito mais, em uma única API. <br><br>
          </li>
          <li>
            <b>Compatibilidade aprimorada:</b> GroupDocs.Total garante desempenho consistente e confiável em todos os formatos e plataformas de arquivo suportados, eliminando problemas de compatibilidade que podem surgir ao usar produtos separados. <br><br>
          </li>
          <li>
            <b>Tamanhos de pacote otimizados:</b> O pacote vem como um pacote único e compacto, reduzindo o consumo de recursos e simplificando a integração em seus aplicativos em comparação ao uso de produtos individuais com instalações separadas.
          </li>
        <ul>

    #  loop
    - question: "Por que preferir GroupDocs.Total em vez de comprar produtos GroupDocs individuais?"
      answer: |
        A compra de uma única licença GroupDocs.Total normalmente custa menos do que a compra de licenças para dois ou mais produtos GroupDocs individuais. <br>
        Isso se traduz em vários benefícios importantes para você: <br><br>
        <b>Poupança de custos:</b> GroupDocs.Total oferece um desconto significativo em comparação à compra de produtos individuais, permitindo que você estenda ainda mais seu orçamento. <br><br>
        <b>Gestão simplificada:</b> Com o GroupDocs.Total, você gerencia tudo sob uma licença, eliminando a necessidade de rastrear e manter várias licenças para produtos diferentes. Isso simplifica suas tarefas administrativas e reduz os custos gerais. <br><br>
        Se você está procurando uma solução econômica e rica em recursos para suas necessidades de gerenciamento de documentos, GroupDocs.Total é a escolha perfeita.

    #  loop
    - question: "Como posso começar a usar o GroupDocs.Total?"
      answer: |
        Você pode começar com uma avaliação gratuita para explorar os recursos e ver se ele atende às suas necessidades. O GroupDocs também oferece vários recursos de [documentação](https://docs.groupdocs.com/total/) e [tutoriais](https://groupdocs.github.io) para ajudar você a começar a integração e o desenvolvimento.
        
    #  loop
    - question: "O GroupDocs.Total oferece algum suporte técnico?"
      answer: |
        Sim, o GroupDocs oferece suporte técnico abrangente para garantir seu sucesso com o GroupDocs.Total. Eles têm duas opções: <br><br>
        <b>[Fórum de suporte gratuito](https://forum.groupdocs.com):</b> Este fórum permite que você se conecte com a equipe do GroupDocs, que pode responder às suas perguntas e oferecer soluções com base em sua experiência. É um ótimo recurso para problemas comuns e dúvidas gerais. <br><br>
        <b>[Helpdesk de suporte pago](https://helpdesk.groupdocs.com):</b> Esta opção fornece suporte prioritário. Se você encontrar problemas complexos ou precisar de soluções mais rápidas, o suporte pago oferece assistência personalizada e tempos de resposta mais rápidos. <br><br>
        Ao fornecer opções gratuitas e pagas, o GroupDocs atende a diferentes necessidades e orçamentos, garantindo que você tenha o suporte necessário para prosperar com o GroupDocs.Total.

    #  loop
    - question: "O GroupDocs.Total requer software adicional para manipulação de documentos?"
      answer: |
        GroupDocs.Total é um pacote independente e não requer nenhum software adicional de terceiros para tarefas básicas de manipulação de documentos, como visualização, conversão, anotação ou assinatura. No entanto, dependendo dos recursos específicos usados ​​(por exemplo, OCR para documentos digitalizados), bibliotecas externas podem ser necessárias.

############################# Cloud and Apps ############################

cloud_links:
  enable: true
  title: "GroupDocs.Soluções totais"
  description: "Aprimore o processamento de documentos em seus aplicativos com nossa API REST na nuvem e aplicativos on-line gratuitos"

  items:
    #  loop
    - icon: "groupdocs_total-cloud"
      title: "GroupDocs.Total Cloud"
      link: "https://products.groupdocs.cloud/total"
      content: "Soluções robustas em nuvem para automatizar com eficiência o processamento de documentos PDF do Microsoft Office em seus aplicativos."

    #  loop
    - icon: "groupdocs_total-apps"
      title: "GroupDocs.Total Online Apps"
      link: "https://products.groupdocs.app"
      content: "Aplicativos da web online gratuitos para visualizar e editar conteúdo de documentos, comparar e mesclar diferentes Microsoft Office, OpenOffice, imagens e outros formatos de arquivo populares."    

    #  loop
    - icon: "groupdocs_total-windows"
      title: "GroupDocs.Total Windows"
      link: "https://products.groupdocs.app/total/windows"
      content: "Aplicativos off-line para converter, anotar, comparar, assinar, montar, analisar, classificar, redigir e pesquisar documentos em qualquer sistema operacional."   

---