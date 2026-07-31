# 🚲 Bike Sales Dashboard — Excel Data Analytics Project

An interactive Excel dashboard analyzing customer purchase behavior for a bike retailer, built with Pivot Tables, Slicers, and dynamically linked KPI cards.

![Excel](https://img.shields.io/badge/Tool-Excel-217346?logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 📌 Project Overview

This project transforms a raw customer dataset (1,000 records) into a decision-ready, interactive dashboard. The goal was to move beyond static charts and build something a real business stakeholder could use to filter, explore, and draw insights from customer purchasing behavior in real time.

**Business question explored:** *What customer characteristics (income, age, region, education, marital status, commute distance) are associated with a higher likelihood of purchasing a bike?*

---

## 🖼️ Dashboard Preview

![alt text](image-1.png)

---

## 🔑 Key Features

- **Live KPI Cards** — Total Customers, Purchase Rate, Average Income, and Bikes Sold, all dynamically linked to Pivot Table data using `GETPIVOTDATA`
- **Fully Interactive Slicers** — Filter by Marital Status, Region, and Education Level; every chart and KPI updates instantly and in sync
- **Multi-dimensional Analysis** — Purchase patterns broken down by:
  - Gender vs. Average Income
  - Age Brackets (Adolescent / Middle Age / Old Age)
  - Commute Distance
- **Error-Proof Formulas** — `IFERROR` handling prevents `#DIV/0!` errors when filters return zero matching records
- **Clean Visual Design** — Consistent color palette, custom typography, no gridlines, subtle background styling, and aligned card layout

---

## 🛠️ Tools & Techniques Used

| Category | Details |
|---|---|
| **Software** | Microsoft Excel (2019) |
| **Data Analysis** | Pivot Tables, Pivot Charts, GETPIVOTDATA |
| **Interactivity** | Slicers with multi-pivot Report Connections |
| **Formulas** | GETPIVOTDATA, IFERROR, dynamic cell linking |
| **Design** | Custom shape styling, grouped objects, conditional number formatting, dynamic (formula-linked) titles |

---

## 📂 Repository Structure

```
bike-sales-dashboard/
│
├── README.md                        
├── Excel_Project_Dashboard.xlsx     
├── data/
│   └── bike_buyers_raw.csv          
├── images/
│   └── dashboard_preview.png        
└── LICENSE                          
```

---

## 📊 Dataset

- **Source:** Bike Buyers dataset (customer demographic + purchase data)
- **Records:** 1,000 customers
- **Fields include:** Marital Status, Gender, Income, Region, Education, Occupation, Age, Commute Distance, and Purchased Bike (Yes/No)

> Note: This dataset is used for educational/portfolio purposes only.

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `Excel_Project_Dashboard.xlsx` in Microsoft Excel (2016 or later recommended for full Slicer/Pivot compatibility)
3. Go to the **Dashboard** sheet
4. Use the **Marital Status**, **Region**, and **Education** slicers to filter the data — all charts and KPI cards update live
5. Explore the **Pivot Table** sheet to see the underlying calculations feeding the dashboard

---

## 📈 Key Insights

- Customers with higher income showed a higher likelihood of purchasing a bike, across both genders
- The "Middle Age" bracket represented the largest share of both buyers and non-buyers
- Shorter commute distances (0–2 miles) correlated with higher bike purchase counts

---

## 🎯 What I Learned

- Structuring dynamic reports with Pivot Tables and `GETPIVOTDATA` instead of static cell references
- Connecting multiple Pivot Tables to a single set of Slicers for synchronized, dashboard-wide filtering
- Applying visual design discipline (alignment, color consistency, spacing) to make a spreadsheet output feel like a professional BI tool
- Handling formula edge cases (e.g., `#DIV/0!`) so a dashboard stays reliable under any filter combination

---

## 📬 Connect

If you have feedback, suggestions, or just want to connect — I'd love to hear from you.

**[LinkedIn](www.linkedin.com/in/aayan-mansoori-a47a03362) | [Email](mdayaanmansoori4@gmail.com)**

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
