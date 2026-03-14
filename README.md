# 📊 HR Attrition Analysis Dashboard

> An interactive data analytics dashboard built to analyse employee attrition patterns across departments, age groups, job roles, and salary bands.

![Dashboard Preview](https://img.shields.io/badge/Power%20BI-Project-yellow?style=flat-square&logo=powerbi)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)
![Year](https://img.shields.io/badge/Year-2025-blue?style=flat-square)
![Type](https://img.shields.io/badge/Type-Course%20Project-orange?style=flat-square)

---

## 🔍 Project Overview

This project analyses HR attrition data for **1,470 employees** to uncover why employees leave and what characterises those who stay. The dashboard is divided into **3 analytical pages**, mimicking the structure of the original Power BI report.

| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Employees Left | 237 |
| Attrition Rate | **16.1%** |
| Avg. Tenure | 7.0 years |

---

## 📁 Project Structure

```
hr-attrition-dashboard/
│
├── index.html          ← Main interactive dashboard (open in browser)
└── README.md           ← Project documentation
```

---

## 📄 Dashboard Pages

### 1. Attrition-Wise Analysis
- KPI cards: Total employees, attrition count, attrition rate, avg tenure
- Attrition by Department (Clustered Column Chart)
- Attrition by Age Group (Area Chart)
- Attrition by Gender (Pie Chart)
- Attrition by Job Role (Funnel Chart)
- Salary vs Attrition Trend (Line & Column Combo Chart)
- Department-wise attrition table with risk levels

### 2. Employee Left Company
- KPI cards: Left count, avg age, avg tenure, avg salary
- Left by Department (Clustered Column Chart)
- Left by Education Field (Bar Chart)
- Left by Marital Status (Pie Chart)
- Left by Job Level (Funnel Chart)

### 3. Employee Stayed Company
- KPI cards: Retained count, avg age, avg tenure, avg salary
- Stayed by Department (Clustered Bar Chart)
- Stayed by Job Satisfaction (Clustered Column Chart)
- Stayed by Gender (Donut Chart)
- Retained by Business Travel (Ribbon/Stacked Chart)

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Original dashboard creation |
| **HTML / CSS / JavaScript** | Web version of dashboard |
| **Chart.js** | Interactive charts |
| **DAX** | Measures & calculated columns |
| **HR Analytics Dataset** | IBM HR Attrition dataset |

---

## 💡 Key Insights

- **Sales department** has the highest attrition rate at **20.6%**
- **Single employees** are more likely to leave (120 out of 237)
- **Entry-level (Job Level 1)** employees account for **60%** of attrition
- Employees who left had a **lower average salary ($4,787)** vs those who stayed **($6,832)**
- Attrition is highest in the **26–35 age group**

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/hr-attrition-dashboard.git
   ```
2. Open `index.html` in any modern browser — no setup required.

---

## 📌 About

This project was completed as part of a **Data Analytics course in 2025**.  
It demonstrates skills in **data visualization, dashboard design, HR analytics, and data storytelling**.

---

*Built with Power BI · Data Analyst Portfolio Project · 2025*
