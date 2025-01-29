# Dynamic Pricing Model for Ride-Sharing Company

## Overview 

This repository contains a dynamic pricing model for a ride-sharing company. The model predicts the optimal fare for a ride based on historical data and real-time market conditions such as demand patterns and supply availability.

### Project Overview

The goal of this project is to develop a predictive model that adjusts ride fares dynamically using a variety of features including ride duration, the number of riders, the number of drivers, location category, customer loyalty status, and vehicle type, among others. The model uses machine learning algorithms to predict ride costs based on historical data and features related to the current market conditions.

### Dataset Overview

The dataset contains 1,000 entries and the following features:

| **Feature**                | **Description**                              |
|----------------------------|----------------------------------------------|
| `Number_of_Riders`         | Number of riders requesting rides.           |
| `Number_of_Drivers`        | Number of available drivers.                 |
| `Location_Category`        | Urban, Suburban, or Rural.                   |
| `Customer_Loyalty_Status`  | Loyalty level of the customer (e.g., Gold).  |
| `Number_of_Past_Rides`     | Number of rides completed by the customer.   |
| `Average_Ratings`          | Customer’s average rating.                   |
| `Time_of_Booking`          | Time of day when the booking was made.       |
| `Vehicle_Type`             | Type of vehicle (Economy or Premium).        |
| `Expected_Ride_Duration`   | Predicted duration of the ride (in minutes). |
| `Historical_Cost_of_Ride`  | Actual cost of the ride (in currency).       |

### Model Evaluation Results:

After training the model, the following evaluation metrics were calculated:

- RMSE (Root Mean Squared Error): 75.45
- R² (R-squared): 0.839

These results indicate that the model does a good job of predicting ride costs with a relatively high R² score and an acceptable RMSE value.

### Feature Importance

![screenshot-localhost_8888-2025 01 29-13_25_41](https://github.com/user-attachments/assets/193ef012-a2c8-4b40-bd40-80a89aae6fdc)

### Source

Dataset: [Dynamic Pricing Dataset on Kaggle](https://www.kaggle.com/datasets/arashnic/dynamic-pricing-dataset)
