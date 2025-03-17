# sales-dashboard
The dataset describes a chocolate company aiming to enhance sales by analyzing five months of provided data. This data is organized into four distinct tables: locations, people, products, and sales. Each table focuses on specific aspects of the company.

Detail:

_Locations Table_:

Includes information about the geo (country) and the associated region (e.g., Asia, America, Europe).

_People Table_:

Identifies the salespeople and their corresponding teams, like Yummies, Delish, and Juices.

_Products Table_:

Lists chocolate categories (Bites, Bars, Other), their cost per box in dollars, and different product variants.

_Sales Table_:

Captures details such as sales amounts, number of boxes sold, customer count, sales date, country, product variant, and the salesperson responsible.

The company aims to uncover trends and reasons behind sales growth using this structured data.


now here is the data visualized:

_KPI_:

Total cost : 32.56k [total cost = SUM(sales5[cost])]
Total amount : 78k [total amount = SUM(sales5[Amount])]
Total profit : 45k [total profit = [total amount]-[total cost]]
Profit ratio : 58.17% [profit ratio = DIVIDE([total profit],[total amount],0)]

_key visualizations_:

clustered column chart : Total cost and profit by Region (UK, Australia, India, USA, Canada ,New Zealand)
lines chart : Total profit by month and day
Pie chart : Total boxes by category ( bars, bites , other)
stacked bar chart: Total profit of top five products(99% Dark & pure,85% Dark Bars,Peanut Butter cubs ,Caramel stuffed Bars, Mint Chip Coco)

_Slicers_:

Months , sales person 
