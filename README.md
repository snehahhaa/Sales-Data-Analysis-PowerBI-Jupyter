# Sales-Data-Analysis-PowerBI-Jupyter
This project explores real-world sales data using Python (pandas, matplotlib) and Power BI to uncover business insights from a US-based electronics retailer.

## Project Files

- `Sales Analysis.ipynb` — Python Jupyter Notebook with complete data cleaning and analysis  
- `Electronic Sales Data Analysis.pbix` — Interactive Power BI Dashboard for quick insights

## Objective

To analyze 12 months of sales data and answer key business questions that can help improve marketing strategies, product offerings, and operations.

## Tools Used

- Python Libraries: pandas, matplotlib, itertools, collections  
- Power BI: For interactive visualizations  
- Jupyter Notebook: For exploratory data analysis (EDA)

## Steps Performed

1. Data Collection: Merged 12 monthly CSV files into a single dataset  
2. Data Cleaning:
   - Removed rows with NaNs and invalid entries  
   - Converted data types (e.g., dates, numeric columns)  
3. Feature Engineering:
   - Extracted Month, City, Hour, and Sales  
   - Grouped products bought together  
4. Exploratory Data Analysis (EDA):
   - Created bar plots, line charts, and combo plots to visualize trends  
5. Dashboard Creation:
   - Built 2 KPI Cards (Total Sales, Quantity)  
   - Designed 4 charts to visualize city-wise, month-wise, hour-wise, and product-wise trends

## Business Questions and Insights

1. **What was the best month for sales?**  
   December generated the highest sales (~$4.61M), likely due to holiday season and promotions.

2. **Which city had the highest number of sales?**  
   San Francisco (CA) was the top-performing city in terms of revenue.

3. **What time should advertisements be displayed to maximize likelihood of purchase?**  
   Sales peak around 11 AM and 7 PM. Recommended ad slots: 10–11 AM and 6–7 PM.

4. **What products are most often sold together?**  
   Most common combo: iPhone and Lightning Charging Cable. Suggests bundling or combo offers can boost sales.

5. **What product sold the most? Why?**  
   AAA Batteries (4-pack) sold the most by quantity. Most likely due to its low price and high necessity as an add-on item.

## Power BI Dashboard

The Power BI dashboard includes:
- KPI Cards: Total Sales, Total Quantity  
- Bar Charts: Sales by City, Monthly Sales  
- Line Chart: Orders by Hour  
- Bar Chart: Product Sales (Quantity)

## What You Can Learn from This Project

- Real-world dataset handling  
- Cleaning messy data for analysis  
- Drawing actionable insights using simple visualizations  
- Creating end-to-end projects using both Python and Power BI

