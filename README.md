# Project 3 — Timeless Transport Models Business Recommendations
**Course:** CSB304 H10 31429 — Data Analytics in Business  
**Instructor:** Eric Lloyd  
**Authors:** Bea Sauve, Elton Nichols, Kainen Osborne  
**Date:** March 2026

---

## Overview

This project provides recommendations for **Timeless Transport Models**, a B2B manufacturer and distributor of modeled vehicles. Using data collected since 2003 across three factories, sales metrics, and email marketing metrics, the project delivers:

- Suggestions to maximize profits
- Exploratory data analysis (EDA) of production and sales trends
- Priorities for sales efforts
- Email marketing suggestions
- Production modifications

All analyses are conducted in **R** using reproducible, documented workflows.

---

## Repository Structure

```
Project_3_Analysis_Profit_Forecasting/
├── Documents/
│   ├── TeamLime_Sales_Tracking_Dashboard.twbx    # Original Report Analyzing Company Sales metrics
│   ├── Email_Marketing_Technical_Report.nb.html  # Original Report Analyzing Company Email metrics
│   ├── Forecasting_Technical_Report.nb.html      # Original Report Analyzing and Forecasting company production and sales metrics
│   └── CSV/
│       ├── cleaned_email_metrics_with_sales.csv           # File containing company email metrics 
│       ├── cleaned_sales_data_sample.csv                  # File containing company sales data
│       └── monthly_salesXproduction_by_productline.csv    # File containing company sales and production metrics
├── Business_Recommendations.ppt                  # Slide Deck presentation of Business Analyses and Deliverables
├── Plan_of_Action.pdf                            # Report describing business deliverables for 2005
├── README.md                                     # Project overview (this file)
├── CONTRIBUTING.md                               # Contribution guidelines and team roles
└── AI.md                                         # AI usage transparency log
```

---

## Getting Started

### Observing the Report

1. Clone this repository:
   ```bash
   git clone <https://github.com/oi12bu/Project_3_Analysis_Profit_Forecasting>
   cd Project_3_Analysis_Profit_Forecasting
   ```

2. Open `Plan_of_Action.pdf`.

    *  Read the report, based on your sector, discuss with you team the next steps for the remainder of 2005.

3. Open `Business_Recommendations.ppt`.
    * Use this slide deck for digestable deliverable and observations

> **Note:** higher detailed analyses that assisted in our final conclusions may be observed in reports within the `Documents/` folder.

---

## Data Sources

| File | Description |
|------|-------------|
| `cleaned_email_metrics_with_sales.csv ` | Weekly email metrics containing customer interactions and resulting sales |
| `cleaned_sales_data_sample.csv ` | Customer order history including sales, territories, and order dates (2003–2005) |
| `monthly_salesXproduction_by_productline.csv` | Monthly production counts and sales data grouped by month and product line |

---

## Plan of Action Summary

### Executive Summary
Description of project objective and deliverables

### Analysis and Forecasting Summary
Visual and statistical exploration of production trends, factory performance, and sales patterns across product lines and territories. Descriptions on analysis and forecasting aids to increasing our profits.

### Business Reccomendations
Suggestions of deliverables for the remainder of 2005 backed by statistical deductions

### Conclusion
Wrap up of report analyses and deliverables.

---

## Team

| Name | Role |
|------|------|
| Bea Sauve | Project Manager — documentation, production forecasting, data refinement |
| Elton Nichols | Version Control Manager — repository management, sales data refinement, EDA |
| Kainen Osborne | Analysis Auditor — profit forecasting, analysis verification |

See [CONTRIBUTING.md](CONTRIBUTING.md) for a full breakdown of individual contributions.

---

## AI Usage

This project documents all AI tool usage transparently. See [AI.md](AI.md) for a complete log of prompts, outputs, and files affected per team member.

---

## License

This project was produced for academic purposes as part of CSB304 at [North Seattle Community College]. Not intended for commercial use.