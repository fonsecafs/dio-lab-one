# dio-lab-one
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

# Cloud
  A cloud, ou computação em nuvem, é um data center que foi virtualizado, refere-se ao fornecimento de serviços de computação, como servidores, armazenamento, bancos de dados, redes, software e muito mais, através da internet "a nuvem". 
  Em vez de hospedar esses recursos localmente em um computador ou servidor físico, eles são disponibilizados online por meio de provedores de serviços, como Amazon Web Services (AWS), Microsoft Azure e Google Cloud Platform (GCP).

# Tipos de Nuvem
  Nuvem Privada
    A nuvem privada no Azure refere-se à configuração de um ambiente de nuvem que é dedicado a uma única organização, oferecendo maior controle, segurança e personalização em comparação a uma nuvem pública, onde os recursos são compartilhados entre várias organizações. A nuvem privada é ideal para empresas que têm requisitos rigorosos de conformidade ou regulamentação, como bancos ou órgãos governamentais.

  Nuvem Publica
    Uma entrega de diversos serviços e recursos a vários clientes, por meio de um único proveide.
	  Exemplo a Microsoft Azure, tem diversos datacenter espalhados no mundo, que entregam serviços de computação, IA, banco de dados e segurança, para quem puder pagar pela compra.	
	  Isso é muito utilizado por empresas multinacionais.	
	  Nenhuma despesa de capital para escalar verticalmente, também conhecida como CAPEX, é um modelo de consumo.
	  Isto significa, que ao comprar você não paga na hora, você vai pagar ao final de 30 dias, conforme os recursos utilizados/consumidos, tempo de utilização, armazenamento, segurança, requisições etc.
	  A facilidade os aplicativos podem ser provisionados e desprovisionados rapidamente, é bem simples basta excluir e colocar o correto.
	  As organizações e clientes, pagam somente por aquilo que estou utilizando.
  
  Tipos de Híbrida
    É o melhor dos dois mundos, porque tem a nuvem privada e publica, neste cenário a nuvem privada e publica se comunicam.
		A Azure Nuvem Híbrida é uma solução de computação em nuvem oferecida pela Microsoft Azure que combina o uso de nuvem pública e nuvem privada, permitindo que as empresas integrem e gerenciem recursos locais (on-premises) com a infraestrutura em nuvem. Isso permite que as organizações aproveitem as vantagens da nuvem pública — como escalabilidade, flexibilidade e economia de custos — sem abandonar os sistemas e dados locais que precisam manter por questões de conformidade, segurança ou desempenho.
  	Características da Nuvem Híbrida com Azure:
	  Flexibilidade: A nuvem híbrida permite que as empresas escolham onde hospedar diferentes cargas de trabalho, de acordo com suas necessidades. Aplicações que exigem alta performance e baixo tempo de latência podem rodar localmente, enquanto serviços que exigem escalabilidade podem ser movidos para a nuvem pública.
    Gerenciamento Unificado: O Azure oferece ferramentas como o Azure Arc para centralizar a gestão de recursos locais e na nuvem. Isso permite que as equipes de TI gerenciem tanto o ambiente on-premises quanto o ambiente de nuvem de uma única interface.
	  Segurança e Conformidade: Empresas que precisam de controle mais rígido sobre dados confidenciais ou que possuem requisitos regulatórios podem manter dados sensíveis no local (nuvem privada) e mover apenas partes menos críticas para a nuvem pública.
	  Escalabilidade sob demanda: As empresas podem usar a nuvem híbrida para escalar suas operações rapidamente quando necessário, sem a necessidade de fazer grandes investimentos em infraestrutura local.
	  Conectividade Integrada: Ferramentas como o Azure Stack permitem a extensão dos serviços da nuvem Azure para data centers locais, permitindo a integração perfeita entre os dois ambientes.
	  Em resumo, o Azure Nuvem Híbrida oferece uma solução eficiente para organizações que querem combinar o melhor de ambos os mundos — nuvem pública e infraestrutura local — para otimizar seus recursos e operações de TI.

  Nuvem Multicloud
    Neste caso a empresa que trabalha em paralelo com nuvens privadas, nuvens publicas da Azure, AWS e GCP.
  	A nuvem multicloud (ou multicloud) é uma estratégia que envolve o uso de mais de um provedor de serviços de nuvem, geralmente de diferentes fornecedores, para otimizar e diversificar os serviços de computação em nuvem de uma empresa. Ao adotar a abordagem multicloud, uma organização pode escolher o melhor provedor para cada necessidade específica (como armazenamento, banco de dados, processamento, etc.), em vez de depender de um único provedor de nuvem.
  	Essa abordagem oferece várias vantagens:
  	Redundância e Resiliência: Caso um provedor enfrente problemas ou uma interrupção, os serviços críticos podem continuar operando em outra nuvem.
	  Flexibilidade: As empresas podem utilizar diferentes provedores para necessidades específicas. Por exemplo, uma nuvem pode ser usada para processamento intensivo, enquanto outra é mais adequada para armazenamento.
	  Evitar Dependência de um Único Fornecedor: Também chamada de "vendor lock-in", evita que a empresa fique presa às condições e limitações de um único provedor de nuvem.
	  Melhor Custo-Benefício: Permite comparar preços e escolher as melhores soluções conforme o orçamento e as necessidades de negócios.
	  Os principais provedores de nuvem incluem Amazon Web Services (AWS), Microsoft Azure, Google Cloud, entre outros, e as empresas podem combinar os serviços oferecidos por eles para criar uma infraestrutura mais robusta e eficiente.

   Obs: a Nuvem Multicloud não cai na prova de certificação da AZ-900

