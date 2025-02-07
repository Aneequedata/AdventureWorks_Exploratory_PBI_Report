# 📊 AdventureWorks Power BI Report
A comprehensive, interactive Power BI report designed for **sales performance analysis, customer insights, and product profitability tracking** using **advanced DAX calculations, Power Query transformations, dynamic navigation, and parameterized what-if analysis**.

---

## 📂 Data Sources & Preprocessing

### **Datasets Used:**
- **Sales Data (2020-2022)**
- **Customer Lookup**
- **Product & Category Lookup**
- **Territory Data**
- **Returns Data**
- **Dynamically Generated Calendar Table**

### **Power Query Transformations:**
- **Data Cleaning & Standardization**
- **Feature Engineering:** SKU Classification, Start of Quarter, Aggregated Metrics
- **Hierarchical Structuring:** Category → Subcategory → Product
- **Time Intelligence Preparation:** Automated week, month, quarter, and YTD calculations

---

## 📌 Data Modeling & Relationships
- **Optimized Star Schema** with **fact and dimension tables**
- **One-to-Many Relationships:**  
  - Sales → Customers, Products, Calendar, Territories  
- **Hierarchical Drill-Downs** for **regional & product-based analysis**
- **Cross-filtering Enabled** where necessary for **accurate aggregations**

---

## 📌 Advanced DAX Calculations
### **Time Intelligence Measures**
- **Previous Month & YTD Revenue/Profit Analysis**
- **Rolling Averages & Running Totals (10-day, 90-day)**
- **Revenue Growth Rate Comparisons**

### **Customer & Product Insights**
- **Revenue Per Customer Segmentation**
- **Top Customer & Product Ranking Calculations**
- **Customer Lifetime Value Estimations**

### **Financial & Performance Metrics**
- **Dynamic Sales & Profit Target Adjustments**
- **Custom Order & Return Rate Metrics**
- **Profitability Variance & Performance Tracking**

---

## 📌 Price Adjustment Parameter (What-If Analysis)
- A **Price Adjustment (%) parameter** is implemented in the **Product Detail View**
- **Dynamically recalculates revenue, profit, and returns** when adjusting the slider
- Helps **simulate pricing strategies** to evaluate the impact on revenue & profitability

---

## 📌 Navigation & Custom Tooltips
- **Dynamic Page Navigation with Buttons & Bookmarks**
- **Custom Tooltip Pages for Detailed Insights**
- **Drill-through Pages for Interactive Data Exploration**

---

## 📊 Power BI Report Features

### 📈 **Executive Dashboard**
- Revenue, Profit, Orders, Return Rate KPIs
- Monthly & Yearly Revenue Trends
- Revenue & Profit Target Gaps

### 🗺️ **Regional Sales Performance**
- Sales by **Continent, Country, & Territory**
- **Interactive Map Visualization & Drill-Downs**

### 👥 **Customer Analysis**
- Customer segmentation by **Occupation & Income Level**
- Revenue per Customer & **Top 100 Customers**

### 🛍️ **Product Performance**
- **Top-performing products & return rates**
- **Dynamic Price Adjustment Impact Analysis**
- **Revenue and Profit Fluctuation Simulation**

### 📉 **Returns Analysis**
- High return **products & categories**
- **Monthly Return Trends & Comparisons**

### 🔄 **Interactive Features**
- **Navigation Pane with Page Selection Buttons**
- **Drill-through Pages for Customer & Product Details**
- **Custom Tooltips for Enhanced Data Context**


### **Retracing File Paths for Analysis**
- If you need to **modify or reload the data**, ensure your local file paths match the Power Query source paths.
- Navigate to **Transform Data → Advanced Editor** in Power BI to locate the **original file paths** used for data import.
- Adjust the paths to your local system and **refresh the dataset** to replicate the analysis in your own environment.

---

## ⚙️ Tech Stack
- **Power BI** (Data Modeling, DAX, Visualizations)
- **Power Query (ETL & Data Transformation)**
- **DAX (Custom Measures, Time Intelligence, Aggregations)**

---

## 📌 Repository Contents
📁 **AdventureWorks.pbix** → Power BI Report  
📂 **Datasets/** → Processed CSVs  
📜 **README.md** → Project Documentation  

---

## 🚀 Future Enhancements
- **🔗 SQL Integration for Live Data Updates**
- **📈 Predictive Analytics & Forecasting**
- **🧠 AI-powered Insights (Power BI AI Visuals)**


---

## 📬 Contact
💼 **LinkedIn:** [(https://www.linkedin.com/in/aneeque-data/)]  
📧 **Email:** [aaneequemushtaque@gmail.com]  
 
