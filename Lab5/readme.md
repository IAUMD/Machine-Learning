# ARTI308 Lab 5 – Feature Engineering for Order Status Prediction

## Overview
This lab builds a baseline classification model to predict `Order_Status` using the dataset `talabat_enhanced_orders.csv`. The dataset is already clean, so the focus is on feature engineering and understanding how engineered features affect model performance and feature importance.

Each row in the dataset represents a single food delivery order and includes information about the customer, restaurant, driver, order timing, pricing, and final order outcome.

## Objective
Predict the target variable:

Order_Status*

Possible classes:
- Delivered
- Cancelled
- In Transit

The goal is to build a baseline model and analyze how engineered features influence predictions.

## Dataset
File used:

talabat_enhanced_orders.csv

Characteristics of the dataset:
- No missing values
- No duplicate rows
- Consistent data types
- Order level delivery data including timing, price, distance, and categorical attributes

Because the dataset is already clean, the lab focuses primarily on feature engineering rather than data cleaning.
