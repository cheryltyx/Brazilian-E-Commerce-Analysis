# Brazilian-E-Commerce-Analysis
## About
This is a mini project for Data Science and Artificial Intelligence(CZ1115).
This project has the aim of exploring data from Olist, a Brazilian E-commerce marketplace, to recommend to new sellers how they can potentially maximise thier profits and sales. 
## Contributors
Tiyyagura Rochana\
Tan Ying Xia Cheryl\
Nan Shi Yuan
## Problem Definition
**POV: As a seller entering the OList Marketplace, how can one potentially maximise sales and profits?**
* Do certain geographical locations generate more revenue?
* Do certain products generate more revenue?
* Do certain time period generate more revenue?
## Project Summary
* Dataset used
  - olist_customers_dataset
  - olist_geolocation_dataset
  - olist_order_items_dataset
  - olist_order_payments_dataset
  - olist_order_reviews_dataset
  - olist_orders_dataset
  - olist_products_dataset
  - olist_sellers_dataset
  - product_category_name_translation

* Utilised 3 Machine Learning Models namely
  1. Random Forest Classifier Model
  2. CatBoost Regressor Model
  3. Random Forest Regression Model

* Used visualization libraries (Bokeh, Plotly and Cufflinks)
* Data Cleaning (rectification of misspelt words, checks for missing/NA values)
* Identification and removal of outliers and anomalies
* Removal of noise for more accurate feature importance
* Data Preparation (data merging, selection of attributes for use with ML models)


## Conclusion
* Based on demand and supply: ‘watches and gifts’ have the most number of sales
* A graph showing which product has highest demand in each month has also been created
* Based on Geospatial Analysis, we see that the states of SP, RJ, and, ES respectively have the most revenue generated
* While there is no strong correlation between number of sales and review scores, we still recommend that sellers maintain a score > 3.5 as this is the trend for high number of sales

## Distribution Of Work
Nan Shi Yuan : Data Preparation and Products Analysis\
Tan Ying Xia Cheryl: Random Forest Classifier and Regression and Sales Analysis\
Tiyyagura Rochana : Geospatial Analysis and CatBoost Regressor Model
	
	




