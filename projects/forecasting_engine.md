# Predictive Forecasting Engine — Perk ROI Modeling  
**Machine Learning | Feature Engineering | Financial Simulation**

---

## Overview
A predictive modeling pipeline used to forecast perk usage, subsidy cost, and ROI.  
Integrated into BI reporting as a real-time simulation layer.

---

## Architecture
![Forecasting Engine Architecture](../architecture/metrics_arch.png)

---

## Pipeline Components
### 1. Feature Engineering
- Aggregated perk usage trends  
- Customer-level behavioral features  
- Cost curves + seasonal patterns

### 2. Model Training
- Regression models  
- Time-series forecasting  
- Cross-validation + error analysis  

### 3. Output Integration
- BI dashboards consume:  
  - Projected subsidy cost  
  - Predicted ROI  
  - Confidence bands  

---

## Tech Stack
Python (pandas, sklearn) · SQL · ML Pipeline
