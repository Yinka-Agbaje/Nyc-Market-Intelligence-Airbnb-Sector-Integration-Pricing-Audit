# Nyc-Market-Intelligence-Airbnb-Sector-Integration-Pricing-Audit
![Status: Production-Grade](https://img.shields.io/badge/Status-Production--Grade-brightgreen?style=for-the-badge)
![Category: Data Integration / ETL](https://img.shields.io/badge/Category-Data_Integration_/_ETL-blue?style=for-the-badge)
![Tech: Multi--Format_Processing](https://img.shields.io/badge/Tech-Multi--Format_Processing-orange?style=for-the-badge)

---

**An end-to-end Data Engineering and Market Intelligence solution that integrates multi-format datasets (Excel, TSV, CSV) to provide a unified view of the NYC short-term rental landscape.**


## 🎯 Business Impact
Data silos are the enemy of business growth. In this project, I acted as a **Data Architect** for a real estate investment firm to:
* **Bridge Data Silos:** Seamlessly merge disparate data streams from Finance (Excel), Operations (TSV), and Public Records (CSV).
* **Price Benchmarking:** Establish an "Average Market Rate" to identify high-yield investment neighborhoods.
* **Sector Growth Tracking:** Utilize time-series review data to determine market maturity and demand peaks.

## 🛠️ The Technical Stack (Production Focus)
* **Advanced Data Merging:** Utilizing primary key mapping (`listing_id`) across 3+ data formats.
* **Data Sanitization:** High-precision string manipulation for currency conversion and case-standardization.
* **Temporal Normalization:** Converting non-standard review strings into production-ready `datetime` objects.
* **Vectorized Logic:** Performing high-speed calculations without inefficient loops.

## 📂 Project Architecture
* `/data`: Multi-format source files (Raw Data).
* `/notebooks`: Full ETL logic and exploratory audit.
* `/outputs`: Final consolidated market report.
* `requirements.txt`: Full dependency tracking for replication.

## 📈 Executive Summary of Findings

### 1. Unified Market Overview
Through rigorous cleaning and data casting, the raw "dollars" string data was converted to a float-basis, revealing a **Mean Market Price of $141.78**. This serves as a baseline for identifying "Under-Market" investment opportunities.

### 2. Private Room Dominance
The audit identified **11,356 private room listings**, indicating a high-density, high-turnover market segment that differs significantly from "Entire Home" investment strategies.

### 3. Review Recency
The temporal audit spans from **2011 to 2019**, providing a decade-long window into consumer behavior and listing longevity in NYC.

## 🏛️ Recommendations
* **Automated Ingestion:** This logic should be moved to a Python script to automate weekly market updates.
* **Dynamic Pricing Model:** Future iterations should include a regression model to predict prices based on the `nbhood_full` feature engineered during this audit.

---

## 👩‍💻 Author & Lead Analyst
**Olayinka Agbaje** | Data Scientist
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](www.linkedin.com/in/olayinka-agbaje-188102224) 
[![Email](https://img.shields.io/badge/Email-Contact-red?style=flat&logo=gmail)](mailto:olayinkaagbaje01@gmail.com)
