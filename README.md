# 💳 Banking Data Analytics Project

A complete end-to-end data analytics project using Power BI, PostgreSQL, and Python. This project explores risk analytics in the banking sector, helping identify clients likely to repay or default on loans.

## 🧩 Problem Statement

To minimize the risk of monetary loss in lending, this project uses client data to assess eligibility and risk profiles. Dashboards provide insights into deposits, loans, client engagement, and other financial metrics.

## 📊 Tools & Technologies Used

- **Power BI**: For creating interactive dashboards and KPI visualizations.
- **Python (Pandas, Matplotlib)**: For data exploration and cleaning.
- **PostgreSQL**: For data storage and SQL querying.
- **Git & GitHub**: For version control and project hosting.

## 🗃️ Dataset Overview

The dataset includes:
- `Banking`

Relationships are defined through primary and foreign keys. Data cleaning involved:
- Creating `Engagement Days` from joining dates.
- Binning `Estimated Income` into bands.
- Generating a `Processing Fee` column based on `Fee Structure`.

## 📈 KPIs Calculated

- **Total Clients**  
- **Total Loan** = Bank Loan + Business Lending + Credit Card Balance  
- **Total Deposit** = Bank Deposit + Savings + Checking + Foreign Currency  
- **Processing Fees**  
- **Engagement Length** (in days)  
- **Credit Cards Balance**  
- **Income Band Distribution**  

All calculations were implemented using DAX functions like `SUM`, `SUMX`, `DISTINCTCOUNT`, `SWITCH`, and `DATEDIFF`.

## 📌 Dashboards

### 📍 Home  
Snapshot of total clients, deposit, loan, and engagement metrics.
![Screenshot (26)](https://github.com/user-attachments/assets/cfe1afae-165a-48c2-8da5-d70a2240d28f)

### 📍 Loan Analysis  
Breakdown by gender, advisor, loan type.
![Screenshot (27)](https://github.com/user-attachments/assets/b5717ff4-b2da-4301-b156-e7646841c075)

### 📍 Deposit Analysis  
Insight into various deposit types across investor profiles.
![Screenshot (28)](https://github.com/user-attachments/assets/4385b1f9-8a68-4a47-aedb-16adf038f86e)

### 📍 Summary Dashboard  
All KPIs and filters integrated into a high-level dashboard.
![Screenshot (29)](https://github.com/user-attachments/assets/dd3bedb1-09e9-4f08-9df5-d80d2627ec9e)


## 🔍 EDA and SQL Integration

Python EDA includes:
- Missing value analysis
- Client engagement trend over time
- Loan vs deposit heatmaps


## 🔚 Conclusion

Power BI enables banks to:
- Monitor high-risk clients
- Evaluate client engagement by nationality, advisor, or bank type
- Strategize client acquisition and retention

## 🔮 Future Scope

- Add time-series forecasting for loan defaults
- Integrate ML for risk prediction
- Real-time Power BI refresh via API or stream data

---

## 📂 Project Setup Instructions

1. Clone this repo  
   `git clone https://github.com/yourusername/banking-data-analytics.git`

2. Install Python dependencies  
   `pip install -r requirements.txt`

3. Open `.pbix` file in Power BI Desktop  
   
---

## 📧 Contact

Created by **Vedant Jaiswal**  
[GitHub](https://github.com/Vedantjaiswal4352)
