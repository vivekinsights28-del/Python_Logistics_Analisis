# Python_Logistics_Analisis
📦 Courier Billing Audit & Logistics Cost Analysis
📌 Overview

This project implements an end-to-end courier billing audit to validate invoice charges against expected pricing based on shipment weight slabs, delivery zones, and contractual rate cards. The analysis helps identify overcharged, undercharged, and correctly charged shipments, supporting logistics cost control and invoice reconciliation.

🎯 Objectives

Audit courier invoices for billing accuracy

Apply 0.5 KG slab-based weight logic

Validate zone-based Forward and RTO pricing

Identify billing discrepancies and financial impact

Generate business-friendly audit reports

⚙️ Methodology

Cleaned and standardized multi-source logistics datasets

Aggregated product-level orders to shipment-level weights

Derived expected delivery zones using pincode mapping

Calculated expected charges using zone-wise rate cards

Reconciled expected vs billed amounts and classified results

📊 Outputs

Order-Level Audit Report – detailed charge comparison per shipment

Summary Report – count and financial impact of billing discrepancies

Both outputs are exported as Excel workbooks for easy review.

🛠️ Tech Stack

Python (Pandas, NumPy), Excel, Data Cleaning, Data Aggregation, Analytics

📁 Repository Structure
├── courier_audit.ipynb
├── Order_Level_Calculation.xlsx
├── Summary_Table.xlsx
└── README.md

📌 Use Cases

Courier invoice validation

Logistics cost analysis

Audit and reconciliation analytics

Data Analyst portfolio project
