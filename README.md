# 🪵 Timber Trading Management System

> **An Excel-based business management system designed and developed from scratch to digitize and streamline the operations of a timber trading business.**

## 📌 **Project Overview**

The business was previously managed using traditional **paper-based processes**, making it difficult to accurately track inventory, sales, receivables, supplier payables, expenses, and cash flow.

I designed and developed an **integrated Excel-based management system** that connects the main business operations and provides a centralized view of the company's **financial and operational position**.

## 🎯 **Objectives**

- 🔄 **Digitize** manual business processes
- 🎯 **Improve** data accuracy and reduce manual errors
- 📦 **Automate** inventory and financial tracking
- 🔗 **Connect** sales, purchases, collections, and payments
- 📊 **Provide** clear and up-to-date business insights for decision-making

## 🏗️ **System Modules**

### 💰 **Sales**

Records customer information, invoices, wood type, dimensions, quantities, prices, and transaction dates.

### 📋 **Receivables & Collections**

Tracks customer credit sales and automatically updates outstanding receivables based on collections.

### 📦 **Inventory Management**

Tracks available timber stock and automatically updates inventory based on **sales, purchases, and wood cutting operations**.

### 🛒 **Purchases**

Records purchases and connects them directly to inventory movements.

### 🤝 **Supplier Payables**

Tracks amounts owed to suppliers and updates outstanding balances as payments are made or new purchases are recorded.

### 💵 **Expenses & Cash Management**

Tracks business expenses, supplier payments, and collections to provide an accurate view of the **available cash position**.

### 📊 **Dashboard**

Provides a centralized overview of key business metrics:

| KPI | Description |
|---|---|
| 📦 **Inventory Volume** | Current timber stock |
| 💰 **Inventory Value** | Estimated value of current inventory |
| 📋 **Receivables** | Total amount owed by customers |
| 🤝 **Payables** | Total amount owed to suppliers |
| 💵 **Financial Position** | Overall current financial position |

## ⚙️ **Tools & Techniques**

- **Microsoft Excel**
- **XLOOKUP**
- **SUMIFS**
- **IF / IFERROR**
- **Pivot Tables**
- **Data Validation**
- **Linked Worksheets**
- **Dashboard & Data Visualization**
- **Business Process Automation**

## 🔄 **Business Workflow**

```text
                         ┌──────────────┐
                         │    SALES     │
                         └──────┬───────┘
                                │
                                ▼
                      ┌──────────────────┐
                      │   RECEIVABLES    │
                      └────────┬─────────┘
                               │
                               ▼
                      ┌──────────────────┐
                      │   COLLECTIONS    │
                      └────────┬─────────┘
                               │
                               ▼
                         ┌───────────┐
                         │   CASH    │
                         └───────────┘


┌──────────────┐       ┌──────────────────┐
│  PURCHASES   │ ────► │    INVENTORY     │
└──────┬───────┘       └────────┬─────────┘
       │                         ▲
       ▼                         │
┌──────────────┐                 │
│   SUPPLIER   │                 │
│   PAYABLES   │                 │
└──────┬───────┘                 │
       │                         │
       ▼                         │
┌──────────────┐                 │
│   SUPPLIER   │                 │
│   PAYMENTS   │                 │
└──────────────┘                 │
                                 │
                      ┌──────────┴──────────┐
                      │    WOOD CUTTING    │
                      └─────────────────────┘
       COLLECTIONS ────────────┐
       SUPPLIER PAYMENTS ──────┼──► CASH POSITION
       EXPENSES ───────────────┘

## 📈 **Business Impact**

The system transformed the business from a largely manual, paper-based workflow into a **structured digital management system**.

### **Key Improvements**

- 📦 **Improved inventory visibility**
- 💰 **Better financial tracking**
- 🎯 **Increased data accuracy**
- ⚡ **Improved operational efficiency**
- 💵 **Better cash flow monitoring**
- 📊 **Faster and more informed decision-making**

## 💡 **Key Learning**

This project provided practical experience in translating **real-world business processes into a structured data system**.

### **Core Areas**

**Excel** • **Data Analysis** • **Business Process Automation** • **Financial Tracking** • **Operations Management**

The project strengthened my understanding of how **data can be used to improve real business operations and support management decisions**.

## 📷 **Screenshots**

Screenshots of the system and dashboard will be added to demonstrate the main features, dashboards, and workflow.

## 📌 **Project Information**

| **Project Type** | Business Management & Data Analytics |
|---|---|
| **Technology** | Microsoft Excel |
| **Domain** | Timber Trading |
| **Focus** | Data Management, Operations, Financial Tracking & Business Intelligence |
