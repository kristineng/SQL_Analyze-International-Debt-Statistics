# SQL - Analyze International Debt Statistics

An exploratory data analysis project utilizing SQL to analyze international debt data collected by The World Bank. The dataset tracks external debt (in USD) owed by developing countries across various financial indicators.

## Key Findings
* **Total Global Debt:** Over 3.07 trillion USD is owed by the developing countries.
* **Highest Debtor:** **China** holds the highest total amount of debt, exceeding 285.79 billion USD.
* **Top Debt Category:** Long-term external debt principal repayments (`DT.AMT.DLXF.CD`) average the highest amount of debt across all indicators globally.
* **Prevalence:** There are 6 primary debt categories that apply universally to every single developing nation in the dataset, highlighting shared global macroeconomic patterns.

## Skills
* **Language:** SQL (PostgreSQL)
* **Environment:** Jupyter Notebook
* **Libraries:** `ipython-sql` (for executing inline SQL queries) and `pandas` (for rendering data results into clean dataframes)

## Database Schema
The data is structured inside a single table named `international_debt`:

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `country_name` | VARCHAR | Name of the country |
| `country_code` | VARCHAR | 3-letter unique country code |
| `indicator_name` | TEXT | Description of the purpose of the debt |
| `indicator_code` | VARCHAR | Unique code representing the type of debt |
| `debt` | NUMERIC | Total debt amount in USD |

## Key Queries Executed
The project answers specific economic questions through SQL optimization techniques including:
* Advanced aggregations (`SUM`, `AVG`, `MAX`) to scale figures dynamically.
* `DISTINCT` and `COUNT` operations to pinpoint global market participants.
* Data filtering and isolation using `GROUP BY`, `HAVING`, and conditional string clauses.

*Data Source: The World Bank (International Debt Statistics)*

### For further details, please visit the Notebook.

Thank you!
