
<img width="1376" height="768" alt="new_banner_linkedin" src="https://github.com/user-attachments/assets/9e8eaab7-7377-42ea-b520-90da462519c6" />


# 👋 Hi, I'm Julian

## ❄️ Analytics Engineer – Snowflake & dbt

I'm a **Analytics Engineer specialized in Snowflake & dbt**, working at the intersection of **data platforms, analytics, and business impact**.

I specialize in warehouse optimization, efficient clustering, QAS/SOS, and enforcing data governance through masking policies. I manage end-to-end data quality, automated testing, comprehensive documentation, and proactive platform auditing. I transform raw layers into clean, production-ready dimensional models to deliver reliable data to downstream BI teams.

My work focuses on **Data Quality**, **Cost Optimization** and **Performance Tuning** to deliver scalable and cost-efficient data architectures.

---

## 🚀 Highlight Project
## ❄️ Snowflake & dbt Core Hub
**Core Focus:** Analytics Engineering | Cost Optimization (FinOps) | Performance Tuning | GitOps Governance

## Key Implemented Features

### 🛠️ GitOps Infrastructure & Governance
* **DCM Infrastructure as Code:** Native automation of Snowflake environments via `Snowflake Database Change Management (DCM)` integrated into a robust **GitHub Actions CI/CD pipeline**.
* **Streamlit Access Manager App:** A secure, self-service app deployed natively inside Snowflake for multi-user creation and bulk `RBAC` grant management, backed by a dedicated audit log system.

### 💵 FinOps & Cost Optimization (`dbt Core`)
* **Cross-Entity Credit Allocation:** Automatically aggregates multi-warehouse metrics (`Ecom`, `Marketing`, `Finance`) to compute real execution-to-billing ratios and track idle capacity costs.
* **Warehouse Behavior Analyzer:** Minimizes compute waste by detecting idle gaps, excessive warehouse wakeups, and high-cost *isolated queries* (paying 60s of auto-suspend for a 2s execution).

### ⚡ Snowflake Performance Engineering (`dbt Core`)
* **Multi-Layer Cache Profiling:** Maps queries served by `Metadata/Result Cache` vs. `Local SSD` to isolate warehouse cold-starts and identify remote storage bottlenecks.
* **Query Spilling Tracker:** Automates detection of memory overflows by flagging queries with `>30%` local disk spill or `>1%` critical remote storage spilling.
* **Data Skew & Partitioning Monitor:** Catches heavy join bottlenecks by calculating execution speed per partition, highlighting critical distribution skewing (`>0.5s/partition` for `>5min`).
* **Automatic Clustering Cost Control:** Tracks monthly credit and GB consumption of Snowflake’s auto-reclustering feature to flag tables with high maintenance costs.

### 🔍 Data Observability & Quality
* **Metadata-Aware Freshness Engine:** A smart SLA tracker that accounts for Snowflake’s 3-hour data latency to correctly distinguish real data gaps from silent loading failures.

### 📊 Core Business Modeling (`dbt Core`)
* **User Cohort Retention Framework:** Analytics pipeline processing active vs. non-paying user lifecycles to extract retention insights.

---
**Tech stack:**

* Snowflake
* dbt
* SQL

👉 **Repository:** [Link](https://github.com/julianrocci/Snowflake-dbt-Core-Hub)

---

## 🤝 Let's connect

* 💼 Looking for Analytics Engineer / Data Engineer roles
* 🌍 Open to relocation in Switzerland🇨🇭
* 📫 Contact: [LinkedIn](https://www.linkedin.com/in/julianrocci/) / rocci.julian@gmail.com
