# Problem Statement

Given a number, we have to use gradient descent to check whether or not that number is a perfect square.

For this use case, we can use the objective function: (x**2 - num)**2 as we want the absolute form which we can minimize till it reaches 0. 

# Gradient Descent Optimization

It is a first order optimization algorithm as it explicitly makes use of first order derivatives of target objective function. In other words, it utilises the slope of the function in order to perform optimization.

If the target variable takes multiple input values then it becomes multivariate function and the input variable can be thought of as a vector. In that case the derivative of the input vector is thought of as a gradient. 

**Gradient**: First order derivative for a multivariate objective function.

Derivative of the gradient points in the direction of steepest ascent of the target function.  

Gradient Descent is not a lone algorithm but rather a family of algortihms, all of which utilise first-order of derivatives to navigate to the optima of a target function. Variations of the optimisers are usually named after the modification that they make to the original version.

SGD is one of those variations and this version is commonly used for deep learning tasks and training of deep neural networks.


**I hope people who view this find it to be as useful and interesting as I did.**
