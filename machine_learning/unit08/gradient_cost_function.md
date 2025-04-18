# Gradient Cost Function

Gradient descent is a method used to minimize the cost function in machine learning by adjusting model parameters step by step. The size of these steps is determined by the learning rate. If the learning rate is too high and iterations are few, the algorithm might skip over the global minimum. On the other hand, a very low learning rate could result in slow progress. The goal is to find the right balance between learning rate and iteration count, ensuring that the cost is minimized efficiently without overshooting or taking too long to converge.

### Summary of the Gradient Descent Process:
- Start with initial guesses for 𝑚 and 𝑏
- Calculate the gradients for 𝑚 and 𝑏
- Update the values of 𝑚 and 𝑏 by subtracting the product of the learning rate and the gradient
- Repeat steps 2 and 3 for a predefined number of iterations or until convergence (when the cost function reaches a minimum)


[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit08/Ex4%20gradient_descent_cost_function.ipynb)

### Bibliography

Mayo, M. (2017) 'Neural Network Foundations, Explained: Updating Weights with Gradient Descent & Backpropagation - KDnuggets,' Available at: https://www.kdnuggets.com/2017/10/neural-network-foundations-explained-gradient-descent.html (Accessed: 21 March 2025). 

[Back to Machine Learning](/machine_learning/)