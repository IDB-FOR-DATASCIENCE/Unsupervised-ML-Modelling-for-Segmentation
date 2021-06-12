# Segmentation-Modelling
Python Implementation of multiple unsupervised segmentation models and evaluating them through multiple evaluation metrics

In the current age, the availability of granular data for a large pool of customers/products and technological capability to handle petabytes of data efficiently is growing rapidly. Due to this, it’s now possible to come up with very strategic and meaningful clusters for effective targeting. And identifying the target segments requires a robust segmentation exercise. In this blog, we will be discussing the most popular algorithms for unsupervised clustering algorithms and how to implement them in python.
In this blog, we will be working with clickstream data from an online store offering clothing for pregnant women. It includes variables like product category, location of the photo on the webpage, country of origin of the IP address and product price in US dollars. It has data from April 2008 to August 2008.
The first step is to prepare the data for segmentation. I encourage you to check out this article for an in-depth explanation of different steps for preparing data for segmentation before proceeding further:

[One Hot Encoding, Standardization, PCA: Data preparation for segmentation in python](https://towardsdatascience.com/one-hot-encoding-standardization-pca-data-preparation-steps-for-segmentation-in-python-24d07671cf0b)

Selecting the optimal number of clusters is another key concept one should be aware of while dealing with a segmentation problem. It will be helpful if you read the article below for understanding a comprehensive list of popular metrics for selecting clusters:

[Cheatsheet for implementing 7 methods for selecting the optimal number of clusters in Python](https://towardsdatascience.com/cheat-sheet-to-implementing-7-methods-for-selecting-optimal-number-of-clusters-in-python-898241e1d6ad)

We will be dealing with 4 categories of models in this code:
1. K-means
2. Agglomerative clustering
3. Density-based spatial clustering (DBSCAN)
4. Gaussian Mixture Modelling (GMM)
