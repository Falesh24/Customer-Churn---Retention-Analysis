# Customer Churn & Retention Analysis

An end-to-end customer churn analysis project using **SQL, Python, Pandas, Seaborn, Matplotlib, and Tableau**.

The project analyses customer subscription, contract, support, satisfaction, tenure, and CLTV data to identify **patterns associated with customer churn** and derive retention insights.

## Objective

Identify customer segments and behavioural patterns associated with churn, quantify the observed patterns, and recommend potential retention actions.

## Tech Stack

* **SQL / SQLite** — Data querying and analysis
* **Python / Pandas** — Data cleaning and feature engineering
* **Seaborn / Matplotlib** — Exploratory data analysis
* **Tableau Public** — Interactive dashboard
* **Jupyter Notebook** — Analysis workflow

## Key Findings

* Monthly contracts showed a **55.6% churn rate**, compared with **8.3% for annual contracts**.
* Basic plan customers showed the highest churn rate at **60.0%**.
* Customers with support interactions showed **85.7% churn** within this dataset.
* All customers with recorded escalations churned.
* Churned customers with support interactions had lower CSAT scores than the retained support customer.
* Churned customers had lower average tenure and CLTV than retained customers.

> **Note:** The dataset contains only 21 customers, so these findings are directional and should not be treated as statistically generalisable or causal.

## Tableau Dashboard

[View Customer Churn & Retention Dashboard](https://public.tableau.com/views/CustomerChurnRetentionAnalysis_17895291852470/CustomerChurnRetention___)

## Project Files

```text
customer_churn.db
customer_churn_data_raw.xlsx
customer_churn_analysis.ipynb
customer_churn_analysis.csv
tested.sqlite
README.md
```

* `customer_churn.db` — SQLite database
* `customer_churn_data_raw.xlsx` — Raw dataset
* `customer_churn_analysis.ipynb` — Complete analysis
* `customer_churn_analysis.csv` — Final analytical dataset
* `tested.sqlite` — SQLite testing database

## Analysis Workflow

**SQL → Pandas → EDA → Business Insights → Tableau Dashboard**

## Author

**Falesh Kumar Sahu**
B.Tech — Computer Science & Engineering (Data Science)
