<div align="center">

# Hi, I'm Oscar

**Analytics Engineer · Finance background · I build data pipelines**

Python · SQL · Databricks · dbt ·  Airflow · Power Bi · Docker

<a href="https://www.linkedin.com/in/oscar-rodriguez-7b341823b/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:orodriguezh33@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<sub>Based in Colombia (UTC-5) · Open to remote roles</sub>

</div>

---

## About me

Analytics Engineer with a Finance background — I spent years reading financial and operational numbers before I started building the systems that produce them.

I have a Master's in Financial Management, and I work with Python, SQL, dbt, Airflow, Databricks and Power BI to turn raw, multi-source data into reliable, analytics-ready models.

**How I work**

- End-to-end ownership: ingestion → transformation → validation → output
- Reproducible by default — containerized and version-controlled
- Every model traces back to a business question, not just a schema
- Real operational and financial data: banking, QuickBooks, payments, regulatory filings

---

## Featured project

### [Customer Churn Analysis Portfolio](https://github.com/orodriguezh33/Customer-Churn-Analysis-Portfolio)

A Bronze → Silver → Gold pipeline on Databricks and dbt across 6,007 customers (28.8% historical churn), feeding a logistic regression tuned for recall over precision — missing an at-risk customer costs more than calling a safe one.

- **0.82 recall, 0.87 ROC AUC**, with the threshold chosen for the business cost of a false negative rather than for a leaderboard metric.
- **A churn rate that can't be gamed** — the KPI uses the exposed base (churned + stayed) as its denominator, excluding newly joined customers, so the number can't be improved just by acquiring more.
- **Output the commercial team can use** — a Power BI dashboard that ranks 280 of 405 scored customers into a prioritized call list.

`Python` `scikit-learn` `Databricks` `dbt` `SQL` `Power BI` `DAX`

---

## Also on my GitHub

- **[SQL Data Warehouse ELT Pipeline](https://github.com/orodriguezh33/sql-datawarehouse-etl)** — Bronze/Silver/Gold medallion ELT with reusable validation logic, containerized with Docker.

- **[Weather ETL — Airflow on Astro Runtime](https://github.com/orodriguezh33/ETL-Weather-con-Astro-Airflow-y-PostgreSQL)** — a small, reproducible Airflow reference: a scheduled extract/transform/load DAG against the Open-Meteo API, with connections declared in `airflow_settings.yaml` rather than clicked into the UI, idempotent table creation, and `astro dev parse` / `pytest` checks.

- **[Data Engineering Projects](https://github.com/orodriguezh33/data_engineering_projects)** — SQL exercises and notebooks working through data engineering patterns.


---

## Tech stack

**Pipelines & orchestration** — Python, dbt, Apache Airflow, Astro Runtime, Docker

**Storage & warehousing** — Databricks, PostgreSQL, SQL Server, DuckDB, Delta Lake, Parquet

**Analysis & BI** — pandas, scikit-learn, Power BI, DAX, advanced Excel

**Workflow** — Git, GitHub, uv, Linux terminal

**Learning** — AWS (S3, IAM), Terraform

---

## Currently building

- **Customer Revenue Prediction** — regression and behavioral segmentation on the UCI Online Retail II dataset: raw transactions rolled into a customer-level feature table, then used to predict forward revenue and cluster customers by purchasing behavior.
- **Walmart Data Platform** — a retail lakehouse with Postgres CDC into Databricks, a dbt medallion architecture, and Airflow orchestration, with the cloud layer as infrastructure as code: Terraform provisioning the S3 bucket and IAM policies instead of console clicks.

---

<div align="center">
<sub>Open to remote Analytics Engineering, Data Engineering and BI roles · <a href="mailto:orodriguezh33@gmail.com">orodriguezh33@gmail.com</a></sub>
</div>
