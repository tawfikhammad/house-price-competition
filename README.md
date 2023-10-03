# House price competition
## Goal
It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

---

## File descriptions
* train.csv - the training set
* test.csv - the test set
* data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here
* sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms
* prediction.csv - predictions of our model

---

## Outline
1. import libariers and data

2. data review & understanding data

3. clean data
* handle with nulls

4. explore data
* 4.1. explore numerical data
   * handle with outliers
   * handle with skewness
* 4.2. explore descrete data
* 4.3. explore categorical data
   * label encoding
   * hot label encoding
5. bivariate analysis
6. modeling
* use :
    * Random Forest Regressor
    * XGBoost Regressor
    * CatBoost Regressor
7. Evaluate
8. Submission




