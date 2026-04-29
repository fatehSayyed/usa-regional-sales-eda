<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=USA%20Regional%20Sales%20Analysis&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=36&desc=End-to-End%20Sales%20Intelligence%20%7C%20Power%20BI%20%7C%20Python%20EDA&descAlignY=58&descSize=18"/>

<p>
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Jupyter-FA0F00?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Orders-64K%2B-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Revenue-%241.2B-purple?style=flat-square"/>
  <img src="https://img.shields.io/badge/Profit%20Margin-37.36%25-green?style=flat-square"/>
</p>

</div>

---

## 📌 Overview

> **A comprehensive, end-to-end sales analytics project** combining Python-powered Exploratory Data Analysis with an interactive Power BI dashboard — built to uncover hidden revenue drivers, channel efficiencies, and regional performance patterns across the United States.

This project transforms raw transactional sales data into actionable business intelligence through rigorous statistical analysis, rich visualizations, and a fully interactive executive dashboard — enabling data-driven decision-making across product, sales, and regional teams.

---

## ⚡ Key Metrics at a Glance

<div align="center">

| 💰 Total Revenue | 📈 Total Profit | 📦 Total Orders | 🎯 Profit Margin |
|:-:|:-:|:-:|:-:|
| **$1.2 Billion** | **$461.7 Million** | **64,000+** | **37.36%** |

</div>

---

## 📁 Repository Structure

```
📦 usa-regional-sales-analysis/
│
├── 📊 SALES_REPORT.pbix                   # Interactive Power BI Dashboard
├── 📓 EDA_Regional_Sales_Analysis.ipynb   # Python Exploratory Data Analysis
├── 📄 EDA_Dashboard_Report.pdf            # Visual Report & Dashboard Snapshot
├── 📋 README.md                           # Project Documentation
└── 📂 assets/                             # Screenshots & Visual Assets
    ├── dashboard_page1.jpg
    ├── dashboard_page2.jpg
    └── nb_*.png                           # EDA chart exports
```

---

## 📊 Power BI Dashboard — `SALES_REPORT.pbix`

A fully interactive, multi-page executive dashboard providing real-time slicing across time, region, channel, and product dimensions.

### 🖥️ Page 1 — Executive Overview & Trends + Product & Channel Performance

![Dashboard Page 1](assets/dashboard_page1.jpg)

**What's on this page:**
- 📌 KPI Cards — Total Revenue ($1.2B), Profit ($461.7M), Orders (64K), Margin (37.36%)
- 📈 **Profit Pulse** — Monthly revenue momentum from 2021–2025
- 📊 **Order Value Spectrum** — Histogram of customer spending tiers
- 💹 **Unit Price vs. Profit Margin** — Scatter identifying high-margin price bands
- 🥧 **Channel Power Play** — Revenue split: Distributor 54% · Wholesale 31% · Export 15%
- ⚖️ **Channel Efficiency Scorecard** — Margin per sale by route to market
- 🏆 **High-Margin Heroes** — Top products ranked by profit margin %
- 🎯 **Revenue vs. Profitability Matrix** — Strategic product positioning scatter

---

### 🗺️ Page 2 — Geographic & Customer Insights

![Dashboard Page 2](assets/dashboard_page2.jpg)

**What's on this page:**
- 🌍 **Revenue by US Region** — Donut chart: Midwest 30.1% · South 27.1% · Northeast 25.9% · West 16%
- 🎯 **Profit Margin % by Region** — Consistent ~37% margin across all four regions
- 👥 **Bottom 5 Customers by Revenue** — SEINDNI Corp, Voonyx Group, Mycone Ltd, Yodoo Ltd, BB17 Company
- 📍 **Bottom 5 States by Revenue** — Wyoming, South Dakota, District of Columbia, Maine, Delaware
- 📊 **Customer Profit Margin Distribution** — Margin spread across customer segments

---

## 🐍 EDA Notebook — `EDA_Regional_Sales_Analysis.ipynb`

A deep-dive Python notebook performing statistical profiling and visual storytelling on the sales dataset.

---

### 📈 1. Monthly Sales Trend

![Monthly Sales Trend](assets/nb_monthly_sales_trend.png)

> Monthly revenue fluctuates between **$21M–$26M** across the full time period (2014–2018), with a notable dip in early 2017. Overall revenue shows no systemic decline — seasonal cycles are consistent year-on-year.

---

### 📅 2. Seasonal Revenue Pattern (Excluding 2018)

![Seasonal Trend](assets/nb_seasonal_trend.png)

> **May** is the peak revenue month at ~$102M aggregate, while **February** is the weakest at ~$91.5M. This pattern suggests strong Q2 performance and a mid-winter lull — useful for planning targeted promotional campaigns.

---

### 🏆 3. Top 10 Products by Revenue

![Top 10 Products Revenue](assets/nb_top10_products_revenue.png)

> **Product 26** leads all SKUs at ~$117M in total revenue, followed by **Product 25** (~$109M) and **Product 13** (~$78M). The top 3 products account for a significant portion of overall sales, indicating revenue concentration risk.

---

### 💰 4. Top 10 Products by Average Profit Margin

![Top 10 Products Margin](assets/nb_top10_products_margin.png)

