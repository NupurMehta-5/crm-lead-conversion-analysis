# 📊 CRM Lead Conversion Analysis

## 📌 Project Overview

This project analyzes CRM lead data to evaluate sales conversion performance across different sources, industries, and regions.

The objective is to understand key drivers behind successful conversions and revenue generation using SQL for KPI analysis and Python for exploratory data visualization.

---

## 🗂 Dataset Description

The dataset contains 250 CRM leads with the following attributes:

- LeadID  
- Source (LinkedIn, Email Campaign, Cold Call, Referral, Website)  
- Industry (IT, Healthcare, Retail, Finance, Manufacturing)  
- Region (UK, India, USA)  
- LeadScore  
- ResponseTimeHours  
- Converted (1 = Converted, 0 = Not Converted)  
- DealValue  

---

## 🛠 Tools Used

- **Microsoft SQL Server** – Core KPI and conversion analysis  
- **Python (Pandas, Matplotlib)** – Exploratory Data Analysis & Visualization  
- **Excel** – Dataset preparation  
- **GitHub** – Project hosting and documentation  

---

## 📊 SQL Analysis Performed

The following key business questions were answered using SQL:

1. Total number of leads  
2. Total converted leads  
3. Overall conversion rate (%)  
4. Conversion rate by source  
5. Average lead score (Converted vs Not Converted)  
6. Average response time comparison  
7. Total revenue generated from converted leads  

SQL techniques demonstrated:

- COUNT()
- SUM()
- GROUP BY
- ORDER BY
- CAST()
- Aggregation-based KPI calculations
- Data type handling (BIT to INT casting)

---

## 📈 Key Business Insights

- Higher lead scores are associated with higher conversion probability.
- Faster response times significantly improve conversion outcomes.
- Referral and LinkedIn channels show stronger performance compared to cold outreach.
- Revenue concentration varies by industry.

---

## 📊 Python Exploratory Data Analysis (EDA)

Python was used to:

- Check for missing values and duplicates
- Analyze distribution of lead scores
- Visualize conversion rate by source
- Compare response time between converted and non-converted leads
- Explore revenue distribution

This complements the SQL findings by adding visual interpretation.

---

## 📂 Project Structure

```
crm-lead-conversion-analysis/
│
├── data/
│   └── crm_leads.csv
│
├── sql/
│   └── crm_analysis.sql
│
└── python/
    └── crm_eda.ipynb
```

---

## 🚀 Future Improvements

- Predictive lead scoring model
- Conversion probability modeling using Python
- Dashboard visualization (Power BI)
- Response time optimization insights

---

## 👩‍💻 Author

Nupur Mehta  
Aspiring Data Analyst | SQL | Python | EDA  
Ahmedabad, India
