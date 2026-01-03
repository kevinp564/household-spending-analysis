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

1. Data cleaning and standardization of product categories
2. Inflation context integration (macro-level reference)
3. Aggregation of spending by period and category
4. Comparative analysis of nominal spending trends
5. Interpretation using economic theory

---

## Key Insight

* Nominal spending decreased despite inflation, implying that quantity reductions and substitution effects dominated price-driven pressures

---

## Reproducibility

All steps required to reproduce this analysis are documented. The repository includes:

* Raw and cleaned datasets
* Analysis notebooks
* Clear assumptions and data processing logic

To reproduce:

1. Clone the repository
2. Install required dependencies
3. Run notebooks in numerical order

---

## Repository Structure

```
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_insights_and_conclusions.ipynb
├── visuals/
├── README.md
└── requirements.txt
```

---

## Tools & Skills

* Data cleaning & validation
* Exploratory data analysis
* Economic reasoning
* Documentation & reproducibility

---

## Author

**Kevin Pelaez**
Bilingual (Spanish–English) Customer Support Specialist transitioning into Data Analytics
