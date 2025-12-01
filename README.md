# Vendor Performance Data Analysis Project
***Data Analysis | Python, SQL***<br>

- Performed comprehensive data extraction, cleaning, and transformation using SQL, and executed Exploratory Data Analysis (EDA) with Python to identify meaningful trends and patterns.
- Engineered SQL queries incorporating aggregations and joins to derive actionable insights and support strategic decision-making.<br><br>

This project performs in-depth Vendor performance analytics using liquor inventory data.<br>
It integrates SQL + Python + Visualization + Statistical testing to identify:<br>

✔ Most profitable vendors<br>
✔ Vendors with low sales but high margins (ideal for pricing push)<br>
✔ Capital locked in unsold inventory<br>
✔ Bulk-order price advantage assessment<br>
✔ Top vendors driving 65.7% of total procurement<br>
✔ Pricing elasticity & profitability relationships<br>
✔ Underperforming stock — slow moving products, dead inventory<br><br>

***1. Correlation Heatmap***<br>

<p align="center">
   <img src="/images/1.png" width="550">  
</p>

***2. Top 10 Vendors by Sales***<br>

<p align="center">
   <img src="/images/2.png" width="550">  
</p>

***3. Top 10 Brands by Sales***

<p align="center">
   <img src="/images/3.png" width="550">  
</p>

***4. Vendor Purchase Contribution***

<p align="center">
   <img src="/images/4.png" width="550">  
</p>

***5. Top Vendor Share***

<p align="center">
   <img src="/images/5.png" width="550">  
</p>

***6. High-Margin Low-Sales SKUs***

<p align="center">
   <img src="/images/6.png" width="550">  
</p>

***7. Impact of Bulk Purchase on Unit Price***

<p align="center">
   <img src="/images/7.png" width="550">  
</p>

***8. Confidence Interval Comparison — Top vs Low Margin Vendors***

<p align="center">
   <img src="/images/8.png" width="550">  
</p>

<br><br>
💻 ***Highlights***

- Performed large-scale EDA on multi-table inventory & sales database
- Used SQL joins + aggregations + CTEs to merge purchase, sales & invoice data
- Implemented data cleaning, type conversions, null handling & feature creation
- Engineered metrics: GrossProfit, ProfitMargin, StockTurnover, SalesPurchaseRatio
- Automated workflow using Python functions + logging + ingestion pipeline
- Visualized KPIs using matplotlib / seaborn (sales distribution, vendor share, margins etc.)
- Wrote scalable reusable script for ETL + analysis + summary table generation
