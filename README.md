# Gradient-Descent

**What is Gradiant ?**
Gradiant means slope of rate of change / derivative.

**What is Descent ?**
Descent means falling

**What is Gredient Descent ?**
- Gradient descent is an optimization algorithm used to find the values of parameters (coefficients) of a function (f) that minimizes a cost function (cost).
- Gradient descent is best used when the parameters can not be calculated analytically (e.g. using linear algebra) and must be searched for by an optimization algorithm.
- Gradient descent is an iterative optimization algorithm to find the minimum value of a function.
- It is also called trail and error.

**Types of Gradiant Descent**
- Batch Gradiant Descent
- Stochastic Gradiant Descent
- Mini Batch Gradiant Descent

**Steps in Gredient Descent**
- Initialize parameters (Weights and bias) at random position or simply as zero.
- Calculate cost function (J).
- Take the partial derivative of the cost function with respect to Weights and bias (dW and db).
- Change parameters values as:
  Wnew = W – learning rate * dW
  Bnew = b – learning rate * db
- Again, start from step 2 with new values of W and b and repeat the same for ‘n’ no. of iterations. With each iteration, the value of cost will progressively decrease and eventually end up with flat value / convergence.

**What is Cost Function in Gredient Descent ?**
- Cost function in gredient descent is a function which minimize the parameters over our dataset like mean square error 1/n *Sum(Actual y - Predicted y)^2

