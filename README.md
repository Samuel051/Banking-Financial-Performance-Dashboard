# 💳 Digital Banking Performance Dashboard

An end-to-end **Business Intelligence (BI)** solution built entirely in **Microsoft Excel** using **Power Query**, **Power Pivot**, **DAX**, **Pivot Tables**, **Pivot Charts**, and **VBA**. The project analyses digital banking transactions across East Africa and delivers interactive dashboards that support executive decision-making through data-driven insights.

---

# 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Business Objective](#-business-objective)
- [Dataset Overview](#-dataset-overview)
- [Project Statistics](#-project-statistics)
- [Technology Stack](#-technology-stack)
- [Project Workflow](#-project-workflow)
- [Dashboard Overview](#-dashboard-overview)
- [Key Business Insights](#-key-business-insights)
- [Business Recommendations](#-business-recommendations)
- [Challenges Encountered](#-challenges-encountered)
- [Future Improvements](#-future-improvements)
- [Conclusion](#-conclusion)

---

# 📌 Project Overview

Digital banking continues to transform the financial services industry by offering customers multiple channels through which they can access banking services. Understanding customer behaviour, transaction trends and channel performance is essential for improving customer experience and supporting strategic business decisions.

This project demonstrates how Microsoft Excel can be used as a complete Business Intelligence platform by combining Power Query, Power Pivot, DAX and VBA to create an interactive executive dashboard.

The solution enables stakeholders to monitor:

- Overall business performance
- Country performance
- Regional performance
- Banking channel adoption
- Transaction type performance
- Monthly performance trends

---

# 🎯 Business Objective

The primary objective of this project was to build an executive reporting solution capable of:

- Monitoring banking transaction performance.
- Comparing country performance.
- Evaluating regional performance.
- Measuring banking channel adoption.
- Understanding customer transaction behaviour.
- Tracking monthly performance trends.
- Supporting interactive decision-making using dashboard filters and slicers.

---

# 📂 Dataset Overview

### Reporting Period

**January 2025 – June 2025**

### Countries Included

- Kenya
- Tanzania
- Rwanda
- DR Congo
- Uganda

### Kenyan Regions

- Nairobi
- Mombasa
- Nakuru
- Eldoret
- Kisumu

---

# 📊 Project Statistics

| Metric | Value |
|---------|-------:|
| Total Transaction Value | **KES 101,690.73 Million** |
| Total Transactions | **607,415** |
| Number of Records | **707** |
| Average Transaction Value | **KES 167.42K** |

---

# 🛠 Technology Stack

- Microsoft Excel
- Power Query
- Power Pivot
- DAX
- VBA
- Pivot Tables
- Pivot Charts

---

# 🔄 Project Workflow

## 1. Data Preparation

The raw dataset was imported into Power Query where data validation and cleaning were performed before loading the data into the Excel Data Model.

---

## 2. Data Modelling

Power Pivot was used to create relationships between:

- Transactions
- Countries
- Regions
- Channels
- Transaction Types
- Date Table

The star schema allowed efficient filtering and reporting.

---

## 3. DAX Measures

Several DAX measures were developed including:

- Total Transaction Value
- Total Transactions
- Average Transaction Value
- Market Share
- Previous Month Value
- Month-over-Month Growth
- Highest Performing Month
- Highest Monthly Value

---

## 4. Dashboard Development

Interactive dashboards were created using Pivot Tables, Pivot Charts and Slicers.

Navigation between dashboards was automated using VBA.

---

# 📈 Dashboard Overview

## Executive Overview

Provides a high-level summary of:

- KPI Cards
- Monthly Trends
- Country Performance
- Channel Performance
- Transaction Summary

---

## Country Performance

Analyses:

- Revenue by Country
- Transaction Volume
- Market Share
- Average Transaction Value
- Country Rankings

---

## Regional Performance

Focuses on Kenyan regional performance through:

- Regional Revenue
- Transaction Volume
- Market Share
- Average Transaction Value

---

## Channel Performance

Evaluates the performance of:

- Internet Banking
- Mobile Banking
- Agent Banking
- Branch Banking
- ATM

---

## Transaction Analysis

Compares:

- Deposits
- Bill Payments
- Loan Repayments
- Fund Transfers
- Loan Disbursements
- Forex Transactions

---

## Time Intelligence

Tracks business performance through:

- Monthly Trends
- Previous Month Comparison
- Month-over-Month Growth
- Seasonal Patterns

---

# 📊 Key Business Insights

## Country Performance

- Kenya generated the highest transaction value and transaction volume.
- Tanzania ranked second, followed by Rwanda.
- DR Congo and Uganda performed below the overall average.
- Average transaction value remained relatively consistent across countries, suggesting that differences in revenue are primarily driven by transaction volume rather than transaction size.

---

## Regional Performance

- Mombasa recorded the largest regional market share.
- Nakuru ranked second.
- Eldoret, Nairobi and Kisumu followed.
- Kisumu recorded the lowest transaction volume but the highest average transaction value, indicating fewer but higher-value transactions.
- Additional regional data from the remaining countries would provide richer geographical insights.

---

## Channel Performance

Internet Banking generated the highest transaction value and market share (**KES 24,773.90 Million**), followed by:

1. Agent Banking
2. Branch Banking
3. Mobile Banking
4. ATM

A notable observation was that the gap between Internet Banking and the second-ranked channel was significantly larger than the gap separating the remaining channels. The same trend was observed in transaction volume, suggesting a stronger customer preference and trust in Internet Banking.

Interestingly, Internet Banking led monthly transaction value in every month except **April**, where Mobile Banking slightly outperformed it.

Average transaction value showed a different pattern:

1. Mobile Banking
2. Branch Banking
3. Agent Banking
4. Internet Banking
5. ATM

Although Internet Banking generated the largest overall revenue, Mobile Banking users tended to perform slightly larger transactions on average.

---

## Transaction Analysis

Deposits generated the highest transaction value (**KES 19,120.56 Million**) followed by:

- Bill Payments
- Loan Repayments
- Fund Transfers
- Loan Disbursements
- Forex Transactions

Transaction volume closely mirrored transaction value, demonstrating a strong relationship between transaction popularity and revenue generation.

---

## Time Intelligence

January recorded the highest transaction value and transaction volume, reflecting increased business activity following the holiday season.

February experienced the sharpest decline before the business recovered in March and stabilised through April, May and June.

### Months with Negative Month-over-Month Growth

| Month | Growth |
|--------|--------:|
| February | **-19%** |
| May | **-1%** |
| June | **-1%** |

Despite these declines, overall business performance remained relatively stable after February.

---

# 💡 Business Recommendations

- Increase marketing efforts in Uganda to improve customer acquisition.
- Improve brand awareness campaigns in Nairobi and Kisumu.
- Investigate the relationship between tourism and transaction performance in Mombasa and Nakuru.
- Promote customer confidence in Agent Banking, Branch Banking, Mobile Banking and ATM services to reduce overreliance on Internet Banking.
- Expand regional data collection for all countries to support deeper geographical analysis.
- Continue monitoring monthly performance trends to identify early signs of business change.

---

# ⚠ Challenges Encountered

Although the dataset was synthetically generated using Claude AI, several real-world data quality issues were identified during development.

These included:

- Inconsistent region mappings.
- Duplicate transaction tables.
- Power Pivot modelling issues.
- Relationship inconsistencies.
- Data validation challenges.

Each issue was investigated, diagnosed and resolved before the final dashboard was completed.

This experience highlighted the importance of validating synthetic datasets before beginning analysis and reinforced practical skills in troubleshooting Power Query, Power Pivot and DAX models.

---

# 🚀 Future Improvements

Future enhancements could include:

- SQL Server integration.
- Automated data refresh.
- Power BI implementation.
- Python-powered predictive analytics.
- Forecasting transaction volumes using Machine Learning.
- Expanded regional data for all countries.

---



# 🎯 Conclusion

This project demonstrates a complete Business Intelligence workflow using Microsoft Excel. From data preparation and modelling to interactive dashboard development and business storytelling, the project showcases practical skills in Power Query, Power Pivot, DAX, VBA and executive reporting.

Beyond technical implementation, the project emphasises the importance of data validation, analytical thinking and translating data into actionable business recommendations. It reflects real-world BI development by combining technical expertise with business insight to support informed decision-making.
