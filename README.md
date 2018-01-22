# CrimeDataForcasting

Hyperparameter tuning is a computationally intensive and confusing process, even when you have domain knowledge of a particular algorithm's parameters. Bayesian Optimization is a method that uses a small amount of random grid search evaluation data to choose parameters that often far outperform those selected by intensive grid search. Below, I will outline how to use Bayesian Optimization to tune the hyperparameters in Facebook's Prophet time-series package. We will be predicting property crime in a specific Chicago police districts at a weekly level. I'll extend this in subsequent scripts to be implemented in parallel for all Chicago police districts to determine if any of them saw a spike in property crime in the past week.


View code with output at:
http://rpubs.com/tdneumann/351073
