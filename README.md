# 2025-1A-T02-G57-PUBLICO
Repository for group 57 of class T02 (2025/1A)

Versions:
- [Em português](#-pt-br-)
- [in english](#-en-us-)


# [ PT-BR ]

**Publicado por:**  
João Vitor Oliveira Rodrigues  

**Desenvolvido por:**  
João Vitor Oliveira Rodrigues  

## Histórico do Documento  
| Versão   | Data        | Resumo                     | Autor(es)            |  
|----------|-------------|----------------------------|----------------------|  
| 0.0.1    | 28/02/2025  | Inicio do Documento        | João Rodrigues       |  


## Resumo Executivo

A solução proposta é um sistema modular que centraliza serviços essenciais para a operação de pequenos negócios, como controle de estoque em tempo real, registro automatizado de vendas e disponibilização de métricas financeiras. A integração dessas ferramentas visa substituir processos manuais e fragmentados – atualmente realizados, em sua maioria, por meio de planilhas ou anotações físicas – por um sistema intuitivo e acessível. A eficácia do modelo baseia-se no conjunto de desafios identificados pelo estudo [Fatores que contribuíram para o fechamento dos negócios](https://sebrae.com.br/sites/PortalSebrae/artigos/a-taxa-de-sobrevivencia-das-empresas-no-brasil,d5147a3a415f5810VgnVCM1000001b00320aRCRD), realizado pelo SEBRAE, que correlaciona diretamente a falta de uma gestão profissionalizada com a longevidade do negócio.




## Problemática

Os Microempreendedores Individuais (MEIs) correspondem a 53,4% dos negócios ativos no Brasil, totalizando cerca de 14,6 milhões de empreendimentos. No entanto, a longevidade desse segmento é comprometida por desafios sistêmicos: 29% encerram suas atividades em até cinco anos. Uma análise detalhada revela quatro eixos críticos que minam a sustentabilidade desses negócios.

**1. Deficiências na Gestão Empresarial** <br></br>
Ausência de estruturadas bem definidas nas práticas gerenciais. Estudos indicam que 62% dos MEIs não utilizam ferramentas básicas de controle financeiro, como registro de fluxo de caixa ou análise de custos, limitando o entendimento sobre a saúde econômica do negócio. Além disso, apenas 18% realizam planejamento anual, o que inviabiliza a antecipação de riscos sazonais e a adaptação a flutuações de demanda. Essa lacuna compromete não apenas a rentabilidade, mas também a capacidade de reinvestimento acertivo e crescimento.
<br></br>
<br></br>
**2. Complexidade Burocrática**  <br></br>
Atividades burocráticas — como cálculos tributários e emissão de documentos — consomem até 20% da jornada de trabalho, desviando o foco de atividades produtivas e estratégicas. A falta de familiaridade com obrigações legais e a sobrecarga de normas tributárias geram insegurança jurídica. Pequenas empresas acabam enfrentando multas por descumprimento de prazos ou erros em declarações, agravando a pressão financeira.
<br></br>
<br></br>
**3. Fragilidade Competitiva**  <br></br>
A maioria dos microempreendedores (53%) opera sem estratégias claras de diferenciação: não segmentam clientes, não analisam a concorrência e não monitoram tendências de mercado. Essa limitação reduz a capacidade de adaptação, posicionando os negócios em desvantagem frente a players organizados.

**Referências:**
- [Boletim Mapa de Empresas do Governo Federal, 2024](https://www.gov.br/empresas-e-negocios/pt-br/mapa-de-empresas/boletins/mapa-de-empresas-boletim-2o-quadrimestre-2024.pdf)
- [SEBRAE: Brasil tem quase 15 milhões de microempreendedores individuais](https://sebrae.com.br/sites/PortalSebrae/artigos/brasil-tem-quase-15-milhoes-de-microempreendedores-individuais,e538151eea156810VgnVCM1000001b00320aRCRD)
- [SEBRAE: Sobrevivência das empresas](https://sebrae.com.br/Sebrae/Portal%20Sebrae/Anexos/sobrevivencia-das-empresas-no-brasil-102016.pdf)


## Descrição do Empreendimento

O empreendimento consiste em uma plataforma de gestão simplificada para microempreendedores, focada nas rotinas essenciais do negócio. Desenvolvida em Electron.js, a solução é multiplataforma e funciona offline, garantindo acessibilidade mesmo em ambientes com conexão limitada.
A plataforma oferece um conjunto de funcionalidades modulares, permitindo que os usuários personalizem sua experiência. As principais funcionalidades incluem:
- **Gestão Financeira:** Controle de fluxo de caixa, categorização de receitas e despesas.
- **Cadastro de Produtos e Estoque:** Registro de produtos e serviços, controle de estoque com alertas de baixa e cálculo de margem baseado em custo e preço.
- **Gestão de Vendas:** Histórico de vendas e emissão de recibos.
- **Relatórios Essenciais:** Visão geral do faturamento e despesas, com exportação de dados em CSV para análise externa. <br></br>

A interface será intuitiva e otimizada para dispositivos básicos, com navegação simplificada. O modelo de negócios oferecerá uma versão gratuita com funcionalidades essenciais e um plano de pagamento mensal para recursos avançados.



## Objetivos do Negócio
O propósito central do empreendimento é ampliar a sustentabilidade dos MEIs, reduzindo sua taxa de falência precoce por meio de um sistema integrado de gestão que combina acessibilidade, eficiência e inteligência estratégica. Para alcançar essa meta, o projeto irá:

**Facilitar a profissionalização da gestão**
- Centralizar informações essenciais, eliminando a dependência de planilhas e anotações dispersas.
Oferecer um painel intuitivo com ferramentas que simplificam o controle financeiro, comercial e operacional.

**Garantir acessibilidade e inclusão digital**
- Desenvolver um sistema multiplataforma que opere offline e funcione mesmo em dispositivos com recursos limitados.
Criar uma interface amigável, com suporte a tutoriais e cartões explicativos, reduzindo a curva de aprendizagem.

**Oferecer um modelo de negócios sustentável e escalável**
- Disponibilizar planos acessíveis para diferentes perfis de usuários, desde uma versão gratuita até pacotes premium.
Monetizar por meio de assinaturas e parcerias estratégicas, garantindo viabilidade financeira.

## Descrição das Funcionalidades Principais
O sistema oferecerá funcionalidades essenciais para otimizar a operação diária de pequenos negócios, com ferramentas simples e eficazes para melhorar a gestão. As principais funcionalidades incluem:

- **Gestão Financeira:** O módulo de controle financeiro permitirá que os usuários acompanhem facilmente o fluxo de caixa, categorizem receitas e despesas, e monitorem a saúde financeira do negócio. A plataforma também permitirá a emissão de relatórios financeiros e contará com alertas para períodos de baixa de caixa ou pagamentos pendentes, evitando surpresas no fechamento do mês.

- **Cadastro de Produtos e Controle de Estoque:** Os usuários poderão registrar produtos e serviços, gerenciar o estoque e definir parâmetros como preço de venda e custo. O sistema monitorará os níveis de estoque em tempo real, com alertas automáticos para produtos abaixo do estoque mínimo, ajudando a evitar rupturas. Também serão disponibilizados relatórios de inventário para facilitar auditorias e ajustes.

- **Relatórios e Análises:** A plataforma fornecerá relatórios detalhados sobre o desempenho do negócio, incluindo faturamento, despesas e margem de lucro, com opção de exportação para formatos como CSV e PDF. Também serão apresentados gráficos e métricas-chave, como taxa de crescimento de vendas e distribuição de receitas, para apoiar a tomada de decisões estratégicas.

## Cronograma de Trabalho
### Módulo 1 - Estruturação e Prototipação

**Sprint 1 (Semana 1-2) - Pesquisa e Documentação**

- Levantamento de problemática e justificativa
- Elaboração do Resumo Executivo e Objetivos do Negócio
- Definição das funcionalidades principais

[ **Sprint 2 (Semana 3-4) - Planejamento e Arquitetura** ](./sprint-2/)

- Estruturação inicial da arquitetura do sistema
- Definição do banco de dados e fluxo de informações
- Criação da documentação em Docusaurus

[ **Sprint 3 (Semana 5-6) - Desenvolvimento do Protótipo** ](./sprint-3/)

- Revisão do conograma
- Prótotipo de interface
- Criação de fluxos da interface

[ **Sprint 4 (Semana 7-8) - Planejamento Estratégico** ](./sprint-4/)

- Diagrama de Soluções
- Modelo de Monetização

[ **Sprint 5 (Semana 9-10) - Preparação para Go To Market** ](./sprint-5/)

- Extruturação do Market Validation


---

<br></br>
<br></br>
<br></br>



# [ EN-US ]

**Published by:**  
João Vitor Oliveira Rodrigues  

**Developed by:**  
João Vitor Oliveira Rodrigues  

## Document History  
| Version   | Date        | Summary                     | Author(s)            |  
|----------|-------------|----------------------------|----------------------|  
| 0.0.1    | 28/02/2025  | Document Start             | João Rodrigues       |  


## Executive Summary

The proposed solution consists of a modular system that centralizes essential services for the operation of small businesses, such as real-time inventory control, automated sales recording, and the provision of financial metrics. The integration of these tools aims to replace manual and fragmented processes – mostly carried out in spreadsheets or physical notes – with an intuitive and accessible system. The model's effectiveness is based on the direct correlation between professionalized management and business longevity, aligning with demands identified based on [SEBRAE studies](https://sebrae.com.br/sites/PortalSebrae/artigos/a-taxa-de-sobrevivencia-das-empresas-no-brasil,d5147a3a415f5810VgnVCM1000001b00320aRCRD).


## Problem

Individual Microentrepreneurs (MEIs) represent 53.4% of active businesses in Brazil, totaling around 14.6 million enterprises. However, the longevity of this segment is compromised by systemic challenges: 29% close their activities within five years, according to SEBRAE data. A detailed analysis reveals four critical areas that undermine the sustainability of these businesses.

**1. Deficiencies in Business Management** <br></br>
Lack of structured management practices. Studies indicate that 62% of MEIs do not use basic financial control tools, such as cash flow tracking or cost analysis, limiting their understanding of the business's economic health. Additionally, only 18% engage in annual planning, making it impossible to anticipate seasonal risks and adapt to demand fluctuations. This gap compromises not only profitability but also the ability to reinvest effectively and grow.

**2. Bureaucratic Complexity**  <br></br>
Bureaucratic activities — such as tax calculations and document issuance — consume up to 20% of the workday, diverting focus from productive and strategic activities. The lack of familiarity with legal obligations and the overload of tax regulations generate legal insecurity. Small businesses end up facing fines for missing deadlines or errors in filings, worsening financial pressure.

**3. Competitive Fragility**  <br></br>
Most microentrepreneurs (53%) operate without clear differentiation strategies: they do not segment clients, analyze competitors, or monitor market trends. This limitation reduces the ability to adapt, putting businesses at a disadvantage compared to organized players.

**References:**<br></br>
- [Boletim Mapa de Empresas do Governo Federal, 2024](https://www.gov.br/empresas-e-negocios/pt-br/mapa-de-empresas/boletins/mapa-de-empresas-boletim-2o-quadrimestre-2024.pdf)
- [SEBRAE: Brazil has almost 15 million individual microentrepreneurs](https://sebrae.com.br/sites/PortalSebrae/artigos/brasil-tem-quase-15-milhoes-de-microempreendedores-individuais,e538151eea156810VgnVCM1000001b00320aRCRD)
- [SEBRAE: Business Survival](https://sebrae.com.br/Sebrae/Portal%20Sebrae/Anexos/sobrevivencia-das-empresas-no-brasil-102016.pdf)


## Business Description

The business consists of a simplified management platform for microentrepreneurs, focused on essential business routines. Developed in Electron.js, the solution is multiplatform and works offline, ensuring accessibility even in environments with limited connectivity.  
The platform offers a set of modular features, allowing users to customize their experience. The main features include:
- **Financial Management:** Cash flow control, categorization of income and expenses.
- **Product and Inventory Management:** Registering products and services, inventory control with low stock alerts, and margin calculation based on cost and price.
- **Sales Management:** Sales history and receipt issuance.
- **Essential Reports:** Overview of revenue and expenses, with data export in CSV for external analysis. <br></br>

The interface will be intuitive and optimized for basic devices, with simplified navigation. The business model will offer a free version with essential features and a monthly payment plan for advanced resources.


## Business Objectives
The central purpose of the business is to enhance the sustainability of MEIs, reducing their early failure rate through an integrated management system that combines accessibility, efficiency, and strategic intelligence. To achieve this goal, the project will:

**Facilitate the professionalization of management**
- Centralize essential information, eliminating dependence on spreadsheets and scattered notes.
- Offer an intuitive dashboard with tools that simplify financial, commercial, and operational control.

**Ensure accessibility and digital inclusion**
- Develop a multiplatform system that works offline and operates even on devices with limited resources.
- Create a user-friendly interface, with support for tutorials and explanatory cards, reducing the learning curve.

**Offer a sustainable and scalable business model**
- Provide affordable plans for different user profiles, from a free version to premium packages.
- Monetize through subscriptions and strategic partnerships, ensuring financial viability.

## Main Features Description
The system will offer essential features to optimize the daily operation of small businesses, with simple and effective tools to improve management. The main features include:

- **Financial Management:** The financial control module will allow users to easily track cash flow, categorize income and expenses, and monitor the business's financial health. The platform will also allow the generation of financial reports and will feature alerts for low cash periods or pending payments, preventing surprises at the end of the month.

- **Product Registration and Inventory Control:** Users will be able to register products and services, manage inventory, and set parameters such as selling price and cost. The system will monitor stock levels in real-time, with automatic alerts for products below the minimum stock level, helping to avoid stockouts. Inventory reports will also be available to facilitate audits and adjustments.

- **Reports and Analytics:** The platform will provide detailed reports on business performance, including revenue, expenses, and profit margin, with export options for formats like CSV. Graphs and key metrics, such as sales growth rate and revenue distribution, will also be displayed to support strategic decision-making.

## Work Schedule
### Module 1 - Structuring and Prototyping

**Sprint 1 (Week 1-2) - Research and Documentation**

- Problem identification and justification
- Creation of Executive Summary and Business Objectives
- Definition of main features

[ **Sprint 2 (Week 3-4) - Planning and Architecture** ](./sprint-2/)

- Initial system architecture structuring
- Database and information flow definition
- Documentation creation in Docusaurus

[ **Sprint 3 (Week 5-6) - Prototype Development** ](./sprint-3/)

- Review of schedule
- Interface prototype
- Creation of interface flows

[ **Sprint 4 (Week 7-8) - Integration and Testing** ](./sprint-4/)

- Backend structuring
- Usability tests and interface adjustments
- Implementation of reports and data export
- Simulation of usage by microentrepreneurs

[ **Sprint 5 (Week 9-10) - Refinement and Presentation** ](./sprint-5/)

- Performance optimization and bug fixes
- Final adjustments to user experience
- Creation of support materials
