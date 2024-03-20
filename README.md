# Comparing different models on Cereal Data
In this report, I will talk about the dataset of 77 cereals, and will predict their ratings based on their nutritional attributes. I looked at three different regression models: Random Forest, SVM (Support Vector Machine), and Gradient Boosting. 

Model Analysis:
1. Random Forest:

•	Mean Squared Error (MSE): 37.00

•	Root Mean Squared Error (RMSE): 6.08

•	Mean Absolute Error (MAE): 5.12

•	R-squared (R2): 0.83

 
2. Support Vector Machine (SVM):
   
•	Mean Squared Error (MSE): 191.51

•	Root Mean Squared Error (RMSE): 13.84

•	Mean Absolute Error (MAE): 11.35

•	R-squared (R2): 0.13

 
3. Gradient Boosting:
   
•	Mean Squared Error (MSE): 25.50

•	Root Mean Squared Error (RMSE): 5.05

•	Mean Absolute Error (MAE): 3.89

•	R-squared (R2): 0.88

 
Best Model:

The Gradient Boosting has shown the best performance compared to all the three models, with the lowest MSE, RMSE, and MAE, and the highest R2 value (0.88). This indicates that the Gradient Boosting model has the highest predictive accuracy and explains a substantial portion of the variance in the cereal rating.
 The Random Forest Regressor also performed well, with reasonable error metrics (MSE, RMSE, and MAE) and a good R2 score of 0.83, making it a competitive alternative to the Gradient Boosting model. The SVM Regressor, on the other hand, did not perform as well as the other two models. It has the highest MSE, RMSE, and MAE, coupled with a low R2 score of 0.13, showing that it is not effective at predicting cereal ratings in this dataset.
 
Conclusion: 

Gradient Boosting is the most suitable model for predicting cereal ratings based on the given dataset. It provides the most accurate and reliable predictions, as evidenced by its performance metrics. It's recommended to use this model for any further predictions or analyses related to this dataset. 
