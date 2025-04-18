# Convolutional Neural Networks

## Activities

After reviewing a notebook that implemented a simple CNN using the CIFAR-10 dataset, I gained a clearer understanding of the typical steps involved in image classification tasks. 

The dataset, loaded directly from Keras, included 60,000 32x32 color images across 10 categories. The notebook began by examining the dataset’s shape and structure, which helped contextualise the input format. Pixel values were scaled to a 0–1 range to normalise the data, and class labels were one-hot encoded for compatibility with the softmax output layer. A validation set was also set aside from the training data to evaluate model performance during training. 

The CNN architecture was kept simple, using a Conv2D layer with ReLU activation, followed by max pooling, a dense hidden layer with 256 units, and a final softmax output layer. The model was compiled with the Adam optimiser and trained with early stopping enabled, which helped prevent overfitting by monitoring validation loss.

Because of the inherent randomness in the learning process, the metrics can vary between different training runs. That said, here’s the output from my run.

| Epoch | Accuracy | Loss     | Val_Accuracy | Val_Loss  |
|-------|----------|----------|--------------|-----------|
| 0     | 0.428450 | 1.582629 | 0.5324       | 1.291762  |
| 1     | 0.552375 | 1.255629 | 0.5824       | 1.165473  |
| 2     | 0.604675 | 1.121423 | 0.6132       | 1.106196  |
| 3     | 0.641525 | 1.021945 | 0.6296       | 1.071485  |
| 4     | 0.672650 | 0.931910 | 0.6365       | 1.071656  |
| 5     | 0.700650 | 0.856021 | 0.6360       | 1.091396  |


The training results show a clear upward trend in accuracy, starting at approximately 43% and reaching just over 70% by the sixth epoch. Validation accuracy also increased, peaking at around 63.6%. Training loss decreased steadily, indicating effective learning on the training data. However, validation loss began to plateau and slightly increase in the later epochs. This suggests the model may have started to overfit, as performance on the validation set stopped improving.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit09/Ex1%20Convolutional%20Neural%20Networks%20(CNN)%20-%20Object%20Recognition.ipynb)

[Back to Machine Learning](/machine_learning/)