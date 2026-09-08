# Bank Marketing Campaign Analysis

## Overview

This project analyzes a bank marketing campaign to understand customer subscription behavior and identify the customer segments and campaign characteristics associated with higher subscription rates.

The analysis follows a complete data analyst workflow:

**Excel → Python → Power BI → Business Insights**

The goal is to move from raw campaign data to actionable findings that can help improve customer targeting and campaign effectiveness.

---

## Business Problem

The bank wants to understand:

- How successful was the marketing campaign?
- Which customer segments were more likely to subscribe?
- Does previous campaign history relate to current subscription?
- Does the number of contacts affect campaign performance?
- Is call duration associated with subscription?
- Which campaign periods and contact methods perform better?
- How can future campaigns be targeted more effectively?

---

## Dataset

The dataset contains **11,162 customer records** and **17 variables** covering:

- Customer demographics
- Financial information
- Current campaign activity
- Previous campaign history
- Campaign outcome

### Target Variable

`deposit`

- `yes` → Customer subscribed
- `no` → Customer did not subscribe

---

## Tools Used

- **Excel** — Initial exploration, PivotTables and basic analysis
- **Python** — Data cleaning, exploratory data analysis, statistical exploration and segmentation
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualizations
- **Power BI** — Interactive dashboard and DAX analysis
- **DAX** — Measures and calculated columns

---

## Project Workflow

### 1. Excel

Used Excel for initial exploration and business-oriented analysis using:

- Data checks
- PivotTables
- Customer segmentation
- Subscription-rate analysis
- Basic campaign performance analysis

### 2. Python

Performed deeper exploratory analysis including:

- Dataset profiling
- Data quality checks
- Subscription analysis
- Customer segmentation
- Distribution analysis
- Correlation analysis
- Campaign behaviour analysis
- Relationship analysis between customer characteristics and subscription

### 3. Power BI

Built an interactive two-page dashboard.

#### Page 1 — Campaign Performance

Focuses on:

- Overall subscription performance
- Customer segmentation
- Subscription rate by job
- Subscription rate by age group
- Monthly subscription trends
- Subscription rate by contact method

#### Page 2 — Campaign Insights

Focuses on:

- Previous campaign outcomes
- Housing-loan relationship
- Number of campaign contacts
- Call duration
- Age-group subscription performance

---

## Key Metrics

| Metric | Value |
|---|---:|
| Total Customers | 11,162 |
| Subscribed Customers | 5,289 |
| Non-Subscribed Customers | 5,873 |
| Subscription Rate | 47.4% |
| Average Call Duration | 372 seconds |

---

## Key Insights

- The campaign achieved an overall subscription rate of **47.4%**.
- Students and customers aged **60+** showed the highest subscription rates among the analyzed segments.
- Customers without housing or personal loans generally showed higher subscription rates.
- Customers with a previous successful campaign outcome had a **91.3%** current subscription rate.
- Customers with previous contact history generally performed better than customers with no previous contacts.
- Subscribers had a much higher median call duration than non-subscribers.
- Higher numbers of repeated contacts generally showed weaker subscription rates.
- Subscription rates varied considerably across campaign months, with May showing particularly weak performance.

---

## Business Recommendations

Based on the analysis:

1. Prioritize customer segments with consistently higher subscription rates.
2. Use previous campaign outcomes to improve customer targeting.
3. Focus on the quality of customer conversations rather than simply increasing contact frequency.
4. Investigate campaign periods with weaker subscription performance.
5. Review customers and records with unknown contact or campaign-history information.
6. Use customer characteristics and previous interactions together when designing future targeting strategies.

---

### Dashboard Preview

### Page 1 — Campaign Performance

![Campaign Performance Dashboard](screenshots/page1-dashboard.png)

### Page 2 — Campaign Insights

![Campaign Insights Dashboard](screenshots/page2-dashboard.png)
---

## Conclusion

The analysis shows that campaign performance varies substantially across customer characteristics, previous marketing history and current campaign behaviour.

Previous campaign success, call duration, customer segment and loan status showed notable associations with subscription. These findings can help the bank improve targeting, reduce inefficient repeated contacts and focus marketing efforts on higher-potential customer groups.

---

## Project Structure

```text
Bank-Marketing-Campaign-Analysis/
│
├── data/
│   └── bank.csv
│
├── excel/
│   └── bank_marketing_analysis.xlsx
│
├── python/
│   └── bank_marketing_eda.ipynb
│
├── powerbi/
│   └── bank_marketing_dashboard.pbix
│
├── README.md
└── insights.md
