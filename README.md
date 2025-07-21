# Cafe-Sales-Data-Cleaning

Project: Cleaning a Dataset of Sales from a Cafe using Python

## Introduction

Dataset obtained from: [Kaggle](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training)

I worked on a synthetic dataset obtained from Kaggle for practising and showing my skills and knowledge by using Python. The data represent the sales transaction from a café, having 10,000 rows containing some missing values, inconsistent data, and errors.

## Data Cleaning Steps

- Rename the columns to snake type.
- Replace the UNKOWN and Error with Null values.
- Changing the data type of the quantity, price per unit, and total spent columns, from object to integers.
- Convert the transaction date to data time format.
- Check that the price list from the menu corresponds to the item, and viceversa.
- Data imputation
    - Fill the Null values from quantity and price per unit columns with the mean from these.
    - To preserve the data, I changed the Null values with Unknown in the item, payment method, and location columns
- Dropping Null values left

## Results

Going from a dataset with uneven rows, wrong data format, and inconsistencies, to a nicely dataset ready for further feature engineering and exploratory data analysis. The dirty dataset contains 10,000 rows but most of the columns were incomplete, and the clean one contains 9540 rows in all the columns, dropping only 460 rows due to the transaction date columns
