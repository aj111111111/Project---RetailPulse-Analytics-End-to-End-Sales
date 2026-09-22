**SQL-to-Pandas Refactoring:** Translated 10 complex SQL analytical queries into efficient, using SQL.

**Data Preprocessing & Encoding:** Cleaned the 3,900-record customer behavior dataset.

**Regression Modeling & Evaluation:** 

**Classification Modeling:** Built a Logistic Regression model to predict customer subscription status, achieving a strong 83% prediction accuracy.

**Business Insights & Strategy:** Evaluated model outputs, highlighting the readiness of classification for targeted marketing campaigns.

---

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

## 🤖 Machine Learning Model

A **Linear Regression** model was built using `scikit-learn` to predict sales based on features including `Units Sold`, `Gross Sales`, `Profit`, `Country`, `Product`, and `Segment`.

* **$R^2$ Score:** `0.9981` (The model explains **99.81%** of the variance in sales).
* **Mean Squared Error (MSE):** `105,081,273.08` ($\text{USD}^2$).
* **Root Mean Squared Error (RMSE):** `$10,250.92` (Indicates an average prediction error margin of about $10.2k against transactions exceeding $1,000,000).

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
