# US Food Consumption Trend
Overview

This repository contains an end-to-end data analysis and visualization project examining U.S. daily food consumption from 1970–2017, forecasting future intake through 2027, and comparing actual consumption against recommended dietary guidelines.

Data Source

All data comes from the U.S. Department of Agriculture. The dataset provides average daily per-capita availability across key categories:

  Meat, Eggs & Nuts
  
  Vegetables
  
  Dairy
  
  Flour & Cereal Products
  
  Added Oils & Fats
  
  Added Sugars & Sweeteners
  
  Forecasting Approach

To project consumption for 2018–2027, the analysis applies:

  ARIMA
  
  Holt-Winters exponential smoothing

For each food category, the model with the lower MAPE is chosen to generate the final forecast line.

Visualization

Deliverable dashboard:
https://public.tableau.com/app/profile/zixian.wei/viz/USDailyFoodConsumption/Dashboard?publish=yes
