# Perceptrons
{: .hidden-title }

## Overview

A perceptron is a basic type of artificial neural network used for classification tasks. It takes input features, applies weights and a bias, then uses an activation function to produce an output. Essentially, it helps make decisions by classifying data into two categories. While simple and effective for linear problems, the perceptron has limitations, especially when it comes to handling more complex, non-linear data. 

## Activities
The following activities were completed as part of this unit's coursework to better understand perceptrons and how they work in machine learning, providing a foundation for more advanced topics in neural networks.

A perceptron is a simple type of neural network used for classifying data into two categories. It works by taking in several input values, multiplying each by a weight, and adding them together along with a bias. This total is then passed through an activation function, which decides the output—usually 0 or 1. During training, the perceptron adjusts its weights based on how accurate its predictions are. Over time, this helps it learn patterns in the data. While basic, the perceptron is an important starting point for understanding more advanced neural networks and deep learning models.

The completed notebooks can be found on colab.

### Simple Perceptron

A gentrle introduction to how a perceptron is constructed. 

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit07/Ex1%20simple_perceptron.ipynb)

### AND Operator

A perceptron that learns the weights and bias to correctly model the logical AND function.

To see how this would be build using something like scikit-learn, I have added a self-contained implementation with a similar function in the last cell of the notebook. It outputs 1 only when both inputs are 1, mimicking the behavior of the logical AND. This is an example of using a perceptron for binary classification.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit07/Ex2%20perceptron_AND_operator.ipynb)

### Multi-layer Perceptron

Demonstrates a perceptron that can learn a simple rule where it outputs a value close to 1 when the input X is large, and close to 0 when X is small. It does this by adjusting weights and bias during training to create a decision boundary that separates the two input ranges.

The idea was also implemented using skikit-learn's ```MLPClassifier```:

![sigmoid-like](sigmoid_like.jpg)
{: .centered}

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit07/Ex3%20multi-layer%20Perceptron.ipynb)

## Reflection

This unit provided a clear introduction to perceptrons and how they function as basic neural networks for classification tasks. The perceptron model itself is simple yet powerful for linear problems. It works by taking input features, applying weights and a bias, and using an activation function to classify data into two categories. This gave me a foundational understanding of how neural networks learn from data, adjusting weights over time to improve predictions.

The activities helped me explore the different applications of perceptrons. In the Simple Perceptron notebook, I got a hands-on understanding of how a perceptron works from the ground up. In the AND Operator exercise, I was able to see how a perceptron can be trained to model a logical AND function, learning weights and bias to make binary classifications. The last task, the Multi-layer Perceptron, was a great way to see how adding layers and adjusting the weights can help the model learn more complex patterns, even though it’s still relatively simple compared to deeper neural networks.

While the perceptron is limited in handling non-linear data, this unit laid the groundwork for more advanced topics in deep learning. I also explored how to implement perceptrons using scikit-learn's MLPClassifier, which helped me see how the concepts I learned can be applied in more practical scenarios.


[Back to Machine Learning](/machine_learning/)