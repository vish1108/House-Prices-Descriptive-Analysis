# House-Prices-Descriptive-Analysis

## Description
This project focuses on conducting a descriptive analysis of US house prices over the past 20 years, aiming to identify and understand the factors influencing these prices.

## Problem Statement 
Find publicly available data for key factors that influence US home prices nationally. Then, build a data science model that explains how these factors impacted home prices over the last 20 years.


# Steps:

## [Data](https://fred.stlouisfed.org/series/CSUSHPISA) Collection
For this project i did some research by my self from wall street journal & yahoo finance, Most of the Data was collected from [CSUSHPISA](https://fred.stlouisfed.org/series/CSUSHPISA)
This Data include different financial data such as PCE, CPI, Inflation rate etc.

## Data Cleaning and Integration
The collected data was clean and process to ensure accuracy and reliability. Date and year were utilized as common elements to connect different data frames over a specified time span. This integrated approach aimed to unveil patterns and correlations between various factors and house prices.

## Identifying Influential Factors
Utilizing a correlation matrix, it was determined that PCE has a significant impact on house prices. Machine learning models, specifically decision trees,predict house prices with good results.

## Model Evaluation
The selected model demonstrated its effectiveness, with a Mean Squared Error on the test set of 4.07429350980393 and an R-squared value on the test set of 0.9966914823726227, indicating strong predictive capabilities.

## [Temporal Analysis](https://github.com/vish1108/House-Prices-Descriptive-Analysis/blob/master/Exploring_HousingData.ipynb)
To further enhance the predictive model, the date table was split into year and month, enabling a more granular analysis. This refined model, combined with PCE, provided improved predictions of house prices over time.

## [Predicting PCE](https://github.com/vish1108/House-Prices-Descriptive-Analysis/blob/master/PCE%20Linear%20Regression.ipynb)
As part of the analysis, PCE was predicted over the entire time range (1960 to 2022). This allows users to explore and understand how PCE affect prices of House,and this step is usefull to find right PCE for prediction.

## [Finacial Data](https://github.com/vish1108/House-Prices-Descriptive-Analysis/blob/master/Data/financial_data.csv)
Using Python code i saved the clean & Processed data for Power BI

## [Power BI  Dashboard](https://github.com/vish1108/House-Prices-Descriptive-Analysis/blob/master/Power%20BI%20Visualization.pbix)
Power BI dashboard has been created to visually represent the findings of the analysis over the twenty-year period. The dashboard provides an intuitive and insightful display of key trends and relationships.

## Dashboard [Image](https://github.com/vish1108/House-Prices-Descriptive-Analysis/blob/master/Screenshot%202023-11-25%20024018.png) :

<img width="505" alt="Screenshot 2023-11-25 024018" src="https://github.com/vish1108/House-Prices-Descriptive-Analysis/assets/68471486/589f55c1-3141-4fa6-8d1d-40c83169dc83">

## Conclusion
This project not only successfully identified key factors influencing US house prices but also developed a robust predictive model. The combination of descriptive analysis, machine learning, and visualization through Power BI contributes to a comprehensive understanding of the dynamics driving US house prices.

Feel free to explore the data, methodology, and results outlined in this project. Any inquiries or suggestions are welcome.

Happy coding!
