# 🚀 Revenue Leakage & Data Quality Analysis (Food Delivery Dataset)

> 🔍 Identified ~10% revenue leakage and critical data quality issues in a 46K+ record dataset using SQL

---

## 📌 Project Overview
Analyzed a large-scale food delivery dataset to identify **revenue drivers, profit leakage, and data reliability issues** impacting business decisions.

---

## 🎯 Business Objective
- Identify high-revenue markets  
- Detect revenue loss due to discounts  
- Improve data reliability for decision-making  

---

## 🧹 Data Cleaning Impact
- Processed **46,451 records**
- Converted invalid ratings (0) → NULL  
- Standardized numeric fields (pricing, ratings)  
- Identified inconsistent and duplicate entries  

👉 Result: Improved data accuracy for reliable analysis

---

## 🛠️ Analysis Approach

### 📊 Revenue Analysis
- Identified top-performing cities using aggregation  
- Compared **order volume vs pricing impact**

### 💸 Revenue Leakage Detection
- Estimated ~10% discount impact across cities  
- Identified highest loss in **Hyderabad, Chennai, Mumbai**

### 🔍 Advanced SQL
- Used **window functions (RANK)**  
- Identified **top 3 restaurants per city**

### ⚠️ Data Quality Analysis
- Detected **high ratings with zero votes**  
- Found **location-based entries misclassified as restaurants**

---

## 📊 Key Insights

- Hyderabad generates highest revenue due to **high volume + pricing**
- High-revenue cities also suffer **maximum discount losses**
- Revenue ≠ Profit → discounts heavily impact margins
- Data inconsistencies can lead to **wrong business decisions**

---

## 💡 Business Recommendations

- Reduce unnecessary discounts in high-performing cities  
- Focus growth strategy on top revenue markets  
- Filter unreliable data (low votes, invalid ratings)  
- Implement better data validation pipelines  

---

## 🛠️ Tech Stack
- SQL (MySQL)  
- Data Cleaning & Analysis  
- Excel / Power BI  

---

## 📂 Project Structure

/data        → dataset  
/sql         → queries with explanations  
/insights    → analysis outputs  
/dashboard   → charts  


## 📌 Future Improvements

- Add real discount dataset instead of assumptions  
- Perform customer-level analysis  
- Build interactive dashboard  

---

## 📢 Key Takeaway

This project demonstrates how structured data analysis can uncover hidden revenue losses and improve strategic decision-making in real-world business scenarios.
