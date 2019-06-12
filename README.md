# clustering-techniques.-PCI-MNIST-Data
clustering techniques. PCI MNIST Data
Description: The aim of thi is to explore clustering techniques. Use the following data for testing your implementation: (MNIST Digit Recogntion Data – available through mnist.load_data() in Keras).
Part I: Apply PCA to MNIST Data
Use the function pca(X) from Homework 3 or from an existing library. Recall that this function takes an 𝑛×𝑑 matrix 𝑿 and returns mean, weights and vectors. 𝑿 has in each row the pixel of an input image. The mean is the mean of the columns of X. The principle components of X are in vectors. The corresponding eigenvalues are in weights. Using only a number of components, obtain a new data matrix 𝑿′. Use this new matrix 𝑿′ in the next part.
Part II: Using PCA before Classification
Use an existing k-means algorithm with three different distannce metric: 1) L2 norm (Euclidean distance), 2) L1 norm (Manhattan distance), and 3) Cosine distance.
Using the transformed data apply k-means algorithm (use k=10 for ten digits) to cluster 80% of the data and test the result on the remaining 20% of the data (repeat this 5 times for cross validation). Report the performance of the clustering using the following measurement.
• Labeling of clusters:
o Using the given labels for the training data form the following table:
