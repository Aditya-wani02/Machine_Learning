# Standardization 

Standardization , also known as z-score normalization or feature scaling, is a preprocessing technique commonly used in machine learning to transform the features of a dataset to have a mean of 0 and a standard deviation of 1. It is an essential step in many machine learning algorithms that are sensitive to the scale of input features.

When working with features that have different scales or units, some machine learning algorithms can be biased towards features with larger magnitudes. Standardization helps to bring all features to a common scale, which ensures that each feature contributes equally to the learning process and prevents one feature from dominating the others.

The standardization formula for a feature x is given by:

z = (x - mean) / standard deviation

where:
- x is the original value of the feature.
- mean is the mean value of the feature across the dataset.
- standard deviation is the standard deviation of the feature across the dataset.

The resulting "z" value is the standardized value of the feature.

Standardization is usually applied separately to each feature in the dataset, and it does not change the shape of the distribution of the data. It only shifts the distribution to have a mean of 0 and a standard deviation of 1.

Common machine learning algorithms that benefit from standardization include those based on distance metrics (e.g., k-nearest neighbors, support vector machines) and optimization algorithms (e.g., gradient descent-based algorithms).

It's important to note that some algorithms, such as decision trees or random forests, are not sensitive to feature scaling, so standardization is not required for these models. However, for algorithms like logistic regression, neural networks, and support vector machines, standardization can significantly improve convergence and performance.
