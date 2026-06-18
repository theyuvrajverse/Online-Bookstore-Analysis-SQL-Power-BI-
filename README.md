#Online Bookstore Analytics System | SQL Database Design, Business Analysis & Power BI Dashboard

End-to-end bookstore analytics: self-designed SQL schema with revenue/customer queries, paired with a Power BI dashboard visualizing genre performance and sales trends
# Online Bookstore Analysis (SQL + Power BI)

## Business Problem

An online bookstore needed a structured system to track inventory, customer purchases, and sales performance. The objective was to design a relational database capable of supporting business reporting and to generate actionable insights on customer behavior, product performance, and revenue trends.

## Database Design

Designed and implemented a normalized relational database consisting of three interconnected tables:

* Books
* Customers
* Orders

Key design features:

* Primary and foreign key relationships
* Referential integrity between customers, orders, and books
* Inventory tracking through stock quantity management
* Scalable schema suitable for business reporting and analytics

## SQL Analysis

Developed business-focused SQL queries to answer operational and strategic questions:

* Total revenue generated from all completed orders
* Remaining inventory after order fulfillment
* Identification of repeat customers (2+ orders)
* Best-selling book by quantity ordered
* Highest-spending customer
* Revenue contribution by genre
* Revenue contribution by author
* Customer purchasing patterns and order distribution

## Dashboard Development (Power BI)

Built an interactive Power BI dashboard connected to the bookstore dataset to visualize sales performance, inventory movement, and customer trends.

### Dashboard Metrics

* Total Revenue: ₹75.63K
* Units Sold: 2,697
* Total Inventory: 25K units
* Revenue per Unit Sold: ₹28.04

### Key Insights

* Romance generated the highest revenue at ₹13.09K.
* Mystery closely followed with ₹12.79K in sales revenue.
* Science Fiction recorded the highest average selling price at ₹28.98 per book.
* Inventory analysis showed significant stock depletion across top-performing genres.
* Sales were distributed across multiple countries, indicating a geographically diverse customer base.
* Revenue concentration within a small number of genres highlighted key growth opportunities for inventory planning and marketing.

## Business Recommendations

* Increase inventory allocation toward high-performing genres such as Romance and Mystery.
* Launch targeted promotions for premium-priced Science Fiction titles.
* Develop loyalty campaigns for repeat customers identified through SQL analysis.
* Optimize procurement planning using stock depletion insights.
* Expand marketing efforts in regions with higher order concentration.

## Files

* `bookstore_schema.sql` — Database schema, table creation scripts, and analytical SQL queries
* `bookstore_dashboard.pbix` — Interactive Power BI dashboard
* `dashboard_screenshot.png` — Dashboard preview

## Tools & Technologies

* MySQL
* Power BI
* DAX
* SQL Joins
* Aggregate Functions
* Data Modeling
* Data Visualization
