# Taxi Demand Forecasting

This project predicts hourly taxi demand to help optimize driver allocation during peak hours.

## Goal
Forecast the number of taxi orders for the next hour to improve service efficiency.

## What I did
- Resampled time-series data to hourly intervals
- Performed exploratory data analysis to identify trends and seasonality
- Created lag and rolling features
- Trained multiple models (Linear Regression, Decision Tree, Random Forest)
- Evaluated performance using RMSE

## Results
- Best model: Random Forest
- Test RMSE: ~42
- Model meets project requirement (RMSE ≤ 48)

## Key Insights
- Strong daily and weekly patterns in demand
- Peak hours during mornings and evenings
- Higher demand on weekends

## Business Impact
This model can help the company allocate drivers more efficiently, reduce wait times, and improve customer satisfaction.

## Tools
Python, Pandas, Scikit-learn

## Final Conclusion

In this project, I built a model to predict hourly taxi demand so the company can better plan for busy times.

The data showed clear daily and weekly patterns, with higher demand during rush hours and weekends. I used lag features and rolling averages to capture these patterns.

The Random Forest model performed best, with a test RMSE of about 42, meeting the project requirement.

Overall, this model can help the company better match driver availability with demand, reduce wait times, and improve service.
