# HICES 2023 — Household Income & Consumption Expenditure Analysis
### Saudi Arabia | General Authority for Statistics (GASTAT)

![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Phase](https://img.shields.io/badge/Phase-5%20of%205-success)
![Tools](https://img.shields.io/badge/Tools-SQL%20Server%20%7C%20Power%20BI%20%7C%20Excel-blue)

---

## 📌 Project Overview

An end-to-end data analytics project built on the 2023 Household Income and Consumption Expenditure Survey (HICES) published by GASTAT. The goal is to transform raw national survey data into actionable insights about household economic behavior in Saudi Arabia — covering income, expenditure, demographics, regions, and savings.

---

## ❓ Key Analytical Questions

| # | Question | Answered In |
|---|---|---|
| 1 | What is the income gap between Saudi and non-Saudi households? | Overview |
| 2 | Which administrative regions have the highest income and expenditure? | Regional Analysis |
| 3 | How does education level affect household income? | Demographics |
| 4 | At what age does household income peak? | Demographics |
| 5 | What are the largest household spending categories (COICOP)? | Expenditure & Savings |
| 6 | Are households saving or spending beyond their income? | Expenditure & Savings |

---

## 🗂️ Project Structure

```
HICES-2023-Analytics/
├── 01_raw_data/          # Original Excel file from GASTAT
├── 02_cleaned_csv/        # 7 cleaned and structured CSV datasets
├── 03_sql/                # SQL Server analytical queries (7 queries)
├── 04_powerbi/            # Power BI dashboard (.pbix) — 4 pages
└── 05_docs/               # Project scope document (PDF)
```

---

## 📊 Datasets

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

## 🔍 SQL Queries

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

## 📈 Power BI Dashboard — `HICES_2023_Dashboard.pbix`

A 4-page interactive dashboard:

| Page | Content |
|---|---|
| **Overview** | Income & expenditure comparison (Saudi vs. Non-Saudi), income gap gauge, donut chart |
| **Demographics** | Income by age group and education level, with key insights |
| **Regional Analysis** | Filled map + bar chart comparing income and expenditure across all 13 regions |
| **Expenditure & Savings** | COICOP spending treemap + savings rate by region |

---

## 🔧 Tools Used

- **Excel** — Data cleaning and CSV export
- **SQL Server (SSMS)** — Relational database and analytical queries
- **Power BI Desktop** — Interactive 4-page dashboard
- **GitHub** — Version control and project documentation

---

## 🗺️ Project Phases

| Phase | Description | Status |
|---|---|---|
| 1 | Project Scoping | ✅ Complete |
| 2 | Data Preparation | ✅ Complete |
| 3 | SQL Server Database & Queries | ✅ Complete |
| 4 | Power BI Dashboard | ✅ Complete |
| 5 | Final Documentation | ✅ Complete |

---

## 💡 Key Insights

> **Saudi household income is 232% higher** than non-Saudi household income — the largest gap among all demographic factors analyzed.

> **Household income peaks in the 55-59 age group**, then declines after retirement age (65+).

> **Education has the strongest single impact on income** — Master's degree holders earn nearly 3x more than those with no schooling.

> **Riyadh and the Northern Border** lead in both income and expenditure, while **Jazan** shows the highest expenditure relative to its income.

> **Food and beverages account for 27.9%** of household spending — the largest COICOP category, followed by housing and transport.

> **Jazan and Najran are the only regions** where households spend more than they earn, showing negative savings rates of -24.06% and -2.38% respectively.

---

## 📁 Data Source

**General Authority for Statistics (GASTAT) — Saudi Arabia**
Household Income and Consumption Expenditure Survey 2023

---

## 👤 Author

**Hussain Alsabah**
