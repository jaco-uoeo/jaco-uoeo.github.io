# Model Performance Measurement
{: .hidden-title }

## Overview

While reviewing a notebook that used sklearn.metrics to evaluate a machine learning model, I found it helpful to see a variety of performance measures applied in one place. Accuracy gave a general sense of how often the model predicted correctly, but more detailed metrics added valuable insight. In particular:

- Precision measured how many of the model’s positive predictions were actually correct
- Recall showed how well the model identified actual positive cases
- F1 Score balanced precision and recall, which was useful in cases of class imbalance
- ROC (Receiver Operating Characteristic) Curves and AUC (Area Under Curve) scores were used for each class, giving a visual and numerical sense of the model’s ability to distinguish between classes

On the regression side, the notebook also used several key metrics:
- RMSE (Root Mean Squared Error) captured how much large prediction errors were affecting the model
- MAE (Mean Absolute Error) showed the average error in predictions
- R-squared (R²) reflected how well the model explained the variability in the target variable

One point worth noting is that newer versions of Keras have removed or changed support for some of these built-in metrics, making it more common to calculate them manually using sklearn.metrics. Here's a link to the [GitHub: Precision, Recall and F1 Metrics Removed #5794](https://github.com/keras-team/keras/issues/5794) ticket detailing this action.

The notebook can be accesses via colab.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit11/model_Performance_Measurement.ipynb)


## Reflection

While reviewing a notebook that used sklearn.metrics to evaluate a machine learning model, I found it helpful to see various performance measures applied together. Accuracy gave a general sense of model performance, but precision, recall, and the F1 score provided deeper insights, especially in cases of class imbalance. ROC curves and AUC scores helped assess class distinction. In regression, RMSE, MAE, and R² helped evaluate prediction errors and model fit. I also noted the removal of some built-in metrics in newer Keras versions.

[Back to Machine Learning](/machine_learning/)

