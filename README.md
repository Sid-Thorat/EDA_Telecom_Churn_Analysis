# Telecom-Churn-Analysis-EDA<br>
![ezgif com-gif-maker](https://github.com/Sid-Thorat/EDA_Telecom_Churn_Analysis/assets/126258682/da5f5da0-3037-43dc-b085-cb4fe4810ef0)

This repository contains an exploratory data analysis (EDA) project focused on the root causes of customer churn in telecommunication industry, addressing the pain points, and strategica
lly re-engaging with churned users.This case is related to telecom industry where particular organizations want to know that for given certain parameters whether a person will churn or not.

# Problem Statement
In the era of rapid technological advancement, telecommunications corporation, faces a pressing challenge of customer churn.Customer churn, in this context, refers to the phenomenon where subscribers discontinue their telecom services.This telecom churn analysis dataset will help you to understand and explore various factors responsible for customer churn.This dataset contains information like whether a customer churned the network according to states,account length,area code, opting for internation plan,voice mail plan,customer service calls, total day, evening, night, international calls,minutes,charges.Explore and analyze the data to discover important factors that affect customer churn.

# Project Summary
The Telecom Churn Analysis project involves analyzing Orange S.A., formerly France Telecom S.A., telecommunications corporation dataset focusing on whether a customer churned their service or not.The project aims to clean, analyze, manipulate, and visualize the data to gain insights into the factors influencing customer churn. Here's an overview of the project steps:

# Data Import & Cleaning
The project starts by importing essential libraries. The telecom churn CSV file is imported and transformed into a pandas DataFrame. Data analysis and visualization will be conducted using libraries like NumPy, pandas, Matplotlib, and Seaborn.

# Data Exploration
The dataset contains 3333 rows & 20 columns, we explored data and figured out of all columns except 4(State, International Plan, Voicemail Plan, Churn) remaining all are of numerical types i.e, either int64 or float64. Even though the Area Code is numerical it is not ordinal that means there is no mathematical significance to that number other than for referring. State is the only variable which is string. Although International Plan and Voicemail plan are given as strings(Yes/No) we need to consider them as Boolean for analysis.It is observed that there are no duplicate,missing/null values in our dataset.

# Data Wrangling
Most of our Data set is numerical. Only State, International Plan, Voice mail plan and Churn columns are non-numberic. Churn is boolean, but International Plan and Voice mail plan is given as strings(Yes/No), So for easier analysis converted Yes to True and No to False.

# Data Visualization
Visualizations are performed to understand relationships between variables. Univariate, bivariate, and multivariate analyses are conducted using various chart types such as bar plots, scatter plots, box plots and pie charts.The project concludes with a heatmap to represent the correlation level in single glance & also a pairplot to show pairwise relation in our dataset.

# Insights
Users with International Plan tend to churn more frequently.<br>
11 states out of 51 states have more than 20% churn rate.<br>
Inter Quartile Range(IQR) is more spread for churned users compared to non churned users.<br>
Users opting for voice mail plan are more likely to continue with their telecom service.<br>
There's almost no(near to zero) correlation among day, evening and night time calls.<br>
Users with more than or equal to 4 customer service calls are more likely to churn.
