Retail Fashion Business Trend Analysis 👗📊

Goal: To understand retail fashion sales trends, seasonality, category performance, AOV (Average Order Value), RFM/cohort analysis—supporting data-driven business decisions.

Dataset
Source: (https://docs.google.com/spreadsheets/d/1-t6W-vA9u7d0ejDJiqTdQHFyZD7tWCDd/edit?usp=sharing&ouid=100581268667425889882&rtpof=true&sd=true)

Code Source:(https://colab.research.google.com/drive/1QpdK1dw0f6WY4bY3GImv7M0GLjTXwnXb?usp=sharing)

Time span: 2022-01 → 2024-12 (example)

Key fields: order_id, date, product_category, price, qty, revenue, customer_id, channel…

Analysis Steps
Data Cleaning – Handling missing values, outliers, type conversions

Feature Engineering – Calculating GMV, AOV, basket size, season/month, channel split

Trend & Seasonality – Monthly/weekly sales, YoY & MoM growth

Category & SKU Mix – Identifying top and worst performers

Customer Analytics – RFM analysis, cohort retention analysis

Insights & Recommendations

Key KPIs
GMV / Revenue Trend

AOV = Revenue / Orders

Conversion Proxy (if available)

Category Mix (% contribution)

Repeat Rate / Retention (cohort-based)

Results: https://drive.google.com/file/d/1zvPOLRYqhe-jAHfrdwPSU9Fyn_jsMm-B/view?usp=sharing, https://drive.google.com/file/d/1eiS-VvoPss5JSOt3WXY-FDDq8xe-eQYu/view?usp=sharing

Reproduce
bash
Copy
Edit
python -m venv .venv && source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
Google Colab   # or jupyter notebook
