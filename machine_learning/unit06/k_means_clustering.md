# K-Means Clustering

K-means clustering is a way to automatically group similar items in a dataset without needing labels. You start by picking how many groups (or "clusters") you want. The algorithm places some starting points (called centroids), then sorts the data into groups based on which centroid each point is closest to. It keeps adjusting the centroids and regrouping the data until things settle. It’s a simple but powerful tool for spotting patterns—like grouping customers by behavior or organizing images by similarity. Just keep in mind that results can vary depending on where those starting points are placed.

## Activities

### Tutorial: Customer Segmentation with K-Means

Customer segmentation involves dividing customers into groups based on shared traits. This helps businesses target each group more effectively. For example, one segment might include high-value, loyal customers worth focusing retention efforts on, while another might include low-profit customers. It's a key strategy for smarter marketing and resource allocation. 

The main tutorial activity's notebook can be found on colab.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit06/K-Means%20demo%20notebook.ipynb)

The data file was not supplied as part of the activity brief, however, the data can be found on [Kaggle](https://www.kaggle.com/datasets/sam1o1/cust-segmentation?resource=download).


### Task A: Iris data

Perform K-Means clustering on the Iris dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris).

K-Means clustering on the Iris dataset showed strong alignment with the actual species labels. Most data points were correctly grouped into three clusters, with some overlap between similar species. The elbow method confirmed that three clusters are appropriate, reflecting the natural class structure present in the dataset's feature space.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit06/k-means-iris.ipynb)


### Task B: Wine data

Perform K-Means clustering on the Wine dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine).

K-Means clustering on the Wine dataset produced accurate groupings, with most samples correctly assigned to clusters corresponding to the original cultivars. Minor misclassifications were observed, but overall performance was consistent. The elbow method supported the use of three clusters, indicating that the data naturally separates into three distinct groups.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit06/k-means-wine.ipynb)

[Back to Machine Learning](/machine_learning/)