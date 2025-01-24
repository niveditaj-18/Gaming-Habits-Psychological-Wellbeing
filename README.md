# Gaming-Habits-Psychological-Wellbeing
This project explores gaming habits and their impact on psychological well-being using data from over 13,000 gamers across 109 countries. Machine learning models like Logistic Regression, Random Forest, and Gradient Boosting predict anxiety levels while uncovering correlations between gaming behavior, socio-economic factors, and mental health.

## Overview
This project explores the relationship between gaming habits and the psychological well-being of over 13,000 gamers from 109 countries. Using machine learning models, the project predicts anxiety levels and uncovers key correlations between socio-economic factors, gaming behaviors, and psychological metrics.

## Features
1. **Key Predictors**:
   - Hours played per week.
   - Gaming platform (PC/Mobile).
   - Motivation for gaming (Fun/Competitive).
   - Demographics: Age, Gender, Education level, Employment status.
2. **Machine Learning Models**:
   - Logistic Regression: 85% accuracy.
   - Random Forest: 84.88% accuracy.
   - Gradient Boosting: 84.56% accuracy.
3. **Visualization**:
   - Geographic distribution of gamers.
   - Correlation matrix for psychological metrics.
   - Gaming hours histogram and life satisfaction plots.

## Dataset
- **Description**:
  - 13,000+ gamers from 109 countries.
  - Psychological metrics: Anxiety, Life Satisfaction, Social Phobia.
  - Demographics: Age, Gender, Country, Education, Employment.
  - Gaming behaviors: Hours played, Platforms, and Motivation.

## Methodology
1. **Data Preprocessing**:
   - Removed irrelevant columns and handled outliers.
   - Imputed missing values and standardized categorical data.
2. **EDA**:
   - Explored relationships between gaming behaviors and psychological metrics.
   - Identified patterns in anxiety, life satisfaction, and social phobia.
3. **Modeling**:
   - Gradient Boosting, Random Forest, and Logistic Regression.
   - Evaluated using Accuracy and AUC-ROC scores.
4. **Visualization**:
   - Geographical maps, histograms, boxplots, and correlation matrices.

## Results
1. **Top Predictors**:
   - SPIN_T, SWL_T, and hours played emerged as the most influential factors.
2. **Best Model**:
   - Logistic Regression with hyperparameter tuning achieved the highest accuracy (85%).
3. **Insights**:
   - Significant gaming behaviors like hours played and streams strongly correlate with anxiety levels.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn
- **Data Source**: International survey dataset of gamers


