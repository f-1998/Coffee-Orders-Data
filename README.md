# Coffee Orders Data 

### Key Tasks Performed:

- Explored coffee dataset using Excel.
- Utilized advanced lookup methods: `XLOOKUP` and `INDEX MATCH`.
- Calculated total sales using a multiplication formula: `(quantity sold * unit price)`.
- Employed multiple `IF` functions for data categorization.
- Checked for duplicates to maintain data integrity.
- Converted the dataset into a structured table for easier management.
- Used `Pivot Tables` and `Pivot Charts` for deeper insights into sales trends.
- Incorporated `Timelines` and `Slicers` for enhanced data visualization.
- Updated `Pivot Table` data sources for relevance.
- Built a comprehensive dashboard presenting key metrics and visualizations.




### Structured Table Overview

The structured table is the backbone of the dashboard, comprising various columns that store critical data points. Key columns in the table include:

#### Order Details:
- **Order ID:** Unique identifier for each order placed.
- **Date:** The date when the order was placed, formatted for easy timeline analysis.
- **Product Details:** Information about the coffee sold, including type (roast), size, and unit price.

#### Customer Information:
- **Customer ID:** Unique identifier for each customer, used to link customer-specific data.
- **Customer Name:** Names of customers, retrieved using lookup formulas (e.g., `XLOOKUP`).
- **Country:** The country from which the order originated, aiding in the sales by country analysis.
- **Loyalty Card Status:** Indicates whether the customer holds a loyalty card, essential for tracking loyalty-driven sales.

#### Sales Data:
- **Quantity Sold:** The number of units sold in a particular order.
- **Unit Price:** The price of each unit sold.
- **Total Sales:** This is calculated by multiplying the quantity sold by the unit price (i.e., `Quantity Sold * Unit Price`). This column is vital for calculating the overall revenue.

#### Product Details:
- **Product Type:** Type of coffee (e.g., specific roast type).
- **Size:** Coffee size (in kg), useful for segmenting sales data by product variations.
- **Roast Type:** Whether the product is light, medium, or dark roast, providing an additional level of categorization for analysis.

---

By organizing the data into a structured table, the user can easily reference specific data points using formulas (like `INDEX MATCH` or `XLOOKUP`), which dynamically populate charts and pivot tables in the dashboard. This structure ensures flexibility and accuracy as data updates are easily reflected in the visualizations.


![coffeestuff](https://github.com/user-attachments/assets/148471d4-0bfe-4c40-93c8-b1675219e82a)

![Screenshot 2024-08-23 164223](https://github.com/user-attachments/assets/e469532d-4bc2-4e7d-81fd-2a586a40d61e)

## Key Performance Indicators (KPIs)

### Total Sales:
- **Description:** This KPI measures the overall revenue generated from coffee sales over a period of time.
- **Key Metric:** Total sales are tracked using a line chart, segmented by coffee type, to visualize revenue trends and identify the highest- and lowest-performing products.
- **Purpose:** Helps identify overall sales performance and assess revenue-generating products.

### Sales by Country:
- **Description:** This KPI tracks revenue generated from coffee sales across different countries.
- **Key Metric:** Represented by a bar chart, this provides insights into geographic performance and market penetration.
- **Purpose:** Assists in identifying top-performing regions and opportunities for geographical expansion.

### Top 5 Customers:
- **Description:** This KPI highlights the top five customers in terms of revenue contribution.
- **Key Metric:** Bar chart showing the top customers ranked by their total spending on coffee.
- **Purpose:** Identifies key customer relationships that drive significant revenue, allowing for tailored engagement strategies.

### Sales by Coffee Type:
- **Description:** A breakdown of revenue by coffee type, highlighting the distribution of sales across various products.
- **Key Metric:** Split by roast type, size, and other characteristics using slicers to show sales patterns across product categories.
- **Purpose:** Assists in determining which coffee products are most popular and contribute the most to overall revenue.

### Timeline-Driven Sales Analysis:
- **Description:** A KPI tracking sales performance over specific periods.
- **Key Metric:** Using the timeline slicer, users can analyze how sales evolve over months, quarters, or years.
- **Purpose:** Provides insights into seasonal trends, helping optimize inventory and marketing strategies.

### Customer Loyalty:
- **Description:** Tracks the revenue generated from customers who have loyalty cards.
- **Key Metric:** Visualized through slicers that separate loyalty card holders from regular customers, highlighting their contribution to sales.
- **Purpose:** Shows the impact of loyalty programs on customer retention and sales.

---

## Key Takeaways

### Strong Product Performance:
- Certain coffee types (e.g., specific roast types or sizes) generate significantly higher sales compared to others. By analyzing this data, it is possible to optimize the product mix and marketing strategies.
- The timeline chart provides insights into fluctuations in sales over time, revealing seasonal trends. For example, sales might spike during specific months, which could help with inventory planning.

### Geographical Insights:
- The sales by country chart highlights which regions are performing well and where there are opportunities for growth. For example, the United States and a few other countries may account for the bulk of sales, suggesting a strong market presence in those areas. Identifying underperforming regions can guide targeted marketing efforts.

### Customer Focus:
- The top five customers by sales reveal key relationships that the business should prioritize. Maintaining strong relationships with these high-value customers can have a disproportionate impact on revenue.
- Loyalty card data demonstrates the effectiveness of retention strategies. Customers with loyalty cards may contribute more to sales, suggesting that expanding loyalty programs could enhance customer lifetime value.

### Customization for User Engagement:
- The use of slicers and timelines provides an interactive experience, allowing users to drill down into specific metrics. This customization enhances the user experience and makes the dashboard more versatile for various stakeholders, such as sales teams or management.

### Actionable Data for Decision-Making:
- By identifying trends and top performers (e.g., coffee types, regions, customers), the dashboard provides actionable insights. Management can adjust inventory, optimize product offerings, or refine marketing tactics based on these insights.

https://github.com/user-attachments/assets/71e45557-4fb0-4cf6-a74d-c89163702a7d

## Conclusion

The coffee sales dashboard offers a comprehensive and dynamic view of business performance, combining visual appeal with data-driven insights. By effectively leveraging Excel’s advanced functions like XLOOKUP, pivot tables, and slicers, this project not only enhances the decision-making process but also facilitates a more in-depth analysis of key metrics such as total sales, customer performance, and geographical reach.

The dashboard's interactivity, driven by slicers and timelines, allows users to focus on specific data points or time periods, making it an adaptable tool for various stakeholders. With features such as loyalty tracking, top customer identification, and trend analysis, the dashboard provides valuable insights that can be used to improve business strategies, optimize product offerings, and enhance customer retention efforts.

Overall, this project exemplifies how well-structured data and visually engaging dashboards can transform raw data into actionable insights, providing a clear path toward business growth and optimization.



