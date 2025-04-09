# Machine-Learning---Concepts-GSU-
This repository contains assignments and practical implementations of Machine Learning basics.


# 1 - Principal Component Analysis (PCA)
Principal Component Analysis (PCA) is a dimensionality reduction technique that transforms data into a new coordinate system, where the most significant variance lies along the principal components. It helps reduce redundancy and improve interpretability while retaining essential patterns in the data.

This notebook explores PCA using a small dataset with two characteristics. The following steps have been performed:

Data Visualization: The dataset is plotted using a scatter plot to understand its distribution.
Normalization: Each feature is centered around the origin by subtracting its mean.
Covariance Matrix Computation: The relationship between features is analyzed using a covariance matrix.
Eigen Decomposition: Eigenvalues and eigenvectors of the covariance matrix are computed to determine principal components.
Dimensionality Reduction: The data is projected onto the principal component with the highest variance.
Reconstruction: The projected data is transformed back to its original space to compare with the initial dataset.
The notebook includes visualizations of the original, normalized, and reconstructed data, along with computed eigenvalues and eigenvectors. This implementation provides insights into how PCA works and its effect on data transformation.

# 2 - Image Segmentation using DeepLabV3+ model on CityScape Dataset.
