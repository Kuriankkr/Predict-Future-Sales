# Predict Future Sales

## Overview
This is one of my side projects that I had worked with sourcing data form Kaggle. I like to use data science specifically to predict the sales of items(an area of my interest), be it tractors like in the project below or in this project where the goal was to predict the total amount of products sold in every shop for a supermarket chain. I had borrowed techniques from other fellow Kagglers (mentioned in the credits) and learnt a lot on the kind of strategies and technique that one should look into during feature engineering. This notebook focuses heavily on feature engineering that captures the trend of previous sales  

## Objective 

(taken from [Kaggle](https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview))

We are asking you to predict total sales for every product and store in the next month. By solving this competition you will be able to apply and enhance your data science skills.
You are provided with daily historical sales data. The task is to forecast the total amount of products sold in every shop for the test set. Note that the list of shops and products slightly changes every month. Creating a robust model that can handle such situations is part of the challenge.

## Dataset

The link for the dataset is given [here](https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data). The data is sourced from Kaggle that was provided by [1C Company](https://1c.ru/eng/title.htm)(Russian software firm) and it was part of a competition that was hosted by Kaggle.

- **sales_train.csv:**  *The training set. Daily historical data from January 2013 to October 2015.*
- **test.csv:** *The test set. You need to forecast the sales for these shops and products for November 2015.*
- **sample_submission.csv:**  *A sample submission file in the correct format.*
- **items.csv:** *Supplemental information about the items/products.*
- **item_categories.csv:** *Supplemental information about the items categories.*
- **shops.csv:** *Supplemental information about the shops.*


## Data fields description:
- **ID:** *An Id that represents a (Shop, Item) tuple within the test set*
- **Shop_id:** *Unique identifier of a shop*
- **Item_id:** *Unique identifier of a product* 
- **Item_category_id:** *Unique identifier of item category*  
- **Date_block_num:** *A consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33* 
- **Date:** *Date in format dd/mm/yyyy*
- **Item_cnt_day:** *Number of products sold. You are predicting a monthly amount of this measure*
- **Item_price:** *Current price of an item*
- **Item_name:** *Name of item*
- **Shop_name:** *Name of shops* 
- **Item_category_name:** *Name of item category*  
 

## Credits

**Note:** This notebook has been done with help from Coursera course 
[How to Win a Data Science Competition: Learn from Top Kagglers](https://www.coursera.org/learn/competitive-data-science)


and also with help from the following links

- [Link 1](https://www.kaggle.com/dlarionov/feature-engineering-xgboost)
- [Link 2](https://www.kaggle.com/kyakovlev/1st-place-solution-part-1-hands-on-data)

## Technology Used
<p>
  <img width="500" height = "250" align='left' src="https://github.com/Kuriankkr/Predict-Future-Sales/blob/master/Images/Pandas_Image.png">
</p>



