# PIMA-Diabetes_Prediction_ML

## This Notebook provides you a deep insight on Machine Learning Modelling and HyperParameter Tuning.
- Prediction whether a women has diabetes.

### Topics
- Data Analysis
- Data Scaling
- Data Modeling
- Hyper-parameter Tuning.
- Cross Validation
- Predictions

## Data Analysis:
- The Dataset has 768 rows and 9 columns
- Target Columns is: 'Outcome'
- We plot graphs to see the variation of each Independent variable

![](/Images/PIMA1.png)

- We plot graph to verify the outliers so that we can clean our dataset.

![](/Images/PIMA2.png)

- Plot to check the correlation between the data points.

![](/Images/PIMA3.png)

## Data Scaling:

**RobustScaler** is a transformation technique that removes the median and scales the data according to the quantile range (defaults to IQR: Interquartile Range). The IQR is the range between the 1st quartile (25th quantile) and the 3rd quartile (75th quantile). It is also robust to outliers, which makes it ideal for data where there are too many outliers that will drastically reduce the number of training data.

## Data Modeling

- We use the state-of-the-art XGBClassifier to predict the outcome.(whether a person has diabetes)
- Use GridSearchCV for hyperparameter tuning on
 - learning_rate
 - n_estimators
 - max_depth
 - min_child_weight
 - reg_alpha
 - reg_lambda
 
> We get a accuracy score of 82.1429% 

- Graph plot for ROC and AUC

![](/Images/Pima3.png)
 
- We also use Logistic Regression with cross-validation technique to check:
 - log_loss
 - accuracy
 - f1 score
> We get a mean accuracy of 78.02% 

### If you like my content, please STAR my work and you can also upstar me at [KAGGLE](https://www.kaggle.com/lokeshrth4617/hyperparamter-modeling-the-beginner-s-guide?scriptVersionId=38224491)
## Thank you!
