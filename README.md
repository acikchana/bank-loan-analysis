# Bank Loan Analysis | Python Data Analysis Project

## Project Overview
This project analyzes **bank loan performance and customer behavior** using Python to support **risk assessment, loan monitoring, and data-driven financial decision making**.  
The analysis focuses on loan applications, funded amounts, repayments, interest rates, and borrower characteristics.

---

## Business Objectives
- Monitor overall loan application and funding performance
- Analyze month-to-date (MTD) loan metrics
- Evaluate **Good vs Bad loan** performance
- Identify trends in loan funding and repayment over time
- Understand borrower behavior by region, purpose, employment length, and home ownership

---

## Dataset Information
- **File**: `financial_loan.xlsx`
- **Data Type**: Financial loan transaction data
- **Records**: Loan-level data
- **Time Field**: Issue date

### Key Columns
- Loan ID  
- Issue Date  
- Loan Amount  
- Total Payment  
- Interest Rate  
- Debt-to-Income Ratio (DTI)  
- Loan Status  
- Term  
- Employment Length  
- Loan Purpose  
- Home Ownership  
- State  

---

## Tools & Technologies
- **Python**
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

---

## Key Metrics & KPIs
- Total Loan Applications
- Month-to-Date (MTD) Loan Applications
- Total Funded Amount
- MTD Funded Amount
- Total Amount Received
- MTD Amount Received
- Average Interest Rate
- Average Debt-to-Income (DTI)
- Good Loan vs Bad Loan Ratio

---

## Analysis Performed
- Data loading and validation
- Exploratory Data Analysis (EDA)
- Loan performance metrics calculation
- Good vs Bad loan classification
- Trend analysis by issue date
- Geographic analysis by state
- Borrower profile analysis (employment length, home ownership)
- Loan purpose and term analysis

---

## Key Insights
- The majority of loans are classified as **Good Loans** (Fully Paid or Current), indicating healthy portfolio performance.
- **Month-to-date loan applications and funded amounts** provide clear visibility into recent lending activity.
- Loan funding and repayments show consistent **monthly trends**, supporting predictable cash flow.
- Certain states contribute disproportionately to total funded amounts.
- Borrowers with longer employment length tend to receive higher loan funding.
- Most loan funding is concentrated in **36-month terms**.
- Loan purposes such as debt consolidation and credit card refinancing dominate funded amounts.

---

## Visualizations
The project includes the following visual analyses:
- Monthly trend of total funded amount
- Monthly trend of total amount received
- Monthly loan application count
- Total funded amount by state
- Funded amount by loan purpose
- Funded amount by loan term
- Funded amount by employment length
- Funded amount by home ownership

Sample visualizations are available in the `images/` folder.

---

## Repository Structure

<pre>
bank-loan-analysis/
├── data/
│   └── financial_loan.xlsx
├── notebooks/
│   └── Bank Loan.ipynb
├── images/
│   └── Total Funded Amount by Month.png
│   └── Total Received Amount by Month.png
│   └── Total Loan Applications by Month.png
│   └── Total Funded Amount by State.png
│   └── Total Funded Amount by Term.png
│   └── Total Funded Amount by Employment Length.png
│   └── Total Funded Amount by Loan Purpose.png
│   └── Total Funded Amount by Home Ownership (MORTGAGE).png
│   └── Total Funded Amount by Home Ownership (RENT).png
│   └── Total Funded Amount by Home Ownership (OWN).png
├── requirements.txt
└── README.md
</pre>


---

## Business Value
- Supports financial institutions in **loan portfolio monitoring**
- Helps identify **risk exposure** through bad loan analysis
- Provides actionable insights for **credit policy and lending strategy**
- Demonstrates analytical and visualization skills relevant to **Data Analyst and Financial Analyst roles**

---
