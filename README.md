# ML-Regularized_Linear_Regression_Models

In this Project, I have done implementation of different regularization techniques.

I've used Python's famous libraries like [Pandas](), [Numpy](), [Matplotlib](), [Sklearn](), etc. for analysis and model development.

I've used the Boston house prediction dataset. This [dataset](https://github.com/Anuragtsl/ML-Regularized_Linear_Regression_Models/blob/main/Dataset.txt) is present in the datasets module of sklearn (scikit-learn) library.

# What is Regularization

In regression analysis, the features are estimated using coefficients while modelling. 

Also, if the estimates can be restricted, or shrinked or regularized towards zero, then the impact of insignificant features might be reduced and would prevent models from high variance with a stable fit. 

***Regularization is the most used technique to penalize complex models in machine learning, it is deployed for reducing overfitting (or, contracting generalization errors) by putting network weights small. Also, it enhances the performance of models for new inputs.***

# Penalty Terms
 
Through biasing data points towards specific values such as very small values to zero, Regularization achieves this biasing by adding a tuning parameter to strengthen those data points. Such as:

* **L1 regularization:** It adds an L1 penalty that is equal to the absolute value of the magnitude of coefficient, or simply restricting the size of coefficients. For example, Lasso regression implements this method. 

* **L2 Regularization:** It adds an L2 penalty which is equal to the square of the magnitude of coefficients. For example, Ridge regression and SVM implement this method.

* **Elastic Net:** When L1 and L2 regularization combine together, it becomes the elastic net method, it adds a hyperparameter.


# Conclusion

From the above analysis we can reach the following conclusion about different regularization methods: 
 

  * **Regularization is used to reduce the dependence on any particular independent variable by adding the penalty term to the Loss function. This term prevents the coefficients         of the independent variables to take extreme values.** 
 
  * **Ridge Regression adds L2 regularization penalty term to loss function. This term reduces the coefficients but does not make them 0 and thus doesn’t eliminate any independent       variable completely. It can be used to measure the impact of the different independent variables.**
 
   * **Lasso Regression adds L1 regularization penalty term to loss function. This term reduces the coefficients as well as makes them 0 thus effectively eliminate the                    corresponding independent variable completely. It can be used for feature selection etc.** 
 
  * **Elastic Net is a combination of both of the above regularization. It contains both the L1 and L2 as its penalty term. It performs better than Ridge and Lasso Regression for       most of the test cases.**


# Preview

![Image1](https://github.com/Anuragtsl/ML-Regularized_Linear_Regression_Models/blob/main/Images/1.png)

![Image2](https://github.com/Anuragtsl/ML-Regularized_Linear_Regression_Models/blob/main/Images/2.png)

![Image3](https://github.com/Anuragtsl/ML-Regularized_Linear_Regression_Models/blob/main/Images/3.png)

![Image4](https://github.com/Anuragtsl/ML-Regularized_Linear_Regression_Models/blob/main/Images/4.png)

![Image5](https://github.com/Anuragtsl/ML-Regularized_Linear_Regression_Models/blob/main/Images/5.png)


#Njoy!
