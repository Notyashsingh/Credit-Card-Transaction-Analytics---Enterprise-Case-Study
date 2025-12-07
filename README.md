This project explores how a major US credit card issuer can use data analytics to understand customer behaviour, merchant performance, category patterns, fraud risks, and long-term growth trends. The analysis uses a real-world scale dataset with 1.29M+ transactions, 983 customers, 693 merchants, and 14 categories, spanning 434 days.

The final case study includes SQL-based insights, customer and merchant analytics, fraud patterns, category performance, and strategic recommendations.

📌 Project Overview

The goal of this project was to:

Identify customer spending patterns and high-value segments

Evaluate merchant performance and revenue concentration

Analyse category trends to find key growth areas

Detect fraud patterns across channels, customers, and merchants

Generate time-series insights for operational and strategic decisions

📂 Dataset Summary

Transactions: 1,290,000+

Customers: 983

Merchants: 693

Categories: 14

Timeline: Jan 2019 – Jun 2020

Data Model

Star schema consisting of:

Fact table: Transactions

Dimensions: Customers, Merchants, Categories, Date

🛠️ Tools and Technologies

PostgreSQL — storage and SQL analytics

Python — data processing and visualization

Pandas, Matplotlib, Seaborn

Jupyter Notebook for EDA and charting

📈 Key Analysis Sections
1. Customer Analytics

94% customers active in last 90 days

Average revenue per customer: $92.8K

VIP customers contribute $275K–$296K each

RFM analysis highlights strong recency and repeat-use behaviour

2. Merchant Performance

Heavy Pareto effect: <2% merchants generate most revenue

Top merchants: $295K–$391K each

100% merchants active in the last 90 days

Fraud concentrated in a handful of merchant segments

3. Category Insights

Grocery POS leads revenue share (15.85%)

Shopping POS, Net Shopping, Gas/Transport are major spend drivers

Travel has the highest order value

Certain categories show elevated fraud risk

4. Fraud Analysis

Overall fraud rate: 0.58%

Fraud spikes during holiday seasons and lockdown months

Late-night transactions show higher fraud probability

Some customers appear in 15–19 fraudulent events

5. Time-Series Trends

Seasonal demand spikes (Dec +10%)

Rolling windows (3-month & 6-month averages)

YTD 2020 revenue: $26.24M

Q2 2020: $14.04M

🎯 Strategic Recommendations

Strengthen retention and win-back programs

Optimize merchant partnerships based on revenue + fraud insights

Invest in high-potential categories (Home, Kids/Pets)

Use behaviour-based real-time fraud detection

Incorporate rolling-window metrics into dashboards

📘 Full Case Study

The PDF report contains the complete analysis with visualizations, SQL queries, insights, and recommendations.

📎 How to Use This Repository

/sql_queries → Contains SQL scripts used for analysis

/notebooks → EDA, transformations, visuals in Python

/data_model → Schema designs and entity diagrams

/report → Case Study PDF

📬 Contact



Feel free to reach out for collaboration, improvements, or data analytics discussions.
