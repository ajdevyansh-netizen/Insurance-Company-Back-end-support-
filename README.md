# Insurance-Company-Back-end-support-
# 📊 Insurance Business Intelligence Dashboard

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-742774?style=for-the-badge)
![Power Pivot](https://img.shields.io/badge/Power%20Pivot-107C41?style=for-the-badge)
![DAX](https://img.shields.io/badge/DAX-00599C?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-blue?style=for-the-badge)

Enterprise Business Intelligence Dashboard built using **Microsoft Excel**, **Power Query**, **Power Pivot**, **DAX**, and **Microsoft Power BI** for Insurance Business Performance Analysis.

</div>

---

# Project Overview

This project demonstrates the complete Business Intelligence lifecycle—from raw operational data to executive dashboards.

The solution transforms monthly insurance business reports into an interactive analytics platform that enables management to monitor business performance, commitments, revenue generation, and agent productivity in real time.

The dashboard was designed to eliminate manual reporting and provide a scalable, refreshable solution where new monthly data can be incorporated with minimal effort.

---

# Business Problem

The organization receives monthly insurance business reports from multiple sources.

Challenges included:

- Manual Excel reporting
- No centralized dashboard
- Difficult RM and Agent performance tracking
- No commitment vs achievement analysis
- Time-consuming monthly reporting
- No drill-down capability
- High probability of manual errors

---

# Solution

Designed an end-to-end Business Intelligence solution using:

- Microsoft Excel
- Power Query
- Power Pivot
- Data Modeling
- DAX
- Microsoft Power BI

The solution automatically:

- Cleans raw data
- Creates a Star Schema
- Calculates KPIs
- Builds interactive dashboards
- Enables drill-down analysis
- Supports monthly refresh

---

#  Project Architecture

```
                    Raw Business Data
                           │
                           ▼
                    Power Query ETL
                           │
            ┌──────────────┴──────────────┐
            ▼                             ▼
    Fact_Business_Raw          Fact_Commitment_Raw
            │                             │
            └──────────────┬──────────────┘
                           │
        ┌──────────────────┼──────────────────┐
        ▼                  ▼                  ▼
    Dim_Agent          Dim_RM            Dim_Date
                           │
                           ▼
                     Data Model
                           │
                           ▼
                      DAX Measures
                           │
                           ▼
                 Power BI Interactive Reports
```

---

#  Features

## Executive Dashboard

- Executive KPI Cards
- Business Commitment
- Net Premium
- Achievement %
- Monthly Trends
- RM Leaderboard
- Dynamic Filtering

---

## RM & Agent Analysis

- RM Performance
- Agent Performance
- Commitment vs Achievement
- Company-wise Analysis
- Searchable Filters

---

## Product Analysis

- LOB Analysis
- Company Analysis
- Product Contribution
- Premium Distribution

---

## Interactive Features

- Dynamic Slicers
- Searchable Filters
- Cross Filtering
- Drill Down
- Navigation Buttons
- Matrix Visuals
- Interactive Charts

---

#  Dashboard Preview

## Executive Summary

> *(Insert Screenshot Here)*

```
assets/executive-summary.png
```

---

## RM & Agent Analysis

> *(Insert Screenshot Here)*

```
assets/rm-analysis.png
```

---

## Product Analysis

> *(Insert Screenshot Here)*

```
assets/product-analysis.png
```

---

#  Repository Structure

```
Insurance-Business-Intelligence-Dashboard
│
├── assets
│
├── data
│   ├── raw
│   ├── processed
│   └── sample-data
│
├── docs
│
├── excel
│
├── powerbi
│
├── sql
│
├── README.md
├── LICENSE
└── .gitignore
```

---

#  Data Model

The dashboard follows a **Star Schema**.

## Fact Tables

- Fact_Business_Raw
- Fact_Commitment_Raw

## Dimension Tables

- Dim_Agent
- Dim_RM
- Dim_Date

---

#  Key Performance Indicators

The dashboard calculates:

- Agent Actual
- Agent Committed
- Achievement %
- Net Premium
- Business Commitment
- RM Performance
- Company Contribution
- LOB Contribution

---

# ⚙ ETL Process

The ETL pipeline was developed using **Power Query**.

Major transformations include:

- Data Cleaning
- Null Handling
- Remove Duplicates
- Data Type Conversion
- Custom Columns
- Business Month Key
- Date Dimension
- Dimension Table Creation
- Reference Queries
- Group By Operations

---

#  Data Modeling

Implemented using:

- One-to-Many Relationships
- Star Schema
- Date Dimension
- DAX Measures
- Optimized Data Model

---

#  Power BI Report Pages
## Executive Summary

Displays:

- KPI Cards
- Monthly Trends
- RM Leaderboard
- Dynamic Filters

---

## RM & Agent Analysis

Displays:

- RM Performance
- Agent Performance
- Company Performance
- Achievement Analysis

---

## Product Analysis

Displays:

- LOB Contribution
- Company Contribution
- Product Performance
- Premium Distribution

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| Microsoft Excel | Raw Data |
| Power Query | ETL |
| Power Pivot | Data Modeling |
| DAX | Business Calculations |
| Power BI | Dashboard |
| GitHub | Version Control |

---

#  Project Workflow

```
Raw Data

↓

Power Query

↓

Data Cleaning

↓

Dimension Tables

↓

Fact Tables

↓

Relationships

↓

DAX Measures

↓

Power BI Dashboard

↓

Executive Reporting
```

---

#  Monthly Refresh Process

1. Replace monthly raw data files
2. Refresh Power Query
3. Refresh Data Model
4. Refresh Power BI
5. Validate KPIs
6. Publish Updated Dashboard

---

#  Documentation

Additional documentation available in:

```
docs/
```

Includes:

- Standard Operating Procedure
- Dashboard Guide
- Data Dictionary
- Business Rules

---

#  Future Improvements

- SQL Database Integration
- Incremental Refresh
- Power BI Service Deployment
- Row-Level Security (RLS)
- Mobile Dashboard
- Automated Email Reporting
- Azure Data Factory Integration

--- Portfolio Highlights

✔ End-to-End BI Solution

✔ ETL Development

✔ Data Modeling

✔ Star Schema

✔ DAX Development

✔ Power BI Reporting

✔ Interactive Dashboard Design

✔ Business Performance Analytics

✔ Executive Reporting

✔ Refreshable Architecture

---

#  License

This project is licensed under the MIT License.

---

#  Author

**Devyansh Ajmera**

Business Intelligence | Data Analytics | Power BI | Excel | DAX | Power Query

GitHub: *(Add your GitHub Profile)*

LinkedIn: *(Add your LinkedIn Profile)*

---

<div align="center">

⭐ If you found this project useful, consider giving it a star.

</div>
