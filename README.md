# Teacher
Final Capstone analysis of Teaching career 

Final supervised classification model was an XGBoost with hyperparameters: {'learning_rate': 0.1, 'max_depth': 5, 'n_estimators': 50}.

This was it's accuracy report:
Accuracy: 0.91875
Classification Report:
              precision    recall  f1-score   support

           0       0.58      0.25      0.35        28
           1       0.93      0.98      0.96       292

    accuracy                           0.92       320
   macro avg       0.76      0.62      0.65       320
weighted avg       0.90      0.92      0.90       320

Final suppervised regression model was  SciKit Learn's out of the box, Linear Regression model. Here is how it performed:
Mean Squared Error: 142.69384484942597
R-squared: 0.544168796999436
