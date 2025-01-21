# Superstore Sales Insights: Data Analyis and Visualization

This Superstore sales analytics project aims to provide deep insights into business performance by analyzing sales data, profitability, and customer behavior. The process involves data cleansing, analysis using pivot tables, and visualization through interactive dashboards. The project seeks to identify sales trends, evaluate product category performance, measure product subcategory contributions, and assess customer segmentation and delivery efficiency. The results of this analysis will support data-driven decision-making, improve marketing strategies, optimize operations, and drive overall business growth.

---
### 🎯 Project Objectives
1. Identify sales trends, evaluate product category performance, and measure subcategory contributions to explore factors that affect profitability.
2. Conduct customer segmentation to improve marketing strategies and optimize delivery efficiency to improve service and resource management.
3. Presents insights through interactive dashboards and data-driven analysis to support better decision-making in marketing strategy, operations, and business growth.

---
### 📂 Dataset
**Data Source:**
- URL: [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- Number of Rows and Columns: 9994 rows and 21 columns

**Dataset Columns:**
| **Column Name**  | **Definition**  |
| ------------ | ------------ |
| Row ID   | A unique ID for each row of data.  |
| Order ID  | A unique ID for each order placed by a customer.  |
| Order Date   | The date the product order was placed.  |
| Ship Date   | The date the product was shipped.  |
| Ship Mode  | The shipping mode selected by the customer.  |
| Customer ID  | A unique ID to identify each customer.  |
| Customer Name  | The name of the customer.   |
| Segment  | The segment where the Customer belongs.  |
| Country  | The country where the customer lives.  |
| City  | The city where the customer lives.  |
| State  | The state where the customer lives.   |
| Postal Code  | The postal code of the customer.   |
| Region   | The region where the customer is located.   |
| Product ID   | Unique ID for the product ordered.  |
| Category  | The category of the ordered product.  |
| Sub-Category  | The subcategory of the ordered product.  |
| Product Name  | The name of the ordered product.  |
| Sales  | Sales of the product.  |
| Quantity  | The number of units of the product ordered.  |
| Discount  | The discount given on the product.  |
| Profit   | The profit or loss earned on the ordered product.  |

---
### 📈 Methodology

The analysis process was conducted using Microsoft Excel, starting with Data Cleaning, followed by Exploratory Data Analysis (EDA), and concluding with Data Visualization.

**1. Data Cleaning**

The Data Cleaning process ensures that the dataset is accurate, consistent, and ready for analysis. It involves identifying and resolving potential issues such as missing values, duplicates, and inconsistent formatting. This step is crucial to maintain the integrity of the analysis and ensure meaningful insights. Below are the specific steps taken during the data cleaning process:

| **Steps**  | **Reason**  |  **Notes** |
| ------------ | ------------ | ------------ |
| Check Empty Data | Ensure the data is free of empty values that may affect the analysis. | No empty data found. |
| Check Duplicate Data | Prevents duplication that could lead to incorrect analysis results. | No duplicate data found. |
| Change Date Format | Standardizes the date format to make time analysis easier. | Date format updated to dd/mm/yyyy. |
| Add Currency Symbol | Provides clear context to numerical data related to sales and profits. | Currency symbol ($) added in Sales and Profit columns. |
| Change Discount Format | Makes the discount column easier to read and understand in percentage terms. | Discount format changed to percentage. |
| Splitting Order Date Information | Simplify analysis based on a specific day, month, or year. | Day, Month, and Year columns added. |
| Add Delivery Time Column | Measure shipping efficiency by calculating the difference between Order Date and Ship Date. | Added Delivery Time column in days. |

**2. Exploratory Data Analysis (EDA)**

The EDA process aims to uncover patterns, trends, and insights within the dataset. By utilizing Pivot Tables, various analyses were performed to address specific business questions and 
objectives. Below are the steps taken for the EDA process:

| **Steps**  | **Method**  | **Goal** |
| ------------ | ------------ | ------------ |
| Total Sales, Total Profit, Total Quantity Sold | Use Pivot Table to calculate the total values of Sales, Profit, and Quantity. | Measure sales performance, profitability, and the volume of products sold. |
| Profit Margin   | Add a calculated column in the Pivot Table: [Total Profit] / [Total Sales]. | Assess profitability efficiency across various dimensions. |
| Daily Sales Trend | Create a Pivot Table with Day as rows and Sales as values. | Analyze daily sales fluctuation patterns. |
| Category Performance | Use Pivot Table to calculate Total Sales, Total Profit, and Profit Margin for each category. | Evaluate the performance of each product category. |
| Sub-category Contribution | Use Pivot Table to calculate each Sub-Category's contribution to Total Sales. | Identify sub-categories with the largest contribution to total sales. |
| Customer Segmentation | Group Segment based on their percentage contribution to Total Sales. | Understand key customer segments for targeted marketing strategies. |
| Delivery Time by Ship Mode | Calculate the average delivery time based on Ship Mode using delivery time calculations. | Evaluate the efficiency of each shipping method to improve customer satisfaction. |

**3. Data Visualization**

The Data Visualization process focuses on creating an interactive dashboard allowing users to explore insights easily and dynamically. The dashboard incorporates the following elements:

| **Dashboard Elements** | **Description** |
| ------------ | ------------ |
| Slicer | Add slicers to filter data by Year, Month, and State, allowing users to focus on specific analysis areas.  |
| Cards  | Display key metrics such as Total Sales, Total Profit, Total Quantity Sold, and Profit Margin in cards to provide a quick overview of business performance.   |
| Line Chart  | Create a line chart to analyze daily sales trends, helping to understand fluctuations in sales over time.  |
| Vertical Bar Chart  | Create a vertical bar chart to compare product category performance based on Total Sales, identifying categories with the highest contribution.  |
| Horizontal Bar Chart  | Use a horizontal bar chart to analyze the contribution of each Sub-Category to Total Sales, highlighting the top-performing sub-categories.   |
| Pie Chart  | Create a pie chart to visualize customer segmentation based on Total Sales, providing insights into key customer segments.   |
| Table  | Add a table to display the average delivery time (Delivery Time) by Ship Mode, helping to evaluate shipping efficiency.  |

---
