### Project Description:
**Title:** Sales Dashboard for Adventure Works Bicycle Company Using Power BI

1. **Objective:**
   - Create a dynamic sales dashboard using data from Adventure Works, a bicycle company.
   - Clean, model, and visualize the sales data to provide insights into staff performance, customer behavior, product sales, and order trends.

2. **Steps:**

   **Step 1: Data Collection**
   - Collected data from online sources for six tables: `Staff`, `Order`, `Order_items`, `Customer`, and `Products`.
   - Created an additional table, `Calendar`, to manage time-based analysis.

   **Step 2: Data Cleaning**
   - Imported the data into Power BI.
   - Cleaned each dataset in Power BI’s Power Query Editor by handling missing values, correcting data types (e.g., dates, integers, text), and renaming columns for better clarity.
   - Ensured consistency across tables, such as aligning dates and ensuring customer and product IDs matched across relevant tables.

   **Step 3: Data Modeling**
   - Established relationships between the tables: connected `Order_items` to `Orders`, linked `Customers` to `Orders`, and connected `Products` to `Order_items`.
   - Linked the `Staff` table to the orders for staff performance analysis.
   - Integrated the `Calendar` table with the `Order` data for time-based reporting and trends analysis.

   **Step 4: DAX Calculations**
   - Utilized DAX (Data Analysis Expressions) functions to create calculated columns and measures:
     - **Total Sales**: Calculated total revenue from product sales.
     - **Average Order Value**: Analyzed the average sales value per order.
     - **Staff Performance**: Created measures to compare staff performance based on the number of orders handled and total revenue generated.
     - **Sales by Date**: Summarized sales data by different time periods (e.g., daily, monthly, quarterly).
   - Used additional DAX functions like `SUM()`, `CALCULATE()`, `RELATED()`, `IF()`, and `FILTER()` to perform advanced calculations.

   **Step 5: Data Visualization**
   - Designed a Power BI dashboard with various visual elements:
     - **Area Chart**: To display sales trends over time, showing how revenue has evolved over months and years.
     - **Donut Chart**: To break down the percentage of sales by product category or customer type.
     - **Map Visualization**: To show the geographic distribution of customers and sales, helping to identify regional trends.
     - **Table**: To present detailed data such as sales per staff member, individual orders, or product quantities.
     - **Violin Plot**: To depict the distribution of sales values and identify outliers or concentrated sales figures.
     - **Line Chart**: To highlight trends such as sales growth or customer acquisition over time.

   **Step 6: Interactivity and Filtering**
   - Added interactive features to the dashboard, such as slicers for filtering by date, product category, and region.
   - Created tooltips and drill-down options to allow users to explore the data in more detail.

3. **Conclusion:**
   - The dashboard provided a comprehensive view of Adventure Works’ sales, helping to analyze staff performance, customer distribution, and product sales. It allowed the company to identify trends, outliers, and growth opportunities efficiently.
