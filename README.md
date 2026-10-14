# Sales Performance Dashboard (Power BI)
An interactive 5-page Power BI dashboard analysing sales, profit, products, customers, regions, discounts and shipping, built on the Superstore sample dataset.

#Dataset
Superstore sample dataset: [public practice data]

#Tools
Power BI Desktop, DAX, Power Query, Data Modeling

#Dashboard pages
1.Executive Overview: KPI cards (Total Sales, Total Quantity, Total Profit, Profit Margin %), sales by segment, profit margin by ship mode, monthly  sales, and slicers for Region, Category and Order Date.
2.Product Performance: sales by category, a top products list, and a sub-category table of sales and profit.
3.Customer Analysis: top 10 customers by sales and sales by segment.
4.Geographical Analysis: sales by region and a map of sales by state.
5.Discount and Shipment Analysis: profit by ship mode, a ship mode table, and a scatter chart of discount against profit.

#Data model
Star-style model with a fact table (Data) connected to Product, Customer, Location, Segment, ShipMode and a Date table.

#DAX measures
Total Sales, Total Quantity, Total Profit, Profit Margin %, Total Orders, Total Discount, Average Discount, Sales YoY, YoY Growth %.

#Key insights
- Total sales were $2.06M, profit was $263.70K, and the profit margin was 12.80%.
- Consumer was the largest segment ($1.05M, about 51% of sales).
- West was the top region ($0.66M, about 32%); South was the lowest ($0.34M, about 17%).
- Technology was the top category by sales ($0.75M).
- Copiers earned the most profit ($43.7K). Chairs had the highest sales ($296K) but earned only $23.6K profit, and Machines sold $176K but earned only $7.9K, so high sales do not always mean high profit.
- Standard Class earned about 57% of total profit ($151K of $264K); Same Day earned the least ($19K).
- Among the top 10 customers by sales, Sean Miller ($25.0K sales) and Becky Martin ($11.8K sales) were loss-making.

#Files
- powerbi dashboard.pdf: all dashboard pages
- powerbi_dashboard.pbix: the Power BI file (open with Power BI Desktop)

## Author
Pavitra S Patil | [LinkedIn](https://www.linkedin.com/in/pavitra-patil-46494a392)
