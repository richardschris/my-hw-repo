### ***Project 2 Feedback***

***Nico Van de Bovenkamp***
***

**Overall** Good work! You very thoroughly went through each question and were very precise about your assumptions, definitions, and approach. It seems you are doing well, so I definitely encourage you to try your hand at the bonus questions! If you weren't sure how imputation of missing values might work, [check out this link!](http://chrisalbon.com/python/pandas_missing_data.html)

**Some Notes**

* **Q.9:** Great use of statistical tests here! You have interpreted your results very well, and all of the distributions are slightly skewed. However, keep in mind that even if we run a test and it informs us that it is unlikely that the data comes from a normal distribution, we use this information to inform our subsequent models. In other words, if a model is not very working (and it requires assuming normally distributed data) then we may know why. Or, if it is working, we know why it may not be working even better. We will still be building models that are slightly violated by the normality requirement. (Please let me know if this is clear).
* **Q.13** You are spot on for potential choice of model! Generally speaking, there are two bins of labeled, supervised learning problems that are discussed: 'classification' and 'regression.' A linear regression model is appropriate for, as indicated in the name, 'regression' problems where our outcome $Y$ is a continuous variable. In this case, you are right that this is a classification problem: the outcome variable $Y$ is discrete. So, a logistic regression would work. If you are curious, of course, there are many other models that you could choose, which have pros and cons, like a Support Vector Machine, Probit model, Decision Tree, many more! If you would like to know more, please let me know!   
