### ***Final Project - Modeling Analysis Feedback***

***Nico Van de Bovenkamp***
***

**Overall** Super interesting project! I really enjoyed reading through this and seeing the work you have done with it! Also, great use of Matplotlib for the handy plotting of counts and co-relations with your outcome.

**Some thoughts**

* The only bits that may be missing a bit in your exploratory analysis is relationships within your feature set. Now, given you are using non-linear models mostly, there isn't too much concern, but you may have some redundant features, and opportunity to perform some data transformations.
* Experiment with downsampling! And setting up the class weighting for the random forrest, as well as with other models. You definitely have a cool graph waiting for you to loop through sample weights and plot AUC Scores (or any other metric you'd like).
* Question: How did you deal with NaN values?
* Also, why did you choose to drop all the text data on the complaints? My bet is this could add quite a bit of value to your model.
* Check out the `.feature_importance_` attribute with the random forrest. This may give some insight into the 'why' your model is predicting the way it is, and what are the best indicators in your model (via maximum information gain/lowest change in entropy).

***I noticed you haven't quite sent in your model draft? We can discuss further on Tuesday!***
