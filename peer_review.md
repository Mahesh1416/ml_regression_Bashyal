### Peer Review: Final Project: Regression analysis project
# Reviewer: Mahesh Bashyal
#Notebook Link: https://github.com/wkarto/ml_regression_karto/blob/main/regression_karto.ipynb

___

1. Clarity and Organization:
   
The notebook is very well-structured and is numbered properly. The visuals are appropriate and well labelled. Overall, the steps such as data import, exploration, feature engineering, model selection, training and evaluation were done very well. 

___

2. Feature Selection and Justification: Womenker used input features such as 'age', 'sex', 'bmi', 'children', 'smoker', 'region' and 'bmi_smoker' for his input features. Womenker's target feature was 'insurance charges'. Womenker also created a new feature called 'bmi_smoker' where Womenker multiplied 'bmi' and 'smoker' to capture the combined effect of obesity and smoking which was an excellent work. 
___

3. Model Performance and Comparisons:

Womenker used two regression pipelines to improve the model:

- Pipeline 1: Imputer → StandardScaler → Linear Regression
- Pipeline 2: Imputer → Polynomial Features (degree=3) → StandardScaler → Linear Regression

Based on their evaluations, Womenker found that  Pipeline 1 (Linear Regression) slightly outperformed Pipeline 2 (Polynomial Regression) in terms of R², MAE, and RMSE. In womenker's case, the Polynomial Regression did not significantly improve performance. Womenker concluded that in their case, it was likely that the relationships in the dataset are mostly linear, and adding polynomial terms introduced unnecessary complexity.

___

4. Reflection Quality:
 Womenker did a great job in adding reflection after each section. They have summarized their results effectively, and also have done an excellent job in highlighting key observations and findings.

___
Final thoughts:
Overall, Womenker did an excellent job in summarizing the major findings. They have also effectivley highlighted their findings and added conclusions throughout the reflection sections in their notebook. 

___



