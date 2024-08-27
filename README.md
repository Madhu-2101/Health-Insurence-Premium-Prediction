# Health Insurance Premium Prediction

## Project Summary:

- **Dataset Overview:** The dataset includes 1338 records with attributes like age, gender, BMI, number of children, smoking status, region, and insurance charges.
- **Goal:** Develop a predictive model to estimate health insurance premiums based on customer information.
- **Data Transformation:** Categorical features (e.g., sex, smoker, region) were encoded into numerical formats for modeling.
- **Features & Target:** Features were stored in `X`, while the insurance charges were stored in `y`.
- **Model Development:** Several regression models were trained and evaluated:
  - Linear Regression
  - Support Vector Regressor (SVR)
  - Random Forest Regressor
  - Gradient Boosting Regressor
- **Performance Comparison:** Models were assessed using R-squared score and mean absolute error (MAE). Gradient Boosting Regressor achieved the best results.
- **Final Model:** The Gradient Boosting Regressor was chosen as the final model for predicting insurance premiums.
- **Outcome:** The model accurately predicts health insurance costs for new customers based on their profile.

## Conclusion:
The Gradient Boosting Regressor is the most suitable model for predicting health insurance premiums, offering reliable and accurate estimates based on customer details.
