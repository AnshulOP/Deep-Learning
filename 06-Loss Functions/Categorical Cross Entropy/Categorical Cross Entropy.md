                                                       Categorical Cross Entropy
Categorical cross-entropy loss function is used for multi-class classification tasks where the target variable is categorical in nature. It is a measure of dissimilarity between the predicted probability distribution and the actual probability distribution of the classes. In other words, it calculates the difference between the predicted probability distribution and the true distribution of the classes.

The formula for categorical cross-entropy loss function is as follows:

    L(y, ŷ) = −∑ y_i log(ŷ_i)
    where y is the true probability distribution of the classes and ŷ is the predicted probability distribution of the classes.

Advantages:
1. It is a popular and widely used loss function for multi-class classification problems.
2. It can handle a large number of classes efficiently.
3. It is differentiable and can be used with gradient descent optimization algorithms.

Disadvantages:
1. It suffers from the problem of class imbalance, where some classes may have very few samples or too many samples, leading to biased predictions.
2. It assumes that the classes are mutually exclusive, which may not be the case in some scenarios.
3. It can be sensitive to outliers in the training data.                                                       
