# Modelo de Negócio 

## Introdução
Este documento compila os estudos realizados até aqui, estruturando os em modelo de negócio voltado para micro e pequenos empreendedores (MEIs e MEs). A proposta é apresentar, de forma estratégica, como a solução pode evoluir para uma operação rentável e escalável, servindo de base para validações futuras e guiando os próximos ciclos de desenvolvimento.

Para melhor aproveitamento dessa documentação acesse o figma do projeto pelo link a seguir: [Estruturação de Negócio - FIGMA](https://www.figma.com/design/dnBqepKRepi4wqaEI2k5nA/Negócio?node-id=75-2&p=f&t=iAy5ShMnVbSZh1hO-0)

## Business Model Canvas

Para facilitar a visualização do modelo de negócio, utilizei o Business Model Canvas, uma ferramenta estratégica amplamente adotada por empreendedores para descrever, planejar e validar modelos de negócio.

O canvas é composto por nove blocos fundamentais — como proposta de valor, segmentos de clientes, canais, fontes de receita e estrutura de custos — permitindo uma compreensão resumida da operação, além de apoiar na identificação de oportunidades.


![Canvas](../../img/Modelo%20de%20Negócio%20-%20Canvas.png)


---

### Segmento de Clientes
Empreendedores de 24 a 45 anos registrados como **MEI** ou **ME**, com interesse em **expansão de seus negócios**.  
Mercado potencial com mais de **19 milhões de empresas**, crescendo a uma taxa de **2,8 milhões por ano**, embora **20% fechem ainda no primeiro ano**.

---

### Proposta de Valor
- **Gestão simples, suporte real, foco no crescimento.**
- Softwares modulares: **pague apenas pelo que usar.**
- Interface **intuitiva** e acessível.
- Sistema **escalável** que cresce com o empreendedor.

---

### Canais de Acesso
- **Prospecção direta:** WhatsApp, abordagem presencial.
- **Relacionamento contínuo:** WhatsApp.
- **Educação do lead:** Blog com conteúdo relevante.
- **Venda:** Presencial ou por meio do site.

---

### Relacionamento com Clientes
- **3 meses gratuitos** para cidades onde a empresa ainda não atua (via prospecção).
- **Descontos por indicação**, vinculados ao tempo de uso da empresa indicada (site e prospecção).
- **1 mês gratuito de teste** do sistema (site e prospecção).
- **Blog com dicas práticas** para o nicho atendido.
- Canal de **suporte e dúvidas** pelo site.

---

### Atividades-Chave
- Desenvolvimento e manutenção do software.
- Criação de conteúdo educativo e relevante.
- Prospecção ativa e atendimento comercial.
- Gestão e expansão de parcerias estratégicas.
- Análise de dados e melhoria contínua.

---

### Recursos-Chave
- Site institucional e plataforma web.
- Desenvolvedor sênior.
- Time de conteúdo e comercial.
- Acordos com fornecedores e consultores.
- Marca confiável com apelo ao crescimento dos pequenos negócios.
- Base de dados dos usuários.

---

### Parcerias-Chave
- **Fornecedores** de produtos (ex: dropshipping).
- **Consultores especializados** para conteúdo técnico e validação.
- **Parceiros locais** para prospecção comercial.
- **APIs e serviços externos:**
  - Mercado Pago (pagamentos)
  - Google Cloud Platform
  - Firebase Authentication
  - Hostinger (hospedagem e dns)

---

### Estrutura de Custos
A seguir, detalhamos os principais custos envolvidos na operação, organizados por natureza:

### Custos Fixos Diretos

| Item                                 | Valor Mensal      | Observação                                        |
|--------------------------------------|-------------------|---------------------------------------------------|
| Hospedagem Premium (viafacilis.com.br) | R$ 38,99           | Plano anual dividido em 12 meses                 |
| Domínio .COM.BR                      | R$ 4,99            | Registro anual dividido em 12 meses              |
| Colaboradores PJ (2x)                | R$ 3.600,00        | Pró-labore dos sócios                             |
| Funcionário CLT                      | R$ 2.756,33        | Salário de R$ 1.800,00 + encargos trabalhistas    |

### Custos Indiretos

- Marketing e aquisição de usuários (CAC)
- Prospecção comercial em novas regiões
- Consultorias especializadas e validação de módulos
- Treinamento interno e capacitação técnica da equipe

### Custos Variáveis Diretos

| Item                                 | Valor Estimado    | Observação                                        |
|--------------------------------------|-------------------|---------------------------------------------------|
| Google Cloud Firestore               | R$ 18,18           | Base de 1.000 usuários utilizando 3GB/mês         |
| ISS (Imposto sobre Serviço)          | 2% da receita      | Aplicado sobre a receita bruta mensal             |

> **Ponto de equilíbrio (break-even):** estimado a partir de **212 usuários ativos pagantes**, com base na estrutura atual de custos e no ticket médio planejado.

Para uma visão mais detalhada, acesse a documentação completa sobre a [estrutura de custos](./estrutura_custos.md).

---




## Conclusão
A análise deste modelo de negócios, aliada à estrutura de custos e à definição do ponto de equilíbrio, aponta para uma proposta financeiramente viável, escalável e alinhada às necessidades reais dos micro e pequenos empreendedores apontadas na [sprint 1](../../README.md). Ao longo da estruturação, buscou-se partir de uma base concreta — a elevada taxa de mortalidade desses negócios — para desenvolver uma solução que ultrapassa a oferta de um sistema, propondo um ecossistema de suporte.

Com base nas estimativas iniciais, o ponto de equilíbrio é atingido com aproximadamente 212 usuários ativos pagantes, o que demonstra potencial de sustentabilidade a médio prazo. As estratégias de aquisição previstas — como prospecção local, programas de indicação e marketing de conteúdo — foram definidas considerando tanto a capacidade de execução quanto a realidade de acesso digital da [persona](../../sprint-3/pt-br/persona.md). Além disso, a estrutura modular do sistema previstas na [sprint 4](../../sprint-4/README.md) garante flexibilidade na adoção, permitindo ao usuário o crescimento dentro da mesma plataforma.

Durante o desenvolvimento deste modelo, buscou-se garantir aderência ao perfil do público atendido, priorizando a mitigação dos [desafios sistêmicos](../../README.md/#problemática) que comprometem a sustentabilidade dos negócios. A proposta representa, portanto, uma síntese entre oportunidade de mercado, capacidade técnica e uma tese de impacto com potencial de retorno.

O próximo passo será a validação de todas essas hipóteses por meio de pesquisa com o público e testes com usuários reais. Esse processo permitirá calibrar o produto, ajustar a estratégia e refinar os elementos do modelo para que se mantenham coerentes com a realidade do mercado.