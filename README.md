# Anime Dashboard — Data Cleaning & Visualization

This project analyzes and visualizes a dataset of **28,627 anime titles** using **Google Sheets**.  
It includes data cleaning, KPI metrics, and multiple pivot charts to explore industry patterns such as studio activity, rating distribution, and content types.

---

## Link
**[Anime Dashboard (Google Sheets)](https://docs.google.com/spreadsheets/d/1OpV8CJ_FgUHCkgm7SXEChfhtyMhQbYVNupBGjf8fSmA/edit?usp=sharing)**

---

## Data Cleaning Steps
- Removed **2,000+ rows** with null or empty cells  
- Replaced blanks with `"N/A"`  
- Standardized column names (`title_english`, `title_japanese`, etc.)  
- Removed duplicates based on `mal_id`  
- Fixed inconsistent entries in categorical columns (e.g. `"Light novel"` vs `"light novel"`)  
- Converted rating categories into **numerical scale** for visualization  

---

## KPIs (Key Performance Indicators)

| Metric | Description | Value |
|--------|--------------|-------|
| **Total anime titles** | Total entries after cleaning | 28,627 |
| **Total studios** | Unique animation studios | 1,885 |
| **Average score** | Mean viewer score (filtered numeric) | 6.40 |
| **Average rating (age)** | Mean age-based category rating | 2.46 |
| **Missing scores** | Rows without score values | 13,620 |
| **% Missing scores** | Share of missing values | 47.6% |

---

## Visualizations
- **Distribution by Rating** — G and PG-13 dominate (~65%)  
- **Titles by Studio** — Top 15 studios cover ~30% of total production  
- **Average Score by Type** — OVA and TV formats score highest  
- **Data Cleaning Summary** — automated and manual corrections  

---

## Tools Used
- **Google Sheets** — data cleaning, formulas, KPI dashboard  
- **Pivot Tables & Charts** — visualization  
- **CSV Dataset** — from public anime databases  

---

## Project Goals
To create a clean, interpretable dataset and visualize key insights about anime production, ratings, and studio output.  
This dashboard demonstrates **data cleaning**, **exploratory analysis**, and **presentation of metrics** — essential skills for a data analyst.

---

## Files Included
- `anime_cleaned_v2.csv` — cleaned dataset  
- `README.md` — project overview
- `Licence` - terms of use and distribution for this project

---

## Author
**[Alex Shevchenko](https://github.com/Borock1212)**
