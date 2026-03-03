# 📊 E-Commerce Sales Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Project Overview
End-to-end exploratory data analysis of an e-commerce retail dataset containing **541,909 transactions** from a UK-based online retailer. This project uncovers sales trends, top products, customer behavior, and provides data-driven business recommendations.

---

## 🎯 Objectives
- Analyze overall sales performance
- Identify top-selling products
- Understand customer behavior & segmentation
- Provide actionable business recommendations

---

## 🗂️ Dataset
- **Source:** [Online Retail Dataset - UCI / Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
- **Records:** 541,909 transactions (392,692 after cleaning)
- **Period:** 1 year of transaction data
- **Features:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## 🛠️ Tools & Libraries
| Tool | Usage |
|------|-------|
| Python | Core language |
| Pandas | Data manipulation |
| Matplotlib | Visualization |
| Seaborn | Statistical charts |
| Jupyter Notebook | Analysis environment |

---

## 📊 Key Insights

### 💰 Sales Performance
- **Total Revenue:** £[ISI DARI OUTPUT]
- **Total Orders:** [ISI]
- **Total Customers:** [ISI]
- **Average Order Value:** £[ISI]
- **Repeat Customer Rate:** [ISI]%

### 📦 Product
- Top product by quantity: **[ISI]**
- Top product by revenue: **[ISI]**

### 🕐 Time Analysis
- Peak month: **[ISI]**
- Peak day: **[ISI]**
- Peak hour: **[ISI]:00**

### 👥 Customer Segments (RFM)
- **Champions:** [ISI]% of customers
- **At Risk:** [ISI]% need re-engagement

---

## 💡 Business Recommendations

1. **Peak Season Campaign** — Launch promotions in [peak month], revenue historically highest
2. **Retain Champions** — Top [ISI]% customers drive majority of revenue, create VIP loyalty program
3. **Re-engage At Risk** — Send win-back email campaign to [ISI]% at-risk customers
4. **Stock Optimization** — Ensure top products always in stock, especially pre-peak season
5. **International Expansion** — [Top non-UK country] shows strong demand outside UK

---

## 📁 Project Structure
```
ecommerce-sales-analysis/
├── data/
│   └── online-retail.csv
├── notebook/
│   └── ecommerce_analysis.ipynb
├── images/
│   ├── monthly_revenue.png
│   ├── top_products.png
│   ├── time_analysis.png
│   ├── country_analysis.png
│   └── rfm_analysis.png
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run
```bash
git clone https://github.com/[USERNAME]/ecommerce-sales-analysis.git
cd ecommerce-sales-analysis
pip install -r requirements.txt
jupyter notebook notebook/ecommerce_analysis.ipynb
```