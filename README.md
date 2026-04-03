# Flight_Price_Sensitivity_Analysis

## 📖 Overview

This project explores the key drivers of airline ticket pricing using regression analysis. The objective is to understand how different factors influence flight prices and to uncover insights related to price sensitivity across customer segments.

Using a dataset of over 300,000 flight records, the analysis focuses on how variables such as booking timing, travel class, airline, route, and number of stops impact ticket prices.

## 🎯 Objectives
Identify key drivers of flight price variation
Analyse customer price sensitivity across different scenarios
Build a regression model to quantify pricing effects
Generate business insights for pricing strategy

## 🧰 Tools & Technologies
Python (Pandas, NumPy)
Data Visualisation (Matplotlib, Seaborn)
Statistical Modelling (Statsmodels – OLS Regression)

## 📊 Key Features
Data cleaning and preprocessing
One-hot encoding of categorical variables
Log transformation of price
Correlation analysis
OLS regression modelling
Business-driven interpretation of results

## 🔍 Key Insights
⏳ Booking Timing
Prices decrease by ~1.4% for each additional day before departure
Strong evidence of price sensitivity among early bookers

## 💼 Travel Class
Business class tickets are significantly more expensive
Premium customers exhibit lower price sensitivity

## 🧳 Stops
Multi-stop flights tend to be more expensive than single-stop routes
Indicates variation in pricing strategies across route types

## ✈️ Airline Effects
Premium airlines charge significantly higher prices
Reflects brand positioning and customer segmentation

## 🌍 Route Differences
Price levels vary across cities, indicating demand and competition effects

## 📈 Model Performance
R²: 0.915
Strong explanatory power
All major variables statistically significant

## ⚠️ Limitations
No demand or booking data (true price elasticity not measured)
No seasonality or external factors (holidays, events)
Potential autocorrelation in residuals
🚀 Future Improvements
Incorporate demand-side data
Add time-series forecasting
Implement machine learning models (Random Forest, XGBoost)
Deploy as a pricing recommendation tool
📌 Conclusion

This analysis demonstrates that flight pricing is driven by a combination of operational and behavioural factors. The results highlight significant differences in price sensitivity across customer segments, providing valuable insights for dynamic pricing strategies and revenue optimisation.
