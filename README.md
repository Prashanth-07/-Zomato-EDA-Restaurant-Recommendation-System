# Zomato EDA Restaurant Recommendation System

## Overview

This repository contains the code and findings for a restaurant recommendation system developed for Zomato, a leading food delivery platform. The project includes exploratory data analysis (EDA) and the development of a machine learning model to provide personalized restaurant recommendations based on user preferences, past orders, and location.

## Key Findings

1. **Popular Cuisines**: The top three cuisines among users are North Indian, Chinese, and Fast Food.
2. **Enhancing Revenue through Strategic Service Offerings**:
   - Online Delivery: 7100 restaurants offer online delivery services, while 2451 do not.
   - Table Booking: 8393 restaurants offer table booking services, with 1158 not providing this option.
3. **Location-based Insights**: 
   - Top Cities: Delhi, Noida, and Gurugram have the highest number of restaurants and total orders.
   - Average Order Value: Hyderabad, Kolkata, and Bangalore exhibit higher average order values.
4. **Average Cost Optimization**: The correlation between average cost for two and aggregate rating is weak (0.052), indicating minimal impact of pricing on customer satisfaction.
5. **Top Countries**: India leads in transaction counts, reflecting higher demand for food delivery services.
6. **Number of Cities Placing Orders**: India has a greater number of cities placing food orders compared to other countries.
7. **Average Ratings**: Customers typically give ratings ranging from 2.8 to 4.1 on average.

## Model Building

### Data Preprocessing
- Handled missing values and encoded categorical variables.

### Machine Learning Model
- Developed a Random Forest Regressor model.
- Achieved \(R^2\) score of 0.891.

### Dependencies
Python 3
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook
