# KPMG-SPROCKET-DATASET
Used python to clean and analyze the dataset.

The dataset contains data about medium size bikes & cycling accessories and also customer and transactions data.<br>
The project contains 3 datasets:<br>

Customer Demographic<br>
Customer Addresses<br>
Transactions data<br>

The following were the issues i found:<br>

Quality issues<br>

Transactions dataset<br>
1.Some columns have recorded NULL values: online_order, brand, product_line, product_class_product_size, standard_cost and product_first_sold_date.
2.Irrelevant columns to my analysis: online_order, product_first_sold_date.
Customeraddress dataset
1. Some states are recorded as Victoria, Newsouthwales instead of VIC and NSW respectively.
Customerdemographic dataset
1.Irrelevant columns such as deceased_indicator and default.
2.Some genders are recorded as F,Female,M, instead of Male or Female.
3.Some genders are recorded as U.
4.Missing values in columns last_name, DOB,job_title,job_industry_category.
Data cleaning
1.Dropping rows with missing values.
2.Dropping columns not relevant to my analysis.
3.Replacing genders recorded as F, Femal and M as either Male or Female.
4.Dropping genders recorded as U.
5.Replacing recorded states as Victoria, Newsouthwales as VIC and NSW.
6.Joining the three datasets into one clean dataset.




