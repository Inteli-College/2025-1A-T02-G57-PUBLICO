# 2025-1A-T02-G57-PUBLICO
Repository for group 57 of class T02 (2025/1A)

**Publicado por:**  
João Vitor Oliveira Rodrigues  

**Desenvolvido por:**  
João Vitor Oliveira Rodrigues  

## Histórico do Documento  
| Versão   | Data        | Resumo                     | Autor(es)            |  
|----------|-------------|----------------------------|----------------------|  
| 0.0.1    | 28/02/2025  | Inicio do Documento        | João Rodrigues       |  


## Resumo Executivo

A solução proposta consiste em um sistema modular que centraliza serviços essenciais para a operação de pequenos negócios, como controle de estoque em tempo real, registro automatizado de vendas e disponibilização de métricas financeiras. A integração dessas ferramentas busca substituir processos manuais e fragmentados – hoje majoritariamente realizados em planilhas ou anotações físicas – por um sistema intuitivo e acessível. A eficácia do modelo fundamenta-se na correlação direta entre gestão profissionalizada e longevidade empresarial, alinhando-se às demandas identificadas com base em [estudos do SEBRAE](https://sebrae.com.br/sites/PortalSebrae/artigos/a-taxa-de-sobrevivencia-das-empresas-no-brasil,d5147a3a415f5810VgnVCM1000001b00320aRCRD).


## Problemática

Os Microempreendedores Individuais (MEIs) correspondem a 53,4% dos negócios ativos no Brasil, totalizando cerca de 14,6 milhões de empreendimentos. No entanto, a longevidade desse segmento é comprometida por desafios sistêmicos: 29% encerram suas atividades em até cinco anos, segundo dados do Sebrae. Uma análise detalhada revela quatro eixos críticos que minam a sustentabilidade desses negócios.

**1. Deficiências na Gestão Empresarial** <br></br>
Ausência de estruturadas bem definidas nas práticas gerenciais. Estudos indicam que 62% dos MEIs não utilizam ferramentas básicas de controle financeiro, como registro de fluxo de caixa ou análise de custos, limitando o entendimento sobre a saúde econômica do negócio. Além disso, apenas 18% realizam planejamento anual, o que inviabiliza a antecipação de riscos sazonais e a adaptação a flutuações de demanda. Essa lacuna compromete não apenas a rentabilidade, mas também a capacidade de reinvestimento acertivo e crescimento.
 
**2. Complexidade Burocrática**  <br></br>
Atividades burocráticas — como cálculos tributários e emissão de documentos — consomem até 20% da jornada de trabalho, desviando o foco de atividades produtivas e estratégicas. A falta de familiaridade com obrigações legais e a sobrecarga de normas tributárias geram insegurança jurídica. Pequenas empresas acabam enfrentando multas por descumprimento de prazos ou erros em declarações, agravando a pressão financeira.


**3. Fragilidade Competitiva**  <br></br>
A maioria dos microempreendedores (53%) opera sem estratégias claras de diferenciação: não segmentam clientes, não analisam a concorrência e não monitoram tendências de mercado. Essa limitação reduz a capacidade de adaptação, posicionando os negócios em desvantagem frente a players organizados.

**Referências:**<br></br>
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

- **Relatórios e Análises:** A plataforma fornecerá relatórios detalhados sobre o desempenho do negócio, incluindo faturamento, despesas e margem de lucro, com opção de exportação para formatos como CSV. Também serão apresentados gráficos e métricas-chave, como taxa de crescimento de vendas e distribuição de receitas, para apoiar a tomada de decisões estratégicas.

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

[ **Sprint 4 (Semana 7-8) - Integração e Testes** ](./sprint-4/)

- Estruturação do backend
- Testes de usabilidade e ajustes na interface
- Implementação de relatórios e exportação de dados
- Simulação de uso por microempreendedores

[ **Sprint 5 (Semana 9-10) - Refino e Apresentação** ](./sprint-5/)

- Otimização de performance e correção de bugs
- Ajustes finais na experiência do usuário
- Elaboração de materiais de suporte
