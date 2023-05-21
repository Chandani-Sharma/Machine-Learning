Appliance Energy Prediction
This GitHub repository contains the code and documentation for the Appliance Energy Prediction project. The goal of this project is to accurately predict energy consumption for various household appliances. The project utilizes the Extra Trees Regressor algorithm to analyze a provided dataset.

Key Findings
After rigorous analysis and model evaluation, the following key findings were discovered:

The untuned Extra Trees Regressor model achieved an impressive result, explaining 66% of the variance present in the test set.
Despite attempts to fine-tune the model, the performance of the tuned model was less promising. It only explained 58% of the variance, resulting in a 12% decrease compared to the default model. Therefore, it is recommended to employ the untuned model for predictions.
The final model utilized a set of 19 relevant features for analysis.
Feature reduction focusing solely on the top 5 features did not lead to a better R2 score, indicating that these features alone were not sufficient for accurate predictions.
However, an intriguing result was obtained when the feature reduction process eliminated the five least important features. This approach resulted in an improved R2 score of 67.50%, along with a mean squared error (MSE) of 30% and a root mean squared error (RMSE) of 55%. These metrics represent the best results achieved throughout the project.
