# 📊 Marketing Campaign Effectiveness Analysis  
### EDA Using Power BI

---

## 📌 Project Overview

This project focuses on analyzing the **effectiveness of marketing campaigns** using **Power BI**.  
The objective is to help management understand whether increasing marketing spend is delivering a good **Return on Investment (ROI)** and to identify opportunities for better budget allocation.

Campaigns were run across multiple channels including:
- Email
- Social Media
- TV
- Search Ads

---

## 🎯 Business Problem

Despite increasing marketing expenditure, leadership lacks clarity on:
- Which channels generate the highest revenue
- Which campaigns are underperforming
- How efficiently marketing budgets are utilized

This analysis provides **data-driven insights** to support smarter marketing decisions.

---

## ❓ Key Questions Answered

- Are there any missing or inconsistent values in the marketing data?
- Which marketing channels generate the highest revenue?
- What is the ROI of each campaign?
- How do conversion rates vary across channels?
- How is campaign spend distributed?
- Which campaigns are underperforming?
- Which channels deserve increased investment?
- How can insights improve future marketing strategy?

---

## 🧹 Data Quality Check

- ✔️ No missing values found  
- ✔️ No inconsistent or erroneous data detected  
- ✔️ Dataset is clean and ready for analysis  

---

## 💰 Revenue Insights

- **Search Ads** generate the **highest overall revenue** among all channels.

---

## 📈 ROI Calculation (DAX)

ROI was calculated using a custom **DAX measure** in Power BI:

```DAX
ROI = DIVIDE([Total Revenue] - [Total Spend], [Total Spend])
