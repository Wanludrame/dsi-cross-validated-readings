# Cross Validated Questions for DSI Reading

This document collates many questions and answers from [Cross Validated](https://stats.stackexchange.com/) that are relevent reading for the Galvanize data science curriculum.

## Linear Algebra

[What justifies this calculation of the derivative of a matrix function?](https://stats.stackexchange.com/questions/257579).  The great whuber on matrix deriviatives.


## Sample Statistics

[Correlations with categorical variables](https://stats.stackexchange.com/questions/108007).  Options for calcualting sample correlations between catagorical variables.


## Linear Models

[Why is the squared difference so commonly used?](https://stats.stackexchange.com/questions/132622).  Whuber gives a detaied answer from a decision theoretic point of view.

[Regressors with low varaince](https://stats.stackexchange.com/questions/291558).  Comments and warnings on the practice of dropping regression predictors with low variance.

[Correct way to use polynomial regression in Python](https://stats.stackexchange.com/questions/289056).  A quick answer on how to use `Pipeline`s and `FeatureUnion`s to do polynomial regression in Python.

[Why is a T distribution used for hypothesis testing a linear regression coefficient?](https://stats.stackexchange.com/questions/286179)

[Proof that the coefficients in an OLS model follow a t-distribution with (n-k) degrees of freedom](https://stats.stackexchange.com/questions/117406).  Similar to the above, but with more mathematical details.

[Can there be multiple local optimum solutions when we solve a linear regression?](https://stats.stackexchange.com/questions/144080).  Whuber gives a nuanced answer.




## Logistic Models

[Regularization methods for logistic regression](https://stats.stackexchange.com/questions/228763).  A clear description of how to regularize logistic regression with great viuals.

[Is there any intuitive explanation of why logistic regression will not work for perfect separation case? And why adding regularization will fix it?](https://stats.stackexchange.com/questions/239928).  A clear explanation with good visuals.

[Should sampling for logistic regression reflect the real ratio of 1's and 0's?](https://stats.stackexchange.com/questions/259341).  Comments on Logistic Regression's ability to accurately estimate probabiities vs. estimating marginal effects of predictors.

[Logistic regression: maximum likelihood vs misclassification](https://stats.stackexchange.com/questions/95250).  Why we use likelihood instead of classification error as a loss function.


## Regularization Methods

[What is the smallest λ that gives a 0 component in lasso?](https://stats.stackexchange.com/questions/289075/).  Math heavy but interesting.

[Is iterating LASSO a reasonable idea?](https://stats.stackexchange.com/questions/209794). A question about the motivating the iterated/adaptive LASSO.

[Elastic net: How to improve unstable cross validation of lambda](https://stats.stackexchange.com/questions/269603).  Measuring the sensitivity of results with respect to the regularization parameter.

## Evaluation Metrics

[What does AUC stand for and what is it?](https://stats.stackexchange.com/questions/132777)

## Mathematical Optimization

[How does the L-BFGS work?](https://stats.stackexchange.com/questions/284712). Mark Stone gives a high level description of Quasi-Newton methods.


# Variety Pack

[Is there a serious problem with dropping observations with missing values when computing correlation matrix?](https://stats.stackexchange.com/questions/262925).  Comments on the common practice of dropping missing data when running basic sample statistics in EDA.

[Maximum gap between samples drawn without replacement from a discrete uniform distribution](https://stats.stackexchange.com/questions/253990).  Fun probability theory.
