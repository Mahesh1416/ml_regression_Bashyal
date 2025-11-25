
---
## PROJECT SUMMARY
Project Title: Final Project - Regression analysis

Author: Mahesh Bashyal

Date: November 2025
___

### 1. Identify the Target Variable
- Target variable: charges
- Type: Continuous variable
-  Missing values: No missing values
- Importance: This feature is important becuase it is a measure for total medical insurance cost
---

### 2. Review Features Variables
The featuers selected for analyis in the model were:
Numerical: age, BMI, children
Categorical: smoker

I selected these features becuase I found strong relationship of these features with the target variable after initial exploratory anaysis.

---
### 3. Feature Engineering
- I converted categorical data (i.e., somker status to numeric data)
- No new features were created
---

### 4. Understand Relationships and Distributions
Patterns: 
- The insurance cost for smokers is high
Correlations:
- BMI and charges show positive correlation
- Age and charges show positive correlation
- Children and charges show positive correlation
___

### 5. Select the Regression Model
Baseline model: Linear Regression
- The base model used for this dataset was a linear regression
- It was appropriate for this dataset
Assumptions:
- Regarding the homoscedasticity, charges target variable was skewed to the right so there might be some violations in that case

### 6. Evaluate Model Performance

Metrics used: 
R squared: Explains how much variance in target variable is explained by the model
MAE: Measures absolute error
RMSE: Meaures Root Mean Squared error
___

### 7. Improve the Model
In order to improve the model we used the following procedures:
- Add scaling
  It did not improve the linear regression model
- Polynomial Features: This improved R squared values and other metrics and improved the overall model

___

### 8. Validate and Compare Models

| Model                  | R²        | MAE           | RMSE         |
|------------------------|-----------|---------------|--------------|
| Linear Regression      | 0.781115  | 4213.798595   | 5829.378522  |
| Polynomial (Degree 3)  | 0.869055  | 2745.538146   | 4508.772727  |

___

### 9. Real-world Interpretation
- What does the model tell us? People with smoking habits have higher probability of getting higher insurance costs
- Practical insights for stakeholders: People with higher BMI and smoking habits have higher chance of getting higher medical insurance costs. These analyses could be valuable to insurance companies.
- Any limitations and caveats of the model: This model looks into certain features such as age, BMI, chidlren and smoking status to predict the insurance charges. There may be other features not inlcuded in this dataset which could also be an excellent predictor for insurance charges, need to look into those. 

___

