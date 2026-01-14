# 📊 Excel Call Center Performance Dashboard

## 📌 Project Overview
This project is an interactive Excel dashboard designed to analyze Call Center performance and support management decision-making.

The main focus was not just building visuals, but understanding the business problem, cleaning real-world data, and transforming it into clear and actionable insights.

---

## 🎯 Business Problem
Management needed a clear and structured report to:
- Monitor overall call center performance
- Track agent productivity
- Identify answered vs missed calls
- Make faster, data-driven decisions

The raw data was unstructured and required cleaning before analysis.

---

## 📈 Key KPIs
- Total Calls
- Answered Calls
- Missed Calls
- Average Handle Time (AHT)
- Agent Performance Metrics

---

## 🧹 Data Cleaning & Preparation
Several data quality issues were identified and resolved:
- Incorrect date formats
- Agent first and last names stored in separate columns
- Missing and null values in the dataset

### Example Fix:
```excel
=[@[Agent_First_Name]] & " " & [@[Agent_Last_Name]]
Null values in the final rows were grouped under "Other" to maintain consistency.

---

## 🛠 Tools & Techniques Used
- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- KPI Cards
- Data Cleaning & Transformation
- Dashboard Layout & UI Design

---

## 📊 Dashboard Features
- Interactive KPI cards
- Dynamic charts connected to Pivot Tables
- Slicers for filtering by agent and date
- Clean and easy-to-read dashboard layout

---

## 📷 Screenshots
<img width="1860" height="831" alt="Screenshot 2026-01-14 141049" src="https://github.com/user-attachments/assets/d40a8e30-e67f-42d7-8855-ade05f5b160d" />

All the rest of the screenshots are available in the screenshots folder.

---

## 🚀 Key Takeaways
- Effective dashboards start with understanding the business requirements
- Clean and structured data is essential for accurate analysis
- Excel can be a powerful analytical tool, not just a spreadsheet
