# Mokshith Talari – Data / Business Analyst Portfolio

Welcome to my public portfolio showcasing practical examples of my expertise in data engineering, business analytics and risk management.  I’ve spent the last three years building analytics pipelines and compliance solutions in the banking, compliance and energy sectors.  My work ranges from automating complex workflows to designing intuitive dashboards that drive business decisions and regulatory compliance.

## 🔍 About Me

- **Role:** Business Analyst / Data Analyst (STEM OPT)
- **Experience:** 3+ years across banking, compliance and energy sectors
- **Skills:** SQL, Python, Airflow, NiFi, SSIS, Power BI, Tableau, Excel VBA, Snowflake, PostgreSQL, Oracle, SAP
- **Strengths:** Building end‑to‑end data pipelines, producing data‑driven dashboards, authoring BRD/FRD documentation, migrating multi‑terabyte data workloads, and collaborating with cross‑functional teams
- **Achievements:** Shipped analytics automation that reduced churn by **18%** and delivered **~$120K/year savings**; migrated **3.5 TB** of risk data; authored 10+ BRD/FRDs; implemented KYC validation solutions

## 💂 Portfolio Projects

Each repository below includes a clear problem statement, approach and results, synthetic data only, unit tests and a CI workflow running on GitHub Actions.  These projects mirror real projects I’ve delivered at scale while keeping proprietary data confidential.

| Repository | Description |
|-----------|-------------|
| **[etl‑bi‑pipeline](https://github.com/vickymokshith/etl-bi-pipeline)** | Demonstrates a **CSV → SQLite ETL pipeline** built with Python and pandas.  It extracts synthetic sales data, transforms it by calculating revenue (units × price) and loads it into a SQLite database, producing a simple revenue‑over‑time chart.  This project reflects my hands‑on experience building ETL processes that feed BI dashboards and generate actionable insights. |
| **[risk‑model‑validation](https://github.com/vickymokshith/risk-model-validation)** | Showcases how to validate **scorecard models** in compliance and credit‑risk contexts using statistical metrics.  Functions compute the **Population Stability Index (PSI)** and **KS statistic**, and a notebook walks through splitting data by date and interpreting results.  SQL files include schema definitions and quality checks.  This mirrors my work ensuring model performance and governance for regulatory compliance. |
| **[automation‑kpi](https://github.com/vickymokshith/automation-kpi)** | Builds a tiny CLI that parses raw **application logs** to compute KPIs—total requests, error counts, error rate and peak requests per minute.  The project demonstrates turning unstructured logs into metrics that help monitor system health and surface issues faster.  It reflects my experience automating operational reporting and building self‑service analytics tools. |

### Getting Started

For each repo you can clone the repository, install the requirements (`pip install -r requirements.txt`), and run the tests via `pytest`.  The CI workflows ensure that every commit runs against Python 3.11 on GitHub Actions.

---

If you’re interested in collaborating or have questions about my work, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/talari-mokshith/).
