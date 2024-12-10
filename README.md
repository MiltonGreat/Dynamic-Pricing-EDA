# Dynamic-Pricing-EDA

### Overview 

This project focuses on building a dynamic pricing model for a ride-sharing service using historical ride data. The goal is to implement a data-driven pricing strategy that optimizes fares based on real-time market conditions while considering factors like demand, supply, ride duration, and customer loyalty.

### Project Objectives

1. **Exploratory Data Analysis (EDA):**
   - Understand the dataset through statistical summaries and visualizations.
   - Identify key factors influencing ride costs.

2. **Feature Engineering:**
   - Transform raw data into meaningful features, including one-hot encoding of categorical variables and scaling of numerical features.
   - Create derived metrics like the demand-supply ratio.

3. **Pricing Strategies:**
   - **Rule-Based System:** Define base pricing rules based on expected ride duration.
   - **Fuzzy Logic:** Incorporate fuzzy logic to adjust prices dynamically based on demand and supply patterns.

4. **Predictive Modeling:**
   - Train machine learning models to predict optimal ride fares.
   - Evaluate model performance using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score.

5. **Dynamic Pricing Simulation:**
   - Simulate real-world scenarios to adjust prices dynamically and optimize revenue.

6. **Data Visualizations:**
   - Explore ride patterns and trends using a variety of plots, including correlation heatmaps, scatter plots, and interactive visualizations.

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

### Source

https://www.kaggle.com/datasets/arashnic/dynamic-pricing-dataset
