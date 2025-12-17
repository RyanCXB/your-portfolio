# Financial Data Pipeline — ARPU, Churn & Subsidy Modeling  
**DBT Modeling | Python ETL | Parquet Data Lake | Metric Layer**

---

## Overview
This project reconstructs Verizon’s financial analytics logic as an end-to-end data engineering pipeline.  
It simulates industrial-grade data modeling for ARPU, churn, device subsidy margin, and profitability.

---

## Architecture
![Financial Pipeline Architecture](../architecture/financial_pipeline_arch.png)

---

## Pipeline Stages
### 1. Ingestion (Python)
- Synthetic financial & subscriber datasets
- Written to a Parquet-based data lake (bronze)

### 2. Transformations (DBT)
- `staging` models clean + normalize raw data  
- `intermediate` models: subscriber lifecycle, revenue mapping  
- `marts`: ARPU, churn, subsidy profitability

### 3. Metric Layer
Models include:
- **ARPU = total_revenue / active_subscribers**  
- **Subsidy Margin = revenue - subsidy_cost**  
- **Churn Rate = lost_subscribers / previous_month_active**

### 4. Dashboard Layer
Outputs consumed by Streamlit/Qlik dashboards.

---

## Tech Stack
Python · DBT · SQL · Parquet · Data Modeling  
