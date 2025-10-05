# Student-Performance-Linear-Regression-Project
Predicts the probability of student participation in extracurricular activities using a linear regression model based on study habits, previous scores, sleep hours, and practice sessions.

## Project Overview

This project aims to predict whether a student participates in extracurricular activities based on their study habits, previous scores, sleep hours, and practice sessions.

* Target Variable: Extracurricular Activities (Yes/No, converted to numeric 0/1)

* Features: Hours Studied, Previous Scores, Sleep Hours, Sample Question Papers Practiced

Even though the original target was categorical, converting Yes/No into numeric allowed the use of Linear Regression, predicting the probability of participation.


### Objective

Explore student data and identify factors influencing extracurricular participation.

Build a Linear Regression model to predict participation probability.

Evaluate the model using standard regression metrics.

Visualize results to understand feature importance and model performance.

## Project Steps and Analysis
### 1. Data Exploration

* Explored dataset structure and summary statistics.

* Visualized correlation between features and target using a heatmap.

* Purpose: Identify important features and relationships among variables.

### 2. Data Preprocessing

* Converted target variable to numeric (0 for No, 1 for Yes).

* Checked and ensured no missing values.

* Purpose: Prepare dataset for modeling and ensure model can process numeric targets.

### 3. Feature and Target Selection

* Selected meaningful features (study habits, previous scores, sleep hours, practice) for prediction.

* Purpose: Focus on factors that could influence extracurricular participation.

### 4. Train-Test Split

* Split data into training (80%) and testing (20%) sets.

* Purpose: Train the model on one subset and evaluate performance on unseen data to measure generalization.

### 5. Model Building

* Built a Linear Regression model to predict numeric target (0/1 probability of participation).

* Purpose: Quantify the relationship between features and extracurricular participation.

### 6. Predictions and Evaluation

* Predicted target values on the test set.

Evaluated using:

* R² Score: Proportion of variance explained by the model

* MAE (Mean Absolute Error): Average prediction error

* MSE / RMSE: Magnitude of errors

* Purpose: Measure how accurately the model predicts participation probability.

### 7. Feature Importance

* Examined regression coefficients to understand which features influence participation most.

* Positive coefficients increase probability, negative coefficients decrease it.

* Purpose: Gain insights into the most influential factors.

### 8. Visualizations

* Correlation Heatmap: Shows relationships between features.

* Residual Distribution: Analyzes prediction errors.

* Residuals vs Predicted: Checks regression assumptions.

* Purpose: Visual exploration and communication of model performance.

### 9. Optional Professional Steps

* Ridge & Lasso Hyperparameter Tuning: Reduce overfitting and improve performance.

* Cross-Validation: Validate robustness of the model.

* Model Saving: Save the trained model for future use.

* Purpose: Enhance model reliability and prepare project for professional portfolio.

### Insights

* Hours Studied and Sample Question Papers Practiced most positively influence participation.

* Previous Scores have moderate influence.

* Sleep hours have slight negative effect.

* Linear regression predicts participation probability effectively

### Conclusion

* Project demonstrates a full regression workflow: data loading, preprocessing, EDA, model building, evaluation, visualization, and interpretation.

* Model can help predict which students are likely to participate based on study habits and performance metrics.

* Fully ready for GitHub portfolio with clean code and visualizations.
