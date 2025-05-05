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

CityScape Dataset contains images and their masks.
So a total of overall more than 6000 images are there.

# 3 - DNA Sequence Clustering using K-Means

This task demonstrates unsupervised clustering on DNA sequences using K-means. The dataset consists of 120 DNA sequences, each 264 nucleotides long.

The steps include:

- **FASTA Parsing**: DNA sequences are extracted from a `.fas` file, ensuring all are of equal length and contain only valid nucleotides (A, C, G, T).
- **One-Hot Encoding**: Each sequence is converted into a 1056-dimensional binary vector using one-hot encoding (each base represented by 4 binary digits).
- **K-Means Clustering**: Scikit-learn's KMeans algorithm is used to cluster sequences into 3 groups based on their nucleotide patterns.
- **Dimensionality Reduction**: PCA is applied to reduce the high-dimensional encoded data to 2D and 3D for visualization.
- **Visualization**: Cluster assignments are visualized using 2D and 3D scatter plots with color-coded clusters.

This project showcases how machine learning can be applied to biological sequence data for exploratory analysis and pattern discovery.



   


# 4 - CNNs on CIFAR 10 Dataset
With few hidden and normalization layers
