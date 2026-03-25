# Sales-Performance-Dashboard-project
Excel  dashboard analyzing retail sales trends and customer behavior
# Sales Performance Dashboard

## Project Goal
Analyse retail sales data to identify trends, top customers, and key drivers of revenue. Answer business questions and generate actionable insights.

## Sample Questions Addressed
1. Compare sales and orders by month using a single chart  
2. Which month got the highest sales and orders?  
3. Who purchased more – men or women in 2022?  
4. What are the different order statuses in 2022?  
5. Top 10 states contributing to sales  
6. Relation between age and gender based on number of orders  
7. Which channel contributed to maximum sales  
8. Highest selling category

## Data Cleaning & Preprocessing
- Standardized **Gender** column: M → Men, W → Women  
- Standardized **Quantity** column: One → 1, Two → 2  
- Created **Age Group** column using: `=IF(F2>=50,"Senior", IF(F2>=30,"Adult","Teenager"))`  
- Created **Month** column: `=TEXT(G3, "mmm")` to analyze sales trends by month

## Data Analysis
- Pivot tables and combined charts used to analyse sales trends by month  
- Pie charts to compare men vs women purchases and order status distribution  
- Bar charts for top contributing states  
- Column charts for relation between age, gender, and number of orders  
- Pie charts for sales channel contribution  
- Slicers added for interactive dashboard reporting

## Sample Insights
- Women are more likely to purchase than men (~64%)  
- Maharashtra, Karnataka, and Uttar Pradesh are the top 3 contributing states  
- Adults aged 30–49 years are the highest contributing group (~50%)  
- Amazon, Flipkart, and Myntra generate the maximum sales

## Conclusion & Recommendations
- Prioritize women aged 30–49 in Maharashtra, Karnataka, and Uttar Pradesh with targeted marketing  
- Retarget male and teenage customers through category-specific campaigns  
- Plan off-season sales (Aug–Nov) to balance yearly performance

## Files
- `Dataset/sales_data.xlsx` – Raw data  
- `Dashboard/Sales_Dashboard.xlsx` – Pivot tables and charts  
- `Screenshots/charts_overview.png` – Dashboard overview
