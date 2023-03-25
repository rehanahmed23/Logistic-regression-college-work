# Logistic-regression-college-work

# Intoduction

* Mr. hughes wants  to create a machine learning model in order to distinguish between two varieties of raisin which are kecimen and besni which are grown in Turkey(from reference).
* In order to create the model, we have been provided a dataset with 900 records.
* The dataset has 7 features which has been obtained using image processing technique.
* We will use logistic regression for classification of the type of raisin using the 7 independent feature(assumption) we will also provide the ROC-AUC curve associated with the model in order to present better understanding of our model.
* Logistic regression is the appropriate regression analysis to conduct when the dependent variable is dichotomous (binary).  Like all regression analyses, the logistic regression is a predictive analysis.  Logistic regression is used to describe data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent variables.
* AUC - ROC curve is a performance measurement for the classification problems at various threshold settings. ROC is a probability curve and AUC represents the degree or measure of separability.

# Performance Analysis

* Accuracy of our optimized model is 84% which is lower than our base model. However, we cannot decide the efficiency of the model only with accuracy as it does give the idea of type1 and type2 error.
* Going by the business problem we are trying to solve, we can ignore the type 1 and type 2 error as the stakes are not high and false negative or false negative result will not be critical and we are getting the same precision and recall value of 84%. 
* Type 1 and type 2 error can be identified with confusion matrix.
* Type1 error is false negative and type 2 error means false positive.
* Since, we cannot decide with precision and accuracy as well, we will take f1 score into consideration which is the harmonic mean of precision and recall.
* And it can be observed, the f1 score has also gone down from the base model.
* Thus, we need to make some important changes in order to get better results which can be adding more features to reduce the dependency of features.

# Recommendations 
* Since there is no change in the learning rate of our base model validation result, we need to add more features to the data which are independent of other features. This will also help in increasing the accuracy score.
* For our optimized model, we need to add more parameters.
* Some features have correlation and we build the model with the assumption that all features are independent. Thus, we need to do feature selection before building the model to reduce correlation.

### Performance analysis and recommedations can be verfied using the jupyter notebook or the html file provided above and complete report can be viewed through the ppt file provided.
