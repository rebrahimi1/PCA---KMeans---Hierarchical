# PCA---KMeans---Hierarchical

An example of using PCA, K-Means, and Hierarchical Clustering on bank dataset. 

We have two components in PCA process, Index[0] and Index[1] of 'y' are out target.
After applying K-means, the test data point is for index [0] cluster which is green centroid. data point of index [0] is near data point of index [1]. We have two clusters in K-means as we had 2 components in PCA process. After applyting Hierarchical, by using Dendrogram we found 4 clusters.

PCA represented all n data vectors as linear combination of a small number of eigenvectors in order to minimize the mean-squared reconstrcution error but in K-means, it represents all n data vectors by small number of cluster centroids in order to show them as linear combination of a small number of centroid vectors.

K-means algorithm was better option to work with for finding clusters since it works better with large data and has less time complexity.
