# Gradient-Descent-for-Linear-Regression
## Implementing gradient descent to get intercept and coefficients for Linear Regression using Numpy.

   Gradient descent is one of the most basic and easy to implement algorithm for finding minima of the cost function. For a mean square cost function there exists only one minima which it's global minima. This is because the mean square cost function is a Quadratic Function.

   For a complex cost function with many local minimas, the algorithm that I have given below might not work effectively.

   Always check the convergence curve when you're training the model for the first time. If it doesn't converge try decreasing the learning rate(a) and increase the iterations. This is one of the downsides of gradient descent, but in more complex solvers like BGFS, L-BGFS, etc we need not specify the learning rate.
