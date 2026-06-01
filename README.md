# BAT Retail Distribution & Sales Analytics Dashboard

## 📊 Project Overview
An enterprise-grade commercial analytics dashboard built in Power BI to evaluate value-chain performance, distribution efficiencies, and portfolio revenue mix for British American Tobacco (BAT). This project translates a massive weekly dataset across 7 distinct distribution routes into automated financial metrics.

## 🚀 Core Workflow & Methodology
* **Data Transformation (ETL):** Standardized, cleaned, and validated relational keys across thousands of transaction logs spanning May 02 to May 09 using Power Query.
* **Data Modeling:** Established a highly optimized Star Schema architecture with robust one-to-many ($1 \rightarrow *$) active relationship bridges.
* **Advanced DAX Analytics Engine:** Formulated high-performance calculations utilizing iterators (`SUMX`), relational traversal (`RELATED`), conditional safeguards (`DIVIDE`), and subset filtering (`TOPN`).

## 📈 Key Metrics & Achievements
* **Scale of Operations:** Analyzed a **৳365M+ gross revenue** pipeline and **2M+ product volume** across 7 operational routes.
* **Financial Performance:** Monitored critical KPIs including Net Sales, Profit Variance, DoD growth trends, and an average **10.89% retailer profit margin**.
* **Route Efficiency:** Isolated Route 802A as the operational leader, generating nearly **৳93M** in peak volume.
* **Temporal Patterns:** Identified a massive single-day transactional velocity spike of **৳67M on May 03**.
* **Portfolio Concentration:** Discovered that two flagship brands (**HW at ৳199M** and **RL at ৳72M**) command **74% of total revenue**, with a single major brand segment dominating **54.6%** of the entire business line.
