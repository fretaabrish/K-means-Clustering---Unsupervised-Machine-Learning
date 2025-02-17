# K-Means Clustering - Unsupervised Machine Learning
## Overview
This project implements K-Means Clustering on the IRIS dataset to demonstrate unsupervised machine learning techniques. The IRIS dataset consists of 50 samples from three species of Iris flowers:

- Iris Setosa
- Iris Virginica
- Iris Versicolor

Each sample has four features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
Using K-Means Clustering, we group the data into three clusters, revealing natural patterns in the dataset.

## Dataset
- Source: IRIS dataset (built into Scikit-learn)
- Number of Samples: 150
- Features: 4 (Sepal & Petal dimensions)
- True Classes: 3 (Iris Setosa, Iris Virginica, Iris Versicolor)
## Implementation Steps
### 1. Data Preprocessing
- Loaded the IRIS dataset using sklearn.datasets
- Standardized the feature values for better clustering
- Visualized the dataset using Scatterplots
### 2. Applying K-Means Clustering
- Defined K=3 clusters (since we know the IRIS dataset has 3 species)
- Initialized centroids and iteratively updated them
- Assigned each data point to the nearest centroid
- Used elbow method to verify the optimal number of clusters
### 3. Visualizing Clusters
- Plotted clusters using Matplotlib & Seaborn
- Compared predicted clusters vs. actual species labels
- Analyzed the clustering performance
## Technologies Used
- Python
- Scikit-learn (for K-Means Clustering)
- NumPy & Pandas (for data manipulation)
- Matplotlib & Seaborn (for visualization)

## Results & Insights
- The K-Means algorithm successfully clustered the IRIS dataset into three groups.
- Accuracy was evaluated by comparing the predicted clusters with the actual species labels.
- Some misclassifications occurred due to the natural overlap between Iris Versicolor and Iris Virginica in feature space.
## Future Improvements
- Experiment with different distance metrics (e.g., Manhattan, Cosine)
- Compare K-Means with other clustering techniques like DBSCAN or Hierarchical Clustering
- Deploy the clustering model as a web app for interactive use
