# sales
Background and overview:

Chocolate is one of the common items in confectionery. Based on market researrch, 91% of US consumers are willing to pay more for chocolate to fulfill their demands and interest. Chocolate sales reflect not just consumer preferences, but also broader retail trends and purchasing behaviors. Therefore, it is important to analyze the chocolate sales data to explore more opportunity in this market. 

Insights and recommendations are provided on the following key areas:
- Product level performance: an analysis of various chocolate products, understanding their impact on sales and return.
- Regional comparison: an evaluation of historical sales pattern, focusing on revenue return from sales on each country.
- Sales trend analysis: an evaluation of sales and orders from each month across 2022

Data structure and initial checks 
Chocolate's sales data structure contain one table and its features include salesperson, country, product, date, sales amount, and shipping amount with a total row 1095 records. Dataset_link: https://www.kaggle.com/datasets/atharvasoundankar/chocolate-sales

<img width="185" height="143" alt="image" src="https://github.com/user-attachments/assets/abe1c6e9-ac96-4410-989c-25fdbbc924ef" />

Prior to analysis, a variety of checks were conducted for quality control and familiarization with the dataset. Python is utilized to perform dataset cleaning and formalizing. The step is shown as below:

<img width="756" height="191" alt="image" src="https://github.com/user-attachments/assets/5235abe9-6765-435f-9053-422e24a102d0" />

Query is performed afterward to generate the key metrics mentioned in the background and overview:

<img width="1127" height="118" alt="image" src="https://github.com/user-attachments/assets/4b323171-59d3-4391-b979-ef97cf32ab14" />
<img width="796" height="112" alt="image" src="https://github.com/user-attachments/assets/44e02d15-4549-43bb-916b-f9b418b3c00e" />

Each key metric is compiled and convert to CSV for data visualization in tableau.

Executive summary:
Below is the overview page from the Tableau dashboard. The link is shared as below:
https://public.tableau.com/views/chocolatesalesdashboard_17524651718590/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

<img width="1649" height="774" alt="Dashboard 1" src="https://github.com/user-attachments/assets/b920d5a0-2c0b-4d9e-b822-b566c62ecc77" />

Regional comparison:
1. Australia leads in total sales with $1.14M, followed by the UK ($1.05M) and India ($1.05M).
2. Boxes shipped are also highest in Australia (32,647), while New Zealand and USA have the lowest shipping volumes (~26K each).
3. Australia shows strong demand and volume, indicating high customer engagement and distribution efficiency.

Monthly Sales Trend
1. January 2022 was the best-performing month with $896K in chocolate sales.
2. April had the lowest sales at $674K, but sales recovered steadily in May and June, peaking again at $865K.
3. Sales exhibit moderate seasonality. Q1 (Jan–Mar) performs strongly, while Q2 sees a slight dip followed by recovery. This suggests potential promotional or seasonal campaign opportunities in April.

Product level performance:

1.The top 3 products by total sales amount are, Smooth Silky Salty ($394,692), 50% Dark Bites ($341,712), White Choco ($329,14).

2.Products with lower performance include Caramel Stuffed Bars and 70% Dark Bites.

3.Dark bite chocolate have large performance gap, which 50% sales performance is better than 70% dark bites, indicating the customers' perference are more towards mild favour chocolate. 

Recommendation for uncovered insight:
1. Deep dive in the product level performance to extract top sell products in each month and each country.
2. Evaluate underperform products to investigate customer feedback for Caramel Stuffed Bars and 70% Dark Bites. 


