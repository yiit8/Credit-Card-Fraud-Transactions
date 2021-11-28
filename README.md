# Dataset
This dataset contains the real bank transactions made by European cardholders in the year 2013

# Data Preprocessing - Understanding
The features are transformed version of PCA except Amount column. So we can scale Amount column using standard scaler. Then we must drop columns that won't make much effect. Time column will be dropped. Finally if there are any duplicate entries, deleting them is our next step.

# Model Building
After creating training - test data, we trained our model with machine learning algorithms like Decision Tree, SVM, Linear Regression etc. XGBoost technique gave us the best result in terms of F1 score and accuracy.



