# Northwind Traders Analysis Project

Welcome to the **Northwind Traders Analysis Project**! This project delves into an extensive analysis of the Northwind Traders dataset, focusing on SQL-based data manipulation, performance metrics, sales trends, and customer behavior insights.

## Project Overview

In this project, I used SQL to explore and analyze Northwind Traders data, a fictional company with a rich dataset that mimics real-world business operations. My analysis focused on identifying key business insights, customer patterns, and operational efficiencies. Below are the major sections of analysis and the insights uncovered.

### Key Analyses and Queries

1. **Data Cleaning and Preprocessing**:
   - Identified errors in phone numbers and updated them to ensure accurate contact information.

2. **Product and Supplier Analysis**:
   - **Discontinued Products**: Identified products that were discontinued yet still in stock, revealing patterns in seasonal ordering.
   - **Supplier Relationships**: Analyzed suppliers that are still active, along with the number of products sourced from each.

3. **Employee Performance**:
   - Measured employee performance by analyzing order counts, age, and years of service. For example, Margaret was identified as the top-performing employee, with 6 years of service and the highest order count.

4. **Customer Insights**:
   - **Top Cities for Orders**: Ranked cities based on total order volume, highlighting key markets.
   - **New Customers**: Identified customers who made their first purchase in the last six months.
   - **Engaged but Non-purchasing Customers**: Listed customers who inquired but didn’t place any orders, offering potential for targeted follow-ups.

5. **Order and Discount Trends**:
   - **High-spending Customers**: Identified the top 5 companies by total spending, offering insights for loyalty programs.
   - **Discount Patterns**: Analyzed the correlation between discount frequency and order volume, showing a direct relationship.

6. **Shipping and Cost Analysis**:
   - **Shipping Cost Trends**: Observed that the shipping company with `ship_id 3`, Federal Shipping, has particularly high rates. However, this trend was seasonal, with rates increasing during specific periods.
   - **High Shipping Fees**: Determined that high shipping fees were applied regardless of product type, affecting both fragile and non-fragile items.
   - **Top-paying Companies**: Identified companies that paid the highest shipping fees, highlighting potential inefficiencies.

7. **Order Cancellations**:
   - Analyzed order cancellations and found the USA as the leading country for cancellations. The majority of these cancellations were handled by the carrier with `ship_id 2`, United Package.

8. **Top and Least Selling Products**:
   - Listed the top 5 best-selling and bottom 5 least-selling products, providing insights into product popularity and potential discontinuation.

9. **Revenue Analysis**:
   - **Monthly Revenue**: Calculated monthly revenue to identify sales trends and peak seasons.
   - **Order Quantity vs. Discount Frequency**: Observed that higher discount frequencies were generally associated with higher order quantities.

10. **Inventory Management**:
    - Identified products needing restocking based on order demand, helping optimize stock levels.

## Conclusion

This project provides a thorough analysis of the Northwind Traders dataset, offering actionable insights into product performance, customer behavior, employee efficiency, and shipping cost trends. The SQL queries and insights presented here can aid in decision-making, optimize operations, and enhance customer satisfaction.


