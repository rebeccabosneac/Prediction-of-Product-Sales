# Prediction-of-Product-Sales

## Sales predictions analysis

###  Rebecca Amaya

## For this project, my goal is to help predict Item Sales Prices using different features available on the data set

## Data
https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view

## Methods
- I performed exploratory and explanatory data analysis to help visualize and exlore each feature and their correlation with eachother.
- I then imported a fresh version of the data and made a column transformer to fill in the missing values and prepare the data for regression modeling.
- Used Linear Regression and Random Forest Regression on my models to find the best predictor for our target value Sales.

## Results

### Here are 2 visuals from the EDA section

![item sales heatmap](https://github.com/rebeccabosneac/Prediction-of-Product-Sales/assets/144873201/617d8c4a-2eec-4139-a2e2-982d0ccadd7d)

This Heatmap shows a few moderate correlations which are: 
- Outlet_Establishment_Year has .52 correlation with Item_Weight
- Item_MRP has .57 correlation with Item_Outlet_Sales

![item sales boxplot](https://github.com/rebeccabosneac/Prediction-of-Product-Sales/assets/144873201/200f47f6-4a8d-4901-bc39-43e7b37faa94)

This Boxplot shows that grocery store has the lowest sales of any outlet type and supermarket type 3 has the highest.

## Model

- My final model is a tuned Random Forest Regressor model

- My model is able to explain the target with 60% of variance of data .

- The MAE is able to predict approximately on an average sales within $728.614

- ------------------------------------------------------------
Regression Metrics: Training Data
------------------------------------------------------------
- MAE = 755.473
- MSE = 1,153,120.356
- RMSE = 1,073.834
- R^2 = 0.610

------------------------------------------------------------
Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 728.614
- MSE = 1,095,702.976
- RMSE = 1,046.758
- R^2 = 0.603

### For further information
- Contact romo.becky5@gmail.com
