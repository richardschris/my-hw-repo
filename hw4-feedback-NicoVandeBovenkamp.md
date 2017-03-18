### ***Project 4 Feedback***

***Nico Van de Bovenkamp***
***

**Overall:** Nice work on this final notebook! Your discussion and write up is very thorough, and to the point, which will pay off when you are doing this for your final project. ***As always, try out many different models! You may want to take advantage of [stacking models](http://blog.kaggle.com/2016/12/27/a-kagglers-guide-to-model-stacking-in-practice/) too (a method of ensembling)!***

* **Problem Statement/Aim:** Be mindful of using terms like, '*Correlation*' as we aren't just looking for correlation between University prestige and graduate admission, but rather modeling our predicting the likelihood of admittance given Prestige, GRE, and GPA. (A minor point)

**Other Visualizations:** In your final presentation, it is often hard to find the best way to show your results. Sometimes, it is in just bits of code or sudo-code, but often we want clean images and visualizations. The predicted probabilities (which works in the case of classification) across several values provided are one fantastic way of conveying results. However, think back to the lectures were we show learning curves, ROC curves, and discuss many error metrics. Showing those error metrics, and some visualizations of how you control or tune models to impact an evaluation metric is key! Think about this for your final project.

***A Table of Key Evaluation Metrics and Visuals:***

*Below is a brief set of many ways you can communicate/measure results that will be useful for your final project. Please let me know if you have any questions!*

| Metrics | |
|--- | --- |
| *Classification* | Accuracy, Precision, Recall, AUC Score, Lift, F-Score, Log-Loss, Gini, Entropy/Information Gain, Statistical Significance (p-value) |
| *Regression* | Mean Squared Error, Mean Absolute Error, Log-Likelihood Estimation, Statistical Significance (p-value) |

| Visualizations | |
|--- | --- |
| *Model Tuning* | Learning Curves, Regularization Learning Paths with an Error Metric, Model Error stepwise increasing feature set size |
| *Classification* | ROC Curve, Feature Importance Charts, Lift Curves, Expected Value Plots |
| *Regression* | Residual plots(!), KDE and KDE of Predicted Values, Expected Value |
