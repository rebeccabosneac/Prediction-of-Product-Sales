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

## Insights

### Linear Regression
![Lin Reg Imp Feat](https://github.com/rebeccabosneac/Prediction-of-Product-Sales/assets/144873201/67d72479-0e59-46ae-9860-39c785d76043)

- The top 3 most important features are:
    - Outlet Identifier OUT035
    - Outlet Identifier OUT035
    - Outlet Identifier OUT035

All three features are specific outlets that have the highest predicted sales and the most importance to sales.

### Random Forest
![rf imp feat](https://github.com/rebeccabosneac/Prediction-of-Product-Sales/assets/144873201/e264eda7-dc91-4442-9802-97bc725af149)

- The top 5 most important features are:
    - Item_MRP - An items maximum retail price has the most importance in this model for sales prediction

    - Outlet_Grocery_Store - This outlet type has more importance to sales prediction than the others do.

    - Item_Visibilty - An items visibilty affects whether the item has good sales or not.

    - Item_Weight - The weight of the item has value in predicting sales.

    - Outlet_Type_Supermarket Type 3 - Of the supermarket types, type 3 has the most importance when it comes to sales predictions.

## Final Recommendations

- My final recommendation is the Random Forest Model.
- The r2 and MAE scores are better for sales prediction and the most important features give us more information on what affects item sales the most.

### For further information
- Contact romo.becky5@gmail.com
