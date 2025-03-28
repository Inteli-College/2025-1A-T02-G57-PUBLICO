# Diagrama de Fluxo do Sistema

## Introdução
Este documento apresenta o Diagrama de Fluxo do Sistema do sistema, com o objetivo de ilustrar de forma visual e clara os principais processos e interações dos usuários. 

Para a visualização gráfica do fluxo a seguir acesse o link: [Diagrama de Fluxo do Sistema - FIGMA](https://www.figma.com/design/LTdDVyRKmTS6IJDwmCv2yR/TCC---Fluxo-da-Interface?node-id=496-428&t=kMmpALYRFgWz5jDM-1).


## DFD - Nível 0 (Visão Geral)
**Objetivo:** Apresentar o fluxo de dados de alto nível, abordando os principais processos do sistema.

### Elementos principais

#### **Entidades Externas**:
- **Administrador**: Responsável por cadastrar grupos e produtos.
- **Operador de Caixa**: Interage com o sistema para registrar vendas e gerenciar pagamentos.
- **Gerente**: Visualiza relatórios de caixa e produtos.

#### **Processos**:
- **Cadastro de Grupos**: O administrador cadastra grupos de produtos.
- **Cadastro de Produtos**: O administrador cadastra produtos.
- **Abertura de Caixa**: O operador de caixa acessa a tela para registrar vendas e gerenciar pagamentos.
- **Visualização de Relatórios de Caixa**: O gerente visualiza relatórios de caixa.
- **Visualização de Relatórios de Produtos**: O gerente visualiza relatórios de produtos.

#### **Armazenamentos de Dados**:
- **Base de Dados de Grupos**: Armazena os dados dos grupos de produtos cadastrados.
- **Base de Dados de Produtos**: Armazena os dados dos produtos cadastrados.
- **Base de Dados de Vendas e Caixa**: Registra todas as vendas e transações de caixa.
- **Base de Dados de Relatórios**: Armazena relatórios gerados sobre vendas, caixa e produtos.

### **Fluxos de Dados**:
- O **Administrador** interage com o sistema para cadastrar Grupos de Produtos e Produtos.
- O **Operador de Caixa** acessa a tela para registrar vendas e gerenciar pagamentos no Sistema de Caixa.
- O **Gerente** acessa e consulta Relatórios de Caixa e Relatórios de Produtos para auditoria e análise.

```
[Administrador] --> [Cadastro de Grupos] --> [Base de Dados de Grupos]
[Administrador] --> [Cadastro de Produtos] --> [Base de Dados de Produtos]
[Operador de Caixa] --> [Abertura de Caixa] --> [Base de Dados de Vendas e Caixa]
[Gerente] --> [Visualização de Relatórios de Caixa] --> [Base de Dados de Relatórios]
[Administrador] --> [Visualização de Relatórios de Produtos] --> [Base de Dados de Relatórios]
```

## DFD - Nível 1 (Detalhamento dos Processos)
Agora, vamos detalhar cada um dos processos identificados no **Nível 0** para mostrar como os dados são manipulados de maneira mais específica.

### **Cadastro de Grupos**:
- **Entradas**: Dados inseridos pelo administrador (nome, código, status ativo).
- **Processo**: O administrador cadastra um grupo de produtos.
- **Saídas**: O grupo é armazenado na **Base de Dados de Grupos**.

### **Cadastro de Produtos**:
- **Entradas**: Dados inseridos pelo administrador (nome, código, é adicional?, grupo, preço, custo, estoque atual e estoque mínimo).
- **Processo**: O administrador cadastra um novo produto.
- **Saídas**: O produto é armazenado na **Base de Dados de Produtos**.

### **Abertura de Caixa**:
- **Entradas**: Dados do operador de caixa ( seleção de um grupo de produtos, nome, localização, senha, taxa, forma de pagamento e total pago ).
- **Processo**: O operador de caixa registra uma nova venda.
- **Saídas**: A transação é registrada na **Base de Dados de Vendas e Caixa**.

### **Visualização de Relatórios de Caixa**:
- **Entradas**: Dados inseridos pelo gerente ( data da consulta ).
- **Processo**: O sistema gera relatórios baseados nas transações registradas na data expecificada.
- **Saídas**: Relatório de caixa é gerado.

### **Visualização de Relatórios de Produtos**:
- **Entradas**: Dados inseridos pelo gerente ( data da consulta ).
- **Processo**: O sistema gera relatórios baseados nas transações registradas na data expecificada.
- **Saídas**: Relatório de produtos é gerado.

```
[Administrador] --> [Cadastro de Grupos] --> [Base de Dados de Grupos]
    | 
    v
[Administrador] --> [Cadastro de Produtos] --> [Base de Dados de Produtos]

[Operador de Caixa] --> [Abertura de Caixa] --> [Base de Dados de Vendas e Caixa]

[Gerente] --> [Visualização de Relatórios de Caixa] --> [Base de Dados de Relatórios]
    |
    v
[Administrador] --> [Visualização de Relatórios de Produtos] --> [Base de Dados de Relatórios]

```

