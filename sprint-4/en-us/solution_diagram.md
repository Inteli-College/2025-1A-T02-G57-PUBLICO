# Solution Diagram

## Introduction
Considering the broad objective of the problem that this solution aims to address, this section of the documentation intends to present the structure and interrelationships between the platform's domains, highlighting how each contributes to the system's functionality.

For better utilization of this documentation, access the project's Figma through the following link: [Business Structuring - FIGMA](https://www.figma.com/design/dnBqepKRepi4wqaEI2k5nA/Negócio?node-id=8-4&p=f&t=XdYzO5pRCfeSlNEh-0)

## 1. Legend
The legend defines the symbols used in the diagrams:

- **Main Tool**: Represented by a solid black rectangle. It aims to store the fundamental functions of the domain.
- **Secondary Tool**: Represented by a dashed-border rectangle. It stores non-essential actions of the domain.
- **Dependency**: Indicated by a white arrow connecting modules, with the module where the arrow originates being dependent.
- **Connection**: Indicated by a dotted arrow connecting modules. This connection is established through the transmission of information from the arrow's origin.

![Legend](../documentation/static/img/diagrama_solucoes/Legenda.png)

## 2. Domains and Tools
This diagram presents the system's main modules, organized into three major domains:

### **POS (Point of Sale)**
Responsible for directly managing commercial transactions, utilizing the following tools:
- **Group Registration**
- **Product Registration**
- **Sales Recording**
- **Cash Register Report** (Secondary Tool)
- **Product Report** (Secondary Tool)

### **Finance**
Provides a detailed view of the company's financial health through the following tools:
- **Accounts Payable**
- **Accounts Receivable**
- **Cash Flow**
- **Income Statement (DRE)** (Secondary Tool)

### **Clients**
Focuses on strengthening customer relationships, utilizing the following tools:
- **Client Registration**
- **Coupon Registration**
- **Loyalty Management**
- **Customer Tracking** (Secondary Tool)

![Domains and Tools](../documentation/static/img/diagrama_solucoes/Diagrama%20de%20Soluções%20-%20Domínios%20e%20Ferramentas.png)

## 3. Dependencies
This diagram illustrates the dependencies between the system's tools.

### **POS**
- **Product Registration** depends on **Group Registration**.
- **Sales Recording** depends on **Product Registration**.
- **Cash Register Report** depends on **Sales Recording**.
- **Product Report** depends on **Product Registration**.

![Dependencies](../documentation/static/img/diagrama_solucoes/Diagrama%20de%20Soluções%20-%20Depêndecias%20_%20PDV.png)

### **Finance**
- **Cash Flow** depends on **Accounts Payable** and **Accounts Receivable**.
- **Income Statement (DRE)** depends on **Cash Flow**.

![Dependencies](../documentation/static/img/diagrama_solucoes/Diagrama%20de%20Soluções%20-%20Depêndecias%20_%20Finanças.png)

### **Clients**
- **Loyalty Management** depends on **Client Registration** and **Coupon Registration**.
- **Customer Tracking** depends on **Loyalty Management**.

![Dependencies](../documentation/static/img/diagrama_solucoes/Diagrama%20de%20Soluções%20-%20Depêndecias%20_%20Clientes.png)

## 4. Connections Between Domains
This diagram presents the connections between different system domains:
- **Coupon Registration** is connected to **Sales Recording**.
- **Sales Recording** is linked to **Cash Flow**.
- **Sales Recording** is connected to **Loyalty Management**.

![Dependencies](../documentation/static/img/diagrama_solucoes/Diagrama%20de%20Soluções%20-%20Conexões%20Entre%20Domínios.png)

## Conclusion

After analyzing the diagrams, it is clear that each domain operates independently in its main tasks, and their interaction enhances the system's performance. This understanding will guide the monetization model, offering plans that allow access to each domain separately while also limiting free plans to accessing only the main tools of a single domain.

