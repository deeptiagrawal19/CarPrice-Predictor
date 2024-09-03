# Car Price Predictor

## Introduction

This project aims to predict the price of used cars based on various features available in a dataset. The dataset contains information on the sale of more than 1000 used cars and consists of 10 columns and 1435 rows.

## Context

To predict the price of a used car, a model is required which factors in all the variables from the dataset. The dataset contains both numerical and categorical features which are preprocessed to prepare for model training.

## Dataset

The dataset `CarSales.csv` includes the following features:
- `Age`: Age of car in years
- `KM`: Distance driven in kilometers
- `HP`: Power of the engine
- `CC`: Volume of the engine
- `Weight`: Weight in kilograms
- `MetColor`: Metallic paint (1 for yes, 0 for no)
- `Automatic`: Transmission type (1 for automatic, 0 for manual)
- `FuelType`: Type of fuel (Petrol, Diesel, CNG)
- `Doors`: Number of doors
- `Price`: Selling price of the car (target variable)




## Requirements

To run this project, you need the following libraries:
- pandas
- seaborn
- matplotlib

You can install the required libraries using the following command:

```sh
pip install -r requirements.txt
