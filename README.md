
# Hi, I'm Manoj Mali 👋 💳 📊

**Fintech Data Analyst | Financial Analytics, ETL Pipelines & Business Dashboards**  
Transforming high-volume transactional logs into decision-ready business intelligence and risk telemetry. Experienced in engineering reliable end-to-end data pipelines—extracting raw multi-source telemetry, running rigorous data cleaning and validation, building relational stores in MySQL, writing complex analytical SQL (CTEs, Window Functions), and designing interactive Power BI dashboards with Star Schema modeling.

### 💼 Technical Toolkit & Competencies

- **Data E & ETL Pipelines:**  
  ![ETL](https://img.shields.io/badge/Pipeline-ETL-005C8A?style=for-the-badge)
  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
  ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)  
  *Telemetry Ingestion, Automated Extraction, Time-Bucketing, Pipeline Automation*

- **Data Cleaning & Data Wrangling:**  
  *Null & Missing Value Imputation, Outlier Handling, Schema Validation, Currency Normalization, Datetime Parsing, Duplicate Deduplication*

- **Databases & Analytical Querying:**  
  ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
  ![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)  
  *Common Table Expressions (CTEs), Window Functions, Rolling Aggregations, Partition By, Schema Normalization*

- **Business Intelligence & Dashboards:**  
  ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
  ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)  
  *Star Schema (1 Fact + 5 Dimensions), 11 Core DAX Measures, Multi-Page Interactive Dashboards, Trend Telemetry*

- **Spreadsheet Modeling:**  
  ![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)  
  *Pivot Tables, Advanced Lookups (XLOOKUP / VLOOKUP), Nested Conditionals (SUMIFS / COUNTIFS)*


### ⚙️ End-to-End ETL & Analytics Pipeline


```

┌───────────────────────────────┐
│       1. EXTRACT (E)          │  Raw Multi-Source Payment Gateway Logs & Telemetry (CSV)
└───────────────┬───────────────┘
▼
┌───────────────────────────────┐
│     2. DATA CLEANING &        │  • Handling null error codes & schema mismatches
│       TRANSFORM (T)           │  • Timestamp parsing, peak-window flagging & outlier capping
│       (Python / Pandas)       │  • Currency standardizations & categorical normalization
└───────────────┬───────────────┘
▼
┌───────────────────────────────┐
│        3. LOAD (L)            │  Staging & normalized tables loaded into Relational MySQL
│          (MySQL)              │  Executing 24 Analytical Queries (CTEs, Window Functions)
└───────────────┬───────────────┘
▼
┌───────────────────────────────┐
│     4. DATA MODELING &        │  Optimized Star Schema (1 Fact + 5 Dimensions)
│        BUSINESS BI            │  11 Production DAX KPIs & Root-Cause Diagnostics
│      (Power BI / Excel)       │  Executive Dashboards for Platform SLA & Recovery
└───────────────────────────────┘

```


### 🚀 Flagship Project

### 💳 [Digital Payment Transaction Health Analytics](https://github.com/ManojMaliDev/Digital-Payment-Transaction-Health-Analytics)
*An end-to-end data pipeline, cleaning, and analytics audit covering **50,000 payment gateway transactions worth ₹75.53M (~₹7.55 Cr)** to diagnose failure points, switch latency spikes, and revenue exposure.*

- **Quantitative Business Impact:**
  - Audited **₹75.53M TPV** across cards and UPI rails; diagnosed **₹11.43M in failed capital exposure**.
  - Isolated an **HDFC UPI peak-hour bottleneck (20:00–22:59)** where P99 latency jumped to **5,307 ms**, driving 470 timeouts (0 during off-peak).
  - Segregated an **SBI Card ~38% failure profile**, proving >75% of drops were customer balance constraints rather than gateway switch faults.
  - Formulated routing SLAs to save vulnerable conversions via dynamic failover switches.

- **ETL, Data Cleaning &  Highlights:**
  - **ETL Ingestion:** Built an automated ingestion pipeline extracting 50,000 unstructured transaction records.
  - **Data Cleaning & Wrangling:** Imputed missing error codes, standardized transaction statuses, resolved inconsistent date-time stamps, and capped network latency anomalies using **Python (Pandas & NumPy)**.
  - **Relational Storage:** Architected clean schemas and loaded processed records into **MySQL** without data loss.
  - **Analytical SQL:** Authored **24 advanced queries** using CTEs, ranking partitions, and rolling time-window calculations.
  - **Semantic Modeling & Dashboards:** Built a **Star Schema (1 Fact + 5 Dimensions)** with **11 core DAX KPIs** powering a 3-page interactive Power BI dashboard.


### 📬 Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Manoj_Mali-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manoj-mali-367131319)
[![Gmail](https://img.shields.io/badge/Email-manojmali3939@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manojmali3939@gmail.com)


