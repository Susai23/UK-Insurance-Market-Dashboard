# UK Insurance Market Dashboard 🇬🇧

A 6-page Power BI dashboard analyzing the UK insurance market using real, 
publicly available datasets from the FCA, ONS, and Kaggle.

## ✅ Status: Complete

## Dashboard Pages
1. **Cover** — Project overview and data sources
2. **Inflation Tracker** — CPIH insurance price index, 2015–2026
3. **Value Measures** — FCA claims payout % by product, value ratings
4. **Insurer Complaints** — Top firms by complaint volume, group breakdown
5. **Motor Claims** — Risk analysis across 58k+ policies (age, fuel, vehicle)
6. **Market Trend** — UK-wide complaint volumes by financial sector, 2020–2025

## Key Insights
- Insurance prices have risen 73% since 2015 (CPIH Index)
- Travel add-on insurance pays out only 23% of premiums vs 129% for GAP insurance
- British Gas Services had 94.9% of complaints upheld in H1 2025
- Customers aged 65–75 file motor claims at more than double the rate of 35–44 year olds
- UK insurance complaints have fallen 34% from their 2020 peak

## Data Sources
- Financial Conduct Authority (FCA) — Value Measures & Complaints Data
- Office for National Statistics (ONS) — CPIH Insurance Index
- Kaggle — Insurance Claims Dataset

## Raw Data
The source datasets used to build the dashboard are available in [`data/`](data):
- `CPIH_INDEX_Insurance.xlsx` — ONS CPIH insurance price index
- `FCA_General_Insurance_Value_Measures_2024.xlsx` — FCA value measures by product
- `Firm_Level_Complaints_Data_2025H1.xlsx` / `Firm_Level_Complaints_Data_2025H2.xlsx` — FCA firm-level complaints data
- `Volume_of_Complaints_Received_2025H1.xlsx` / `Volume_of_Complaints_Received_2025H2.xlsx` — FCA complaint volumes by sector
- `Insurance_Claims_Data.xlsx` — Kaggle motor insurance claims dataset

## Tools
Power BI Desktop | Power Query | DAX

## Tech Highlights
- Built a normalized data model resolving multi-period (annual/quarterly/monthly) 
  and duplicate-key source data
- Custom DAX measures: YoY change %, claim rate, value ratios, ranking functions
- Conditional formatting and custom theming across all 6 pages
- Resolved many-to-many relationship issues via Power Query merge strategy

## View the Dashboard
[Download .pbix](https://github.com/Susai23/UK-Insurance-Market-Dashboard/raw/main/UK_Insurance_Market_Dashboard.pbix) | [View PDF](https://github.com/Susai23/UK-Insurance-Market-Dashboard/blob/main/UK_Insurance_Market_Dashboard.pdf)
