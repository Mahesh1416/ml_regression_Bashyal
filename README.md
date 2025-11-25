
# Final Project - Using Regression modeling to predict insurance costs
---

## Introduction

In this project we will use the Medical Cost dataset to explore how different factors such as age, BMI, region, smoking status and number of children predict insurance charges. We will use regression techniques to predict insurance charges by evaluating these features. We will perform this in a series of steps such as Data import and inspect, data exploration, feature engineering, evaluation of different models and models comparison. 
___

## Steps Involved

### Section 1: Importing and Inspecting the data
1. Import necessary libraries  
2. Load the dataset and display the first 10 rows  
3. Check for missing values and summary statistics
---

### Section 2: Data Exploration and Preparation

---
### Section 3: Feature Selection and Justification

1. Choose features and target 
2. Define **X** (features) and **y** (target) 

---

### Section 4: Train a Regression Model
1. Split the data into Train/Test sets
2. Train the model
3. Report performance
___

### Section 5: Evaluate Model Performance
1. Pipeline 1: Imputer → Standard scaler → Linear Regression
2. Pipeline 2: Imputer → Polynomial features (degree 3) → StandardScaler → Linear Regression
3. Compare the model performance

### Summarize the findings

| Model                  | R²        | MAE           | RMSE         |
|------------------------|-----------|---------------|--------------|
| Linear Regression      | 0.781115  | 4213.798595   | 5829.378522  |
| Polynomial (Degree 3)  | 0.869055  | 2745.538146   | 4508.772727  |

___

### Section 6. Final Thoughts and Insights

### Section 6.1 Summary of Findings

- #### In this project, I learnt how to predict insurance charges using different features such as age, BMI, children, and smoker status. I used various regression models. The standard linear regression model (base model) showed a R squared value of 0.78 which meant this model explained 78% of the variation in the insurance charges. When we added a scaling component to the standard base model, it did not produce different results. I also learnt that the polynomial (3 degree) model was the best of all these models with the R squared value of 0.86 and lower MAE and RMSE values.

- ### Section 6.2 Challenges 
- #### I would occasionally run into errors while running the codes which i fix it by using AI and online resources
- #### It was also challenging to interpret all the results and compare the models and often needed to understand them well. 

### Section 6.3 What would I do if I had more time?
- #### If i had more time I would explore more models to see which predicts insurance charges more effectively. One model which I would look into would be a Random Forest model.
  
  ### Reflection 6: What I Learned
- #### Overall, from this project I learned how to import the data, explore the data, use feature engineering, convert categorial data to numerical data, run several models, evaluate them and compare those models based on metrics such as R squared, MAE and RMSE values. I was able to predict insurance charges based on features like BMI, age, children and smoker status. 


