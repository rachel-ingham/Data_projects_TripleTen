# TripleTen Data Storytelling Project - What is causing returns?

### The Prompt
What is causing the high number of returned orders at the Superstore? In this project, I prepare an analysis for the CEO of the Superstore to help them understand what is causing customers to return their orders and how to reduce the volume of returned orders. 

### The Data
The Superstore data includes three tables: Orders, People, and Returns. 

- Orders Dataset:   Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country/Region, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit
- People Dataset: Regional Manager, Region
- Returns Dataset: Returned, Order ID
  
### The Process
To prepare the data for analysis, I joined the Orders dataset and the Returns dataset. I created a calculated field where a returned item is labeled 1, and all others are labeled 0. This allowed me to find an average return rate and a total number of returns easily. 

During the data analysis, I took into account various contributing factors to the number of returns including: weekday of order, product category, state and region, individual customers, population segment (corporate, consumer, home office), ship mode, and business quarter. I created 7 visualizations to highlight reasons why return rates are high at Superstore. I also considered whether there is a correlation between total sales and total returned order when examined by product subcategory.

![image](https://github.com/user-attachments/assets/f3236e29-a720-4c0c-9290-9669818f9773)


![image](https://github.com/user-attachments/assets/2b32c2b6-af5d-4139-9b95-d91f1be59029)

After creating a mockup and final version of the return rates dashboard, I created a Tableau Story presentation for the CEO which clearly and concisely reviews the results of my analysis and provides an interactive version of the dashboard which can analyze returns by region and product sub-category. Finally, I included possible next steps that Superstore could take to address the high number of returns.

![image](https://github.com/user-attachments/assets/fd413617-912a-42d6-b2ce-8e172cdc0cd7)

### Results
Three root causes of high returns were identified. 
  1. The West Region has the highest return rates compared to other regions in almost every quarter reported in the data. 
  2. Orders with Same Day Shipping have high return rates compared to other shipping modes.
  3. The Binders and Paper subcategories have high total return numbers. 

Four suggestions are made for how to reduce the volume of returns.
  1. Ending Same Day shipping for the consumer population segment
  2. Reducing or eliminating sales of Paper and Binders
  3. Further investigate why returns are high in Western states like Utah and California
  4. Interview or survey customers with high return rates to identify trends

### Project Link
https://public.tableau.com/shared/RNC3RGSRC?:display_count=n&:origin=viz_share_link
