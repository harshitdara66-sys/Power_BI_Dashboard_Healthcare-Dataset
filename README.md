# 🏥 Healthcare Analytics Dashboard

<div align="center">

# Healthcare Analytics Dashboard using Power BI

*A professional, enterprise-grade Healthcare Business Intelligence solution built with Microsoft Power BI for hospital performance monitoring, patient analytics, billing insights, and operational reporting.*

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)
![SQL](https://img.shields.io/badge/Power%20Query-ETL-blue?style=for-the-badge)
![DAX](https://img.shields.io/badge/DAX-Measures-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge)

</div>

---

# 📌 Project Overview

This project demonstrates an end-to-end Healthcare Analytics solution developed in **Microsoft Power BI**. The dashboard converts raw hospital records into meaningful business insights using Power Query, Data Modeling, DAX, and interactive visualizations.

The solution follows a real-world Business Intelligence workflow:

* Data Cleaning
* Data Transformation
* ETL using Power Query
* Data Modeling
* DAX Measures
* Interactive Dashboard Design
* Business KPI Reporting

---

# 📊 Dashboard Preview

## Healthcare Analytics Dashboard

> Add Screenshot

![image alt](https://github.com/harshitdara66-sys/Power_BI_Dashboard_Healthcare-Dataset/blob/be1e776b71eacdc52af476f6ace321c173e10b47/Healthcare%20Analytics%20Dashboard.png)

```

---

## Billing Analytics Dashboard

> Add Screenshot

```
![image alt](https://github.com/harshitdara66-sys/Power_BI_Dashboard_Healthcare-Dataset/blob/237a10cea032597558be87a035943f1311e2b134/Billing%20Analytics.png)
```

---

## Patient Detail Dashboard

> Add Screenshot

```
![image alt](https://github.com/harshitdara66-sys/Power_BI_Dashboard_Healthcare-Dataset/blob/17b1c8d75977c157d36807a33a4ad3d6712013b8/Scre%E2%80%A2%20Patient%20Detail%20Table.png)
```

---

# 🚀 Business Problem

Hospitals generate large volumes of patient data every day.

Without a centralized dashboard it becomes difficult to monitor:

* Patient admissions
* Revenue performance
* Department workload
* Insurance claims
* Hospital utilization
* Patient stay duration
* Clinical risk
* Billing trends

This Power BI solution provides a single interactive dashboard for decision-makers.

---

# 🎯 Objectives

* Monitor hospital performance
* Analyze patient demographics
* Track medical conditions
* Evaluate department workload
* Analyze billing revenue
* Monitor insurance providers
* Improve operational decision making
* Visualize admission trends

---

# 🛠 Technology Stack

| Tool               | Purpose               |
| ------------------ | --------------------- |
| Microsoft Power BI | Dashboard Development |
| Power Query        | ETL & Data Cleaning   |
| DAX                | KPI & Measures        |
| CSV Dataset        | Data Source           |
| Data Modeling      | Relationships         |
| Excel              | Lookup Tables         |

---

# 📂 Dataset

Healthcare Dataset contains

* 55,500+ Patient Records
* Multiple Admission Years
* 6 Medical Conditions
* 6 Departments
* 5 Insurance Providers
* 8 Blood Groups
* Billing Information
* Admission & Discharge Dates
* Risk Classification

---

# 🔄 Data Preparation

The project includes complete ETL operations.

### ✔ Data Cleaning

* Removed unwanted spaces
* Trim & Clean
* Proper Case
* Upper Case
* Data Type Conversion
* Date Formatting
* Removed negative billing values

### ✔ Feature Engineering

Created custom columns:

* Patient_ID
* Billing_Amount_Fixed
* Billing_Rounded
* Admission_Year
* Admission_Month
* Admission_Month_Num
* Length_of_Stay_Days
* Age_Category
* Billing_Tier
* Stay_Category
* Risk_Flag

### ✔ Power Query Operations

* Merge Queries
* Append Queries
* Folder Connector
* Parameters
* Pivot
* Unpivot
* Group By
* Conditional Columns
* Lookup Merge
* Reference Queries

---

# 📈 Dashboard Features

## Executive Dashboard

✔ Total Patients

✔ Total Revenue

✔ Average Billing

✔ Average Length of Stay

✔ Monthly Admission Trend

✔ Insurance Distribution

✔ Hospital Revenue

✔ Medical Condition Analysis

---

## Billing Dashboard

* Department-wise Revenue
* Billing Tier Analysis
* Insurance Provider Matrix
* Revenue by Medical Condition

---

## Patient Detail Dashboard

Interactive patient-level reporting including:

* Name
* Age
* Gender
* Medical Condition
* Department
* Admission Type
* Stay Category
* Billing
* Insurance
* Test Results
* Risk Flag

---

# 📊 KPIs

| KPI                | Description                 |
| ------------------ | --------------------------- |
| Total Patients     | Number of admitted patients |
| Total Revenue      | Overall hospital billing    |
| Average Billing    | Average patient billing     |
| Average LOS        | Length of Stay              |
| Monthly Admissions | Admission trends            |
| High Risk Patients | Clinical monitoring         |
| Insurance Coverage | Provider performance        |

---

# 📈 DAX Measures

Example measures used:

```DAX
Total Patients =
COUNTROWS(healthcare_dataset)
```

```DAX
Total Revenue =
SUM(healthcare_dataset[Billing_Rounded])
```

```DAX
Average Billing =
AVERAGE(healthcare_dataset[Billing_Rounded])
```

```DAX
Average Length of Stay =
AVERAGE(healthcare_dataset[Length_of_Stay_Days])
```

---

# 🎛 Interactive Features

* Admission Type Filter
* Medical Condition Filter
* Admission Year Filter
* Cross Filtering
* Drill Down
* Navigation Buttons
* Dynamic KPI Cards

---

# 📁 Project Structure

```
Healthcare-Analytics-Dashboard
│
├── Dashboard.pbix
├── healthcare_dataset.csv
├── Condition_Dept_Lookup.csv
│
├── Images
│   ├── Healthcare Analytics Dashboard.png
│   ├── Billing Analytics.png
│   └── Patient Detail Table.png
│
├── README.md
└── LICENSE
```

---

# 💼 Business Value

This dashboard helps hospitals to:

* Improve operational efficiency
* Monitor financial performance
* Track patient admissions
* Analyze departmental workload
* Optimize insurance claim reporting
* Support data-driven decision making

---

# ⭐ Key Learning Outcomes

* Power Query ETL
* Data Cleaning
* Data Modeling
* Power BI Dashboard Design
* DAX Calculations
* Business KPI Development
* Interactive Reporting
* Healthcare Analytics

---

# 👨‍💻 Author

**Harshit Dara**

**BCA Student | Data Analyst | Power BI Developer**

### Skills

* Power BI
* SQL
* Excel
* Power Query
* DAX
* Python
* Pandas
* Data Visualization

---

# 📬 Connect

* GitHub: *Add your GitHub profile*
* LinkedIn: *Add your LinkedIn profile*
* Email: *Add your email address*

---

# ⭐ If you found this project helpful

Please consider giving the repository a **Star ⭐**.

---

<div align="center">

### Turning Healthcare Data into Actionable Insights with Power BI

**Made with ❤️ by Harshit Dara**

</div>

