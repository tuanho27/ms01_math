## Assignment 4

### a. Prove that softmax function map a vector to a probability distribtion.
### b. Find the gradient vector of the loss function in SoftMax Regression model.

Softmax maps f:Rn→(0,1)n such that ∑f(x⃗ )=1. Therefore, we can interpret the output of softmax as probabilities.

With sigmoidal activation, there are no such constraints for summation, so even though 0<S(x⃗ )<1, it is not guaranteed that ∑S(x⃗ )=1. The sigmoidal function does not normalize the outputs, so in your example where class 0 has output 0.7, class 1 could have any value in (0,1), which might not be 0.3.