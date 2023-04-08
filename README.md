# Week19_CryptoClustering

This code reads in crypto market data from a CSV file and prepares the data for clustering. It then uses K-means clustering to cluster the cryptocurrencies into groups and visualizes the clusters using a scatter plot. Finally, it uses principal component analysis (PCA) to optimize the clustering.

The steps in the code include:

Importing the required libraries and dependencies
Loading the data into a Pandas DataFrame and generating summary statistics
Normalizing the data using the StandardScaler module from scikit-learn and creating a new DataFrame with the scaled data
Finding the best value for k (the number of clusters) using the original data
Clustering the cryptocurrencies using K-means and the best value for k, and visualizing the clusters using a scatter plot
Optimizing the clusters with PCA by reducing the data to three principal components.