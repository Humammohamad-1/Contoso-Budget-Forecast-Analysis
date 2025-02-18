# Budget and Forecast Analysis in Power BI 📊

## 📌 Project Overview
This Power BI project analyzes **budget, forecast, and actual financial data** to track financial performance.  
It helps compare **planned (budget)**, **expected (forecast)**, and **actual results** over time.

## 📊 Dataset Description
The dataset follows a **star schema**, consisting of:

### **Fact Table**
- **FactStrategyPlan**: Contains financial figures for different scenarios (Actual, Budget, Forecast).

### **Dimension Tables**
- **DimAccount**: Financial accounts.
- **DimDate**: Date hierarchy for time-based analysis.
- **DimEntity**: Business entities (regions, branches).
- **DimProductCategory**: Product classification.
- **DimScenario**: Types of financial planning (Actual, Budget, Forecast).

---

## 📈 Analysis Conducted

### **1️⃣ Budget vs. Forecast vs. Actual Analysis**
- A **table visualization** showing comparisons across **categories** (Audio, Cameras, Cell Phones, etc.).
- Summarizes **Actual vs. Budget vs. Forecast** performance.

### **2️⃣ Financial Performance Over Time**
- A **bar chart** showing **total financial figures per quarter and year**.
- **Hierarchy added** ➝ Users can drill down from **Year** ➝ **Quarter** ➝ **Month**.

### **3️⃣ Account Type & Product Breakdown**
- A **stacked bar chart** comparing **Income, Expenses, and Taxation** by product categories.
- Helps in understanding which categories contribute to profit and loss.

---

## 🔧 Power BI Features Used
✅ **Hierarchies** ➝ **Drill-down** enabled for better time-based exploration.  
✅ **Filters & Slicers** ➝ Allow users to filter by **Scenario (Actual, Budget, Forecast)** and **Time Period**.  
✅ **Conditional Formatting** ➝ Visual differences between Actual, Budget, and Forecast.  
✅ **Interactive Visualizations** ➝ Users can click and drill down to details.

---

## 📸 Power BI Dashboard Preview
![Budget Breakdown]![image](https://github.com/user-attachments/assets/c4a822be-6633-42e6-a7b2-66257a1990fb)



