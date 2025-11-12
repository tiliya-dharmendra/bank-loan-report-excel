# 🏦 Bank Loan Performance Dashboard  Data Analysis Project

An interactive Excel dashboard that visualizes key insights from loan application data — helping financial teams monitor performance, identify risk patterns, and make data-driven lending decisions.

## 📚 Table of Contents
- [📊 Project Overview](#-project-overview)
- [📈 Dashboard Structure](#-dashboard-structure)
- [🧠 Key Insights](#-key-insights)
- [⚙️ Tools & Techniques](#️-tools--techniques)
- [🧩 Data Preparation Steps](#-data-preparation-steps)
- [📷 Dashboard Preview](#-dashboard-preview)
- [📝 Project Structure](#-project-folder-structure)
- [🚀 How to Use](#-how-to-use-this-project)
- [🏁 Outcomes](#-project-outcomes)
- [⭐ Future Improvements](#-future-improvements)
- [💬 Author](#-author--contact)


## 📊 Project Overview

This project analyzes bank loan data to evaluate funding performance, repayment trends, and risk exposure across different borrower and loan attributes. The dashboard is built entirely in Microsoft Excel, using Power Query, PivotTables, and data visualization techniques to summarize insights.



### 🔹 Key Objectives

- Track loan application and funding trends

- Monitor good vs. bad loan ratios

- Analyze portfolio performance by state, purpose, term, employment length, and home ownership

- Support decision-making for credit and product teams


## 🧾 Dashboard Structure

### 1. Summary Sheet

High-level KPIs providing a quick snapshot of portfolio performance:

- Total Loan Applications  

- Total Funded Amount  

- Total Amount Received  

- Average Interest Rate  

- Average Debt-to-Income (DTI)  

- Good vs. Bad Loan Analysis  

 - % of Applications  

 - Funded Amount  

 - Total Received Amount



### 2. Overview Sheet

Detailed visual analysis:

- 📅 Monthly Trend (Applications, Funded, Received)

- 🌎 Regional Analysis (by State)

- 🕒 Loan Term Analysis

- 👔 Employment Length Analysis

- 🎯 Loan Purpose Breakdown

- 🏠 Home Ownership Analysis


## 🧠 Key Insights

- Identified states with higher proportions of bad loans  

- Longer loan terms correlated with higher risk exposure  

- Borrowers with shorter employment history showed higher DTI  

- Monthly trends revealed seasonal variations in applications and funding  


## ⚙️ Tools & Techniques

 #### • Tool -Microsoft Excel 

 #### • Techniques Used -Power Query, PivotTables, Conditional Formatting, Slicers 

 #### • Data Preparation -Data cleaning, standardization, and transformation 

 #### • Visualization -Dynamic charts and KPI cards 

 #### • Skills Demonstrated -Data Analysis, Reporting, Business Insights, Excel Automation 



## 🧩 Data Preparation Steps


1. Imported raw loan data using Power Query  

2. Cleaned data — handled missing values, standardized state codes, and converted dates  

3. Created calculated columns:

  - Loan Term (in months)

  - Good/Bad Loan Flag  

  - Month-Year for trend analysis

4. Built KPIs using `SUMIFS`, `AVERAGEIFS`, and `COUNTIFS` functions  

5. Designed interactive visuals using Pivot Charts and Slicers  


## 📈 KPIs and Metrics Formulas


 Total Applications - `=COUNTA([Loan_ID])` 

 Funded Amount - `=SUMIFS([LoanAmount], [Status], "Funded")`

 Amount Received - `=SUM([TotalPayment])` 

 Average Interest Rate - `=AVERAGE([IntRate])` 

 Average DTI - `=AVERAGE([DTI])` 

 Good Loan %  - `=COUNTIFS([LoanType],"Good") / COUNTA([Loan_ID])` 


## 📷 Dashboard Preview


![Summary Dashboard](https://github.com/tiliya-dharmendra/bank-loan-report-excel/blob/52954b41a647cb4808685da685efc1c3184bae84/Bank%20Loan%20Report%20Summary.png)


## 📁 Project Folder Structure


```bash

Bank-Loan-Report-Excel/


├── Bank Loan Report Summary.png         # Dashboard images

├── Bank Loan Report Summary.png         # Dashboard images

├── Dashboard.xlsx                       # Final Excel Dashboard

├── Data.xlsx                            # Raw and cleaned datasets

└── README.md                            # Project documentation
```


## 🚀 How to Use This Project

1. <b>Download</b> the Excel file: Dashboard.xlsx

2. Open the workbook and enable content (if prompted)

3. Explore using slicers for date range, state, loan term, or purpose

4. Refresh data using Data → Refresh All if you connect new datasets


## 🏁 Project Outcomes

• Delivered a fully automated, interactive Excel dashboard

• Simplified loan performance tracking for stakeholders

• Highlighted risk trends and data-driven opportunities

• Demonstrated end-to-end analytical workflow using Excel


## ⭐ Future Improvements

• Add automated Power BI version

• Integrate predictive modeling for loan default risk

• Enable auto-refresh with external database connections


## 💬 Author & Contact 

Dharmendra sahu
Data Analyst
📧 [dharmendrasahut2021@gmail.com](mailto:dharmendrasahut2021@gmail.com)

🔗 [LinkedIn Profile](https://www.linkedin.com/in/dharmendra-sahu21)

💻 [GitHub Profile](https://github.com/tiliya-dharmendra)


## 🏷️ Tags


#Excel #DataAnalysis #Dashboard #PowerQuery #LoanAnalytics #FinancialAnalysis

