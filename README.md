# PCA_Dimensionality_Reduction

The Principal Component Analysis (PCA) technique to reduce the dimensionality of a custom image and the MNIST dataset. The goal of this approach is to reduce the number of features in the data while retaining as much information as possible. The project starts by implementing PCA from scratch, using the singular value decomposition (SVD) method.

The steps of this approach include:

- Load the data, in this case, the custom image and MNIST dataset.
- Preprocess the data, this includes normalizing the data and flattening the image.
- Compute the covariance matrix of the data.
- Compute the eigenvectors and eigenvalues of the covariance matrix.
- Select the top k eigenvectors, where k is the number of dimensions to reduce the data to.
- Use the selected eigenvectors to transform the original data into the new, lower-dimensional space.
- Compute the compression Ratio. 
- Reconstruct the images.

## Results:

![90d13f6e-eae0-47f7-b3be-97d7887255aa](https://user-images.githubusercontent.com/60902991/212784728-2e6a57a5-618f-45fa-955a-eed712d7a03c.png)
![dc1049f6-3ca3-489d-aabb-729d33a3f1fe](https://user-images.githubusercontent.com/60902991/212784742-7738d6b7-dc34-4e65-afdd-a6c8aaa49e66.png)
