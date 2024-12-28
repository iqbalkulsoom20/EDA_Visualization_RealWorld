# EDA_Visualization_RealWorld

This repository contains my Exploratory Data Analysis (EDA) task using Python Pandas. The project focuses on analyzing titanic dataset sourced from Kaggle, utilizing Jupyter Notebook for coding.

# Overview
The sinking of the Titanic on April 15, 1912, resulted in the loss of 1,502 lives out of 2,224 passengers and crew. While survival was partly due to luck, certain groups were more likely to survive. This task aims to build a predictive model using passenger data (e.g., age, gender, class) to determine which factors influenced survival.

# Data Source
The dataset used for this analysis is sourced from Kaggle. You can find the dataset here : 
https://www.kaggle.com/datasets/yasserh/titanic-dataset?select=Titanic-Dataset.csv

# Python Libraries Used
* Pandas
* Seaborn
* Matplotlib
* Scikit-learn

# Project Details
1. Data Cleaning: The initial step involves cleaning up the dataset to prepare it for analysis. This includes handling missing values, removing duplicates, and ensuring data consistency.
2. Visualization: The insights derived from the data analysis are visually represented using Seaborn and other visualization libraries. This includes creating plots, charts, and graphs to effectively communicate the findings.
# Visualizations
- Bar charts showing the distribution of passengers by **Sex**, **Embarked**, and **Pclass**.
- Histograms illustrating the distribution of **Age** and **Fare**.
- A correlation heatmap for numeric features.
# Insights and Observations
- The dataset showed a significant skew towards male passengers.
- Most passengers embarked from Southampton, with 'C' being the least represented.
- The age distribution had more younger passengers, and there were some significant outliers in the 'Fare' column.
- The correlation heatmap revealed a strong relationship between 'Fare' and 'Pclass', with higher fares typically associated with higher classes.


