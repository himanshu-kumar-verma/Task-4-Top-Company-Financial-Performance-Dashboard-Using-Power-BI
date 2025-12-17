# 📊 Company Financial Performance Dashboard | Power BI

## 🔹 One-Line Summary
An interactive Power BI dashboard analyzing company financial performance across sales, profit, market value, assets, and countries using Power Query and DAX.


## 📌 Overview
This project focuses on analyzing financial data of companies to understand overall performance, profitability, and regional distribution.  
The dashboard provides high level KPIs and detailed visual insights to help identify top performing companies and country wise financial trends.


## ❓ Problem Statement
Organizations often struggle to quickly understand financial performance across multiple metrics and regions.  
The goal of this project is to transform raw financial data into a clear, interactive dashboard that supports data driven decision making.


## 📂 Dataset
The dataset includes the following columns:
- Company ID
- Company Name
- Sales
- Profit
- Market Value
- Assets
- Country

> Note: Financial values were originally stored as text (e.g., `$345B`, `$1.2T`) and required transformation.


## 🛠 Tools & Technologies
- **Power BI Desktop**
- **Power Query** – Data cleaning and transformation
- **DAX (Data Analysis Expressions)** – Measures and KPIs
- **Excel / CSV** – Data source


## 🔄 Data Cleaning & Transformation
- Removed currency symbols and text indicators (B, T)
- Converted financial values into numeric format
- Handled division by zero scenarios
- Verified correct data types for all columns
- Ensured consistent and clean column naming


## 📐 Data Modeling & Measures
Created DAX measures for accurate and dynamic analysis:
- Total Sales
- Total Profit
- Total Market Value
- Total Assets
- Total Companies
- Profit Margin % (calculated using total profit divided by total sales)

> Profit margin was implemented as a **DAX measure** to avoid incorrect aggregation of row level values.


## 📊 Dashboard & Visualizations
The dashboard includes:
- KPI Cards for key financial metrics
- Top 10 Companies by Sales
- Top 10 Companies by Profit
- Sales vs Profit Scatter Plot
- Country wise Sales Map
- Market Value Distribution by Country
- Interactive slicers for country and company filtering


## 🔍 Key Insights
- Identified top-performing companies based on sales and profitability
- Compared sales performance against profit to evaluate efficiency
- Analyzed regional contribution to overall sales and market value
- Highlighted differences between asset size and market valuation


## 📈 Results & Conclusion
The dashboard successfully converts complex financial data into actionable insights.  
It enables quick comparison of company performance, supports regional analysis, and demonstrates effective use of Power BI for business intelligence.


## 🚀 How to Run This Project
1. Download the `.pbix` file from this repository
2. Open it using **Power BI Desktop**
3. Refresh data (if required)
4. Interact with slicers and visuals to explore insights


## 🔮 Future Enhancements
- Add year-wise trend analysis (if time data is available)
- Implement advanced financial ratios
- Improve dashboard design with custom themes
- Publish dashboard to Power BI Service


## 👤 Author
**Himanshu Kumar Verma**  

📧 Email: himanshukumarverma719@gmail.com  

🔗 LinkedIn: https://www.linkedin.com/in/himanshu-kumar-verma2003

💻 GitHub: https://github.com/himanshu-kumar-verma
