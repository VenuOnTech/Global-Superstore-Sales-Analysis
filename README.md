# Global-Superstore-Sales-Analysis

# 📊 Global Superstore Descriptive/BI Analysis

A comprehensive Business Intelligence (BI) and Descriptive Analytics project leveraging the Global Superstore Sales Dataset. This project uncovers key sales, profit, and shipping insights that could guide strategic decision-making in a retail context.

---

## 📁 Dataset Overview

- **Source:** [Kaggle - Global Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Rows:** ~10,000  
- **Columns:** 24  
- **Time Range:** 2011–2014 (approx.)
- **Key Fields:** `Sales`, `Profit`, `Category`, `Region`, `Order Date`, `Ship Mode`, `Customer Segment`, `Discount`, `Shipping Duration`

---

## 🎯 Project Objectives

- Clean and preprocess the dataset for accurate analysis.
- Perform descriptive analytics to understand sales and profitability trends.
- Build interactive BI dashboards using Tableau/Power BI.
- Provide actionable insights on:
  - Top-performing products and regions
  - Shipping delays and fulfillment issues
  - Impact of discounts on profitability
  - Customer segment behaviors

---

## 🧪 Exploratory Data Analysis

- ✅ Data Cleaning & Transformation  
- ✅ Derived Fields: `shipping_duration`, `profit_margin`  
- ✅ Visual Insights:
  - Top-selling subcategories
  - Profit heatmap by region/country
  - Time-series of sales & profit
  - Shipping delay analysis
  - Discount vs Profit correlation

All EDA is implemented using **Python**, `pandas`, `seaborn`, `plotly`, and `ydata-profiling`.

> 📁 See: [`Retail Performance Unlocked: BI + EDA on Global Superstore Sales.ipynb`](https://colab.research.google.com/drive/1KlcI2qG2a-xsY-o5O60ta2n86csi1_2-?usp=sharing)

---

## 🧠 Key Insights

- 📈 **Technology** and **Office Supplies** were top profit-generating categories.
- 📍 **West** and **East** regions contributed the highest sales.
- 🕓 Orders shipped via **Standard Class** had higher average shipping delays.
- 💸 Higher **discounts often led to losses**, especially in low-margin categories.
- 👤 **Corporate** customers had the highest average order values.

---

## 🧰 Tech Stack & Tools

| Category        | Tool/Library              |
|----------------|---------------------------|
| Language        | Python                    |
| Libraries       | pandas, seaborn, plotly, ydata-profiling |
| Notebook        | Google Colab / Jupyter    |
| Version Control | Git + GitHub              |

---

## 🗃️ Project Structure  

Global_Superstore_Analysis/  
├── data/ # Raw and cleaned datasets  
├── notebooks/ # Jupyter/Colab notebooks  
├── visuals/ # Dashboard screenshots & charts 
├── docs/ # Project documentation  
└── README.md  

🙌 Acknowledgments

i) Kaggle Datasets Community  
ii) Tableau Public / Power BI Docs  
iii) Analytics Vidhya & Medium for visualization inspiration
