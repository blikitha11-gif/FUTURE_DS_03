# 📊 Marketing Funnel & Conversion Performance Analysis

### Future Interns – Data Science & Analytics Task 3

This project analyzes marketing funnel performance to understand how users move from **Impressions → Clicks → Leads → Customers**.

## 🎯 Project Objectives

- Analyze the complete marketing funnel
- Measure conversion rates at each stage
- Identify major funnel drop-off points
- Compare campaign performance
- Analyze customer conversion across demographics
- Evaluate campaign cost efficiency
- Provide actionable marketing recommendations

## 📂 Dataset

The dataset contains Facebook advertising and conversion performance data.

### Key Features

- `ad_id` – Advertisement ID
- `xyz_campaign_id` – Campaign ID
- `fb_campaign_id` – Facebook Campaign ID
- `age` – Customer age group
- `gender` – Customer gender
- `interest` – Customer interest category
- `Impressions` – Number of advertisement impressions
- `Clicks` – Number of advertisement clicks
- `Spent` – Advertising spend
- `Total_Conversion` – Total conversions/leads
- `Approved_Conversion` – Approved conversions/customers

## 🧹 Data Cleaning

The following steps were performed using Python and Pandas:

- Checked dataset shape and columns
- Checked missing values
- Checked data types
- Converted numerical columns to numeric format
- Checked duplicate records
- Checked negative values
- Created funnel metrics
- Created campaign performance metrics
- Created cost-efficiency metrics
- Exported the cleaned dataset

## 📈 Marketing Funnel

| Funnel Stage | Count |
|---|---:|
| Impressions | 213,434,828 |
| Clicks | 38,165 |
| Leads | 3,264 |
| Customers | 1,079 |

## 📊 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Impressions | 213,434,828 |
| Total Clicks | 38,165 |
| Total Leads | 3,264 |
| Total Customers | 1,079 |
| Overall Conversion Rate | 0.0005% |

## 🔎 Key Findings

- The largest drop-off occurs between impressions and clicks.
- Additional drop-offs occur between clicks, leads, and approved customers.
- Campaign performance varies significantly across campaigns.
- Campaign 1178 generated the highest number of customers.
- Campaign 916 achieved the highest customer conversion rate.
- Campaign 916 also had the lowest cost per customer.
- Customer conversion varies across age, gender, and interest segments.
- High customer volume does not always mean high campaign efficiency.

## 🚀 Recommendations

- Optimize advertisement creatives and messaging to improve click-through performance.
- Improve landing pages and calls-to-action to increase lead conversion.
- Strengthen lead follow-up and qualification to improve lead-to-customer conversion.
- Focus more on cost-efficient campaigns.
- Review campaigns with high spending and low customer conversion.
- Use high-performing demographic and interest segments for targeted marketing.
- Continuously monitor conversion rates and customer acquisition costs.

## 📊 Tableau Dashboard

The interactive Tableau dashboard includes:

- Total Impressions
- Total Clicks
- Total Leads
- Total Customers
- Overall Conversion Rate
- Marketing Funnel
- Customer Conversion Rate by Campaign
- Customers by Campaign
- Cost Per Customer by Campaign
- Customers by Gender

### Dashboard Preview

![Marketing Funnel Dashboard](Screenshots/dashboard_1.png)

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Tableau
- GitHub

## 📁 Project Structure

```text
FUTURE_DS_03/
│
├── Dataset/
│   └── Cleaned_Marketing_Funnel_Data.csv
│
├── Notebook/
│   └── Marketing_Funnel_Conversion_Analysis.ipynb
│
├── Screenshots/
│   └── dashboard_1.png
│
├── Tableau/
│   └── Marketing_Funnel_Conversion_Performance_Dashboard.twbx
│
└── README.md

⚠️ Dataset Limitation
The dataset does not contain a date field, so time-period or monthly trend analysis was not performed. The analysis focuses on funnel performance, campaign performance, demographics, interest segments, customer conversion, and cost efficiency.
🏁 Conclusion
This project provides a complete analysis of marketing funnel and conversion performance. The results highlight major funnel drop-offs, differences in campaign efficiency, and opportunities to improve customer acquisition through better targeting, conversion optimization, and cost management.
👩‍💻 Author
Likitha
BCA – Data Science
Aditya Degree College
Future Interns – Data Science & Analytics
Task 3: Marketing Funnel & Conversion Performance Analysis
```
