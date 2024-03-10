Xgboost model that is tracked by mlflow and paramaterized by Optuna. Trained on airflight ticket prices
## Why I used MLFlow and Optuna
In order to get an effective model parameters I used optuna and saved the best parameter settings. MLFlow was important in this project because it allowed me to view all the trials that optuna ran and allowed me to visualize the validation errors easily. Moreover the MLFlow tracking api allowed me to view the top ten best/worst models in terms of MSE and RMSE with fliters. 
## Approach/Steps

## Notable finds
In terms of feature importance, class is by far the important factor. Logically, this makes sense considering flight prices are heavily influenced on whether it is first class or economy. 
## What I would do next time
Although I am satisfied with what I learned, if I were to redo this project with the knowledge I have now, I would try to select features that were important to predictions. 
