# HICES 2023 — Household Income & Consumption Expenditure Analysis
### Saudi Arabia | General Authority for Statistics (GASTAT)

![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![Phase](https://img.shields.io/badge/Phase-3%20of%205-blue)
![Tools](https://img.shields.io/badge/Tools-SQL%20Server%20%7C%20Power%20BI%20%7C%20Excel-green)

---

## 📌 Project Overview

An end-to-end data analytics project built on the 2023 Household Income and Consumption Expenditure Survey (HICES) published by GASTAT. The goal is to transform raw national survey data into actionable insights about household economic behavior in Saudi Arabia.

---

## ❓ Key Analytical Questions

| # | Question |
|---|---|
| 1 | What is the income gap between Saudi and non-Saudi households? |
| 2 | Which administrative regions have the highest income and expenditure? |
| 3 | How does education level affect household income? |
| 4 | At what age does household income peak? |
| 5 | What are the largest household spending categories (COICOP)? |
| 6 | Are households saving or spending beyond their income? |

---

## 🗂️ Project Structure

```
HICES-2023-Analytics/
├── 01_raw_data/          # Original Excel file from GASTAT
├── 02_cleaned_csv/       # 7 cleaned and structured CSV datasets
├── 03_sql/               # SQL Server schema and analytical queries
├── 04_powerbi/           # Power BI dashboard file
└── 05_docs/              # Project scope document (PDF)
```

---

## 📊 Datasets (Phase 2 — Complete ✅)

| File | Description |
|---|---|
| `01_income_by_nationality.csv` | Average & median income — Saudi vs. Non-Saudi |
| `02_income_by_region.csv` | Income across all 13 administrative regions |
| `03_income_by_age.csv` | Income by age group of household head |
| `04_income_by_education.csv` | Income by education level |
| `05_expenditure_by_region.csv` | Expenditure across all 13 regions |
| `06_coicop_expenditure.csv` | Expenditure breakdown by COICOP categories |
| `07_savings_gap.csv` | Savings rate per region (income minus expenditure) |

---

## 🔍 SQL Queries (Phase 3 — Complete ✅)

| File | Business Question |
|---|---|
| `query_01_nationality_gap.csv` | Income gap between Saudi and non-Saudi households |
| `query_02_income_vs_expenditure_by_region.csv` | Which regions have highest income and expenditure? |
| `query_03_income_by_age.csv` | At what age does household income peak? |
| `query_04_income_by_education.csv` | How does education level affect income? |
| `query_05_expenditure_by_region.csv` | Expenditure distribution across regions |
| `query_06_coicop_expenditure.csv` | What are the largest household spending categories? |
| `query_07_savings_gap.csv` | Are households saving or spending beyond their income? |

---

## 🔧 Tools Used

- **Excel** — Data cleaning and CSV export
- **SQL Server (SSMS)** — Relational database and analytical queries
- **Power BI Desktop** — Interactive dashboard
- **GitHub** — Version control and project documentation

---

## 🗺️ Project Phases

| Phase | Description | Status |
|---|---|---|
| 1 | Project Scoping | ✅ Complete |
| 2 | Data Preparation | ✅ Complete |
| 3 | SQL Server Database & Queries | ✅ Complete |
| 4 | Power BI Dashboard | 🔄 In Progress |
| 5 | Final Documentation | ⏳ Not Started |

---

## 💡 Key Insights So Far

> Saudi household income is **232% higher** than non-Saudi — discovered through a computed SQL column combining CAST, arithmetic, and ROUND.

> **Jazan and Najran** show a negative savings rate, meaning households in these regions spend more than their disposable income.

---

## 📁 Data Source

**General Authority for Statistics (GASTAT) — Saudi Arabia**
Household Income and Consumption Expenditure Survey 2023
