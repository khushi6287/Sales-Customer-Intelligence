## Project Title

**Sales & Customer Intelligence Dashboard**

## Project Description

This project is a Power BI dashboard designed to analyze sales data, customer behavior, product performance, profitability, and returns. It provides actionable insights for business decision-making using interactive visuals and DAX measures.

## Objectives

* Analyze overall sales and profit performance
* Identify top and low-performing products
* Understand customer contribution and segmentation
* Monitor returns and their impact on profitability
* Track business growth using time intelligence

## Data Model

The project uses a **Star Schema** consisting of:

### Fact Tables

* **Sales_Fact**: Sales transactions, revenue, cost, profit, units sold
* **Returns_Fact**: Product return details and reasons

### Dimension Tables

* **Date_Dim**: Date, Month, Quarter, Year
* **Product_Dim**: Product details and category
* **Customer_Dim**: Customer information, region, segment
* **Region_Dim**: Region and manager details

## Key Measures Used

* Total Sales
* Total Profit
* Total Units Sold
* Total Customers
* Total Orders (SaleID based)
* Profit Margin %
* Return Rate %
* Average Sales per Customer
* Sales YTD, Sales LY
* Month-over-Month (MoM) Growth %
* Year-over-Year (YoY) Growth %
* Product Rank by Sales

## Dashboard Pages

1. **Executive Overview** – KPIs, sales trends, profitability
2. **Product Performance** – Top products, category analysis
3. **Customer Insights** – Customer segments and top customers
4. **Returns & Profitability** – Return reasons and loss analysis
5. **Growth Analysis** – YoY and MoM trends

## Tools & Technologies

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Power Query
* Star Schema Modeling

## Key Learnings

* Creating relationships using star schema
* Writing DAX measures for business KPIs
* Using time intelligence functions
* Designing interactive and executive-level dashboards

## Conclusion

This dashboard provides a comprehensive view of sales and customer intelligence. It helps identify profit leakage, growth opportunities, and operational inefficiencies, making it suitable for academic projects, interviews, and real-world business analysis.

