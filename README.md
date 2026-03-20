#House_Price_Predictor

Problem statement: To build a ML model to predict house prices, and figure out which attribute contributes the most using MAE and R2 score as the markers.

Dataset description: There are 3 input columns and 1 output column. No missing values are present.
Size_sqft : Area of the house in square feet
Bedrooms : Number of bedrooms
Age : Age of the house (in years)
Price_in_INR : Target variable representing house price in Indian Rupees

Model used : Linear regression

Results: Initially, the MAE score was low and R2 score was high. When age column was removed,the MAE score increased and when Size_per_bedroom column was added, MAE score decreased a lot. This shows that it is a very important feature for the dataset.

Conclusion: Linear Regression successfully models the relationship between house features and price, and despite a small dataset, the model achieved strong predictive performance. 




