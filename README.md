# 📊 Digital Marketing Campaign Performance Analysis

## 📌 Project Overview

This project analyzes the performance of digital marketing campaigns across multiple advertising channels using Python for data preparation and Tableau for interactive visualization.

The objective is to evaluate campaign effectiveness, compare marketing channels, identify high-performing regions and customer segments, and provide business recommendations that support data-driven marketing decisions.

---

# 🎯 Objectives

- Analyze overall marketing performance.
- Compare advertising channels.
- Evaluate campaign profitability.
- Measure customer engagement.
- Identify high-performing regions.
- Analyze customer segments.
- Discover top-performing campaigns.
- Support marketing decision-making through interactive dashboards.

---

# 📂 Dataset

The dataset contains digital marketing campaign information including:

- Campaign ID
- Marketing Channel
- Region
- Customer Segment
- Date
- Revenue
- Spend
- Clicks
- Impressions
- Conversions

---

# 🧹 Data Cleaning (Python)

The dataset was cleaned using **Python (Pandas)**.

Cleaning steps included:

- Removing duplicate records
- Handling missing values
- Correcting data types
- Formatting date columns
- Removing inconsistent values
- Checking for invalid data
- Exporting the cleaned dataset

---

# 🧮 Feature Engineering

The following calculated metrics were created:

| Metric | Formula |
|---------|---------|
| Profit | Revenue − Spend |
| ROI | (Revenue − Spend) / Spend |
| CPC | Spend / Clicks |
| CVR | Conversions / Clicks |
| RPC | Revenue / Clicks |

These metrics were used throughout the dashboard to evaluate campaign performance.

---

# 📊 Dashboard Overview

The Tableau dashboard consists of **5 interactive pages**.

---

## 1️⃣ Executive Summary

Provides a high-level overview of campaign performance.

### KPIs

- Total Revenue
- Total Profit
- Total Spend
- Total Clicks
- Total Conversions
- ROI
- CPC
- CVR

Also includes:

- Revenue Trend
- Interactive Filters

---

## 2️⃣ Channel Performance

Compares marketing channels based on:

- Revenue
- Profit
- ROI
- Clicks
- Impressions

Channels analyzed:

- Facebook Ads
- Instagram Ads
- TikTok Ads

---

## 3️⃣ Regional Analysis

Analyzes campaign performance by region using:

- Revenue
- Profit
- Spend
- ROI
- Impressions
- Conversions

---

## 4️⃣ Customer Segment Analysis

Compares customer segments:

- Awareness
- Consideration
- Conversion
- Retargeting

Metrics include:

- Revenue
- Profit
- Clicks
- Conversions
- ROI

---

## 5️⃣ Campaign Analysis

Identifies the best-performing campaigns using:

- Top 10 Campaigns by Revenue
- Top 10 Campaigns by Profit
- Top 10 Campaigns by Conversions
- Revenue vs Spend Analysis

---

# 📈 Key Insights

- Marketing campaigns generated strong overall revenue and profitability.
- Revenue remained relatively stable during the analysis period with a slight decline toward the latest months.
- ROI varies across advertising channels, indicating differences in campaign efficiency.
- Some regions produced stronger returns despite lower marketing spend.
- Customer segments contribute differently to revenue, conversions, and profitability.
- High-performing campaigns consistently generated higher revenue and profit than the remaining campaigns.
- Higher marketing spend does not always result in higher ROI.

---

# 💡 Business Recommendations

- Increase investment in campaigns with the highest ROI.
- Optimize or discontinue campaigns with consistently low ROI.
- Allocate additional budget to high-performing regions.
- Develop tailored marketing strategies for different customer segments.
- Monitor campaign performance regularly to detect changing trends.
- Evaluate campaigns using multiple KPIs instead of revenue alone.

---

# 🛠️ Tools & Technologies

- Python
- Pandas
- Excel
- Tableau
- GitHub

---

# 📁 Repository Structure

```
Digital-Marketing-Analysis/
│
├── Dataset/
│   ├── marketing_campaign.csv
│   └── cleaned_marketing_campaign.csv
│
├── Python/
│   └── Data_Cleaning.ipynb
│
├── Tableau/
│   └── Marketing_Dashboard.twbx
│
├── Images/
│   ├── Executive.png
│   ├── Channel.png
│   ├── Regional.png
│   ├── Customer.png
│   └── Campaign.png
│
├── README.md
│
└── requirements.txt
```

---

# 🚀 How to Run the Project

1. Clone the repository.
2. Open the Python notebook to review the data cleaning process.
3. Load the cleaned dataset into Tableau.
4. Open the `.twbx` workbook.
5. Explore the dashboards using the interactive filters.

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)
- Feature Engineering
- KPI Development
- Dashboard Design
- Business Intelligence
- Marketing Analytics
- Data Visualization
- Data Storytelling
- Python (Pandas)
- Tableau
- GitHub Documentation

---

# 👨‍💻 Author

**Omar Hazem**

Computer Engineering Student | Aspiring Data Analyst

### Connect with me

- GitHub: *(Add your GitHub profile link)*
- LinkedIn: *(Add your LinkedIn profile link)*

---

⭐ If you found this project helpful or interesting, consider giving it a star!
