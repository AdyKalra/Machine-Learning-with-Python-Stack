# Evaluate the model against test data
- from sklearn import metrics
- to predict accuracy 

## Metrics 
- Confusion Matrix sklearn
- TN FP (true negative, false positive)
- FN TP

# Classification report
- precision = TP / (TP + FP)
- recall = TP / (TP + FN)
- f1 - score 
- support

# Performance impovement options 
- Adjust current algos
- get more data or improve data
- Improve training 
- Switch algos

# Random Forest
- ensemble algo 
- fits multiple trees with subset of data (hence the name forest)
- Average tree results to improve performance and control overfitting

### from sklearn
- sklearn.ensemble import RandomForestClassifier
# Overfitting - works well on training not on test data
- Regularization of hyperparameter to avoid ovetfitting
- Cross validation
- Bias variance tradeoff

# Performance Improvements take 2
- Adjust current algorithm 
- Get more data or improve data
- cross validation
- switch algo ( logistic regression)

# Logistic Regression 
- from sklearn.linearmodel import LogisticRegression

# Unbalanced Classes 
- more of one class than the other

# Cross Validation on Logistic Regression 
- other data fr tuning
- option to split data into training validation and testing

## k-fold cross validation 
- training data split into k folds 
- training validated with k-1 folds in a loop

- for each fold determine best hyperparameter value
- set model hyperparameter value to avg best
