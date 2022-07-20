# <u> House Price Prediction - Advanced Regression Techniques</u>

### Introduction
Machine Learning project to predict Saleprice of houses using advanced Regression techniques. This notebook explores the *Ames Housing Dataset* from the Kaggle contest. 

The notebook covers exploratory data analysis, data preprocessing methodologies to impute missing data, scaling and encoding techniques, feature engineering, feature importance, and application of regression models. Gradient Boosting and XGBoost Regressors were deployed along with model evaluation and hyperparameter tuning. <br/>
Kaggle Score - 0.13551

Kaggle Contest Link: <br/>
https://www.kaggle.com/c/house-prices-advanced-regression-techniques <br/>


### Config
1. Install Anaconda Navigator 
2. Launch Jupyter Notebook 6.4.5
3. Run all cells 

### Required Libraries
- Pandas 
- Numpy
- Seaborn
- Scikit-Learn
- Matplotlib
- Bokeh
- Shap
- Xgboost

### Data Modeling

A total of seven different models were evaluated using Cross Validation technique. R2 score was the primary metrics used for evaluating the models.

|Model|R2 Score|
|:---:|:---:|
|Linear Regressor| 0.8473 |
|Ridge Regressor| 0.8486 |
|K-Nearest Neighbors| 0.7205 |
|DecisionTree Regressor| 0.7002 |
|RandomForest Regressor| 0.8625 |
|Gradient Boosting Regressor| 0.8882 |
|XGB Regressor| 0.8711 |

#### XGB Model Train Scores 

Before Hyperparameter Tuning

    MSE: 0.000225
    R2 score: 0.9985 

After Hyperparameter Tuning

    MSE: 0.0007438
    R2 score: 0.9953

From the above scores, it can be observed that GBM and XGB have the highest R2 scores. Scatter plots were also observed between the actual values and predicted values. Overall, it is observed that the XGBoost model showed improved performance with tuned hyperparameters compared to the performance of all the other models. 

