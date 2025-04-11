# Estrutura de Custos

## Introdução

Este documento apresenta a estrutura de custos projetada para a operação inicial da plataforma, com base em uma base estimada de **1.000 usuários ativos**. Os dados aqui descritos complementam as informações do [modelo de negócio](./modelo_negocio.md), detalhando os investimentos fixos, variáveis e indiretos necessários para garantir a sustentabilidade e o crescimento da operação.

---

## Visão Geral dos Custos Mensais (1.000 usuários)

| Item                              | Observação                                           | Custo Mensal (R$) |
|-----------------------------------|------------------------------------------------------|-------------------|
| **1x CLT**                        | Encargos trabalhistas + benefícios                   | R$ 2.734,91       |
| **2x Pró-labore**                | Remuneração dos founders                             | R$ 3.600,00       |
| **Hospedagem e Domínio**         | (R$ 467,88 hospedagem + R$ 59,99 domínio) / ano      | R$ 44,00          |
| **Suporte técnico**              | 20h/mês a R$ 50/hora                                 | R$ 1.000,00       |
| **Cloud Firestore**              | 1.000 usuários consumindo 3GB/mês                    | R$ 18,18          |
| **Marketing**                    | Mídia paga                                           | R$ 9.000,00       |
| **Consultorias e especialistas** | R$ 500/hora, 3h a cada 6 meses                       | R$ 250,00         |
| **Prospecção comercial**         | Deslocamentos e logística                            | R$ 1.500,00       |
| **Treinamentos e capacitação**   | Cursos e qualificação contínua                       | R$ 500,00         |
| **ISS**                          | 2% sobre receita bruta (não incluído no total fixo)  | -                 |
| **Total Mensal**      |                                                      | **R$ 18.647,09**  |

---

## Classificação dos Custos

### Custos Fixos Diretos

- **Hospedagem Premium**: R$ 38,99/mês (viafacilis.com.br)
- **Domínio .COM.BR**: R$ 4,99/mês
- **Pró-labore (2x)**: R$ 3.600,00/mês (remuneração dos fundadores)
- **Funcionário CLT**: R$ 2.756,33/mês (salário R$ 1.800,00 + encargos legais)

### Custos Indiretos

- **Marketing e Aquisição de Usuários (CAC)**
- **Prospecção Comercial em Novas Regiões**
- **Consultorias de Especialistas e Validação de Módulos**
- **Treinamento da Equipe e Capacitação Técnica**

Estes custos estão relacionados ao crescimento, validação de mercado e formação continuada.

### Custos Variáveis Diretos

- **Google Cloud Firestore**: Baseado no uso — estimativa de R$ 18,18 para 1.000 usuários com 3GB/mês de uso.
- **ISS (Imposto sobre Serviço)**: 2% sobre a receita bruta mensal. Valor proporcional ao número de usuários pagantes.

---

## Ponto de Equilíbrio (Break-even)

Para cobrir os custos fixos mensais estimados (R$ 18.647,09), considerando um ticket médio líquido de R$ 89,90, o ponto de equilíbrio pode ser calculado da seguinte forma:

```
Ponto de Equilíbrio = Custo Fixo / Ticket Médio Líquido
Ticket Médio Líquido = 89,90 * 0,98 ( Descontando o ISS ) → 88,102
Ponto de Equilíbrio ≈ R$ 18.647,09 / R$ 88,102 ≈ 211,6 → 212 usuários
```

Assim, o projeto atinge o ponto de equilíbrio com 212 usuários ativos pagantes.

---

## Economia de Escala

A estrutura modular da plataforma permite diluir os custos fixos à medida que a base de usuários cresce. Recursos como marketing, hospedagem e suporte técnico apresentam ganho de eficiência proporcional ao aumento do volume de clientes.

---

## Projeções de Escalabilidade

Esta seção detalha a evolução esperada dos custos conforme a base de usuários cresce. As estimativas consideram a ampliação do alcance, incremento na estrutura de marketing e suporte, além do aumento proporcional no uso de recursos da nuvem (Google Cloud Firestore).

| Cenário                 | Usuários | Firestore (R$) | Suporte Técnico (R$) | Marketing (R$) | Vendedores (CLT)     | Estimativa Total Mensal |
|------------------------|----------|----------------|-----------------------|----------------|-----------------------|--------------------------|
| **Expansão Moderada**  | 3.000    | R$ 54,54       | R$ 2.000,00           | R$ 12.000,00   | 2 (R$ 2.734,91)       | R$ 22.500,00 (estimado)  |
| **Crescimento Rápido** | 10.000   | R$ 181,80      | R$ 4.000,00           | R$ 18.000,00   | 3 (R$ 8.204,73)       | R$ 33.500,00 (estimado)  |

> O aumento do número de usuários permite a diluição dos custos fixos por cliente, mas também exige maior investimento em marketing e expansão da equipe de vendas e suporte técnico.

**Firestore:** estimado com base em R$ 0,01818 por usuário/mês (3 GB/mês). Custo total = usuários × R$ 0,01818.

**Suporte Técnico:** aumenta proporcionalmente ao volume de usuários e da complexidade da operação.

**Vendedores (CLT):** estimado em R$ 2.734,91 por vendedor.

---

## Conclusão

A estrutura de custos aqui apresentada foi elaborada com base em estimativas realistas e alinhadas ao modelo de negócio proposto. O equilíbrio entre investimento em aquisição, operação e evolução do produto garante um ponto de equilíbrio acessível e uma trajetória de crescimento sustentável. Mais detalhes sobre o racional estratégico podem ser encontrados no [documento do modelo de negócio](./modelo_negocio.md).