<div align="center">

# Hi, I'm Oscar

**Analytics Engineer | SQL, Python, dbt | Finance Data Consolidation**

SQL · Python · dbt · Databricks · Airflow · Power BI · Docker

<a href="https://www.linkedin.com/in/oscar-erh/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:orodriguezh33@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<sub>Based in Colombia (UTC-5) · Open to remote roles</sub>

</div>

---

## About me

Analytics Engineer with a finance background. I spent years reading financial and operational numbers before I started building the pipelines that produce them.

I have a Master's in Financial Management, and my best-known result is cutting a 3-hour financial reporting task to 15 minutes by consolidating 9 entities and 15 bank accounts into one Python pipeline.

**How I work**

- End-to-end ownership: ingestion → transformation → validation → output
- Reproducible by default: containerized, version-controlled, tested in CI
- Every model traces back to a business question, not just a schema
- Real operational and financial data: banking, QuickBooks, payments, tax filings

---

## Featured projects

### [Retail Data Platform](https://github.com/orodriguezh33/retail-data-platform)

A retail lakehouse that moves operational data from PostgreSQL into Databricks through CDC, transforms it with dbt in a medallion architecture and runs daily on Airflow.

- **6 incremental models and 5 SCD Type 2 dimensions** built from dbt snapshots, feeding an order-line fact table in a star schema.
- **A 10-task Airflow DAG** that checks source freshness first and runs dbt tests after each layer.
- **CI on every pull request**: ruff, sqlfluff and dbt test in GitHub Actions.

`Databricks` `Delta Lake` `dbt` `Airflow` `PostgreSQL` `Docker` `GitHub Actions`

### [Customer Churn Analysis](https://github.com/orodriguezh33/Customer-Churn-Analysis-Portfolio)

A Bronze → Silver → Gold pipeline on Databricks and dbt across 6,007 customers (28.8% historical churn), feeding a logistic regression tuned for recall: missing an at-risk customer costs more than calling a safe one.

- **0.82 recall, 0.87 ROC AUC**, with the threshold chosen for the business cost of a false negative.
- **A churn rate that can't be gamed**: the KPI uses the exposed base (churned + stayed) as its denominator, so acquiring new customers cannot improve it.
- **Output the commercial team can use**: a Power BI dashboard that ranks 280 of 405 scored customers into a prioritized call list.

`Python` `scikit-learn` `Databricks` `dbt` `SQL` `Power BI` `DAX`

---

## More projects

- **[Job Market Data Warehouse](https://github.com/orodriguezh33/data_engineering_projects)**: a DuckDB pipeline from Google Cloud Storage into a star schema with 4 analytical data marts, idempotent loads and incremental updates with MERGE.
- **[SQL Data Warehouse ETL](https://github.com/orodriguezh33/sql-datawarehouse-etl)**: a tutorial-based SQL Server warehouse (bronze, silver, gold) that I extended with Python orchestration, Docker Compose and fail-fast validation.

---

## Client work (private repositories)

- **Multi-entity finance consolidation, Santos Coffee (US)**: a Python (pandas) ETL pipeline that consolidates 15 bank accounts, 9 QuickBooks companies and Toast POS data into one reconciled dataset. Cut a 3-hour reporting task to 15 minutes.
- **Colombian tax reporting pipeline (DIAN)**: a config-driven Python ETL (pandas, Parquet) that consolidates e-invoicing exports per company, with data quality checks for duplicate invoice IDs and mismatched taxpayer IDs. Reduced a 2-hour process to 10 minutes.

---

## Tech stack

**Pipelines and orchestration**: Python, dbt, Apache Airflow, Docker

**Storage and warehousing**: Databricks, Delta Lake, PostgreSQL, SQL Server, DuckDB, Parquet, Amazon S3, Google Cloud Storage

**Data quality**: dbt tests, source freshness checks, CI with GitHub Actions

**Analysis and BI**: pandas, scikit-learn, Power BI, DAX, Matplotlib, Plotly

**Workflow**: Git, GitHub, uv, Linux terminal

**Learning**: Terraform, AWS

---

<div align="center">
<sub>Open to remote Analytics Engineering, Data Engineering and BI roles · <a href="mailto:orodriguezh33@gmail.com">orodriguezh33@gmail.com</a></sub>
</div>
