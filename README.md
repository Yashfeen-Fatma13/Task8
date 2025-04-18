# Task8
Dashboard Development Summary – Power BI

To complete the assigned task of designing a simple sales dashboard in Power BI, I followed a structured approach to create a clear, interactive, and informative visualization of the sales performance based on the available dataset. Below is a breakdown of the key steps I performed:


---

1. Data Import and Understanding
I began by importing my dataset into Power BI, which included fields such as Date, Country, Product, Amount, Boxes Shipped, and Salesperson. I reviewed the data to understand what dimensions and measures were available for building the required visuals.


---

2. Data Preparation
To prepare the data for time-based analysis, I extracted the Month, Quarter, and Year from the Date field using Power BI’s built-in date functions. This allowed me to create a custom time hierarchy that I later used in the line chart for monthly trend analysis.


---

3. Visualizations Added

Line Chart (Top Right): I created a line chart that visualizes the Sum of Amount over Year, Quarter, and Month. This helped capture the monthly sales trend and identify seasonal peaks or dips in performance.

Bar Chart – Country-wise Sales (Top Left): Since the dataset didn’t contain a “Region” field, I used Country as a substitute. I plotted a bar chart showing the Sum of Amount by Country to analyze sales performance geographically.

Donut Chart (Top Center): To represent product-level distribution, I created a donut chart that displays the Count of Products by Country, offering a quick visual breakdown of product spread in each market.

Bar Chart – Product-wise Shipment (Bottom Left): I added another bar chart to show the Sum of Boxes Shipped by Product, helping to identify top-performing products in terms of volume.

Waterfall Chart – Product Impact (Bottom Right): As an additional insight, I incorporated a waterfall chart showing how different products contribute to total sales, including positive and negative shifts.



---

4. Interactivity Enhancements

I added a Country filter panel on the right-hand side, allowing users to dynamically filter visuals by specific countries.

To make the visuals more effective, I used manual color assignments and formatting options to highlight top-performing countries and products, making the dashboard visually intuitive.



---

5. Formatting and Layout

I structured the visuals in a grid layout for clarity and ease of reading.

Proper titles were added to each chart to make the purpose of each visual immediately clear.

A clean, consistent color scheme was used to maintain a professional appearance.



---

This step-by-step approach ensured that the dashboard met the project requirements while providing clear insights into sales performance over time, by geography, and by product.