> **Product 18** achieves the highest average profit margin (~$8,500 per unit), followed by **Product 28** and **Product 5**. Notably, high-revenue products are not always high-margin — a key strategic insight for portfolio optimization.

---

### 🚚 5. Total Sales by Channel

![Sales by Channel](assets/nb_sales_by_channel.png)

> The **Wholesale** channel dominates with **54.1%** of total sales volume, followed by **Distributor** at 31.3% and **Export** at 14.6%. All three channels maintain near-identical profit margins (~37–38%), suggesting channel efficiency is uniform across routes to market.

---

### 📦 6. Distribution of Average Order Value

![Order Value Distribution](assets/nb_order_value_distribution.png)

> The vast majority of orders fall in the **$0–$100K** range, with a sharp right-skewed distribution. High-value orders (>$300K) are rare but represent potential VIP or bulk-buyer segments worth nurturing with dedicated account management.

---

### 💹 7. Profit Margin % vs. Unit Price

![Margin vs Unit Price](assets/nb_margin_vs_unitprice.png)

> Profit margin (15–60%) is **relatively independent of unit price**, appearing uniformly distributed across all price bands ($0–$7K). This implies margin is driven more by product category and cost structure than by pricing tier alone.

---

### 🌍 8. Total Sales by US Region

![Sales by Region](assets/nb_sales_by_region.png)

> The **West** region leads in total sales (~$370M), closely followed by **South** (~$335M) and **Midwest** (~$320M). The **Northeast** lags at ~$210M — representing a potential growth opportunity for targeted regional sales strategies.

---

### 👥 9. Top & Bottom 10 Customers by Revenue

![Top Bottom Customers](assets/nb_top_bottom_customers.png)

> **Aibox Company** ($12.5M) and **State Ltd** ($12.3M) are the top revenue generators. Bottom customers like **BB17 Company** and **Yodoo Ltd** generate under $4.5M — flagging opportunities for account development or re-evaluation.

---

### ⚖️ 10. Average Profit Margin by Channel

![Margin by Channel](assets/nb_margin_by_channel.png)

> All three channels maintain nearly identical margins — **Export: 37.93%**, **Distributor: 37.56%**, **Wholesale: 37.09%**. This uniformity confirms no channel is being discounted more than others, validating current pricing strategy.

---

### 🔬 11. Customer Segmentation — Revenue vs. Profit Margin

![Customer Segmentation](assets/nb_customer_segmentation.png)

> Customers cluster between **$4M–$13M revenue** and **34%–43% margin**. Bubble size = order volume. High-value targets sit in the upper-right quadrant (high revenue + high margin). Customers with high revenue but low margin warrant a cost structure review.

---

## 💡 Key Business Insights

```
📌 REGIONAL STRATEGY
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  All 4 regions maintain ~37% margin → pricing discipline is consistent.
  Northeast lags in revenue → prime target for sales expansion.
  Wyoming, Maine, Delaware are bottom-5 states → consider localized campaigns.

📌 CHANNEL EFFICIENCY
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  All channels perform equally on margin (~37–38%).
  Wholesale dominates volume (54%) → scale this channel further.
  Export has highest margin (37.93%) despite smallest volume → growth potential.

📌 PRODUCT PORTFOLIO
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Product 26 leads revenue → protect and scale.
  Product 18 leads margin → push in high-value segments.
  High revenue ≠ high margin → portfolio diversification needed.

📌 CUSTOMER INSIGHTS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Top 10 customers drive $10–13M each → strong key account dependency.
  February is the weakest revenue month → plan promotions accordingly.
  May peaks at ~$102M aggregate → leverage for new product launches.
```

---

## 🛠️ Tech Stack

| Layer | Tools |
|-------|-------|
| **Language** | Python 3.10+ |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **BI Dashboard** | Microsoft Power BI |
| **Notebook** | Jupyter Lab / Jupyter Notebook |
| **Version Control** | Git & GitHub |

---

## 🚀 Getting Started

### Prerequisites

```bash
Python >= 3.10
Power BI Desktop (for .pbix file)
Jupyter Notebook / JupyterLab
```

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/usa-regional-sales-analysis.git

# 2. Navigate into the project directory
cd usa-regional-sales-analysis

# 3. Install required Python packages
pip install pandas numpy matplotlib seaborn plotly jupyter

# 4. Launch the Jupyter Notebook
jupyter notebook EDA_Regional_Sales_Analysis.ipynb
```

### Opening the Power BI Dashboard

1. Download and install **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)** (free)
2. Open `SALES_REPORT.pbix`
3. Use slicers to filter by **Year**, **Month**, **Region**, or **Channel**

---

## 🔮 Future Enhancements

- [ ] 🤖 Predictive Revenue Forecasting using ARIMA / Prophet
- [ ] 🗺️ State-level choropleth map integration in Power BI
- [ ] 🔄 Automated data refresh pipeline with Python + Power BI API
- [ ] 📧 Automated report email distribution
- [ ] 🧠 Customer segmentation with K-Means clustering
- [ ] 📱 Power BI Mobile optimization
- [ ] 📦 Product affinity analysis (market basket)

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### ⭐ If this project helped you, please give it a star!

**Made with ❤️ and lots of ☕**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer"/>

</div>
