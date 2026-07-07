# Project Architecture

```
                   RAW EXCEL FILES
                         │
                         ▼
                  Power Query ETL
                         │
        ┌────────────────┴────────────────┐
        ▼                                 ▼
Fact_Business_Raw             Fact_Commitment_Raw
        │                                 │
        └───────────────┬─────────────────┘
                        │
       ┌────────────────┼────────────────┐
       ▼                ▼                ▼
 Dim_Agent          Dim_RM          Dim_Date
                        │
                        ▼
                   Data Model
                        │
                        ▼
                  DAX Measures
                        │
                        ▼
              Power BI Report Pages
                        │
                        ▼
                 Executive Dashboard
```

---

## ETL

Power Query

---

## Data Model

Star Schema

---

## Calculation Layer

DAX

---

## Presentation Layer

Power BI

---

## Output

Interactive Dashboard

Monthly Reporting

Executive Reporting
