# Energy-Output-Prediction-CCPP

# Objective:
-To predict the energy output at a Combined Cycle Power Plant(CCPP).

# About the Dataset:
-The dataset is obtained from the UCI Machine Learning Repository.
URL: [https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant]

-The dataset contains five columns, namely,
  -  Ambient Temperature (AT).
  -  Ambient Pressure (AP).
  -  Relative Humidity (RH).
  -  Exhaust Vacuum (EV).
  -  Net hourly electrical energy output (PE) of the plant. 
  
-**Dependent variable**:
  PE
  
# Workflow:

1. Data Preprocessing.
2. Regression:
    - a.	Data Modelling.
    - b.	Division of dataset into: Train, Test set.
    - c.  Training **Multiple Linear,Polynomial,Support Vector,Decision Tree,Random Forest** regression models on the training set.
    - d.  Predicting the test results. 
    - e.	Model Evaluations on the Test data using the metrics R^2_Score.
3. Model Selection.
    
# Conclusion

1. Multiple Linear Regression - 93.2% accuracy.
2. Polynomial Regression   - 94.5% accuracy .
3. Support Vector Regression - 94.8% accuracy.
4. Decision Tree Regression  - 92.2 accuracy.
5. Random Forest Regression  - 96.1% accuracy.

The Best Model to predict the Energy Output is therefore **Random Forest Regression Model with 96.1% accuracy**.
