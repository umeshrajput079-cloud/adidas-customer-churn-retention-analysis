# Adidas Customer Churn & Retention Analysis — Power BI

## 📊 Project Overview

This project is a **Power BI customer analytics and retention dashboard** developed to analyze customer churn, repeat purchasing behavior, loyalty program performance, store/channel performance, and Customer Lifetime Value (CLV) for **Adidas**.

The project covers data cleaning and transformation, KPI development, customer segmentation, retention analysis, promotion impact, and executive-level business recommendations.

## 🎯 Business Objectives

- Analyze customer churn and retention
- Identify customer segments with high churn risk
- Understand repeat purchase behavior
- Evaluate loyalty tier performance
- Measure the impact of promotions on purchase value
- Compare Store vs Online channel performance
- Analyze Customer Lifetime Value (CLV)
- Identify opportunities to improve customer retention and loyalty engagement

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- Data Modeling
- Data Cleaning & Transformation
- Data Visualization
- Customer Segmentation
- Business Analytics

## 🔄 Project Workflow

### 1. Data Modeling & Cleaning

Data was loaded and transformed using Power Query.

- Removing duplicate records
- Handling missing values
- Correcting data types
- Creating Membership Duration
- Extracting Transaction Year
- Extracting Transaction Month
- Preparing the data model for analysis

### 2. Churn & Retention Analysis

**Churn Rate = (Churned Customers / Total Customers) × 100**

Analysis was performed across:

- Region
- Income Group
- Store/Online Channel
- Loyalty Tier

A customer funnel was created:

**Total Customers → Repeat Customers → Churned Customers**

**Key Findings**
- Overall churn rate: **29.40%**
- Higher churn was observed in the **Asia-Pacific** region.
- High-income customers showed comparatively higher churn.
- The **Elite loyalty tier** showed significant retention challenges.
- The funnel decreased from **500 total customers to 256 repeat customers**, highlighting retention gaps.

### 3. Repeat Purchase Analysis

Customers were segmented according to purchase frequency:

| Segment | Purchases |
|---|---:|
| Low-Tier | 0–3 |
| Mid-Tier | 4–8 |
| High-Tier | 9+ |

**Key Findings**
- Most customers belong to the **Mid-Tier** segment.
- Average purchase frequency remained fairly consistent across regions.
- The **18–24 age group** showed slightly higher engagement.
- **Elite loyalty customers** showed strong purchase engagement.
- **Footwear** was the most purchased category among loyal customers.

### 4. Promotion & Loyalty Impact

The analysis evaluated:

- Percentage of transactions using promotions
- Average purchase amount with vs. without promotions
- Churn rate by loyalty tier
- Points earned vs. redeemed by loyalty tier

**Key Findings**
- Transactions using promotions generated higher purchase values.
- Higher loyalty tiers, particularly **Elite**, still experienced retention challenges.
- Points earned were higher than points redeemed across loyalty tiers.
- Low reward redemption indicates an opportunity to improve loyalty-program engagement.

### 5. Store & Channel Performance

Store data was merged with transaction data using **Store-ID**.

**Key Findings**
- **Franchise and Outlet** stores generated the highest average transaction values.
- **Flagship stores** had the highest churn rate at approximately **31.30%**.
- Online stores showed comparatively lower churn.
- Older stores demonstrated better customer retention than newer stores.

### 6. Customer Lifetime Value (CLV) Analysis

**CLV = Total Amount Spent / Membership Duration (Years)**

Customers were segmented into:

- Low CLV
- Medium CLV
- High CLV

**Key Findings**
- Total CLV was approximately **45.6K**.
- Most customers were in the **Low CLV** segment.
- Very few customers reached the Medium or High CLV segments.
- The relationship between CLV and days since last purchase was weak.
- **Elite customers** generated the highest CLV across several regions.
- **Base-tier customers** contributed the least CLV.

## 📈 Power BI Dashboard

The final Power BI report contains multiple analytical pages:

### Page 1 — Executive KPIs
- Churn Rate
- Customer Lifetime Value
- Repeat Customer Rate

### Page 2 — Loyalty & Promotion Impact
- Loyalty tier analysis
- Promotion performance
- Points earned vs. redeemed
- Churn by loyalty tier

### Page 3 — Store & Channel Insights
- Store type performance
- Channel performance
- Transaction value
- Churn and retention

### Page 4 — Customer Segmentation
- Churned customers
- Repeat customers
- High-value customers

### Interactive Filters

- Region
- Channel
- Income Group
- Loyalty Tier

## 💡 Business Recommendations

### 1. Prioritize High-Risk & High-Value Customers

Focus retention campaigns on customers with high purchase value but increasing churn risk, particularly within higher-value loyalty tiers.

### 2. Improve Underperforming Channels & Stores

Flagship stores and newly opened stores should be investigated for customer experience and retention issues.

### 3. Strengthen Loyalty Program Engagement

Improve reward redemption through targeted offers, personalized benefits, and easier redemption mechanisms.

## 📁 Project Files

```text
Power-BI-Adidas-Customer-Analysis/
│
├── README.md
├── Power_BI_Report.pdf
├── Power_BI_Dashboard.pbix
└── Screenshots/
    ├── dashboard.png
    ├── churn_analysis.png
    ├── loyalty_analysis.png
    └── clv_analysis.png
```

> The `.pbix` file and project report are included in this repository.

## 📌 Conclusion

This Power BI project provides an end-to-end view of **customer churn, retention, purchasing behavior, loyalty performance, store/channel performance, and Customer Lifetime Value**.

The analysis highlights important retention gaps, particularly among high-value customers and certain loyalty tiers and store types. The dashboard can help business teams identify at-risk customers, improve loyalty engagement, and develop targeted retention strategies.

## 👤 Author

**Umesh Rajput**

Data Analytics | Power BI | SQL | Excel | Python
