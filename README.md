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
1.Some columns have recorded NULL values: online_order, brand, product_line, product_class_product_size, standard_cost and product_first_sold_date.<br>
2.Irrelevant columns to my analysis: online_order, product_first_sold_date.<br>
Customeraddress dataset<br>
1. Some states are recorded as Victoria, Newsouthwales instead of VIC and NSW respectively.<br>

Customerdemographic dataset<br>
1.Irrelevant columns such as deceased_indicator and default.<br>
2.Some genders are recorded as F,Female,M, instead of Male or Female.<br>
3.Some genders are recorded as U.<br>
4.Missing values in columns last_name, DOB,job_title,job_industry_category.<br>

Data cleaning steps<br>
1.Dropping rows with missing values.<br>
2.Dropping columns not relevant to my analysis.<br>
3.Replacing genders recorded as F, Femal and M as either Male or Female.<br>
4.Dropping genders recorded as U.<br>
5.Replacing recorded states as Victoria, Newsouthwales as VIC and NSW.<br>
6.Joining the three datasets into one clean dataset.<br>




