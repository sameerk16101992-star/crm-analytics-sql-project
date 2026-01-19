# crm-analytics-sql-project

## Overview
This repository contains SQL scripts supporting an end-to-end CRM analytics case study focused on lifecycle management, churn prevention, and loyalty-driven growth.

The SQL layer is used for:
- Feature engineering
- Customer segmentation
- KPI calculation
- Business logic transformation

Visualization and storytelling are handled in Power BI.

---

## Dataset
Synthetic telecom CRM dataset (~10,000 customers) including:
- Usage behavior
- Billing & revenue
- Support interactions
- Engagement metrics
- Churn indicator

Several analytical features were **derived**, as they were not present in the raw data.

---

## Key Analytical Concepts
- Lifecycle staging
- Engagement health scoring
- Churn risk profiling
- Revenue exposure estimation
- Upsell readiness identification

---

## File Structure
- `01_table_setup.sql` – Base schema
- `02_feature_engineering.sql` – Derived CRM indicators
- `03_executive_overview.sql` – High-level KPIs
- `04_lifecycle_intelligence.sql` – Lifecycle analysis
- `05_churn_drivers.sql` – Root cause analysis
- `06_loyalty_growth.sql` – Loyalty & revenue insights

---

## Output
The SQL outputs are consumed by a multi-page Power BI dashboard featuring:
- Executive overview
- Lifecycle intelligence
- Churn driver analysis
- Loyalty & growth insights

---

## Next Enhancements
- Predictive churn modeling
- Campaign response tracking
- Cost-based retention ROI
- Automated SQL pipelines
