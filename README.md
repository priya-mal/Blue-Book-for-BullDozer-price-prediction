# Blue-Book-for-BullDozer-price-prediction using machine learning

## **Introduction:**

This project aims to predict the sale price of Bulldozers using **machine learning models**. Since the output variable  we are trying to predict is a number.
This kind of problem is known as a ***regression problem***

You can check the complete code from [Github repository](https://github.com/priya-mal/Blue-Book-for-BullDozer-price-prediction). The approach is inspired from zerotomatery.io

## **Data:**

The data and evaluation metric used is (root mean square log error or RMSLE) as this is a constraint from the [Kaggle Bluebook for Bulldozers competition](https://www.kaggle.com/c/bluebook-for-bulldozers/overview).

Looking at the dataset, we can understand that there's a time attribute to dataset. So  it is ***Time series problem.***

There are 3 datasets:

1. **Train.csv** - Historical bulldozer sales examples up to 2011 (close to 400,000 examples with 50+ different attributes, including `SalePrice` which is the target variable).
2. **Valid.csv** - Historical bulldozer sales examples from January 1 2012 to April 30 2012 (close to 12,000 examples with the same attributes as Train.csv).
3. **Test.csv** - Historical bulldozer sales examples from May 1 2012 to November 2012 (close to 12,000 examples but missing the `SalePrice` attribute, as this is what we'll be trying to predict).
