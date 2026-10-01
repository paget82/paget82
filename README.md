# Hi there, I'm Patrik Pagac! 👋

**Data Analyst | Data Pipelines (dbt & Airflow) | Python & SQL | Power BI | AI Automation**

I'm a self-taught data analyst based in Prague. I work across the data lifecycle: building tested, orchestrated pipelines, modeling data in SQL, and turning it into dashboards, reports and models that help people make better decisions. I'm also exploring how AI agents can make data accessible to everyone, not just people who write SQL.

---

## 🚀 Top Data Projects

### 🏗️ [Loan-data-pipeline](https://github.com/paget82/loan-data-pipeline) | End-to-End Data Engineering Pipeline
* **Core:** Fully orchestrated daily batch pipeline for loan and transaction data: synthetic data generation → raw load into PostgreSQL → dbt staging and dimensional marts → automated data quality tests → Power BI reporting.
* **Tech:** Python (Faker, Pandas, SQLAlchemy, Requests), PostgreSQL, dbt, Apache Airflow, Docker Compose, GitHub Actions (CI), Power BI, public REST API (Frankfurter / ECB exchange rates).
* **Impact:** Replaces manual, error-prone refreshes with a scheduled, tested and observable process. dbt tests and CI catch broken models or bad data before they reach a dashboard. The pipeline handles ~60,000 transactions, ~8,000 loans and ~5,000 clients (synthetic US-market data), enriches loans with live exchange rates and converts USD amounts to EUR, validated end-to-end in Power BI.



### 🤖 [AI Data Analyst Agent](https://github.com/paget82/ai-data-analyst) | AI Agent for Natural-Language Data Analysis
* **Core:** Chat-based AI analyst that lets non-technical users ask questions about an e-commerce database in plain language and get back a written answer, a table and a chart.
* **Tech:** n8n, LangChain agent (GPT), Claude (NL → SQL), PostgreSQL, React + TypeScript + Tailwind, Docker Compose.
* **Impact:** Removes the "ask the data team" bottleneck: no SQL needed for questions like *"What is the average delivery time by state?"*

### 📊 [Bank Loan Dashboard](https://github.com/paget82/dashboard-bankovnich-pujcek) | Power BI & SQL Dashboard
* **Core:** Interactive loan-portfolio dashboard for management, built on 38,576 loan records.
* **Tech:** SQL, Power BI, DAX (`CALCULATE`, `TOTALMTD`, `TOTALYTD`, `SAMEPERIODLASTYEAR`, `DATEADD`).
* **Impact:** Instant view of applications, funded amount, received payments, interest rate and DTI, including MTD and MoM trends and a breakdown by loan status, term, purpose and home ownership.

### 🧪 [Loan Approval Prediction](https://github.com/paget82/Predikce-schvaleni-pujcky) | Machine Learning & Prediction
* **Core:** Predicting loan approval to help automate and speed up the decision process.
* **Tech:** Python, Scikit-learn, EDA, 7 models compared (Logistic Regression, KNN, SVM, Naive Bayes, Decision Tree, Random Forest, Gradient Boosting).
* **Impact:** Benchmarked multiple classifiers on 614 applications, with the best model reaching **81% accuracy**.

### 🛍️ [Mall Customer Segmentation](https://github.com/paget82/segmentace-zakazniku) | Customer Segmentation
* **Core:** Clustering shopping-mall customers by age, income and spending score.
* **Tech:** Python, Pandas, Seaborn, Matplotlib, Scikit-learn (K-Means, Elbow method).
* **Impact:** Identified 5 customer segments, including a high-income, high-spending VIP group, and turned them into concrete marketing recommendations.

### 🍪 [Sales report for Cookie Company](https://github.com/paget82/Report-prodeju-spolecnosti-cookie) | Excel Sales Report
* **Core:** 2024 sales report for Cookie Company, with a summary overview and a detailed view by month, region and product.
* **Tech:** Excel, Pivot Tables, Slicers, `VLOOKUP`, `IFERROR`, line and pie charts.
* **Impact:** Turned 643 raw order records into a report that supports production and marketing planning.



---

## 🛠️ Tech Stack

| Category | Tools & Technologies |
| :--- | :--- |
| **Data Science** | Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib), Jupyter |
| **Data Engineering** | dbt, Apache Airflow, ETL / ELT, dimensional modeling, data quality testing, REST API integration |
| **Databases** | SQL, PostgreSQL |
| **BI & Reporting** | Power BI (DAX), Excel (Pivot Tables, VLOOKUP, Slicers) |
| **Automation & AI** | n8n, LangChain, AI Agents (OpenAI / Anthropic) |
| **Dev Tools** | Docker, Docker Compose, Git, GitHub Actions (CI), React / TypeScript (basics) |

---

## 🎯 What I'm Focused On

* Building end-to-end data solutions: from pipelines and SQL modeling to dashboards and insights
* Machine learning for business problems (classification, clustering)
* AI-powered analytics and workflow automation

---

## 📫 Let's Connect!
- 📧 Email: [patrik.pagac@gmail.com](mailto:patrik.pagac@gmail.com)

---
*I believe that good analysis starts with understanding the business question, and that data should be easy for everyone to use.*
