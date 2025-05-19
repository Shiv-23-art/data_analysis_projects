# 📉 Customer Churn & Segmentation Analysis

This project explores customer churn behavior using Python and Power BI. It segments customers based on tenure and churn likelihood, and visualizes patterns to help businesses retain valuable users and identify risk zones.

---

## 📌 Objective

To analyze customer churn patterns, segment users based on risk and loyalty, and generate actionable insights to reduce churn and improve retention strategies.

---

## 🛠 Tools Used

- **Python (Jupyter Notebook)** – Data cleaning, EDA, churn score calculation, and segmentation logic
- **Power BI Desktop** – Dashboard creation and data visualization
- **Pandas, Eli5, SHAP** – For churn modeling and scoring
- **Excel/CSV** – For data import/export

---

## 🧠 Customer Segments Defined

- **Loyal** – Long tenure, low churn score
- **General** – Moderate churn score and tenure
- **Dormant** – New customers with no high churn risk
- **At Risk** – High churn score, low tenure
- **Churned** – Already left

---

## 📊 Dashboard Highlights

- **Total Customers**: 7,032  
- **Total Revenue**: $16.06M  
- **Average Tenure**: 32.42 months  
- **Churn Rate**: 26.58%

### Key Visuals:

- **Average Revenue per Segment**
- **Churn by Segment**
- **Contract Type and Payment Method Impact**
- **Tenure vs Churn Score**
- **Segment-wise Customer Distribution**
- **Slicer Filters** for Gender and Dependents

---

## 🔍 Key Insights

- **General** segment dominates the customer base
- **Churned** users tend to have shorter tenures and use electronic checks
- **Loyal** users bring in the **highest average revenue**
- Churn score **drops with increasing tenure**, indicating early exits are common

---

## 📂 Files Included

- `Customer_Churn_Analysis.ipynb` – Python notebook for data prep and modeling
- `Customer Churn & Segmentation Analysis Dashboard.png` – Final dashboard screenshot
- `churn_segmented.csv` – Cleaned dataset with churn score and segments
