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
