# Global Vaccination Data Analysis & Dashboard

This project analyzes global vaccination coverage, disease incidence, reported cases, and vaccine introduction data from WHO sources. The goal was to clean, integrate, and visualize data to identify coverage gaps, measure campaign impact, and support better public health planning.

---

## Project Overview

Vaccines remain one of the most reliable ways to prevent infectious diseases, but coverage still varies across countries and regions. This project takes a data-driven approach to answer key questions such as:

* How vaccination rates relate to a drop in disease incidence
* Where drop-offs occur between 1st, 2nd, and 3rd doses
* Which regions are lagging behind global targets
* Where high-priority interventions are urgently needed

The cleaned data is stored in a MySQL database and connected to Tableau/Power BI dashboards for fast, interactive exploration.

---

## Tools & Technologies

* **Python** (Pandas, NumPy) – Data cleaning and preprocessing
* **MySQL** – Database creation, data storage, and indexing for performance
* **Tableau** – Interactive dashboards and visual analytics

---

## Data Processed Summary

* **Coverage dataset:** 399,858 records
* **Incidence dataset:** 84,945 records
* **Reported Cases dataset:** 84,869 records
* **Vaccine Introduction dataset:** 138,320 records
* **Vaccine Schedule dataset:** 8,052 records

**Total Records Processed:** **716,044** records from five datasets

All datasets were cleaned, standardized, and stored for downstream analysis. Missing values were handled carefully, and year columns were validated for consistency.

---

## Key Outcomes

* A fully populated **MySQL database** with indexed tables for fast queries
* **Interactive dashboards** that load in under 3 seconds even on large datasets
* **Regional performance analysis** with clear coverage categories (Excellent, Good, Moderate, Critical)
* Drop-off visualizations for dose administration and disease-specific insights

---

## Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/Sridevivaradharajan/Global-Vaccination-Data-Analysis.git
cd Global-Vaccination-Data-Analysis
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run preprocessing script** to clean data and save CSV files.

4. **Import SQL scripts** to create tables and load data into MySQL.

5. Open the dashboard file in Tableau or Power BI and explore the insights.

---

## License

This repository is licensed under **Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0)**.
You may use, share, and adapt the project **for non-commercial purposes** with proper credit.
