# Excel - Superstore Sales Performance Analysis

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

**2. Data Analysis**

Data analysis process aims to uncover patterns, trends, and insights within the dataset. By utilizing Pivot Tables, various analyses were performed to address specific business questions and objectives. Below are the steps taken for the data analysis process:

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
### 🔍 Results and Insights

This section will explain the results and insights derived from the analyzed data. The goal of this analysis is to identify sales trends, evaluate the performance of product categories, measure the contribution of product subcategories, and assess customer segmentation and shipping efficiency. These findings can be used to support decision-making in the development of more effective sales, marketing, and cost management strategies.

| **Category** | **Results**   | **Insights** |
| ------------ | ------------ | ------------ |
| Total Quantity Sold, Total Sales, Total Profit, and Profit Margin  | Strong sales of 37,873 units generating over $2.3 million in revenue. Profit margin is 12.47%.  | The moderate profit margin indicates that while sales are strong, cost efficiency or pricing strategies could be improved to boost profitability. |
| Daily Sales Trend  | Daily sales range from $44,806.69 to $112,155.14. The average daily sales amount is $74,833.23, with the highest sales recorded on day 17.  | The trend shows significant fluctuations in daily sales, with some days experiencing drastic drops and others seeing high peaks. |
| Category Performance  | Technology leads in total sales and profit margin, outperforming other categories.  | The Technology category is performing exceptionally well, showing both high sales and profit margin, indicating greater efficiency and profitability compared to Furniture and Office Supplies. |
| Sub-category Contribution  | Phones are the leading sub-category in terms of total sales, with the highest contribution to overall sales.   | Given the strong demand for Phones, targeted marketing strategies could further capitalize on this popularity, boosting sales and customer engagement.  |
| Customer Segmentation  | Consumers contribute the highest to total sales.  | The Consumer segment stands out as the most profitable, indicating a strong and consistent demand from individual buyers.   |
| Delivery Time by Ship Mode  | Same Day shipping has the shortest delivery time, followed by First Class, Second Class, and Standard Class.  | Same Day and First Class offer faster delivery options, which are likely to appeal to customers who prioritize speed. Standard Class, with the longest delivery time, could be targeted for cost-sensitive customers, or shipping improvements could be considered to enhance customer satisfaction.  |

---
### 💡 Recommendations

Based on the analysis conducted, several strategic steps can be taken to improve the company's sales performance and profitability, as follows:

- By leveraging daily sales trends, the company can plan promotions more effectively to improve sales stability.
- Further investment in the technology product category is recommended, as it demonstrates strong performance both in sales and profit margin.
- Given the high demand for the phones, more focused marketing strategies such as product bundling or special offers can help boost sales.
- Developing loyalty programs and more personalized offers for the consumer segment, which shows consistent and high demand, can increase customer retention and repeat purchases.
- For more efficient shipping, improve delivery times for standard class shipping or offer incentives to customers who choose slower shipping methods.

---
### 📝 Conclusion

The Superstore sales analysis provides valuable insights into sales trends, profitability, and customer behavior. Findings from the data exploration and interactive visualization offer useful information for formulating more targeted business strategies, including marketing, cost management, and shipping optimization. By following the recommendations, the company can significantly improve sales, profitability, and operational efficiency.

---
### 📫 Contact Information

For further questions or discussions about this project, feel free to reach out:

- Email: tupseptiany@gmail.com

- LinkedIn: https://linkedin.com/in/septianytup

If you have suggestions, feedback, or want to collaborate, don't hesitate to contact me. 😊
