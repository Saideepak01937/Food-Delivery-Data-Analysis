# Food-Delivery-Data-Analysis
Overview
An end-to-end analysis of food delivery order data to understand order trends, delivery performance, customer behavior, and business insights.

Tools Used
Python (Pandas, Google Colab), MySQL, Power BI

What I Did
Cleaned and transformed the raw dataset using Python and Pandas
Imported the cleaned dataset into MySQL
Performed data analysis using SQL queries
Created an interactive Power BI dashboard to visualize key metrics and trends


Key Insights
-Total number of orders: 50K orders placed by 5K customers, across 250 restaurants and 200 delivery partners.

Total revenue: 1.91M in total order value (average order value 38.17), plus 79.11K in tips and 70.35K in discounts. The dashboard shows order value rather than platform revenue, so I used “total order value” here.
Key order and delivery trends: --The average estimated delivery time is 30.95 min, but the actual average is 35.15 min, so deliveries run about 4 min over the estimate. --About 37% of deliveries are late (~18K orders), and the cancellation rate is about 2%. --Delivery time rises with traffic (~31 min Low, ~35 Medium, ~40 High) and with weather (~34 min Clear to ~47 min Storm).
Top-performing category or location: --Burger is the top category, with ~16K orders and ~0.55M in order value. Local is second (~12.8K orders, ~0.47M). --City A is the top location, with ~20K orders (about 40% of the total). City D has the highest average order value (~43) but the fewest orders (~5K).
Other important findings: --Regular customers account for 50% of orders and ~1.0M in order value, while Premium customers have the lowest average order value (~34). --The 20–29 age group places about 48% of all orders. --Credit card is the leading payment method (~0.95M) and also generates most tips. Cash tips are under 1% of cash order value. --Storms raise the cancellation rate to ~3.7%, about 2.6x the rate in clear weather. --Driver experience has almost no effect on delivery time or rating (~35 min and ~4.5 across all experience groups).

Dashboard Preview
Executive Overview 
<img width="842" height="526" alt="Screenshot 2026-11-20 115639" src="https://github.com/user-attachments/assets/fb797ce1-1dea-4fa9-bc99-2abb3349e119" />
Customer Analytics 
<img width="847" height="527" alt="Screenshot 2026-11-20 115927" src="https://github.com/user-attachments/assets/9ed8579a-7db1-4e1d-bfc0-5be08505ef5f" />
Restaurant Analytics
<img width="847" height="530" alt="Screenshot 2026-11-20 115941" src="https://github.com/user-attachments/assets/07c25ede-dc3d-4f57-829b-9078afb3c8e9" />
Driver Analytics
<img width="848" height="531" alt="Screenshot 2026-11-20 115954" src="https://github.com/user-attachments/assets/43439922-4b78-4377-8df2-c994c6bfca31" />
Logistics & ETA 
<img width="843" height="525" alt="Screenshot 2026-11-20 120013" src="https://github.com/user-attachments/assets/9913e8e3-f357-4c2a-96a4-2c39cda70f85" />
Financial Analysis
<img width="845" height="526" alt="Screenshot 2026-11-20 120027" src="https://github.com/user-attachments/assets/328baa11-4093-4e09-a13a-a3bcc21e526c" />
Overall Data Overview
<img width="847" height="527" alt="Screenshot 2026-11-20 120048" src="https://github.com/user-attachments/assets/36b35cdc-5a4c-4095-b315-faa519e04141" />

Files
Dataset/ : food_delivery_raw.csv
cleaned Dataset/ : food_delivery_cleaned.csv
Python_Analysis/ : Food_Delivery_Analysis.ipynb
SQL/ : SQL_Python_Integration.py
PowerBI/ : Food_Delivery_Dashboard.pbix
Images/ : Dashboard screenshots
