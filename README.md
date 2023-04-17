# SVR-Implied-Volatility
How accurately can support vector regression (SVR) predict implied volatilities?

SVR can be effective even in high-dimensional spaces where there are many features. It is robust to outliers, and can use different kernel functions, such as linear, polynomial, and radial basis function (RBF), to map the data into a higher-dimensional space where it is easier to separate the classes. Drawbacks include the sensitivity of SVR to changes in hyperparameters and a tendency to overfit complex datasets.

Future work:

- Create an SQL database to save training data generated over multiple days or weeks
- Create/interpolate a synthetic dataset
