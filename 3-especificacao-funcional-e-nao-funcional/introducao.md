#  	 	3. ESPECIFICAÇÃO FUNCIONAL E NÃO FUNCIONAL

#  3.1 Introdução

  
 O principal propósito da especificação de requisitos está diretamente relacionado à obtenção do detalhamento do programa \(finalidade, escopo, definições, acrônimos, abreviações, referências etc.\), com o intuito de entregar o produto com a melhor qualidade, confiabilidade e que satisfaçam às reais necessidades do cliente dentro de prazo e orçamento adequados.

### 3.1.1 Convenções, termos e abreviações.

 A correta interpretação deste documento exige o conhecimento de convenções e termos específicos e abreviações descritas a seguir.

###   3.1.2 Identificação dos requisitos 

 Os requisitos devem ser identificados com um identificador único. A numeração inicia com o identificador \[RF001\] ou \[NF001\] e prossegue sendo incrementada à medida que forem surgindo novos requisitos.

 A nomenclatura dos fluxos secundários é dada por uma sigla e por um número. A sigla deve ser FA para fluxos alternativos e FE para fluxos de erro. O número é um sequencial que inicia de 001. Um exemplo de fluxo alternativo é \[FA001\], de fluxo de erro é \[FE001\]. A nomenclatura reinicia a cada requisito.

### 3.1.3 Identificação dos processos

 A nomenclatura dos processos segue a mesma regra da nomenclatura de requisitos, ou seja, cada processo é identificado através do identificador do processo na subseção.

### 3.1.4  Requisitos Funcionais e não Funcionais

Os requisitos são classificados em:

 - Funcionais - RF- descrever as funcionalidades do sistema desejado pelo cliente, ou seja, o que se espera que o programa faça;

 - Não-funcionais - NF – buscar as qualidades e restrições globais do programa relacionados com manutenção, uso, desempenho, custo, interface, etc.

 A imagem abaixo demonstra ilustrativamente a estrutura para obtenção dos requisitos.

  
  


![](data:image/png;base64,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)

  
  


1. 1. 1. ###  Regra de Negócio

  
  


 Os modelos são considerados uma prática que ajuda a economizar tempo nos processos de planejamento e padronização dos projetos dentro de qualquer empresa, garantindo que a qualidade no gerenciamento seja devidamente cumprida.

 A tradução mais adequada seria como “guia” para a viabilização de uma ideia, de um desejo, é um documento que procura estabelecer a essência da operação da instituição. Ele é atemporal, faz análises sobre o cenário em que o negócio será inserido. Também faz definições sobre o que é o negócio, sua razão de existir, como estruturá-lo, suas funcionalidades e as alternativas às possíveis necessidades de desvio de percurso.

  
  


1. 1. 1. ###  Linguagem

  
  


 A equipe de gerência de projetos definiu a ferramenta Unified Modeling Language - UML \(Linguagem de Modelagem Unificada\) por contemplar uma série de notações para a construção de diagramas representando diferentes aspectos de um programa, além de não estar presa a metodologias ou tecnologias específicas de desenvolvimento.

 A UML é uma linguagem padrão para visualização, especificação, construção e documentação de um aplicativo ou projeto de software, e objetiva aumentar a produtividade, aperfeiçoar as etapas que envolvem o desenvolvimento de um sistema, aumentando assim a qualidade do produto a ser implementado. A ideia e prover uma visão lógica de todo o processo de forma a facilitar a implementação física do mesmo.

  
  


1. 1. 1. ###  Cliente

  
  


 A Rede de Ensino JK – Faculdade JK observou a necessidade de uma melhor formação educacional dos graduandos no tocante aos Cursos de Enfermagem e Radiologia concernente à valorização do conteúdo programático, como proposta da formação profissional dos alunos da área hospitalar.

 O trabalho a ser desenvolvido é referente à decisão apresentada pelo cliente, ou seja, WIKI - APRENDIZADO DE FERRAMENTAS DO POLO ASA SUL DA JK – WIKI JK.

 O artefato Documento de Especificação Funcional - DEF, após a apuração de todos os pontos, entregará a equipe de programadores as informações particularizadas do projeto para o desenvolvimento e implementação.

 Ao final do processo teremos documento de requisitos bem definido e entendido por todos os intervenientes do projeto, tais como: clientes, desenvolvedores, líderes, analistas, gerentes, patrocinadores, etc.

  
  


1. 1. 1. ###  Prioridades dos requisitos

  
  


 Para estabelecer a prioridade dos requisitos, na seção 5, foi adotada as denominações “essencial”, “importante” e “desejável”.

 • Essencial é o requisito sem o qual o sistema não entra em funcionamento. Requisitos essenciais são requisitos imprescindíveis, que têm que ser implementados impreterivelmente.

 • Importante é o requisito sem o qual o sistema entra em funcionamento, mas de forma não satisfatória. Requisitos importantes devem ser implementados, mas, se não forem, o sistema poderá ser implantado e usado mesmo assim.

 • Desejável é o requisito que não compromete as funcionalidades básicas do sistema, isto é, o sistema pode funcionar de forma satisfatória sem ele. Requisitos desejáveis podem ser deixados para versões posteriores da solução, caso não haja tempo hábil para programar-los na versão que está sendo especificada.

  
  

