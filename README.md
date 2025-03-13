# Dataset Description - Depression Analysis

## Overview  
This dataset explores the relationship between various demographic, lifestyle, and health-related factors with depression. It includes data on individuals' age, marital status, number of children, smoking habits, physical activity levels, employment status, income, alcohol consumption, dietary habits, sleep patterns, history of mental illness, chronic medical conditions, and a depression indicator that highlights whether an individual is experiencing depression.  

## Dataset Details  
- **Total Rows:** 599  
- **Total Columns:** 13  

## Attributes  
The dataset contains the following attributes:  
- **Age** – Age of the individual  
- **Marital Status** – Whether the individual is single, married, divorced, etc.  
- **Number of Children** – The number of children the individual has  
- **Smoking Habits** – Whether the individual smokes or not  
- **Physical Activity Levels** – Frequency and intensity of physical activity  
- **Employment Status** – Whether the individual is employed, unemployed, or retired  
- **Income** – The individual's income level  
- **Alcohol Consumption** – Frequency of alcohol intake  
- **Dietary Habits** – Quality and type of diet followed  
- **Sleep Patterns** – Average sleep duration and quality  
- **History of Mental Illness** – Whether the individual has a history of mental illness  
- **Chronic Medical Conditions** – Presence of chronic illnesses  
- **Depression Indicator** – Whether the individual is experiencing depression (Yes/No)  

## Purpose  
This comprehensive dataset is ideal for studying the correlation between lifestyle and health patterns and mental health outcomes, particularly depression. It can support:  
- **Predictive Modeling** – Building machine learning models to predict depression likelihood  
- **Health Insights** – Identifying key factors influencing mental well-being  
- **Policy & Intervention Strategies** – Assisting in designing targeted mental health interventions  

This dataset provides valuable insights into mental health trends and factors that contribute to depression, making it useful for researchers, healthcare professionals, and policymakers.

## Best Model
This dataset is well-suited for MLP (Neural Network) because it contains both categorical and numerical features, which MLPs handle well after encoding. The dataset likely has complex, non-linear relationships, which neural networks excel at capturing.  
**Best Accuracy Achieved: 89%**

## Reason:
- **MLP Hyperparameter Tuning with GridSearchCV** – Tuned the number of layers, neurons per layer, activation functions, and learning rate, allowing the model to find an optimal setup.
- **Sufficient Data Size** – With 599 samples, the dataset is large enough for an MLP to generalize well.
- **Captures Complex Relationships** – MLP excels at learning non-linear patterns, making it better than simpler models like Naïve Bayes or Linear Regression.
