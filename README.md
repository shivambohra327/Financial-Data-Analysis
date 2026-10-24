# 💳 Credit Card Customer Analytics Dashboard | Power BI

**An interactive financial data analytics project using Power BI, DAX, and business intelligence techniques.**

## 📌 Project Overview

The **Credit Card Customer Analytics Dashboard** is a data analytics project developed using Microsoft Power BI to analyze credit card transactions, customer behavior, financial performance, and potential credit risk indicators.

The project transforms customer-level financial data into meaningful KPIs and interactive visualizations. It focuses on understanding transaction trends, identifying high-value customers, monitoring credit utilization, evaluating customer satisfaction, and analyzing delinquency and customer inactivity.

The objective is to support data-driven decision-making in banking and financial services through effective data visualization and analytical reporting.

## 🎯 Business Objectives

- Analyze credit card transaction patterns and customer spending behavior.
- Monitor transaction performance using key financial KPIs.
- Calculate Month-over-Month (MoM) and Week-over-Week (WoW) growth.
- Develop running totals and four-week moving averages using DAX.
- Evaluate customer acquisition cost relative to transaction amount.
- Identify high-value customers based on transaction activity.
- Monitor credit utilization, revolving balances, and delinquency indicators.
- Identify potentially inactive customers using a six-month inactivity rule.
- Compare customer satisfaction across card categories.
- Analyze average credit limits based on personal loan status.
- Develop rule-based indicators to support credit risk monitoring.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Interactive dashboards and data visualization
- **DAX (Data Analysis Expressions)** — Measures, calculated logic, KPIs, and time-based analysis
- **Data Modeling** — Relationships between customer, credit card, and calendar data
- **Business Intelligence** — KPI monitoring, trend analysis, and customer segmentation
- **Financial Analytics** — Transaction performance, credit utilization, and risk indicators

## 📊 Dataset Overview

The dataset described in the project contains customer-level credit card information and financial behavior.

Key fields include:

- Client Number
- Card Category
- Annual Income
- Credit Limit
- Total Transaction Amount
- Total Transaction Count
- Average Utilization Ratio
- Total Revolving Balance
- Interest Earned
- Delinquent Account Status
- Personal Loan Status
- Customer Satisfaction Score
- Week Start Date

These fields are used to analyze customer activity, credit usage, transaction trends, and financial risk indicators.

*Note: The original dataset and its source are not included in this repository unless added separately.*

## 📈 Key Analytical Components

### 1. Transaction Performance Analysis
- Total transaction amount
- Running total of credit card transactions
- Four-week moving average of credit limits

### 2. Time-Based Growth Analysis
- Month-over-Month transaction growth
- Week-over-Week transaction growth
- Trend and fluctuation analysis

### 3. Customer Acquisition Analysis
- Total customer acquisition cost
- Acquisition cost relative to transaction amount
- Customer transaction ranking

### 4. Credit Utilization Analysis
- Yearly average utilization ratio
- Identification of customers with utilization above 80%
- Analysis of revolving balances relative to credit limits

### 5. Customer Risk Analysis
- Delinquency rate
- Six-month inactivity indicator
- Rule-based credit risk score
- High-risk customer flag

### 6. Customer Satisfaction Analysis
- Average satisfaction score by card category
- Comparison of satisfaction across card products

### 7. Customer Financial Segmentation
- Income and credit limit correlation
- Average credit limit by personal loan status
- Identification of high-value customers

## 🔍 Key Insights from the Presentation

The following findings are reported in the project presentation:

- **Transaction Performance:** The displayed running-total example reaches 45,533,021 for the shown 2023 period.
- **Monthly Growth:** The presentation reports a Month-over-Month growth peak of 29% in July 2023, followed by a steep decline in August.
- **Weekly Growth:** Week-over-Week growth is described as mostly fluctuating between -10% and +15%, with a reported year-end spike of nearly 35% in Week 53.
- **Customer Satisfaction:** Silver cardholders have a reported average satisfaction score of 3.22, followed by Blue cardholders at 3.20. Platinum cardholders have a reported score of 2.72.
- **Credit Limit Comparison:** The reported average credit limit is 8,654.79 for customers without personal loans and 8,557.56 for customers with personal loans.
- **Risk Monitoring:** The analysis uses credit utilization, revolving balance, delinquency, and inactivity indicators to identify customers who may require further review.

*These values are transcribed from the presentation and should be validated against the underlying dataset and final Power BI report before being used for business decisions.*

## 💡 Business Value

This project demonstrates how financial data analytics can help organizations:

- Monitor transaction performance and identify unusual changes.
- Understand customer activity and transaction contribution.
- Identify customers who may need retention or re-engagement efforts.
- Monitor potential credit risk using defined analytical thresholds.
- Compare customer satisfaction across card categories.
- Support financial reporting and data-driven business discussions.

The risk indicators in this project are analytical screening measures and are not a substitute for an institution's approved credit risk policies.

## 📂 Project Structure

```text
credit-card-customer-analytics/
│
├── README.md
│
├── dashboard/
│   └── dashboard_screenshots.png
│
├── powerbi/
│   └── Credit_Card_Analytics.pbix
│
├── presentation/
│   └── Financial_Data_Analysis.pdf
│
└── docs/
    ├── DAX_Measures.md
    ├── Insights.md
    └── Data_Dictionary.md
```

*The file names above illustrate the recommended structure. Add the actual files before presenting them as available in the repository.*

## 🚀 How to Explore the Project

1. Review this README to understand the project objectives and analytical scope.
2. Open the presentation PDF to explore the project methodology and findings.
3. View the dashboard screenshots to understand the visual design and KPIs.
4. Open the Power BI report in Microsoft Power BI Desktop, if the `.pbix` file is available.
5. Review the DAX documentation to understand the calculations and analytical logic.

## 📚 Skills Demonstrated

- Data analysis and interpretation
- Power BI dashboard development
- DAX measures and calculations
- KPI creation and performance monitoring
- Time-series and growth analysis
- Customer segmentation
- Financial data visualization
- Analytical problem-solving
- Business insight communication

## ⚠️ Data Privacy & Limitations

This project is intended for analytical and educational portfolio purposes. Only datasets that are authorized for public distribution should be uploaded. Customer-identifiable or confidential financial information should not be published.

The reported findings reflect the accompanying presentation. DAX calculations, business thresholds, and numerical results should be validated against the actual data model before operational use.

## 👨‍💻 Author

**Shivam Bohra**

Aspiring Data Analyst | Power BI | SQL | Python | Data Visualization

