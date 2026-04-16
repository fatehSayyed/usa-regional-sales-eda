# usa-regional-sales-eda
Data analysis project identifying revenue drivers, regional trends, and customer insights from US sales data using Python and visualization tools.
# links
https://github.com/fatehSayyed/usa-regional-sales-eda/tree/main
# 🛒 USA Regional Sales Analysis (2021–2025)
### Exploratory Data Analysis — Personal Portfolio Project

**Author:** Fateh Mohammed Sayyed  
**LinkedIn:** [fateh-sayyed-258569322](https://www.linkedin.com/in/fateh-sayyed-258569322)  
**Tools:** Python · Pandas · Matplotlib · Seaborn · Plotly  

---

## 📌 Project Overview
Exploratory Data Analysis (EDA) of regional sales data from 2021 to 2025
across products, channels, customers, and US regions — uncovering trends,
outliers, and actionable business insights.

---

## ❓ Problem Statement
Analyze 5 years of sales data to identify key revenue and profit drivers,
uncover seasonal trends, detect outliers, and align performance against
budgets — to support strategic pricing, promotions, and market expansion.

---

## 🎯 Objectives
- Identify top performing products, channels, and regions
- Uncover seasonal trends and monthly patterns
- Detect pricing and margin risks from outlier transactions
- Segment customers by revenue and profitability
- Prepare data and insights for Power BI dashboard development

---

## 📂 Dataset
| Sheet | Description |
|---|---|
| Sales Orders | Transaction level order data |
| Customers | Customer master data |
| Products | Product catalogue |
| Regions | US regional mapping |
| State Regions | State to region mapping |
| Budgets | 2024 budget targets |

---

## 🛠️ Tools & Libraries
| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Static visualizations |
| Seaborn | Statistical visualizations |
| Plotly | Interactive choropleth maps |

---

## 📊 Analysis Performed
1. Data Profiling and Cleaning
2. Feature Engineering — Profit, Margin %, Month/Year columns
3. Monthly Sales Trend — 2021 to 2025
4. Seasonality Analysis — All years combined
5. Top 10 Products by Revenue
6. Top 10 Products by Average Profit Margin
7. Sales by Channel — Pie Chart
8. Average Order Value Distribution
9. Profit Margin % vs Unit Price — Scatter Plot
10. Unit Price Distribution per Product — Boxplot
11. Total Sales by US Region — Bar Chart
12. Total Sales by State — Choropleth Map
13. Top and Bottom 10 Customers by Revenue
14. Customer Segmentation — Revenue vs Profit Margin Bubble Chart
15. Correlation Heatmap of Numeric Features

---

## 💡 Key Insights
- **West region dominates** with ~$360M (35% of total sales)
- **Wholesale channel** accounts for 54% of all revenue
- **Product 26 and 25** are top earners at $118M and $110M
- **California leads** all states with ~$230M in revenue
- **Export channel** has highest profit margin at 37.93%
- **January shows consistent trough** — opportunity for targeted promotions
- **2024 revenue drop** is an outlier warranting further investigation

---

## 📈 Recommendations
1. Scale export channel — lowest volume but highest margin
2. Target Northeast region — significant untapped growth opportunity
3. Investigate 2024 anomaly — one-time disruption or structural shift
4. Retain top 10 customers — tight revenue cluster needs dedicated strategy
5. Shift marketing spend toward January trough and May–June peaks

---

## 📁 Project Structure
```
├── data/
│   └── Regional_Sales_Summary.xlsx
├── notebooks/
│   └── EDA_Regional_Sales_Analysis_Clean.ipynb
├── outputs/
│   └── Sales_data(EDA_Exported).csv
└── README.md
```

---

## ▶️ How to Run
```bash
# 1. Clone the repository
https://github.com/fatehSayyed/usa-regional-sales-eda/tree/main

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn plotly openpyxl

# 3. Place Excel file in data/ folder

# 4. Run the notebook
jupyter notebook notebooks/EDA_Regional_Sales_Analysis_Clean.ipynb
```

---

## 👤 Author
**Fateh Mohammed Sayyed**  
Data Analyst | Python | Power BI | SQL  
🔗 [LinkedIn](https://www.linkedin.com/in/fateh-sayyed-258569322)

