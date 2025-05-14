# Flow Diagram

## Introduction
This document presents the system's Flow Diagram, aiming to visually and clearly illustrate the main processes and user interactions.

This diagram also has an interactive version available via this link: [Flow Diagram - FIGMA](https://www.figma.com/design/LTdDVyRKmTS6IJDwmCv2yR/TCC---Fluxo-da-Interface?node-id=496-428&t=kMmpALYRFgWz5jDM-1).

## DFD - Level 0 (Overview)
**Objective:** To present the high-level data flow, covering the main processes of the system.

### Main Elements

#### **External Entities:**
- **Administrator**: Responsible for registering groups and products.
- **Cashier**: Interacts with the system to register sales and manage payments.
- **Manager**: Views cash and product reports.

#### **Processes:**
- **Group Registration**: The administrator registers product groups.
- **Product Registration**: The administrator registers products.
- **Cash Opening**: The cashier accesses the screen to register sales and manage payments.
- **View Cash Reports**: The manager views cash reports.
- **View Product Reports**: The administrator views product reports.

#### **Data Storage:**
- **Group Database**: Stores data for registered product groups.
- **Product Database**: Stores data for registered products.
- **Sales and Cash Database**: Records all sales and cash transactions.
- **Reports Database**: Stores generated reports on sales, cash, and products.

### **Data Flows:**
- The **Administrator** interacts with the system to register Product Groups and Products.
- The **Cashier** accesses the screen to register sales and manage payments in the Cash System.
- The **Manager** accesses and views Cash and Product Reports for auditing and analysis.

```
[Administrator] --> [Group Registration] --> [Group Database]
[Administrator] --> [Product Registration] --> [Product Database]
[Cashier] --> [Cash Opening] --> [Sales and Cash Database]
[Manager] --> [View Cash Reports] --> [Reports Database]
[Administrator] --> [View Product Reports] --> [Reports Database]
```


## DFD - Level 1 (Process Details)
Now, let's detail each of the processes identified in **Level 0** to show how data is handled more specifically.

### **Group Registration:**
- **Inputs**: Data entered by the administrator (name, code, active status).
- **Process**: The administrator registers a product group.
- **Outputs**: The group is stored in the **Group Database**.

### **Product Registration:**
- **Inputs**: Data entered by the administrator (name, code, price, group, stock, etc.).
- **Process**: The administrator registers a new product.
- **Outputs**: The product is stored in the **Product Database**.

### **Cash Opening:**
- **Inputs**: Data from the cashier (start of cash operation).
- **Process**: The cashier starts a new sale or operation.
- **Outputs**: The transaction is recorded in the **Sales and Cash Database**.

### **View Cash Reports:**
- **Inputs**: Request from the manager to view reports.
- **Process**: The system generates reports based on registered transactions.
- **Outputs**: Cash report generated and presented to the manager.

### **View Product Reports:**
- **Inputs**: Request from the administrator to view product reports.
- **Process**: The system generates reports based on sales and product stock information.
- **Outputs**: Product report generated and presented to the administrator.

```
[Administrator] --> [Group Registration] --> [Group Database]
|
v
[Administrator] --> [Product Registration] --> [Product Database]

[Cashier] --> [Cash Opening] --> [Sales and Cash Database]

[Manager] --> [View Cash Reports] --> [Reports Database]
|
v
[Administrator] --> [View Product Reports] --> [Reports Database]
```