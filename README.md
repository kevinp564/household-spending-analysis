# Household Spending Analysis (Colombia)

## Overview

This project analyzes **household spending based on purchase receipts** to understand consumption patterns, category behavior, and the impact of **inflation in Colombia (2025–early 2026)**. Using cleaned receipt-level data, the analysis explores how prices and spending evolved over time and contrasts observed behavior with **economic theory** (mechanical inflation effect).

---

## Research Questions

* How did total household spending evolve over the period analyzed?
* Which categories contributed most to spending changes?
* How does inflation mechanically affect spending when quantities are held constant?
* Do observed patterns align with theoretical expectations?

---

## Data

* **Source:** Manually collected household purchase receipts
* **Granularity:** Receipt-level transactions
* **Frequency:** Bi-weekly purchases
* **Geography:** Colombia
* **Time span:** 2025

---

## Methodology

1. Manual data entry and validation of receipt-level purchases in spreadsheets
2. Data cleaning and standardization of product categories using Excel / Google Sheets
3. Aggregation of nominal spending by period and category
4. Integration of inflation context as a theoretical benchmark
5. Interpretation of observed trends using economic theory, with explicit assumptions and limitations

---

## Key Insight

* Nominal spending decreased despite inflation, implying that quantity reductions and substitution effects dominated price-driven pressures

---

## Reproducibility

This project follows a spreadsheet-based reproducibility approach. All transformations, aggregations, and calculations were performed in Google Sheets and are reflected in the processed dataset.

To reproduce the analysis:

1. Review the raw dataset in data/raw/
2. Follow documented cleaning and categorization logic to obtain the processed dataset
3. Review the analytical report in docs/, which references the cleaned data

Key assumptions and methodological decisions are explicitly documented in the report.

---

## Repository Structure

```
├── data/
│ ├── processed/
│ │ └── household_goods_2025_cleaned.xlsx
│ ├── raw/
│ │ └── household_goods_2025_raw.xlsx
├── docs/
│ └── household_spending_patterns_under_inflation.pdf
├── README.md
```

---

## Tools & Skills

* Microsoft Excel / Google Sheets
* Data cleaning & validation
* Descriptive analysis and aggregation
* Economic reasoning (inflation & consumer behavior)
* Documentation & analytical reporting

---

## Author

**Kevin Pelaez**
Bilingual (Spanish–English) Customer Support Specialist transitioning into Data Analytics
