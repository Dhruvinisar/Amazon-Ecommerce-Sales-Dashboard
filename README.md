Amazon E-Commerce Sales Dashboard (Power BI + Python)
Project Overview
This project analyzes Amazon e-commerce sales data (~129K records) to uncover insights into sales performance, returns, and customer segments (B2B vs B2C).  
The dataset was cleaned and prepared in Python (Pandas), and the dashboard was designed in Power BI for interactive exploration.

Dataset
- Source: Internal Amazon Sales report
- Rows: ~129,000
- Columns: Order details, product info, fulfillment type, pricing, shipping details, B2B flag, etc.
- Cleaning Steps in Python:
  - Removed unnecessary columns (`index`, `Unnamed: 22`, etc.)
  - Filtered out cancelled orders
  - Handled missing values for `Amount` and `Quantity`
  - Created calculated fields: `Total Sales`, `Year`, `Month`, `Month-Year`, `Is_Returned`
 Tools & Technologies
- Python– Pandas, NumPy (Data cleaning & preparation)
- Power B– Data modeling, DAX calculations, dashboard creation

Dashboard Features
1. KPI Cards
   - Total Sales
   - Total Orders
   - Return Rate %
   - Average Order Value
   - Countries Sold In
2. B2B vs B2C Sales Analysis
3. Monthly Sales Trend & MoM Growth
4. Return Rate by Category
5. Top 10 Products by Sales
6. Geographic Sales Distribution
7. Sales by Fulfillment Type & Shipping Speed


 Dashboard Screenshots
https://drive.google.com/file/d/1zAiyK6SJUCf-1RgOIMtdKPuSJ402lEBK/view?usp=sharing



 📈 Key Insights
- B2B vs B2C:~95% of orders are B2C, with B2B contributing ~5% of revenue.
- Returns: Certain product categories have significantly higher return rates, impacting profit margins.
- Regional Sales: Top-performing regions identified for targeted marketing campaigns.
- Seasonality: Sales peaks observed during specific months, indicating promotional opportunities.

