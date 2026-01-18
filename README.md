# Online Retail Cohort Retention Analysis

## Overview
This project performs an end-to-end cohort retention analysis on an e-commerce transactions dataset.
The goal is to understand customer retention behavior over time and identify patterns in repeat purchasing.

The analysis covers data cleaning, KPI calculation, cohort construction, and interactive visualization using Power BI.

---

## Dataset
The project uses the **Online Retail Dataset**, which contains transactional data from a UK-based online retailer.

**Key fields include:**
- InvoiceNo
- StockCode
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

The raw dataset includes cancellations and incomplete records, which are handled during the data cleaning stage.

---

## Project Structure
```text
online-retail-cohort-retention/
│
├── data/
│   ├── raw/
│   │   └── online_retail.csv
│   └── processed/
│       └── cohort_data.csv
│
├── database/
│   └── retail.db   (generated locally)
│
├── notebooks/
│   └── analysis.ipynb
│
├── dashboard/
│   └── Online_Retail_Cohort_Retention.pbix
│
└── README.md




