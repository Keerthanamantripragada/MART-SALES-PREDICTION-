# MART-SALES-PREDICTION
**INTRODUCTION**:
BigMartSales data have the data of stores of different types which includes variety of food items related to the grocery stores and supermarkets.Aim is to predict the total sales of the particular stores by analyzing the data trends and using different machine learning models to improve the performance of the stores and for identifying where the stores are lagging.


**PROJECT INSIGHTS**: 

We have analysed the data trends and cleaned the data by identifying the outliers and we have done the feature transformations for improving the rmse score of the model predictions. Linear Regression performed better than XGBoost for this dataset.


**Possible reasons**:

The relationship between features and sales is mostly linear, so simpler models capture it well. XGBoost may have overfit the small dataset or didn’t gain much from complexity. We have even used RandomSearchCV for finding the best parameters for XGBoost.


**Business Insights**: 

Stores can focus on high-performing product categories to maximize sales. Product visibility and pricing strategies can be optimized based on sales predictions. Accurate sales prediction helps in inventory management and reducing stockouts.

**FEATURE IMPORTANCE **
Outlettype and combination of mrp and outlet have major contributions to the prediction of the data.