# Definição CapEx e OpEx
  CapEx 
    É a abreviação de Capital Expenditure em português, Despesa de Capital.
    Refere-se aos gastos que uma empresa realiza para adquirir, melhorar ou manter ativos físicos de longo prazo, como imóveis, equipamentos, infraestrutura, máquinas, veículos e tecnologia. Esses investimentos geralmente visam aumentar a capacidade produtiva da empresa ou melhorar sua eficiência operacional.
    Os principais exemplos de CapEx incluem:
      Compra de novos equipamentos ou maquinário;
      Aquisição de imóveis ou terrenos;
      Construção ou reforma de instalações;
      Atualização de sistemas tecnológicos;
      
  OpEx
    É a abreviação de Operational Expenditure em português, Despesa Operacional.
    Refere-se aos custos contínuos necessários para operar um negócio no dia a dia. Isso inclui despesas como aluguel, salários, utilidades, manutenção de equipamentos, marketing, entre outros. Diferentemente de CapEx (Capital Expenditure), que são investimentos em ativos de longo prazo, o OpEx cobre despesas que ocorrem regularmente para manter as operações funcionando.
    Empresas geralmente buscam maneiras de otimizar ou reduzir o OpEx para aumentar a eficiência e melhorar a lucratividade.

# Certificação
  A certificação AZ-900 (Microsoft Azure Fundamentals) é uma certificação básica para quem deseja aprender sobre o Microsoft Azure. Ela é indicada para iniciantes e aborda conceitos fundamentais de computação em nuvem e os principais serviços oferecidos pela Azure.
  Para abrir uma conta, será necessário fornecer um cartão. 
  A recomendação é usar um cartão de crédito virtual com validade de 24 horas, dessa maneira, evitamos a utilização inadvertida de recursos que possam resultar em cobranças não desejadas.

# Git Hub
  É uma plataforma de hospedagem de código e documentação que utiliza o sistema de controle de versão Git. 
  Ela permite que desenvolvedores armazenem, compartilhem e colaborem em projetos de software. 
  Com GitHub, é possível versionar o código, acompanhar mudanças, resolver conflitos e trabalhar em equipe de forma eficiente e organizada através dos repositórios e Branches.
  É uma espécie de LinkedIn dos desenvolvedores.
  
      
