# Sales-analysis
# E-Commerce Sales Analysis: SQL, Python & Tableau

## 📖 Project Overview
This project is a **comprehensive analytical study** of an online store’s sales performance.  
The goal was to demonstrate **end-to-end data analysis skills (ETL, EDA, Statistics, Visualization)** using three key tools:  
- **SQL (Google BigQuery)** for data extraction and preparation,  
- **Python (Pandas)** for statistical analysis and insights,  
- **Tableau** for creating an interactive analytical dashboard.

---

## 🎯 Key Objectives
1. **ETL:** Build a unified dataset from a cloud database (Google BigQuery).  
2. **EDA & Statistics:** Perform exploratory, dynamic, and statistical analysis to identify patterns, correlations, and differences between user groups.  
3. **Visualization:** Develop an interactive Tableau dashboard for business stakeholders.

---

## ⚙️ Tools & Technologies

| Category        | Tools / Libraries                 | Purpose |
|-----------------|-----------------------------------|----------|
| **Database**    | Google BigQuery                   | SQL-based data extraction from the raw dataset |
| **Data Analysis** | Python (Pandas, NumPy)           | Data cleaning, processing, and aggregation |
| **Statistics**  | Python (Scipy.stats, Statsmodels.stats.proportion)              | Correlation tests, normality checks, and group comparison |
| **Visualization (EDA)** | Python (Matplotlib, Seaborn) | Graphs and visual exploration |
| **BI Reporting** | Tableau Public                   | Interactive dashboard creation |

---

## 📊 Data Analysis & Key Insights (Python)

### 1. Dataset Description & ETL
Data was extracted from **Google BigQuery** via a Python script using a **SQL query with LEFT JOIN**, ensuring inclusion of all sessions and orders.

| Metric | Value | Insight |
|--------|--------|----------|
| Total Columns | 18 | Comprehensive dataset for multi-dimensional analysis |
| Time Period | 2020-11-01 → 2021-01-27 | 3-month sales observation window |
| Unique Sessions | 33,538 | Large sample for behavioral analysis |
| Missing Values | `registered_user_id` (~92%) | Most orders made by guests → important segment for analysis |

---

### 2. Top Metrics & Geography
- **Top-3 Continents by Sales**
- **Top-10 Product Categories**
- **Traffic & Channel Distribution**

---

### 3. Statistical Relationship Analysis
- Correlation analysis between sales and user behavior metrics  
- Hypothesis testing for group differences  
- Validation of normal distribution assumptions  

---

## 📈 Interactive Dashboard (Tableau Public)
An **interactive Tableau dashboard** was developed to visualize key metrics and insights, providing a clear and dynamic view of sales performance, user segments, and traffic sources.

*([[View on Tableau Public](https://public.tableau.com/views/Salesanalysis_17619092625440/Sales?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)](#))*

---

## 🧩 Key Takeaways
- Built an integrated ETL pipeline from SQL to Python.  
- Conducted advanced EDA and statistical testing.  
- Identified customer behavior patterns driving higher sales.  
- Visualized findings through an interactive Tableau dashboard.


> **Author:** [Hanna Nikitenko]  
> **Notebook:** [View in Google Colab](https://colab.research.google.com/drive/1En_wJ_3ugrwi3BaYc3Q7Q2vSSZqZtrOV?usp=sharing)
> **Dashboard:** *((https://public.tableau.com/views/Salesanalysis_17619092625440/Sales?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))*
