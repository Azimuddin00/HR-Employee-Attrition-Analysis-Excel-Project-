# 📊 HR Employee Attrition Analysis (Excel Project)

## 🧾 Overview
The **HR Employee Attrition Analysis** project explores the factors influencing employee attrition within an organization using **Microsoft Excel**.  
This project demonstrates complete **data cleaning, transformation, analysis, and dashboard development**, helping HR professionals make data-driven decisions to improve employee retention.

---

## 📂 Dataset Information
The dataset includes details about employees’ demographics, job roles, satisfaction levels, and work-life balance.  
It identifies whether employees are still with the company or have left, allowing for analysis of attrition patterns.

### Sheets in the Excel File:
| Sheet Name | Description |
|-------------|-------------|
| `Raw data` | Original employee dataset containing various HR parameters. |
| `Hr Transfered data` | Cleaned and transformed version with additional calculated fields. |
| `Analysis` | Aggregated data showing attrition metrics and departmental summaries. |
| `Dashboard` | Interactive Excel dashboard with visual insights and slicers. |

---

## 🧹 Data Cleaning & Preparation
Performed extensive cleaning and transformation to prepare the dataset for analysis:

1. **Removed duplicates and blanks** to ensure accuracy.  
2. **Renamed and standardized columns** for consistency.  
3. **Added calculated fields**, including:
   - `CF_attrition label` — identifies current vs ex-employees  
   - `Age Buckets` — groups employees by age  
   - `Performance Status` — categorizes performance (High / Low)  
   - `Working Year Group` — groups employees by experience range  
4. **Applied conditional formatting** to highlight key patterns visually.

---

## 📊 Data Analysis
Analysis focused on discovering:
- Attrition rates across departments and age groups  
- Relationship between job satisfaction, performance, and attrition  
- Gender-based attrition distribution  
- Work-life balance impact on retention  

Formulas and tools used:
- `COUNTIF`, `AVERAGEIFS`, `IF`, and `VLOOKUP` for metrics  
- **Pivot Tables** for grouped summaries  
- **Charts & Slicers** for interactivity  

---

## 📈 Dashboard Features
The interactive Excel **Dashboard** includes:
- ✅ Total employees and attrition percentage  
- 📊 Attrition by department, age group, and gender  
- 📉 Attrition vs. performance & satisfaction  
- 🎯 Visual KPIs and slicers for dynamic filtering  

This dashboard provides a quick overview of workforce dynamics and key retention indicators.

---

## ⚙️ Methods & Tools Used
| Category | Techniques / Tools | Purpose |
|-----------|-------------------|----------|
| Data Cleaning | Remove Duplicates, Filters | Ensure data integrity |
| Data Transformation | Excel Formulas & Derived Columns | Create new insights |
| Analysis | Pivot Tables, Charts, Conditional Formatting | Identify attrition patterns |
| Visualization | Excel Dashboard with Slicers | Present insights interactively |
| Tools | Microsoft Excel | End-to-end analysis |

---

## 💡 Key Insights
- Highest attrition observed in **Sales** and **R&D** departments.  
- Employees aged **25–34** show the most turnover.  
- **Low job satisfaction** and **frequent travel** increase attrition likelihood.  
- Balanced **work-life satisfaction** improves retention significantly.  

---

## 📁 Project Structure

📦 HR-Employee-Attrition-Analysis  
┣ 📄 HR Dataset.xlsx  
┣ 📊 Dashboard  
┣ 📈 Analysis  
┗ 📜 README.md

