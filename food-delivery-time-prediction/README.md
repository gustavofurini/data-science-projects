# Food Delivery Time Prediction

This project leverages machine learning to predict **food delivery times** based on a variety of order, customer, and environmental features. The workflow encompasses data cleaning, exploration, feature engineering, model training, and evaluation to forecast delivery durations accurately.

## Project Objectives

- **Identify key factors** influencing food delivery time.
- **Develop accurate regression models** to predict delivery duration.
- **Provide insights** to help optimize logistics and customer satisfaction.

## Context and Business Problem

Timely delivery is a critical metric in the food delivery industry, impacting customer satisfaction, retention, and operational efficiency. Late deliveries can lead to unhappy customers, negative reviews, and financial losses.

- **Analyzed factors**: Order time, delivery distance, traffic density, weather conditions, vehicle type, restaurant preparation time, and courier experience years.
- **Expected impact**:
  - Enhance ETA (Estimated Time of Arrival) predictions for customers.
  - Optimize route planning and resource allocation.
  - Improve performance tracking and service reliability.

## Dataset

- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/shivamb/food-delivery-time)
- **Key features**:
  - Order Date and Time
  - Delivery Distance (km)
  - Restaurant Preparation Time (minutes)
  - Weather Conditions and Traffic Density
  - Delivery Vehicle Type
- **Target variable**: Delivery Time (minutes)
- **Dataset size**: ~4,500 records

## Technologies and Libraries

- **Language**: Python
- **Libraries**:
  - Data manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Modeling: `scikit-learn`
  - Others: `datetime`, `warnings`

## Methodology

1. **Data preprocessing**:
   - Handled missing and inconsistent values.
   - Encoded categorical variables.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized distribution of delivery times.
   - Analyzed the impact of features like distance and traffic.

3. **Model training**:
   - Regression models tested: XGBoost.

4. **Evaluation metrics**:
   - Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R² Score, Mean Squared Error (MSE).

5. **Model optimization**:
   - Hyperparameter tuning with GridSearchCV.

## Key Findings

- **Key influencers on delivery time**:
  - Traffic density and weather conditions have significant impact.
  - Longer preparation time and distance directly increase delivery time.
  - Certain vehicle types (e.g., motorbikes) are faster in heavy traffic.

- **Actionable insights**:
  - Recommend optimal vehicle types per area and time slot.
  - Adjust preparation estimates based on historical data.
  - Offer dynamic ETAs and manage customer expectations.

## Results
- **Mean Absolute Error:** 4.88
- **Mean Squared Error:** 49.10
- **R2:** 0.90
- **Raiz Mean Squared Error:** 7.01