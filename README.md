# Predict Future Sales

## Objective 

(taken from Kaggle)

We are asking you to predict total sales for every product and store in the next month. By solving this competition you will be able to apply and enhance your data science skills.
You are provided with daily historical sales data. The task is to forecast the total amount of products sold in every shop for the test set. Note that the list of shops and products slightly changes every month. Creating a robust model that can handle such situations is part of the challenge.

## Data fields description:¶
- ID - an Id that represents a (Shop, Item) tuple within the test set
- shop_id - unique identifier of a shop
- item_id - unique identifier of a product
- item_category_id - unique identifier of item category
- date_block_num - a consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33
- date - date in format dd/mm/yyyy
- item_cnt_day - number of products sold. You are predicting a monthly amount of this measure
- item_price - current price of an item
- item_name - name of item
- shop_name - name of shop
- item_category_name - name of item category

Note: This notebook has been done with help from Coursera course 
How to Win a Data Science Competition: Learn from Top Kagglers and also with help from the following notebooks

https://www.kaggle.com/dlarionov/feature-engineering-xgboost

https://www.kaggle.com/kyakovlev/1st-place-solution-part-1-hands-on-data

