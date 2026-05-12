Supplier Scorecard – Procurement Analytics (Python)
Project Overview

Supplier performance plays a critical role in procurement and supply chain efficiency.
This project builds a data-driven supplier scorecard to evaluate suppliers based on cost, delivery performance, and quality.

The goal is to support sourcing decisions by identifying:

Strategic suppliers

Negotiation targets

High-risk suppliers



Business Problem

Organizations rely on multiple suppliers for manufacturing and logistics.
Poor supplier performance can lead to:

Increased procurement costs

Delivery delays

Product quality issues

Supply chain disruption risk

This project develops a supplier performance evaluation framework using Python.



Dataset

Kaggle — Supply Chain Analysis Dataset
File used: supply_chain_data.csv

The dataset includes:

Supplier information

Product and order data

Manufacturing and shipping costs

Delivery lead times

Quality inspection and defect rates

| KPI                      | Description                         |
| ------------------------ | ----------------------------------- |
| **Spend**                | Costs × Order Quantities            |
| **Avg Procurement Cost** | Manufacturing + Shipping cost       |
| **Avg Total Lead Time**  | Supplier + Manufacturing + Shipping |
| **Avg Defect Rate**      | Supplier quality performance        |
| **Order Volume**         | Supplier reliability proxy          |


Methodology

The project follows a full data analytics workflow:

Data understanding and quality checks

Feature engineering of procurement KPIs

Exploratory data analysis (EDA)

Supplier KPI aggregation

Weighted supplier scoring model

Supplier segmentation and recommendations



Supplier Scoring Model

Suppliers were scored using a weighted model based on:

Spend contribution

Cost efficiency

Delivery speed

Quality performance

Scores were normalized and suppliers were segmented into:

Strategic Partners

Competitive (Negotiation Targets)

High-Risk Suppliers



Project Outputs

Generated business-ready outputs:

Tables

final_supplier_scorecard.csv

negotiation_targets.csv

replacement_targets.csv

Charts

Top Suppliers by Spend

Supplier Performance Segmentation



Tools Used

Python
Pandas
NumPy
Matplotlib
Seaborn


Project Structure

notebooks/
outputs/
  ├── charts/
  └── tables/
README.md
requirements.txt


Key Outcome

This project demonstrates how data analytics can support procurement strategy by transforming operational data into actionable supplier insights.
