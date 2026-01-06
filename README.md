# 💊 Indian Pharmaceutical Market Analysis
### *Data-Driven Insights using Excel*

## 📌 Project Overview
The Indian pharmaceutical industry includes thousands of products across diverse therapeutic classes and pricing segments.  
This project analyzes a **large-scale pharmaceutical dataset** to uncover:

- Medicine pricing trends  
- Manufacturer dominance  
- Product discontinuation patterns  
- Therapeutic class insights  

The objective is to support **competitive analysis and pricing strategy decisions** using data-driven insights.

---

## 🎯 Project Objectives
- Understand medicine pricing patterns  
- Identify top manufacturers and market leaders  
- Analyze product discontinuation trends  
- Provide actionable business recommendations  

---

## 📂 Dataset Overview
- **Source:** Kaggle – Indian Pharmaceutical Products Dataset  
- **Total Records:** 153,972  

### Key Fields
| Column Name | Description |
|------------|------------|
| brand_name | Medicine name |
| manufacturer | Producing company |
| price_inr | Price in INR |
| dosage_form | Tablet, syrup, etc. |
| primary_ingredient | Key component |
| therapeutic_class | Drug category |
| is_discontinued | Product availability |

---

## 🧹 Data Cleaning & Preparation
Performed using **Excel – Power Query Editor**:

- Removed unnecessary index columns  
- Handled missing values (pack size, unit, strength)  
- Removed duplicate records and null brand names  
- Standardized text (TRIM, Proper Case)  
- Filtered invalid prices (`price_inr ≤ 0`)  
- Split packaging details into `pack_size` and `pack_unit`  
- Ensured correct data types for all columns  

---

## 💰 Price Categorization
Created a `Price_Group` column for affordability analysis:

| Price Group | Range (INR) |
|------------|-------------|
| Very Low | < ₹50 |
| Low | ₹50 – ₹100 |
| Medium | ₹101 – ₹200 |
| High | ₹201 – ₹500 |
| Very High | > ₹500 |

Used as a **slicer** in the Power BI dashboard.

---

## 📊 Data Analysis & Dashboard Design
### 🛠 Tools Used
- Microsoft Excel  
- Power BI  

### 📈 Key Visuals
- KPI Cards: Total Products, Average Price, % Discontinued  
- Bar Chart: Top 10 Manufacturers  
- Pie Chart: Distribution by Dosage Form  
- Column Chart: Avg Price by Therapeutic Class  
- Scatter Plot: Price vs Pack Size  
- Slicers: Price Group, Therapeutic Class  

---

## 🔍 Key Insights
- **Top Manufacturers:** Sun Pharma, Cipla, GSK  
- **Price Distribution:** ~60% of medicines priced below ₹200  
- **Dosage Form:** Tablets account for over 70%  
- **Therapeutic Class:** Antibiotics dominate market share  
- **Premium Segment:** >₹500 drugs are mainly specialized therapies  
- **Discontinuation Rate:** ~3%  

---

## 💡 Business Recommendations
- Focus on **₹50–₹200 mass-market pricing**  
- Increase R&D in **antibiotics and antihistamines**  
- Standardize packaging to reduce costs  
- Monitor pricing in price-sensitive categories  
- Use dashboards for continuous market tracking  

---

## 🚀 Conclusion & Next Steps
This project demonstrates how **Excel and Power BI** convert raw pharmaceutical data into actionable business insights.

### Future Enhancements
- Integrate sales & regional data  
- Automate using Azure SQL  
- Apply AI-based price forecasting  

---

## 🙌 Acknowledgements
- Dataset: Kaggle – Indian Pharmaceutical Products Dataset  
- Tools: Microsoft Excel & Power BI  
