
# 📊 Sales Performance and Trend Analysis

## 📌 Project Overview
This project analyzes historical sales data from the **Microsoft Financial Sample dataset** to identify trends, evaluate sales performance, and predict future revenue growth. It uses **Power BI** to create interactive dashboards and visualizations.

## 🔍 Objectives
- Analyze key sales metrics, including **Total Sales, Profit, and Revenue Trends**.
- Identify **top-performing products, regions, and customer segments**.
- Forecast future sales using **historical data and growth assumptions**.
- Provide actionable insights for **improving business decision-making**.

## 📈 Key Features  
✅ **Sales & Profit Analysis** – KPI Cards  
✅ **Sales Trends Over Time** – Line Chart  
✅ **Profit Margin by Product** – Pie Chart  
✅ **Sales Forecasting** – Using a **10% growth assumption**  
✅ **Interactive Filters** – Segment & Country slicers  

## 📂 Dataset Information

- **File**: `Financial_Sample.xlsx`  
- **Source:** Microsoft Financial Sample (Excel)
- **Columns Used:**
  - Date
  - Product Category
  - Sales Amount
  - Profit
  - Discount
  - COGS (Cost of Goods Sold)
  - Country/Region

## 🛠️ Tools & Technologies

- **Power BI**: Data visualization and dashboard creation
- **DAX (Data Analysis Expressions)**: Custom calculations and forecasting
- **Excel**: Data preprocessing and cleaning

## 📈 Key Analysis & Insights

### **Sales Trends Over Time**
- Monthly and yearly sales trends were analyzed.
- Seasonal patterns in revenue were identified.

### **Top Products & Regions**
- The most profitable product categories were identified.
- Sales distribution across different regions was compared.

### **Sales Forecasting**
- A **10% annual sales growth** assumption was used to project future revenue.
- DAX formula used:
  ```DAX
  Sales Forecast = 
  VAR LastYearSales = CALCULATE( [Total Sales], SAMEPERIODLASTYEAR( 'Financial Sample'[Date] ) ) 
  RETURN LastYearSales * 1.1  -- Assuming a 10% growth rate

### ** Profitability Analysis**
Profit margins for different products and regions were calculated.
High-profit but low-sales regions were identified for potential investment.

### ** Power BI Dashboard Screenshots









🚀 How to Use This Project

Clone the repository  
   ```bash
   git clone https://github.com/yourusername/PowerBI-Projects.git
                  or
Download the Financial Sample.xlsx dataset from the Data folder.
Open the Power BI report (.pbix file) from the Reports folder.
Explore the visualizations and insights.

🤝 Contributing
If you have suggestions or improvements, feel free to fork this repository and submit a pull request.

📌 Author
[Vijayalakshmi Veeraiyan]
LinkedIn Profile  www.linkedin.com/in/
vijayalakshmi-veeraiyan-viji-6761421a1

