# Used Car Sales Analysis & Price Prediction


## Overview
This project provides an in-depth analysis of a dataset on used car sales, exploring the key factors influencing resale prices. It includes data preprocessing, feature engineering, and comparative performance evaluation of multiple regression models. The final section presents a trained regression model, selected based on performance metrics, for predicting resale prices.

**Link to Jupyter Notebook:**

## Key Insights:
1. **Popular Brands:** Among all brands, **Ford and Chevrolet** have the highest resale frequency, indicating strong market demand.

2. **Engine Preference:** Most buyers prefer mid-range cars with **4-6 cylinders, followed by 8-cylinder vehicles**. This suggests that heavier vehicles are less desirable in the resale market.

3. **Vehicle Type Trends: Sedans and SUVs** dominate the resale market, while off-road vehicles and buses are resold the least, highlighting buyer preferences for practical and versatile vehicle types.

## Factors Influencing the Resale Price

1. **Model:** The car's model, particularly from well-known manufacturers, plays a major role in determining its resale price. Popular and reliable models tend to maintain higher value due to brand reputation and demand.

2. **Car Age (including Odometer and Year):** The age of the car directly affects its price. Older cars with higher odometer readings typically have lower resale values, as they are perceived to have more wear and tear and a shorter remaining lifespan.

3. **Engine Power:** Cars with more powerful engines (more cylinders) may attract buyers looking for performance, but they are usually less fuel-efficient. This can impact pricing based on the buyer's preference for power versus fuel economy.

4. **Fuel Type:** The type of fuel the car uses influences its running costs and environmental impact. Cars that run on petrol, diesel, or electricity each appeal to different buyer groups, with electric and hybrid cars often having higher demand due to eco-friendliness and lower operating costs.

This ordering reflects the priority given to these factors when determining the resale price.

## Conclusion:
The process involved analyzing key factors such as model, car age, engine power, and fuel type to identify their impact on the resale price using a machine learning model. By evaluating feature importance, we optimized pricing strategies based on these critical attributes.

## Next Steps & Recommendations:
1. Enhance Features: Add more relevant features like car condition, accident history, and location to improve the model’s predictions.
2. Model Improvement: Test other regression models and optimize hyperparameters using techniques like RandomizedSearchCV.

