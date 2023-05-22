This GitHub repository contains the code and documentation of following Machine Learning Project:

1. Appliance Energy Prediction:
The goal of this project is to accurately predict energy consumption for various household appliances. The project utilizes the 5 algorithms to analyze a provided dataset.

Key Findings:


After rigorous analysis and model evaluation, the following key findings were discovered:

The untuned Extra Trees Regressor model achieved an impressive result, explaining 66% of the variance present in the test set.
Despite attempts to fine-tune the model, the performance of the tuned model was less promising. It only explained 58% of the variance, resulting in a 12% decrease compared to the default model. Therefore, it is recommended to employ the untuned model for predictions.
The final model utilized a set of 19 relevant features for analysis.
Feature reduction focusing solely on the top 5 features did not lead to a better R2 score, indicating that these features alone were not sufficient for accurate predictions.
However, an intriguing result was obtained when the feature reduction process eliminated the five least important features. This approach resulted in an improved R2 score of 67.50%, along with a mean squared error (MSE) of 30% and a root mean squared error (RMSE) of 55%. These metrics represent the best results achieved throughout the project.

2. Credit Card Default Prediction:

The aim of this project is to predict credit card default payments in Taiwan using data science techniques. The focus is on risk management, where the estimated probability of default is more valuable than a simple binary classification.

Key Findings:

In this project, we first check for data unbalancing, visualize the feaure and investigate in the relationship between different feature to find the strongest predictors of default payment.

We then run 3 different ML models in order to find the best model for detecting credit default:

Logistic model with 78.11% accuracy.
Decision_tree model with 76.96% accuracy.
Randome_forest model with 86.75% accuracy.
Among the various machine learning models employed for predicting default payment for credit cards, the Random Forest model emerges as the top performer, achieving the highest accuracy among all the models evaluated.

Through a meticulous feature selection process, we have identified and utilized a set of 15 features that have proven to be the most influential in producing optimal prediction results. This careful feature selection has played a crucial role in enhancing the accuracy and effectiveness of our model.
