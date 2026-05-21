# Retail Sales Data Cleaning (Excel)

## 📌 Project Overview
This project focuses on cleaning, standardizing, and preparing a retail sales dataset using **Microsoft Excel**.  
The dataset contained common real‑world issues such as inconsistent formatting, missing values, incorrect data types, and duplicated records.  
The final output is a clean, analysis‑ready dataset suitable for dashboards, reporting, and further analytics work.

---

## 🧹 Cleaning Tasks Performed

### ✔ Data Standardization
- Normalized column names  
- Standardized date formats  
- Cleaned inconsistent text fields (regions, categories, channels)  
- Converted numeric fields stored as text into proper number formats  

### ✔ Data Quality Fixes
- Removed duplicate rows  
- Identified and corrected invalid or missing values  
- Repaired broken formulas  
- Fixed trailing spaces, inconsistent casing, and hidden characters  

### ✔ Business Logic Validation
- Verified category ↔ product alignment  
- Ensured discounts were within valid ranges  
- Checked for negative quantities or prices  
- Flagged outliers for manual review  

### ✔ Feature Enhancements
- Added calculated fields (e.g., Revenue = Quantity × Unit Price × (1 − Discount))  
- Created helper columns for filtering and validation  
- Added conditional formatting to highlight data quality issues  

---

## 📁 Repository Structure

```
excel-data-cleaning/
│
├── data/
│   ├── _raw/
│   │   └── Retail_Sales_Transactions_2024-2025_raw.xlsx
│   └── cleaned/
│       └── Retail_Sales_Transactions_2024-2025_clean.xlsx
│
├── documentation/
│   └── data_dictionary.md
│
└── README.md
```

---

## 🛠 Tools Used
- Microsoft Excel  
- Power Query (optional)  
- Data Validation  
- Conditional Formatting  
- PivotTables (for verification)

---

## 🚀 Outcome
The final cleaned dataset is:

- Fully standardized  
- Validated against business rules  
- Free of duplicates and formatting issues  
- Ready for use in Power BI, Tableau, Python, or Excel dashboards  

This project demonstrates practical Excel‑based data cleaning skills used in real analytics workflows.


