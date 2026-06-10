# Global Consumer Goods Sales & Market Share Analysis (FY 2021)

This project focuses on analyzing the sales performance and regional market share of a global consumer goods company for Fiscal Year 2021 using SQL. The objective of the analysis was to identify top-performing customers, evaluate their contribution to overall revenue, and measure their percentage share across different geographical regions. The project demonstrates how SQL can be used not only for data extraction but also for generating meaningful business insights that support strategic decision-making.

To perform the analysis, advanced SQL concepts such as Common Table Expressions (CTEs), aggregate functions, and Window Functions were used. The `SUM() OVER (PARTITION BY region)` window function helped calculate each customer’s percentage contribution within their respective regions without losing individual customer-level details. Data was aggregated from sales and customer dimension tables to create a clean and structured analytical output.

The analysis revealed that Amazon was the leading customer globally with a 13.23% market share, followed by Atliq Exclusive and Atliq E Store. In the APAC region, Amazon generated $57.41M in sales with a 12.99% regional share. The findings also highlighted the strong performance of Atliq’s proprietary channels, contributing over 18% of global sales.

This project showcases practical SQL skills, business analysis capabilities, and data-driven storytelling techniques commonly used in real-world data analytics and business intelligence roles.
