# Starting point search using Bayes Factors

Here we look for that onset of a sigmoidal curve in time series data using an approximate Bayes factor approach.

This works by comparing a linear and linear + simoidal model to the data and evaluating the remaining error.

See below for a combined plot of the different approaches. The different models only see the data until a given sample number (here 150) indicated by the blue area in the bottom row.

![Combined plot of the different approaches.](https://raw.githubusercontent.com/olavolav/BayesFactorOnsetFinder/master/images/fits.png)

The end result would be a plot showing the optimal Bayes constant to use:

![Result](https://raw.githubusercontent.com/olavolav/BayesFactorOnsetFinder/master/images/result.png)
