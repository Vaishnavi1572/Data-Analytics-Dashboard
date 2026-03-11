# Karnataka Crop Production Insights Dashboard (Using Microsoft Excel & Power BI)

---

# 1️⃣ Project Overview

## 🎯 Business Problem

The primary goal of this project was to analyze **agricultural production data from Karnataka** to understand crop productivity, rainfall influence, and revenue generation across different regions.

The business problem focused on:

**“Understanding crop production trends, rainfall impact, and crop efficiency to improve agricultural productivity and resource allocation.”**

Agricultural performance varies widely based on **soil type, rainfall, and crop selection**, making it difficult for stakeholders to identify high-performing crops and regions.

The project aims to provide a **data-driven solution** to:

• Identify high-performing crops  
• Analyze rainfall impact on production  
• Evaluate soil productivity  
• Compare regional revenue performance  
• Support decision-making using an interactive dashboard  

This project transforms raw agricultural data into **actionable insights for improved farming strategies and resource planning**.

---

# 2️⃣ 🗂️ Data Source

📌 **Source:**  🔗 **Mendeley Dataset:**  
https://data.mendeley.com/datasets/nfj84km5fz/1/files/8dc6b376-db39-4bd8-acfc-bfbdc0a911a1
📁 **Dataset:** Karnataka Agricultural Crop Dataset  
📊 **Size:**

• 1,000+ agricultural records  
• 10+ attributes

---

## 🔑 Key Variables

| Column Name | Description |
|-------------|-------------|
| Year | Agricultural production year |
| Location | District or region |
| Crop Type | Type of crop grown |
| Area | Area used for cultivation |
| Rainfall | Annual rainfall in region |
| Temperature | Average temperature |
| Soil Type | Type of soil |
| Irrigation | Irrigation availability |
| Yield | Crop yield |
| Humidity | Environmental humidity |
| Production | Total crop production |
| Revenue | Total revenue generated |

The dataset provides **detailed agricultural performance metrics across crops, regions, and environmental factors.**

---

# 3️⃣ 🛠️ Tools & Technologies

| Component | Technology Used |
|-----------|----------------|
| Language | DAX (Data Analysis Expressions) |
| Data Processing | Microsoft Excel |
| Visualization | Power BI |
| Documentation | Microsoft Word |

---

## 🔧 Excel

• Data cleaning  
• Removing duplicates  
• Handling missing values  
• Pivot table analysis  
• Feature engineering  

---

## 📊 Power BI

• Data modeling  
• DAX calculations  
• Interactive dashboards  
• KPI cards and charts  
• Forecast analysis  

---

# 4️⃣ 🧹 Data Cleaning & Preparation

Before performing analysis, several preprocessing steps were completed.

---

### ✔️ Handling Missing Values

• Checked dataset for null values  
• Replaced missing values in **Soil Type** with **"Unknown Soil Type"**

---

### ✔️ Removing Duplicates

• Identified duplicate rows  
• Removed redundant records

---

### ✔️ Data Type Formatting

• Converted **Year** to numeric format  
• Converted **Rainfall, Yield, Production, Revenue** to numeric values  
• Standardized categorical columns

---

### ✔️ Feature Engineering (New Calculated Columns)

**Total Production**

Production calculated based on crop yield and area.

**Revenue per Area**

Revenue per Area = Revenue / Area

**Production Efficiency**

Production Efficiency = Production / Area

**Rainfall Category**

Rainfall levels categorized as:

• Low Rainfall  
• Medium Rainfall  
• High Rainfall  

These calculated columns helped improve **data analysis and visualization accuracy.**

---

# 5️⃣ 🔍 Exploratory Data Analysis (EDA)

## Main Questions Explored

📈 What is the **year-wise agricultural revenue trend**?

🌧️ How does **rainfall impact crop production**?

🌾 Which **soil types produce higher yields**?

📍 Which **locations generate the highest agricultural revenue**?

🌱 Which **crop types show better production efficiency**?

---

# 6️⃣ 💡 Key Insights

🔹 **Insight 1:** Sandy Loam and Alluvial soil types produce the highest crop yield.

🔹 **Insight 2:** Crop production is significantly higher during **high rainfall periods**.

🔹 **Insight 3:** Some locations such as **Hassan generate the highest revenue**, indicating strong agricultural productivity.

🔹 **Insight 4:** **Cotton shows the highest production efficiency** compared to other crops.

🔹 **Insight 5:** Agricultural revenue shows moderate growth but fluctuates depending on rainfall and environmental conditions.

---

# 7️⃣ 🚀 Recommendations

Based on the analysis:

---

📌 **1. Promote High-Efficiency Crops**

Encourage cultivation of crops with higher production efficiency such as **Cotton**.

---

📌 **2. Improve Irrigation in Low Rainfall Regions**

Invest in irrigation infrastructure to reduce dependency on rainfall.

---

📌 **3. Optimize Soil Usage**

Encourage crop selection based on **soil suitability** to improve yield.

---

📌 **4. Support Low Performing Regions**

Introduce agricultural support programs in regions with lower revenue and production.

---

📌 **5. Improve Agricultural Planning**

Use data-driven insights for **better crop planning and resource allocation**.

---

# 8️⃣ ⚙️ How to Use This Project

## 📥 Requirements

• Microsoft Excel  
• Power BI Desktop  
• Dataset file  

---

## 📌 Steps to Run

1. Open the **Excel dataset**.
2. Perform **data cleaning if required**.
3. Load the dataset into **Power BI Desktop**.
4. Create relationships between tables (if modeled).
5. Create **DAX measures**.
6. Build **dashboard visualizations**.
7. Use **slicers and filters for interactive analysis**.

---

## 📦 DAX Sample Measures

```
Total Revenue = SUM(Data[Revenue])

Total Production = SUM(Data[Production])

Average Yield = AVERAGE(Data[Yield])

Production Efficiency =
DIVIDE(
SUM(Data[Production]),
SUM(Data[Area])
)
```

---

# 9️⃣ Conclusion

This project demonstrates how raw agricultural data can be transformed into **meaningful insights using modern analytics tools**.

The solution combines:

• **Microsoft Excel** for data cleaning and preparation  
• **Power BI** for interactive dashboards  
• **DAX** for advanced calculations  

The dashboard enables stakeholders to:

• Monitor agricultural productivity  
• Understand rainfall impact on crop production  
• Identify high-performing crops  
• Support data-driven agricultural planning  

Overall, this project highlights the power of **data analytics in improving agricultural decision-making and resource optimization.**

---

👩‍💻 **Author**

Vaishnavi T  
Data Analyst | Power BI | Excel | Data Visualization
