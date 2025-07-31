# Product and Sales Analysis Dashboard

This project involves creating a dynamic **Product and Sales Analysis Dashboard** that provides an insightful overview of product and sales performance. The dashboard visualises key metrics such as total sales, orders, and product performance, and includes detailed category breakdowns to help business users make informed decisions.

<br/>

## Business Question

The goal of this project was to develop an interactive dashboard that answers key business questions related to product and sales performance, such as:
- What are the total sales and orders for the given period?
- How do different product categories perform in terms of sales and quantity?
- What are the sales trends over time?

<br/>

## Tools & Technologies Used

- **Power BI**: Used for data transformation, analysis, and visualisation.
- **Power Query Editor**: Employed for data cleaning, transformation, and preparation.
- **DAX (Data Analysis Expressions)**: Used to create dynamic KPIs and calculations.

<br/>

## Data Cleaning & Transformation

The data was cleaned and transformed using Power Query Editor in the following steps:
- **Removed unnecessary rows**: The first 3 rows were irrelevant and removed.
- **Removed blank rows**: Ensured the dataset only contained meaningful data.
- **Filtered rows**: Kept only rows that contained an order number.
- **Column transformation**:
  - Split columns by delimiters (| and -) to properly categorise data.
  - Merged columns back to correctly position header names.
  - Trimmed white space from product related columns.
  - Promoted the top row to headers.
- **Fixed column header typos**: Ensured all column names were accurate.
- **Formatted currency**: Converted Price per Unit and Total Sales columns to currency format.

<br/>

## Dashboard Features

The dashboard includes several key features to provide business insights:

- **Key Performance Indicators (KPIs):**
  - Total Sales
  - Total Orders
  - Unique Products
  - Average Order Quantity
  - Average Price per Unit
  - Unique Categories

- **Visualisations:**
  - **Total Sales by Category**: A bar chart showing total sales for each product category.
  - **Total Quantity by Category**: A pie chart displaying quantities by category.
  - **Product Performance Table**: A table that lists products, total sales, total quantity, and total orders.
  - **Total Sales by Day**: A line graph showing sales trends over time.
  - **Slicers**: Interactive filters allowing users to slice the data by **Product**, **Category**, and **Month**.

<br/>

## Insights & Recommendatios

Key findings from the analysis:

- **Top-Performing Categories:**
  - Electronics generated the highest sales, totalling **€13.2k**, even though it only represented **22%** of orders.
  - Home Appliances and Clothing made up **31%** and **27%** of orders, respectively, but together accounted for only **€8.3k** in sales.

- **Product Performance:**
  - Laptops, Refrigerators, and Tablets accounted for **€11k** in sales.
  - Sneakers led in terms of quantity sold, with **22 units** sold.

- **Sales Trends:**
  - Sales fluctuated significantly, with a peak of **€1,600** in a single day and a low of **€80**. With only **3 months** of data, there isn't enough information to identify any clear seasonal trends.

**Recommendations:**
- **Personal Goods** is the lowest-performing category. Since **Smart Watches** is the only product, it should potentially be moved to the **Electronics** category.
- Marketing efforts should focus on **Electronics**, as it consistently generates higher sales compared to other categories, despite having similar order quantities.

<br/>

## Contact

Lana Trimmer<br/>
[LinkedIn](https://www.linkedin.com/in/lana-trimmer/) • [Portfolio](https://ltrimmer.carrd.co/) • [Email](lana.trimmer32@gmail.com)
