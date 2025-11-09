# 🏦 Bank Loan Risk Analysis Dashboard (Power BI)

## 📊 Project Overview
This Power BI dashboard analyzes **loan approval trends, default risks, and customer profiles** for a financial institution.  
The goal is to help stakeholders identify **key factors influencing loan approvals** and **understand default risks** based on applicant data such as income, credit history, and property area.

---

## 🎯 Objectives
- Analyze loan approval vs. rejection patterns  
- Identify customer segments with higher default probability  
- Visualize relationships between income, loan amount, and credit history  
- Provide actionable insights to minimize lending risk  

---

## 🧩 Tools & Technologies Used
- **Power BI Desktop**
- **Power Query** for data cleaning & transformation  
- **DAX (Data Analysis Expressions)** for calculated measures and KPIs  
- **Excel / CSV dataset** as data source  
- **Data Modeling** for establishing relationships between tables  

---

## 🧠 Key Insights
- Applicants with **credit history = 1** are significantly more likely to get loan approval.  
- **Urban property areas** show higher approval rates and larger loan amounts.  
- Applicants with **total income below ₹10,000** have a higher rejection probability.  
- A **Loan-to-Income ratio above 7** increases the chance of default.  

---

## 📈 Dashboard Features
- Interactive filters for **Gender, Education, Property Area, and Loan Status**  
- KPI cards for quick metrics: *Approval Rate*, *Average Loan Amount*, *Default Rate*  
- Comparative visuals for *Approved vs. Rejected* applicants  
- Dynamic charts showing *Default Rate by Property Area* and *Income vs Loan Amount*

---

## 🧮 DAX Measures Used
- `Total Loan Amount = SUM(LoanAmount)`
- `Approval Rate = DIVIDE(COUNTROWS(ApprovedLoans), COUNTROWS(AllLoans))`
- `Loan to Income Ratio = DIVIDE(LoanAmount, TotalIncome)`
- `Default Rate = DIVIDE(DefaultedLoans, TotalLoans)`

---

## 🧰 How to Use
1. Download the `.pbix` file or open it directly in **Power BI Desktop**.  
2. Connect to the included dataset (if needed).  
3. Explore the dashboard using available slicers and filters.  

---
