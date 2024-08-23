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
