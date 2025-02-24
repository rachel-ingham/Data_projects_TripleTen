# TripleTen Customer Analysis Project - Zomato Restaurant App

### The Prompt
Zomato is a multinational restaurant aggregator and food delivery company. As your first assignment as a junior analyst, you’re given several test datasets to analyze the business performance of restaurants and customers registered in the service. I choose to focus on a Customer Analysis Segmentation. My analysis will answer five questions: 
	1. Who are Zomato's customers in general?
	2. What segments can we split them into?
	3. Who is the typical customer and what are their preferences?
	4. What do we know about customer purchasing trends?
	5. What changes can Zomato make to improve business outcomes?

### The Data
I used three provided datasets with information on 100,000 Zomato users, over 140,000 individual restaurants, and over 150,000 unique orders for this Analysis. 

Orders dataset:

![image](https://github.com/user-attachments/assets/d394558c-fdb8-464e-a18c-4c187f43b43d)

Restaurant dataset: 

![image](https://github.com/user-attachments/assets/49ffd144-df07-49e9-b04d-de7cdeedbce5)

Users dataset: 

![image](https://github.com/user-attachments/assets/4dd0ad03-987b-4aa1-b291-e7144a9fa729)

### The Process
I joined the three datasets for use in my Customer Analysis after some initial data cleaning. To clean and process the data, I deleted any duplicate rows, replaced blanks with null or 0 as appropriate, I converted all currency values to INR, and I split the cuisine column into two columns of text for easier categorization of the restaurants. I also separated customers into income groups, and categorized restaurants into cost categories ($, $$, $$$, $$$$). 

My hypothesis was that the typical Zomato customer is a single, 20 something, male who is a student or a person with low monthly income. I suspected that family groups of size 3 or 4 spend more on their orders and more often order food on the weekend, while students and individuals more often order food during the week. I also expected to find that more orders are placed during colder months (December thru February) than in warmer months (May thru July). I expected to find some differences in which restaurant cost levels and cuisines are preferred by different customer groups. I suspected that families may more likely choose options labeled fast food, while singles or couples may be more adventurous in cuisine choice.    

I created bar graphs, pie charts, tables, and heat charts to highlight and display information about the typical Zomato customer. I incoporated column charts (stacked or not) and scatter plots to further show how customers can be segmented into different groups. Finally, I used line graphs to examine weekly, monthly, or yearly trends among the different customer groups. 

To summarize my findings, I created three dashboards and a Tableau story presenting key insights.

#### Customer Segments Dashboard
![image](https://github.com/user-attachments/assets/bad986ea-3743-453a-b46a-eb2e4562217d)

#### Typical Customer Dashboard
![image](https://github.com/user-attachments/assets/d99e9210-32ac-4be3-86b0-b406e3b312d6)

#### Trend Analysis Dashboard
![image](https://github.com/user-attachments/assets/1473c924-5225-4e3c-b52c-f62a3ee2d306)

### Results
Using data collected from 100,000 Zomato customers and their restaurant orders from October 2017 - June 2020 we can conclude: 
  1. Zomato's customer base are young adults, mostly students, with low or no income who are in small families.
  2. The typical customer is a male single student who prefers low cost Indian or Chinese food.
  3. Students account for the highest total sales.
  4. Sales peak on Fridays and in winter months.
  5. Total number of orders have declined since 2017 and each December there is a significant drop in order numbers.

In order to boost order numbers in the current customer base and thus boost sales, the following recommendations were made:
  1. Advertise "Date Night Friday" deals for couples since customers are mostly single or in small families.
  2. Focus Indian and Chinese cuisine ads to single students who prefer these restaurants.
  3. Further investigate the drop in orders in December and run exclusive holiday promotions for select restaurants to boost orders in winter months.
  4. Expand the selection of low cost restaurants to be more accesible to no and low income customers.

### Project Link
https://public.tableau.com/views/ExampleCustomerAnalysis_17394785083460/WhoAreZomatoCustomers?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
