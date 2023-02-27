### Customer churn analysis with different classifiers

In this notebook we will build a model to predict, based on the available data, if a customer of a telecom company will churn. The model will use a well-known classification algorithm, the [k-nearest neighbors](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm) (KNN), which simply look at the k closest labeled data point and takes a majority vote.

The notebook is organized as follows:
1. Exploratory analysis to clean, format and visualize the data
2. Data preprocessing
3. Building the KNN model
4. Test it and evaluate its performance.
5. Implement a pipeline that [explore different classifier](https://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html#sphx-glr-auto-examples-classification-plot-classifier-comparison-py) and their performances.


