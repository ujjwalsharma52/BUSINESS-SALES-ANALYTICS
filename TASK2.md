# eCommerce Customer Retention & Churn Analytics
> A data-driven analysis of 285M+ user engagement events to optimize conversion funnels and predict customer churn.

[![Data Source: Kaggle](https://img.shields.io/badge/Data%20Source-Kaggle-blue)](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store)
[![Tools Used: Python](https://img.shields.io/badge/Tools-Python%20%7C%20Power%20BI%20%7C%20Excel-orange)](https://github.com/)

---

## 📌 Project Overview
In e-commerce and subscription-based platforms, retaining a user is significantly more cost-effective than acquiring a new one. This project analyzes a massive, real-world multi-category e-commerce dataset (featuring millions of clickstream rows) to decode user behavior, track cohort retention over time, and build data-driven retention strategies.

Instead of analyzing simple contract cancellations, this project focuses on **engagement-based churn**—tracking how users transition from initial interaction (`view`) to consideration (`cart`) and ultimately to revenue (`purchase`).

### 🎯 Key Objectives
* **Cohort Analysis:** Track behavioral retention matrices across weekly/monthly sign-up cohorts.
* **Funnel Optimization:** Pinpoint exact drop-off friction points within the user purchasing journey.
* **Churn Drivers:** Identify which categories, brands, or price points correlate with rapid user inactivity.
* **Actionable Strategy:** Deliver executive-ready recommendations to improve customer lifetime value (CLV).

---

## 📊 Executive Dashboard Preview
*(Tip: Replace these placeholders with actual screenshots of your Power BI dashboard!)*

| Page 1: Retention & Executive Summary | Page 2: Churn & Drop-Off Analysis |
|---|---|
| ![Dashboard Page 1](https://via.placeholder.com/450x250.png?text=Place+Your+Dashboard+Screenshot+Here) | ![Dashboard Page 2](https://via.placeholder.com/450x250.png?text=Place+Your+Dashboard+Screenshot+Here) |

---

## 🛠️ Tech Stack & Architecture
Due to the multi-gigabyte scale of the source dataset (~9 GB for a single month), standard spreadsheet tools like Excel are insufficient for initial processing. A hybrid data architecture was implemented:

* **Data Processing & Engineering:** `Python` (Pandas/Polars) utilized for out-of-core memory management, data cleaning, and calculating cohort matrices.
* **Business Intelligence & Visualization:** `Power BI` utilized to map interactive retention trends, funnel metrics, and stakeholder dashboards.
* **Core Concepts Applied:** Advanced DAX formulas, Data Modeling (Star Schema), Funnel Analysis, Segment-level Churn Modeling.

---

## 📂 Repository Structure
```directory
├── data/
│   └── .gitkeep                 # (Raw data omitted from GitHub due to file size constraints)
├── notebooks/
│   └── data_preprocessing.ipynb # Python code for chunking, cleaning, and cohort calculations
├── dashboard/
│   └── retention_dashboard.pbix # Completed Power BI Dashboard file
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation