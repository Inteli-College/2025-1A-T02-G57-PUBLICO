# Plano de Monetização

---

## Introdução  
Este plano de monetização foi desenvolvido com base nas inter-relações funcionais descritas na documentação [**Diagrama de Soluções**](/sprint-4/diagrama_solucoes.md), que organiza a plataforma em três domínios independentes (**PDV**, **Finanças** e **Clientes**), com dependências e conexões críticas entre suas ferramentas.  

A estrutura modular dos domínios, combinada com a hierarquia de ferramentas principais/secundárias e conexões cruzadas (ex: Registro de Vendas → Fluxo de Caixa), permite a criação de planos escaláveis que acompanham o crescimento progressivo de um MEI, desde a fase inicial até a maturidade operacional.  

---

## Planos por Domínio  

| Plano         | Domínios Incluídos       | Conexões           | Ferramentas                                  | Recursos Adicionais                  | Limitações                           | Preço (Sugestão)  |  
|---------------|--------------------------|--------------------|----------------------------------------------|---------------------------------------|---------------------------------------|-------------------|  
| **Grátis**    | 1 (Escolha do usuário)   | -                  | Ferramentas **principais** do domínio        | -                                     | - PDV/Finanças: 500 transações/mês<br>- Máx. 20 clientes cadastrados | **R$ 0/mês**      |  
| **Básico**    | 1                        | Conexões básicas   | Todas as ferramentas do domínio              | -                                     | - Relatórios cruzados não disponíveis | **R$ 49,90/mês**  |  
| **Integrado** | Todos os domínios        | Conexões avançadas | Ferramentas principais, secundárias<br>e integrações | -                                     | - Máximo de **4 usuários** ativos     | **R$ 69,90/mês**  |  
| **Premium**   | Todos os domínios        | Automações         | Funcionalidades premium                      | - Armazenamento em nuvem<br>- Suporte prioritário | - Personalização limitada            | **R$ 149,90/mês** |  
---

## Lógica de Monetização Baseada em Dependências  

### 1. **Upselling por Conexões entre Domínios**  
- **Exemplo 1:** A conexão **Cadastro de Cupons (Clientes) → Registro de Vendas (PDV)** só é liberada no plano **Integrado/Premium**, pois promove aumento de vendas via promoções.  
- **Exemplo 2:** A dependência **Relatório de Produto → Fluxo de Caixa** exige o plano **Integrado**, justificando-se pela necessidade de análise financeira avançada.  

### 2. **Monetização de Ferramentas Secundárias**  
- **Relatórios (DRE, Relatório de Caixa):** Disponível apenas em planos pagos, com argumento de "controle financeiro estratégico".  
- **Automações**: Painel exclusivo que aproveita os dados produzidos pelos domínios e permite criar automações personalizadas com base nessas informações. ( Indicador do **Fluxo de Caixa** controla porcentagem dos cupons do **Gerenciamento de Fidelização** ) **Premium**.

---

## Promoções de Engajamento  
- **Teste Grátis de 14 Dias:** Acesso a funcionalidades conectadas (ex: **Registro de Vendas → Gerenciamento de Fidelização**).  
- **Indicação Premium:** 1 mês grátis no **Integrado** por indicação convertida.  

---

## Roadmap Futuro  
| Módulo                  | Descrição                                                                 | Lançamento Previsto |  
|-------------------------|---------------------------------------------------------------------------|---------------------|  
| **E-commerce Integrado**| Expansão do **PDV** para vendas online (dependência do **Cadastro de Produtos**) | 05/2025            |  
| **Consultoria Financeira** | Análises personalizadas baseadas em **DRE** e **Fluxo de Caixa**         | 09/2025            |  

---

## Conclusão  
Este plano utiliza a arquitetura modular do **Diagrama de Soluções** para oferecer um caminho claro de crescimento:  
1. **Plano Grátis:** Atrai MEIs iniciantes, limitando-se a um domínio (ex: PDV para quem foca em vendas).  
2. **Planos Pagos:** Liberam conexões entre domínios (ex: Finanças + PDV), alinhadas às necessidades de negócios em expansão.  
3. **Funcionalidades Premium:** Monetizam ferramentas secundárias e automações, críticas para escala operacional.  

A estrutura de dependências (ex: **Cadastro de Grupos → Cadastro de Produtos → Registro de Vendas**) garante que a evolução entre planos seja natural, enquanto as conexões cruzadas (ex: **Cupons → Vendas → Fidelização**) criam valor percebido, incentivando upgrades.  