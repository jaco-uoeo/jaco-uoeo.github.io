# Gradient Cost Function
{: .hidden-title }

## Overview

Gradient descent is a method used to minimise the cost function in machine learning by adjusting model parameters step by step. The size of these steps is determined by the learning rate. If the learning rate is too high and iterations are few, the algorithm might skip over the global minimum. On the other hand, a very low learning rate could result in slow progress. The goal is to find the right balance between learning rate and iteration count, ensuring that the cost is minimised efficiently without overshooting or taking too long to converge.


### Summary of the Gradient Descent Process:
- Start with initial guesses for 𝑚 and 𝑏
- Calculate the gradients for 𝑚 and 𝑏
- Update the values of 𝑚 and 𝑏 by subtracting the product of the learning rate and the gradient
- Repeat steps 2 and 3 for a predefined number of iterations or until convergence (when the cost function reaches a minimum)


[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/jaco-uoeo.github.io/blob/{{ site.github_branch }}/machine_learning/unit08/artefacts/Ex4%20gradient_descent_cost_function.ipynb)

## Reflection

This unit on gradient descent was a great introduction to how optimisation works in machine learning. The key takeaway for me was understanding how gradient descent minimises the cost function by iteratively adjusting the model's parameters. The process involves starting with initial guesses for the parameters (like the slope and intercept), calculating gradients, and then updating the parameters by subtracting the product of the learning rate and gradient. This step-by-step process helps move the model closer to the optimal solution.

A significant challenge is finding the right balance for the learning rate. If it’s too high, the algorithm may overshoot the global minimum, and if it’s too low, it can take too long to converge. This balance is crucial for achieving fast and efficient convergence. The article by Mayo (2017) provided a solid foundation for understanding this concept, and working through it helped clarify the importance of iteration count and learning rate in ensuring that gradient descent minimises the cost function effectively.

### Bibliography

Mayo, M. (2017) 'Neural Network Foundations, Explained: Updating Weights with Gradient Descent & Backpropagation - KDnuggets,' Available at: https://www.kdnuggets.com/2017/10/neural-network-foundations-explained-gradient-descent.html (Accessed: 21 March 2025). 

[Back to Machine Learning](/machine_learning/)