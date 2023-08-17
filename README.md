<h1>Customer Segmentation and Product Analysis</h1>

<h2>Description</h2>
This project involves creating a data visualization dashboard using Python libraries such as Pandas, Plotly Express, and Panel. The goal of the dashboard is to perform customer segmentation and product analysis by visually exploring various aspects of sales, quantities, and discounts of products over time and across different categories. The dashboard provides interactive filters, allowing users to select a specific month and choose between viewing the data on a monthly or yearly basis. The dataset encompasses data from the year 2018.
<br />


<h2>Languages and Libraries Used</h2>

During the development of this project, I utilized the following languages and libraries: 
- <b>Python: </b>  The primary programming language for data analysis and visualization.
- <b>Pandas: </b> A powerful library for data manipulation and analysis.
- <b>Plotly.express: </b> A versatile library for interactive visualizations. 
- <b>Panel: </b> A library for creating interactive dashboards and web applications.

<h2>Data Preprocessing </h2>

To ensure the dataset's integrity and consistency, I undertook critical data preprocessing measures prior to analysis. Here's what I did:
- <b>Conversion of the 'Order_Date' column to a datetime format, facilitating temporal analysis.</b>
- <b>Removal of rows containing missing values via the dropna() function.</b>

Additionally, I leveraged the power of grouping and aggregation functions to extract meaningful insights from the data. Grouping the data by various attributes allowed me to uncover patterns and trends within the dataset.

<h2>Visualization Dashboard </h2>

To visually convey the insights derived from the analysis, I designed an interactive dashboard employing the <b>Panel</b> library and leveraged <b>Plotly.express</b> for visualization purposes. The dashboard consists of distinct components that shed light on diverse facets of customer segmentation and product trends.

- <b>Total Quantity of Orders Over Date</b>

The initial dashboard component presents a line plot portraying the overall quantity of orders over time. A slider feature empowers users to dynamically select distinct months, enabling the observation of variations. This plot furnishes a comprehensive overview of order patterns throughout the year.

- <b>Sales by Product Category</b>

The subsequent component showcases a pie chart delineating the sales distribution across diverse product categories for the chosen filters. As the filters are adjusted, the chart adapts to showcase sales proportions based on the selected criteria.

- <b>Most Profitable Products</b>

The third dashboard component underscores a scatter plot spotlighting the most lucrative products for the chosen filters. This scatter plot aids in the identification of products that contribute significantly to overall profits during the specified period.

- <b>Top 10 Products with Highest Discount Percentage</b>

The following component showcases a bar plot that vividly displays the top 10 products with the highest discount percentages for the chosen filters. This visualization provides insight into products associated with substantial discounts during the specified criteria.

- <b>Age Distribution of Customers</b>

The fifth component presents a box plot illustrating the distribution of customer ages based on the chosen filters. This visualization offers insights into the age demographics of the customer base during the selected timeframe.

- <b>Device Type Distribution of Customers</b>

The final component is a pie chart depicting the distribution of customer device types based on the chosen filters. This visualization provides an overview of the devices customers use to access the e-commerce platform during the selected criteria.

Here is how the Dashboard looks like visually:

![my ecommerce project](https://github.com/MadniAbdulWahab/CustomerSegmentationandProductAnalysis/assets/105889425/35b62e54-2185-4871-95f0-17c3b81fc07f)

<h2>Project Code</h2>

For an in-depth understanding of the implementation, you can explore the project code. The code encompasses data loading, preprocessing, interactive visualization creation using <b>Plotly.express</b>, and assembly of the dashboard using <b>Panel</b>.

Feel free to examine the code, execute the project, and interact with the dashboard to glean valuable insights into customer segmentation and product analysis based on the 2018 dataset.

Thank you for engaging with my Customer Segmentation and Product Analysis project! Should you have inquiries or feedback, please don't hesitate to reach out.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
