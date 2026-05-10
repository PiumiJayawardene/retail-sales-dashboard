\# 📊 Retail Sales Performance Dashboard



\## Business Problem

A retail company needs visibility into sales performance across regions, 

product categories, and customer segments to make data-driven 

decisions about discounting, inventory, and marketing focus.



\## Objective

Build an interactive Power BI dashboard answering 5 key business 

questions, supported by SQL queries and Python EDA.



\## Dataset

\- Source: Sample Superstore (Kaggle)

\- Size: \~10,000 orders | 21 columns | 2014–2017

\- Link: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final



\## Tools \& Technologies

| Tool | Purpose |

|------|---------|

| SQL Server | Data storage \& aggregation queries |

| Python (pandas, seaborn) | EDA \& data cleaning |

| Power BI Desktop | Interactive dashboard |

| Jupyter Notebook | Analysis notebook |



\## Key Findings

1\. West region leads in revenue; East has higher profit margin

2\. Technology is the most profitable category (\~17% margin)

3\. Sales peak every November–December (seasonal pattern)

4\. Orders with >20% discount almost always generate negative profit

5\. Phones \& Chairs lead revenue; Copiers lead profit-per-unit



\## Dashboard Preview

!\[Dashboard](dashboards/screenshots/dashboard\_main.png)



\## How to Run

1\. Clone this repo: git clone <repo-url>

2\. Install requirements: pip install -r requirements.txt

3\. Open notebooks/01\_EDA\_Retail\_Sales.ipynb in Jupyter

4\. Open dashboards/retail\_sales\_dashboard.pbix in Power BI Desktop



\## Project Structure

```

retail-sales-dashboard/

├── data/raw/          ← original CSV

├── data/processed/    ← cleaned CSV

├── notebooks/         ← Jupyter EDA notebook

├── sql/               ← SQL queries

└── dashboards/        ← .pbix file + screenshots

```

