# Machine Learning Regression Techniques in Python

This is a comprehensive guide to understanding and applying various regression techniques using Python. This not only cover theoretical aspects but also provide practical demonstrations using datasets. IT enhanced  knowledge of regression methods, their strengths, limitations, and the scenarios where they are most effective.

# 📁 Contents
## 1. Multiple Linear Regression in Python

This notebook provides a detailed walkthrough of multiple linear regression, focusing on:

  * Introduction to Linear Regression: Understanding the core concept and its applications.
  * Dataset Exploration: Steps to clean and prepare data for linear regression modeling.
  * Feature Selection: Techniques to identify significant predictors using statistical methods like p-values and R-squared.
  * Model Building: Step-by-step guide to fit, interpret, and validate a multiple linear regression model.
  * Evaluation Metrics: Insights into metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Adjusted R².

![p](https://github.com/MAHFUZATUL-BUSHRA/Regression_Analysis/blob/main/linear/lin1.png)

![p](https://github.com/MAHFUZATUL-BUSHRA/Regression_Analysis/blob/main/linear/lin2.png)

####  Notes:
 * Standard Errors assume that the covariance matrix of the errors is correctly specified.

* The Adjusted R-squared (Co-efficient of Determination/Goodness of Fit)= 0.896 i.e. 89.6% implies that 89.6% of the total variation in Sales is explained by the model i.e. the selected features.

* The goodness of fit test's probability value also shows that the model is a good fit.

* We have also found that Investment on TV (p-value= 0.000) and Radio (p-value= 0.000) Advertisement has Statistically Significant Impact on Sales at 5% level of significance.

##### Diagnostic Check of the Model
![p](https://github.com/MAHFUZATUL-BUSHRA/Regression_Analysis/blob/main/linear/lin4.png)
![p](https://github.com/MAHFUZATUL-BUSHRA/Regression_Analysis/blob/main/linear/lin5.png)

##### Model Training on Full Data
![p](https://github.com/MAHFUZATUL-BUSHRA/Regression_Analysis/blob/main/linear/lin6.png)

#### Interpreting the coefficients:

   * Holding all other features fixed, a 1 unit (1 USD) increase in TV Spend is associated with an average increase in sales of 0.045 units .

   * This basically means that for every $1000 dollars spend on TV Ads, we could expect 45 more units sold.


## 2. Polynomial Regression

This notebook explores the use of polynomial regression to model non-linear relationships between variables.
Key highlights include:

  * Conceptual Overview: How polynomial regression extends linear regression by introducing polynomial terms.
  * Data Transformation: Converting features into polynomial features for fitting non-linear data.
  * Model Training and Testing: Implementation of polynomial regression for various degrees to analyze performance.
  * Bias-Variance Tradeoff: Explanation of overfitting and underfitting using visualization techniques.
  * Practical Applications: Examples of where polynomial regression is most useful in real-world scenarios.

#### Comparison with Simple Linear Regression

Results on the Test Set (Note: Use the same Random Split to fairly compare!

   ##### Simple Linear Regression:
        MAE: 1.213
        RMSE: 1.516

  ##### Polynomial 2-degree:
        MAE: 0.4896
        RMSE: 0.664

![p](https://github.com/MAHFUZATUL-BUSHRA/Regression_Analysis/blob/main/poly.png)
## 3. Regularization Techniques: Ridge, Lasso, and ElasticNet
Regularization attempts to minimize the RSS (residual sum of squares) by adding a penalty factor. This penalty factor will penalize models that have coefficients that are too large. Some methods of regularization will actually cause non useful features to have a coefficient of zero, in which case the model does not consider the feature.

This notebook delves into regularization methods that address overfitting in regression models.
Topics covered:

  * Introduction to Regularization: Why it is needed and how it works.
  * Ridge Regression: Adding L2 penalty to shrink coefficients and reduce multicollinearity.
  * Lasso Regression: Adding L1 penalty to perform feature selection by shrinking some coefficients to zero.
  *  ElasticNet Regression: Combining L1 and L2 penalties to balance Ridge and Lasso.
  * Hyperparameter Tuning: Techniques like Grid Search to optimize regularization parameters.
  * Model Comparison: Evaluating Ridge, Lasso, and ElasticNet on the same dataset for performance benchmarking.

## 🎯 Project Objectives

  * Understanding Regression Models: Develop a strong conceptual foundation of regression techniques.
  * Hands-On Learning: Apply regression methods to datasets to gain practical experience.
  * Model Evaluation: Learn to assess model performance and interpret results effectively.
  * Regularization Techniques: Understand how regularization helps in handling overfitting and multicollinearity.
  * Compare and Contrast: Evaluate the strengths and weaknesses of each regression technique.

### Libraries:

  * numpy
  * pandas
  * matplotlib
  * seaborn
  * scikit-learn
  * jupyter

# 🎯 Project Objectives

  * Understanding Regression Models: Develop a strong conceptual foundation of regression techniques.
  * Hands-On Learning: Apply regression methods to datasets to gain practical experience.
  * Model Evaluation: Learn to assess model performance and interpret results effectively.
  * Regularization Techniques: Understand how regularization helps in handling overfitting and multicollinearity.
  * Compare and Contrast: Evaluate the strengths and weaknesses of each regression technique.
# 📖 Learning Outcomes

By working through this project,

  * Gain a solid understanding of regression analysis.
  * Learn to implement regression models using Python.
  * Understand the importance of regularization and how to apply it.
  * Develop skills to interpret model outputs and derive actionable insights.
# 🛠️ Future Improvements

* Add real-world datasets for practical applications.
* Include automation scripts for preprocessing and model evaluation.
* Extend with other regression techniques like Support Vector Regression (SVR).
