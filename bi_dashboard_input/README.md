\# SaaSify: End-to-End Subscription Analytics \& Engineering Pipeline



An enterprise-ready data engineering and business intelligence pipeline that transforms raw subscription transaction logs into executive-level performance metrics.



\## 🏗️ Data Architecture (Star Schema)

To optimize query performance, the backend database was architected using a traditional Star Schema relational model:

\* \*\*Fact Tables:\*\* `fact\_transactions`, `fact\_engagement` (High-frequency event logs)

\* \*\*Dimension Tables:\*\* `dim\_users`, `dim\_plans` (Contextual attributes)



\## 🛠️ Tech Stack \& Skills

\* \*\*Language:\*\* Python 3.x

\* \*\*Database \& ETL:\*\* SQL (SQLite), SQLAlchemy, Pandas

\* \*\*Advanced SQL Concepts:\*\* Window Functions (`LAG`), Common Table Expressions (CTEs), Joins, Aggregations

\* \*\*Business Intelligence:\*\* Power BI Desktop (Data Modeling \& Relational Mapping)



\## 📈 Core Business Insights Discovered

1\.  \*\*Revenue Growth:\*\* Built a localized database pipeline to track rolling Monthly Recurring Revenue (MRR) and Month-over-Month (MoM) growth velocity directly inside the database layer using `LAG()`.

2\.  \*\*The Paid Ads Bottleneck:\*\* Uncovered a massive operational flaw where customers converted via \*\*Paid Ads on Premium Plans\*\* opened an exceptionally high volume of customer support tickets and experienced a rapid churn spike by month 3.



\## 📊 Dashboard Preview



