# TATA-Data-Visualization

## Client's Background
Tata is a multinational conglomerate headquartered in India. Established in 1868, It stands as one of India's largest and most diversified enterprises, operating in over 100 countries. Tata's business portfolio spans various sectors, including automotive, consumer products, engineering, energy, materials, services, and technology.

## Business Problem
Tata's online store is encountering difficulties in managing its revenue data, which has hampered decision-making and limited its ability to seize business opportunities. The CEO/CMO has highlighted several key issues:
- The need to analyze and understand the monthly revenue data for 2011 to identify and investigate seasonal trends, aiding in accurate forecasting for the next year.
- Idenify the top 10 revenue-generating countries and the corresponding quantities sold.
- Identify and target the top 10 revenue-generating customers to ensure their continued satisfaction with the products.
- Gain insights into product demand across all countries, excluding the United Kingdom, to identify regions with the highest demand. This information will inform an expansion strategy aimed at targeting these high-demand areas to generate more business.



## The Data Summary
The dataset for this task was gotten from [Forage](https://www.theforage.com/virtual-experience/MyXvBcppsW2FkNYCX/tata-group/data-visualisation-p5xo/framing-the-business-scenario). It consist of 541,910 rows and 8 columns containing the following information:
- InvoiceNo- This column has the invoice number of each purchase made by customers.<br>
- StockCode- This column has the product stock code.<br>
- Description- This column has the product description and information.<br>
- Quantity- This column tells us the amount of products purchased.<br>
- InvoiceDate- This column has dates from when the purchase happened. <br>
- UnitPrice- This column has the price per unit of the product.<br>
- CustomerID- This column tells us who purchased the product in numerical form.<br>
- Country- This column tells us where the customer resides.<br>

## Data Cleaning and Transformaion
After downloading and thoroughly understanding the dataset, I undertook several steps to clean, transform and prepare the data for analysis. This process is crucial to ensure the accuracy and insightfulness of the data.
- The dataset was checked for duplicate rows, and none were found.
- The columns were reviewed to ensure they had the appropriate data types, and where necessary, were converted to text or numbers.
- Removed Rows in the Quantity column showing negative numbers or below 1.<br>
- Removed Rows in the UnitPrice column that are below $0.<br>
- Removed Rows with blanks.<br>
- Revenue Column was added by multiplying UnitPrice with Quantity.<br>

### Tools Used
Power Query - Data Cleaning and adding new column. <br>
Power BI - Creating Visualization.


## Communicating Insights
1. The CEO wants to view granular revenue data for each month in 2011.

![alt text](https://i.postimg.cc/KYVbg0RQ/Tata-Q1.png)
For the year 2011, November generated the highest revenue at $1,509,496, the lowest revenue was recorded in February with a total of $523,631. A notable increase begins in September, with revenue rising by 40% compared to August. This upward trend continues, and peaked in November at $1.5 million. Although, December's data is incomplete and we cannot draw any conclusions for that month, it indicates a promising month. This analysis indicates significant growth in certain months and highlights a seasonal impact on sales, with significant growth occurring in the last four months of the year. 

2. The CMO is interested in viewing the top 10 countries(excluding United Kingdom) generating the highest revenue along with the quantity sold.

![alt text](https://i.postimg.cc/C54LDjy1/Tata-Q2.png)
Among the top 10 countries, excluding the United Kingdom, the Netherlands ranked highest in both revenue and quantity, with figures amounting to $276,661.86 and 193,550 units, respectively. Conversely, the country with the lowest Revenue and Quantity is Norway, with a total of $32378.32 and 15754 respectively. This insight sheds light on the performance of countries with growth potential. Notably, countries such as the Netherlands, Ireland, Germany, and France demonstrate high volumes of units bought and revenue generated.

3. The CMO of the online retail store wants to view the information on the top 10 customers by revenue.

![alt text](https://i.postimg.cc/CMr2MRnH/Tata-Q3.png)
From the analysis, Customer ID 14646 stands out as the highest revenue-generating customer, with a total of $271614.14, while  Customer with ID 16029 generated the least revenue, amounting to $67912.32. Interestingly, there isn't a significant disparity in purchases among these top customers. The highest revenue-generating customer only purchased 17% more than the second highest, indicating that the business does not overly rely on a few customers for revenue generation.

4. The CEO is looking to gain insights into all countries and the demand for their products.

![alt text](https://i.postimg.cc/cLPnwKtK/Tata-map-Question-4.png)
The map chart illustrates regions with the highest revenue generation compared to those with lower revenues. Apart from the UK, countries such as the Netherlands, Ireland, Germany, France, and Australia are notably contributing to high revenue. The company should consider investing more resources in these areas to stimulate further demand for its products. The map also highlights that the majority of sales occur within the European region. A new strategic approach targeting other regions could potentially enhance sales revenues and overall profitability. Additionally, the country with the highest quantity sold is the Netherlands, totaling  193,550  units.

## The Dashboard
![alt text](https://i.postimg.cc/WbJQkChv/Tata-Final-Dashboard.png)

## Recommendations.
1. Although the data for December is incomplete, it indicates a promising month as monthly revenue shows a significant upward trend during the -ber months (September to November), likely due to the Christmas holiday season. Considering the substantial revenue surge observed in tthese months, it is advisable to initiate targeted marketing campaigns commencing in late August. This strategic approach will enable the company to leverage the seasonal upswing in sales effectively.I recommend introducing special promotions, discounts, and bundled deals during peak months that can further stimulate sales and maximize revenue.
2. The Netherlands generates the highest revenue and quantity of purchases. The company should consider intensifying its marketing efforts in the Netherlands as this is where substantial volume and revenue are already generated. 
3. Growth initiatives should also be targeted at Ireland, Germany, and France and Australia, the company has a significant customer base that we can tap into for expansion opportunities. This can involve localized marketing campaigns, partnerships with local retailers, and customized product offerings.
4. Maintain strong relationships with top customers, as they are loyal and contribute significantly to revenue. Offering special incentives can help retain their loyalty. Implementing retention strategies such as loyalty programs, regular follow-ups, and personalized offers will also help maintain a steady revenue stream from these customers. Additionally, further investigation is needed to understand the customers with lower revenue and identify potential strategies to increase their contributions.


 


