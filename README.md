# Data-Warehouse-BI
The group project focused on creating a streamlined dataset consolidating all customer orders to derive meaningful insights, store data efficiently, and avoid redundancy. This unified repository enables analysis of customer buying patterns, sales trends, and product reviews, supporting data-driven decisions, strategic planning, and market forecasting to mitigate future risks.

We adopted a star schema for its simplicity and improved query performance. The schema includes a central fact table, Fact_OrderValue, linked to dimension tables: Dimension_Time, Dimension_OrderDelivery, and Dimension_SellerCategoryProduct.

  Dimension_Time tracks performance over time.
  Dimension_SellerCategoryProduct analyzes product and supplier data to understand demand and supplier portfolios.
  Dimension_OrderDelivery evaluates regional delivery performance and customer demographics.
  Fact_OrderValue aggregates metrics like total revenue and sales patterns.
This design enhances business alignment, optimizes logistics, and enables effective resource allocation.
