# Childhood Respiratory Disease

* In this activity, you will compare several linear models to predict the effect of smoking on childhood respiratory disease. You will need to apply preprocessing techniques to convert categorical data to numerical values and to apply scaling and normalization to the data.

## Instructions

* Use pandas's `get_dummies` function to convert the categorical data to binary values.

* Fit a standard scaler model to the training data.

* Apply the scaler transform to both the training and testing data.

* Compare the performance for each of the following models: `LinearRegression`, `Lasso`, `Ridge`, and `ElasticNet`.

  * For each of the models, be sure to compute the MSE and R2 score for the test data.

### Bonus

* Plot the Residuals for the Training and Testing data.

### Hints

* You will need to use Scikit-learn's [documentation](http://scikit-learn.org/stable/modules/linear_model.html) to figure out how to use `Lasso`, `Ridge`, and `ElasticNet`. Don't worry though because each of these use the familiar `model->fit->predict` pattern.

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
