# Cross Validated Questions for DSI Reading

This document collates many questions and answers from [Cross Validated](https://stats.stackexchange.com/) that are relevent reading for the Galvanize data science curriculum.

## Linear Algebra

[What justifies this calculation of the derivative of a matrix function?](https://stats.stackexchange.com/questions/257579).  The great whuber on matrix deriviatives.

## Probabilitiy

[How is Pr(X=x|Y=y) defined when Y is continous and X discrete?](https://stats.stackexchange.com/questions/251077).  Xian discusses the need for rigorous measure theory in this circumstance.  Not for everyone.


## Sample Statistics

[Correlations with categorical variables](https://stats.stackexchange.com/questions/108007).  Options for calcualting sample correlations between catagorical variables.

[Is there a serious problem with dropping observations with missing values when computing correlation matrix?](https://stats.stackexchange.com/questions/262925).  Comments on the common practice of dropping missing data when running basic sample statistics in EDA.


## Parameter Estimation

[When is a biased estimator preferable to unbiased one?](https://stats.stackexchange.com/questions/207760)


## Sampling Theory

[Central limit theorem for sample medians](https://stats.stackexchange.com/questions/45124).  Is there an analouge of the CLT for sample medians?


## Null Hypothesis Signifigance Testing

[What is the meaning of p values and t values in statistical tests?](https://stats.stackexchange.com/questions/31).  High level discussion of what the hell all this stuff means.

[Why is it wrong to stop an A/B test before optimal sample size is reached?](https://stats.stackexchange.com/questions/244646)

[How to understand degrees of freedom?](https://stats.stackexchange.com/questions/16921)


## Linear Models

[Why is the squared difference so commonly used?](https://stats.stackexchange.com/questions/132622).  Whuber gives a detaied answer from a decision theoretic point of view.

[Regressors with low varaince](https://stats.stackexchange.com/questions/291558).  Comments and warnings on the practice of dropping regression predictors with low variance.

[Is R^2 useful or dangerous?](https://stats.stackexchange.com/questions/13314).  Is it?

[Correct way to use polynomial regression in Python](https://stats.stackexchange.com/questions/289056).  A quick answer on how to use `Pipeline`s and `FeatureUnion`s to do polynomial regression in Python.

[Simple linear regression, p-values and the AIC](https://stats.stackexchange.com/questions/218667).  A nice discussion around specifying a good regression model for a simple dataset.

[Why is a T distribution used for hypothesis testing a linear regression coefficient?](https://stats.stackexchange.com/questions/286179)

[Proof that the coefficients in an OLS model follow a t-distribution with (n-k) degrees of freedom](https://stats.stackexchange.com/questions/117406).  Similar to the above, but with more mathematical details.

[Can there be multiple local optimum solutions when we solve a linear regression?](https://stats.stackexchange.com/questions/144080).  Whuber gives a nuanced answer.

[GLM Categorical Variable Level grouping / simplification](https://stats.stackexchange.com/questions/215470).  Why grouping varaibles based on estimated coefficients is a bad idea.

[What is the difference between fixed effect, random effect and mixed effect models?](https://stats.stackexchange.com/questions/4700).  Confusing terminology.


## Logistic Models

[Regularization methods for logistic regression](https://stats.stackexchange.com/questions/228763).  A clear description of how to regularize logistic regression with great viuals.

[Is there any intuitive explanation of why logistic regression will not work for perfect separation case? And why adding regularization will fix it?](https://stats.stackexchange.com/questions/239928).  A clear explanation with good visuals.

[Should sampling for logistic regression reflect the real ratio of 1's and 0's?](https://stats.stackexchange.com/questions/259341).  Comments on Logistic Regression's ability to accurately estimate probabiities vs. estimating marginal effects of predictors.

[Logistic regression: maximum likelihood vs misclassification](https://stats.stackexchange.com/questions/95250).  Why we use likelihood instead of classification error as a loss function.


## Regularization Methods

[The origin of the term “regularization”](https://stats.stackexchange.com/questions/250722).  Where does that word come from?

[Why use regularisation in polynomial regression instead of lowering the degree?](https://stats.stackexchange.com/questions/226553).  A defense of regularization methods over discrete feature selection.

[Is standardisation before Lasso really necessary?](https://stats.stackexchange.com/questions/86434).

[How can I estimate coefficient standard errors when using ridge regression?](https://stats.stackexchange.com/questions/2121).  A discussion of the meaningfullness of standard error estimates in regularized regression.

[What is the smallest λ that gives a 0 component in lasso?](https://stats.stackexchange.com/questions/289075/).  Math heavy but interesting.

[Is iterating LASSO a reasonable idea?](https://stats.stackexchange.com/questions/209794). A question about the motivating the iterated/adaptive LASSO.

[Elastic net: How to improve unstable cross validation of lambda](https://stats.stackexchange.com/questions/269603).  Measuring the sensitivity of results with respect to the regularization parameter.

[Variable coefficient rises, then falls as lambda decreases (LASSO)](https://stats.stackexchange.com/questions/206178).  This phenomina seems to be suprising to some.

[Derivation of closed form lasso solution](https://stats.stackexchange.com/questions/17781).  Solving the LASSO equations in the one variable case.

[Closed form solution to lasso problem when data matrix is diagonal](https://stats.stackexchange.com/questions/244753).  How the LASSO works out in the simple case of uncorrelated data.

[The proof of shrinking coefficients using ridge regression through “spectral decomposition”](https://stats.stackexchange.com/questions/220243).  Using the SVD to justify ridge regression shrinking coefficients.


## Evaluation Metrics

[What does AUC stand for and what is it?](https://stats.stackexchange.com/questions/132777)

[When is it appropriate to use an improper scoring rule?](https://stats.stackexchange.com/questions/208529).  A facinating example from Cagdas.

[What are variable importance rankings useful for?](https://stats.stackexchange.com/questions/202277)

[ROC curve drawbacks](https://stats.stackexchange.com/questions/193138).

## Principal Componenets
[What can cause PCA to worsen results of a classifier?](https://stats.stackexchange.com/questions/52773).



## Mathematical Optimization

[How does the L-BFGS work?](https://stats.stackexchange.com/questions/284712). Mark Stone gives a high level description of Quasi-Newton methods.


## Boosting

[How is gradient boosting like gradient descent?](https://stats.stackexchange.com/questions/162928).  What is the connection between gradient boosting and gradient descent?


## Bayesean Methods

[PyMC modeling drug testing with truthiness](https://stats.stackexchange.com/questions/228892).  Bayesean modeling to detect drug abuse when people lie about thier consumption.

[When (if ever) is a frequentist approach substantively better than a Bayesian?](https://stats.stackexchange.com/questions/194035)

## Time Series

[Intuitive explanation of stationarity](https://stats.stackexchange.com/questions/9951)

[Intuitive explanation of unit root](https://stats.stackexchange.com/questions/29121). A difficult concept illuminated with good storytelling.

## Neural Networks

[What does the hidden layer in a neural network compute?](https://stats.stackexchange.com/questions/63152).

[How to choose the number of hidden layers and nodes in a feedforward neural network?](https://stats.stackexchange.com/questions/181)


## Support Vector Machines

[How does a Support Vector Machine (SVM) work?](ps://stats.stackexchange.com/questions/23391).  High level discussion of the intuition and mathematics underlying SVMs.


## Visualization

[What are essential rules for designing and producing plots?](https://stats.stackexchange.com/questions/16631).  Good advice is always welcome here.


# Variety Pack

[Recommendations for non-technical yet deep articles in statistics](https://stats.stackexchange.com/questions/192060)

[How do R and Python complement each other in data science?](https://stats.stackexchange.com/questions/238726).  Very opinion based, but good discussion.

[How did scientists figure out the shape of the normal distribution probability density function?](https://stats.stackexchange.com/questions/227034).  Fun history.

[Maximum gap between samples drawn without replacement from a discrete uniform distribution](https://stats.stackexchange.com/questions/253990).  Fun probability theory.


[Consider the sum of n uniform distributions on 0, 1. Why does the cusp in the PDF disappear for n≥3?](https://stats.stackexchange.com/questions/41467).  More fun probability theory.

[What is “reject inferencing” and how can it be used to increase the accuracy of a model?](https://stats.stackexchange.com/questions/13533).  Dealing with censored data in credit rating models.

[How to sample from Cantor distribution?](https://stats.stackexchange.com/questions/229556).  How does that even work?

[Simulate a Bernoulli variable with probability ab using a biased coin](https://stats.stackexchange.com/questions/209106/).  Simulating coin flips of a given bias using a coin with a different bias.

[Is it possible to have a pair of Gaussian random variables for which the joint distribution is not Gaussian?](https://stats.stackexchange.com/questions/30159).  Couplas and pretty visualizations.

[Approximate e using Monte Carlo Simulation](https://stats.stackexchange.com/questions/193990)
