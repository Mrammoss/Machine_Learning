# Machine_Learning
## Predicting Sales
- Miguel Ramos
## Business Problem
Predicting how much could be made in sales.
## Data:
[sales_predictions_2023.csv](https://github.com/Mrammoss/Machine_Learning/files/12899026/sales_predictions_2023.csv)
## Methods
- First, I cleaned the data; dropping whatever was not needed since it is of no help for predictions. I also made sure value names were consistent and uniform.
- Second, I transformed the data. Transforming the data filled in any missing values and transformed objects into numbers to be able to be computed for predictions.
## Results
### Item Fat Content vs Outlet Type
![download](https://github.com/Mrammoss/Machine_Learning/assets/142689773/e6249a41-2037-4027-aa82-8849b1c8215f)

This visual shows that Item Fat Content is equally distributed when it is shown in context of Outlet Type.

### Outlet Location Type vs Item MRP
![scatplot predictions sales](https://github.com/Mrammoss/Machine_Learning/assets/142689773/24da8d40-63d6-48be-95d2-514de6598789)

This scatterplot shows the general growth of outlet sales as Item MRP increases.

------------------------------------------------------------
Regression Metrics: Training Data
------------------------------------------------------------
- MAE = 642.732
- MSE = 823,642.047
- RMSE = 907.547
- R^2 = 0.722

------------------------------------------------------------
Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 737.884
- MSE = 1,127,473.715
- RMSE = 1,061.826
- R^2 = 0.591

Our lowest metric here is our MAE. The mean absolute error could go down a lot more to make this model accurate for predictions.
  
