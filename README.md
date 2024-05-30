# Car-Data-Analytics
Generating Revenue Insights using Tableau, finding forecasting and ICP using RandomForestRegressor and Clustering:

Task Description: Examine the quality of the attached dataset. Use ML (Python) to find insights, hidden patterns, and forecast trends; anything related to financial and risk forecasting, as well as ideal customer profile (ICP).

## **LifeCycle of the project**
1. Data Analysis
2. Feature Engineering
3. Feature Selection
4. Model Building
5. Model Deployment

## **Forecasting**
Different Forecasting for this scenario:
1. Car Price Forecasting
2. Insurance Payment Forecasting
3. Claim Amount Forecasting

## **1. Car Price Forecasting**

**Objective**: Predict the price of a car based on various features.

**Target Variable**: Price ($)

**Features**: Annual Income, Amount_paid_for_insurance, Claim amount, year, Gender_Female, Gender_Male, Transmission_Auto, Transmission_Manual, Color_Black, Color_Pale White, Color_Red, Body Style_Hardtop, Body Style_Hatchback, Body Style_Passenger, Body Style_SUV, Body Style_Sedan, City_Daugavpils, City_Jelgava, City_Liepaja, City_Riga, City_Tukums, City_Ventspils.

## **2. Insurance Payment Forecasting**

**Objective**: Predict the amount a customer will pay for insurance based on car and customer attributes.

**Target Variable**: Amount_paid_for_insurance

**Features**: Annual Income, Price ($), Claim amount, year, Gender_Female, Gender_Male, Transmission_Auto, Transmission_Manual, Color_Black, Color_Pale White, Color_Red, Body Style_Hardtop, Body Style_Hatchback, Body Style_Passenger, Body Style_SUV, Body Style_Sedan, City_Daugavpils, City_Jelgava, City_Liepaja, City_Riga, City_Tukums, City_Ventspils.

## **3. Claim Amount Forecasting**
**Objective**: Predict the amount of insurance claims based on customer and car characteristics.

**Target Variable**: Claim amount

**Features**: Annual Income, Price ($), Amount_paid_for_insurance, year, Gender_Female, Gender_Male, Transmission_Auto, Transmission_Manual, Color_Black, Color_Pale White, Color_Red, Body Style_Hardtop, Body Style_Hatchback, Body Style_Passenger, Body Style_SUV, Body Style_Sedan, City_Daugavpils, City_Jelgava, City_Liepaja, City_Riga, City_Tukums, City_Ventspils.

# **ICP: Ideal Customer Profile**
 I have used clustering techniques like K-Means to segment the customers into different groups and then analyzed these groups to identify the ideal customer profile. The elbow method is used to determine the optimal number of clusters. The clusters are analyzed by computing the mean of the features for each cluster. The ICP is identified by selecting the cluster with the highest average 'Price ($)' and 'Annual Income'

 # **Conclusion and Next Steps:**

**Conclusion**: After various forecasting methods and applying ICP we can understand about the future of car prices, the amount that will be paid by the customers, and how much amount will be claimed. This will help us to understand the financial situation of the future and also find the Ideal Customer profile to focus on based on their annual income and car purchase. 


**Next Steps**: Analyze ICP Characteristics:

* Further analyze the characteristics of the ICP cluster to understand the profile of ideal customers.
Actionable Insights:

* Use the ICP insights to target similar customers for marketing and sales efforts.


**Tableau Analytics**:
Conducted Revenue Analysis for the company to generate a variety of insightful visualizations and dashboard from the dataset provided. Here are some potential insights and corresponding visualizations:

1. Gender Distribution:
Created a pie chart showing the distribution of sales by gender.
2. Sales Analysis
Popular Car Models and Companies: Stacked bar chart showing revenue contribution by different car models or companies.
Sales Distribution by City: Tabular Format
Revenue Analysis: Line chart showing total sales revenue over time.
3. Insurance Analysis
Insurance Payments distributed by gender:
Bar plot showing the relationship between insurance amounts paid and gender.
4. High Value Customers
Customer Segmentation based on insurance amount paid and annual income.
5. Car Preferences
Car preferred based on annual income

