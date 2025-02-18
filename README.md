# Budget and Forecast Analysis in Power BI 📊

## 📌 Project Overview
This Power BI project analyzes **budget, forecast, and actual financial data** to track **financial performance** and identify **key business insights**.  
It helps compare **planned (budget)**, **expected (forecast)**, and **actual results** over time, enabling businesses to **make data-driven financial decisions**.

---

## 📊 Business Case: Strategic Financial Planning & Variance Analysis
### **Context**
In a fast-paced business environment, companies must track and compare **planned budgets, financial forecasts, and actual revenue/expenses**.  
This Power BI report allows **finance teams, executives, and business strategists** to **monitor financial performance, identify variances, and optimize resource allocation**.

### **Business Questions Addressed**
- 🔹 **How does actual financial performance compare to budgeted and forecasted values?**  
- 🔹 **Are there any major deviations from planned financial targets?**  
- 🔹 **Which product categories contribute the most to revenue and expenses?**  
- 🔹 **What are the key cost drivers, and how can we optimize spending?**  

This dashboard enables **data-driven financial decision-making**, helping businesses **adjust forecasts, control costs, and improve financial performance**.

---

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

## 📈 Key Insights from the Data

### **1️⃣ Budget vs. Forecast vs. Actual Analysis**
- 💰 **Budget vs. Actual Variance**: The actual revenue is **higher than the forecasted amount**, indicating **stronger-than-expected performance**.
- 📉 **Spending Overshoots**: Some expense categories exceed the **budgeted limits**, requiring **cost optimization strategies**.
- 📊 **Profitability Gaps**: The **gap between budget and forecasted revenue suggests cautious financial planning** or market fluctuations.

### **2️⃣ Financial Performance Trends**
- 📅 **Quarterly & Yearly Insights**: The bar chart **shows stable financial performance over time**, but **quarterly fluctuations indicate seasonality effects**.
- 🔄 **Drill-Down Capabilities**: By enabling **hierarchy navigation** (Year → Quarter → Month), finance teams can **pinpoint trends and performance anomalies** at different time levels.

### **3️⃣ Account Type & Product Breakdown**
- 🛒 **Top Revenue Contributors**: Some **product categories drive the majority of income**, helping prioritize profitable segments.
- 📊 **Expense Management**: The breakdown of **expenses vs. taxation vs. revenue** enables financial managers to **understand cost allocation and optimize spending**.
- 📍 **Strategic Cost Reduction**: Certain product categories **show higher-than-expected expenses**, which might indicate **inefficiencies or pricing strategy adjustments needed**.

---

## 🔧 Power BI Features Used
✅ **Hierarchies & Drill-Downs** ➝ Enables deeper exploration (Year → Quarter → Month).  
✅ **Filters & Slicers** ➝ Allow users to filter by **Scenario (Actual, Budget, Forecast)** and **Time Period**.  
✅ **Conditional Formatting** ➝ Highlights differences between Actual, Budget, and Forecast.  
✅ **Interactive Visualizations** ➝ Clickable reports with dynamic insights.  

---

## 📸 Power BI Dashboard Preview

![Dashboard Preview]![image](https://github.com/user-attachments/assets/5fe45e2a-0879-46a5-9f51-a0ea284b4e53)



