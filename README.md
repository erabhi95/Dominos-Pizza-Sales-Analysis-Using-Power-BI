# SuperStore Sales Data Analysis

### Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [KPIs Considered](#kpis-considered)
- [Data Cleaning](#data-cleaning)
- [Data Transformation](data-transformation)
- [Data Visualisation](#data-visualisation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)

### Project Overview
This is a data analysis project that aims to provide insights into the sales performance of a Dominos Pizza Store. By analysing various aspects of the sales data , we seek to identify trends, make data-driven recommendations, and gain a deeper understanding to enhance the store's performance in terms of growth, efficiency and customer satisfaction.
Specifically, we need to provide insights as per the metrices provided by the business teams as KPIs for this analysis.

**Final Report**

![Page1_Dashboard_Dominos_Sales_Analysis](https://github.com/erabhi95/Dominos-Pizza-Sales-Analysis-Using-Power-BI/assets/159037337/98e7637b-7946-4341-ac2c-5be60e2fd5ac)

![Page2_Dashboard_Dominos_Sales_Analysis](https://github.com/erabhi95/Dominos-Pizza-Sales-Analysis-Using-Power-BI/assets/159037337/53bcf96f-00be-4432-8ac3-0ff556655ade)


### Data Sources
The primary dataset used for this analysis are the 'Dominos Sales Data' excel data , containg detailed information about the sales made by the store in 2023.

### Tools
1. **Microsoft SQL Server Management Studio** - For Data querying
2. **Microsoft Power BI** - For Data Visualisation and Anaysis

### KPIs Considered
- Total Revenue
- Total Orders
- Total Pizzas Sold
- Average Pizzas Per Order
- Average Order Value

### Data Cleaning
1. Data loading and inspection.
2. Checking for correct data type and formating.
3. Removing blank rows and duplicates from the data.

### Data Transformation
1. Created new columns and measures using DAX queries to get more insights out of the available data which are further used during dashboard creation.
2. Performed sorting of the columns to get the desired trends. 
   
### Data Visualisation
1. Created an interactive dashboard using sales data that gives information about the sales trends as per user's choice.
2. Added some insights in the dashboard itself for quick bird's eye view on some major trend results.

### Exploratory Data Analysis
EDA is performed on the Sales data to answer some key questions, such as:
- What is the Total Revenue generated in 2023 ?
- What is the Total number of Orders placed in 2023 ?
- What is the Total Pizzas sold in 2023 ?
- What is the Average Order Value ?
- What is the Average Pizzas per Order Value ? 
- What is the Daily & Monthly trends for Total Orders ?
- What is the Percentage of Sales by Pizza Category and Pizza Size trend ?
- What is the Total Pizzas Sold by Pizza Category trend ?
- What are the Top 5 Best Sellers by Revenue, Total Quantity and Total Orders ?
- What are the Bottom 5 Best Sellers by Revenue, Total Quantity and Total Orders ?  

### Results
- Majority sales comes from the **Western & Eastern states(~60%)**.
- In west, **California** is the majorily contributing state with **more than 60% of total sales and more than 70% of total profit**.
- In east, **New York** is the majorily contributing state with **more than 40% of total sales and more than 75% of total profit**.
- Normal **Consumers** are the majority contributors to the **sales(~50%) and profit(~45%)** followed by **Corporates** with **sales(~30%) and profit(~30%)**.
- Majority sales happen via **COD and Online payment modes**.
- In **2019, October has the highest profit** despite average annual sales.
- In **2020, March has the highest profit** despite December having highest sales.
- In terms of Category, **Office Supplies and Technology contribute to majority sales(~70%) and profit(~95%)**.
- Top 5 Sub-categories of products in terms of sales are Phones, Chairs, Binders, Storage and Accessories.
- **Standard Class** is the most preferred Shipment Mode **contributing to majority sales(~60%) and profits(~55%)**.
- **Next 15 days sales** values has been forecasted with **confidence interval of 95%** depicts the sales values ranging between **2.2K to 9.4K** vales.

### Recommendations
Inorder to improve “SuperStore” Sales & Profits :
- **California in west and New York in east US should be analysed** specifically to look what's driving the higher sales in these states and the same should be used to revive sales in the Northern and Southern states of the country.
- In terms of payment modes, major spending should be done in **maintaining the Online & Cash On Delivery customers like more cash back schemes,sales offs on transactions** etc can be given.
- **Year end (specially December) is witnessing higher sales, so more offers should be rolled off** during that period of the year. Also, further analysis should be done to generate more profit from the increased sales during that period.
- **Office Supplies & Technologies inventories should always be maintained** properly as they the majority contributors to sales and profits. Also more schemes should be provided to their buyers. In addition to this, **feeback form can be rolled out to the customers of 'Furniture' to see their pain point** and plan further strategies accordingly.
- Since more customers are using **Shipment mode as Standard Class**, if possible, **try to reduce the delivery time period** which is currently 6 days.
- **As per the forecasted values, stocks should be maintained in advance** specially for demanding item categories like Office Supplies & Technologies.

