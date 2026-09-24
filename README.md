

# RetailPulse Analytics: End-to-End Sales Performance & Predictive Modeling

**RetailPulse Analytics** is an end-to-end data science and business intelligence project designed to analyze multi-national retail sales performance, uncover key profitability drivers, build a high-accuracy predictive regression model, and translate those insights into an interactive executive dashboard.

---

## 🚀 Project Overview

This repository contains a complete data workflow spanning data engineering, exploratory data analysis (EDA), machine learning predictive modeling, and business intelligence reporting. 

### Key Highlights:
* **Data Engineering:** Cleaned and structured multi-national transactional data (2013–2014) to build a production-ready dataset (`cleaned_retail_sales.csv`).
* **Exploratory Data Analysis:** Uncovered major Q4 seasonality spikes, product profitability leaders (Paseo), and segment-driven volume trends.
* **Predictive Machine Learning:** Developed a Linear Regression model achieving an **$R^2$ of 0.9981** and an **RMSE of ~$10,250** to forecast sales accurately.
* **Interactive Business Intelligence:** Built a fully functional Power BI dashboard (`Retail_Sales_Dashboard.pbix`) for real-time stakeholder insights.

---

## 📊 Key Findings & Visual Insights

* **Seasonality:** Sales peak significantly during October and December, while early-year months experience lower overall transaction volumes.
* **Growth Trajectory:** Annual revenue more than tripled in 2014 compared to 2013, indicating rapid business expansion.
* **Segment Dominance:** High-volume sales are concentrated primarily in the Government and Small Business sectors.
* **Product Performance:** Paseo leads in profitability, demonstrating high profit variability and peak outlier returns.


---

## 🗂️ Repository Structure

```text
├── data/
│   └── cleaned_retail_sales.csv                 # Final processed and validated dataset
├── dashboards/
│   └── Sample data (1).csv                      # Initial Sample data
├── notebooks/
│   └── End-to-End-Analysis-Case-Study.ipynb     # Python code for cleaning, EDA, and ML modeling
└── README.md                                    # Project documentation
