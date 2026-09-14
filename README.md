# SAIL-Project-15-Procurement-Analytics & ERP Workflow Integration
SAP-aligned procurement analytics and ERP workflow integration using Excel, Power BI, DAX and ERPNext

## Overview

An end-to-end procurement analytics project combining **Excel, Power BI, DAX and hands-on ERPNext execution** to analyse procurement performance, supplier risk, lead-time variance, purchase-price variance and purchase-order fulfilment.

The project demonstrates how ERP transaction workflows can be integrated with BI-based controls to identify procurement exceptions and support data-driven process improvement.

---

## Business Objective

To analyse procurement performance and demonstrate an **ERP-to-BI procurement control framework** for:

- Supplier performance evaluation
- Purchase-order fulfilment
- Lead-time variance analysis
- Purchase-price variance
- Procurement risk identification
- Working-capital exposure
- Exception monitoring and resolution

---

## Tools & Technologies

- Microsoft Excel
- Power BI
- DAX
- ERPNext
- SAP MM Concepts

---

## Procurement Analytics

Analysed **500 synthetic procurement transactions** covering:

- Purchase requisitions
- Purchase orders
- Goods receipts
- Supplier performance
- Lead-time variance
- Purchase-price variance
- Procurement risk
- Working-capital exposure

### Key Portfolio Metrics

| Metric | Result |
|---|---:|
| Total Purchase Value | ₹46.21 Cr |
| Average Lead Time | 19.75 days |
| Average PO Fulfilment | 97.30% |
| On-Time Delivery | 32.00% |
| High-Risk Transactions | 146 |
| Purchase Price Variance | ₹69.2 L |
| Illustrative Working-Capital Exposure | ₹6.24 Cr |

---

## Hands-on ERP Workflow

A procurement transaction was executed in **ERPNext** to demonstrate an end-to-end ERP workflow:

**Material Request → Purchase Order → Purchase Receipt → Purchase Invoice**

### ERP Control Case

**Material:** Heavy Duty Bearing (BRG-001)  
**Supplier:** ABC Industrial Supplies

| Stage | Quantity | Value |
|---|---:|---:|
| Material Request | 50 | ₹5,00,000 |
| Purchase Order | 50 | ₹5,00,000 |
| Initial Receipt | 47 | ₹4,70,000 |
| Outstanding | 3 | ₹30,000 |
| Final Receipt | 50 | ₹5,00,000 |

The initial receipt created a **94% fulfilment exception**, with 3 units outstanding. The remaining quantity was subsequently received, closing the exception and bringing the PO to **100% fulfilment**.

---

## Power BI Control Dashboard

The Power BI dashboard combines procurement analytics with ERP transaction controls.

### Dashboard Pages

**1. Procurement Overview**
- Purchase value
- Average lead time
- PO fulfilment
- On-time delivery
- Supplier-wise procurement value
- Procurement risk distribution

**2. Supplier Performance**
- Supplier lead time
- PO fulfilment
- Supplier comparison
- Lead-time vs fulfilment analysis

**3. Working Capital & Process Improvement**
- Purchase-price variance
- Working-capital exposure
- Lead-time variance
- High-risk procurement transactions
- Improvement opportunities

**4. ERP Procurement Control Tower**
- ERP PO value
- Invoice-to-receipt matching
- PO fulfilment
- Outstanding quantity
- Procurement quantity flow
- Exception monitoring
- ERP fulfilment vs portfolio benchmark

---

## ERPNext → SAP MM Concept Mapping

| ERPNext Workflow | SAP MM-Aligned Concept |
|---|---|
| Material Request | Purchase Requisition |
| Purchase Order | Purchase Order |
| Purchase Receipt | Goods Receipt |
| Purchase Invoice | Invoice Verification |

The ERP execution was performed in **ERPNext**, while the workflow was structured around **SAP MM procurement concepts**. No SAP S/4HANA hands-on access is claimed.

---

## Key Insight

The ERP control case demonstrated how a BI dashboard can identify a procurement exception below the portfolio fulfilment benchmark, track the outstanding quantity and support follow-up until the purchase order reaches full fulfilment.

This illustrates the connection between:

**ERP Transaction Data → BI Controls → Exception Identification → Process Resolution**

---

## Repository Structure

```text
SAIL-Project-15-Procurement-Analytics/
│
├── README.md
│
├── Excel/
│   └── SAIL_Project_15_SAP_Procurement_Analytics.xlsx
│
├── PowerBI/
│   └── SAIL_Project_15_SAP_Procurement_Analytics.pbix
│
├── Dashboard/
│   ├── Page_1_Procurement_Overview.png
│   ├── Page_2_Supplier_Performance.png
│   ├── Page_3_Working_Capital.png
│   └── Page_4_ERP_Control_Tower.png
│
└── ERPNext/
    ├── 01_Material_Request.png
    ├── 02_Purchase_Order.png
    ├── 03_Purchase_Receipt_47.png
    ├── 04_Exception_3_Units.png
    ├── 05_Stock_Ledger_50.png
    └── 06_Final_PO_Completed.png
