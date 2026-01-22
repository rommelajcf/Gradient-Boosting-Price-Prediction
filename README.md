# Gradient-Boosting-Price-Prediction
### Background

This project is part of the Tripleten data science practium. Focuses of the project is gradient decsent training using diverse libraries.

## Project Description

This project is tasked with building model for car price prediction using gradient boosting libraries. Factor to consider for project:
- Quality of prediction.
- Speed of the prediction.
- Time required for training.

## Data

Features available in our data consist of:
- Price          
- VehicleType    
- Gearbox        
- Power          
- Model          
- Mileage        
- FuelType       
- Brand          
- NotRepaired 

**Evaluation metrics:** Root Mean Squared Error

**Models evaluated:** LinearRegression, RandomForestRegressor, CatBoostRegressor, XGBRegressor, LightGBMRegressor

## Findings

RMSE comparision between models shows CatBoost to be the most viable model to use for this task. 

**RMSE**
- LinearRegression: 3624.52
- RandomForestRegressor: 2627.96
- LightGBMRegressor: 5443.82
- XGBoostRegressor: 2511.47
- CatBoostRegressor: 2324.47

## Software

**Tools:** _python_, _jupyter_

**Libraries:** _pandas_, ,_matplotlib_, _NumPy_, _sklearn_, _LightGBM_, _XGBoost_, __CatBoost_
