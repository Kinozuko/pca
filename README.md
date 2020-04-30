# Principal Component Analysis

Original made in Colabotory, it will have two version:

* Colab/Jupyter notebook
* Python script

In this repository  we will following a [tutorial](https://towardsdatascience.com/a-complete-guide-to-principal-component-analysis-pca-in-machine-learning-664f34fc3e5a) to show how to apply PCA to reduce dimensionality in datasets.

Steps involved in PCA

* Standardize the data
* Compute covariance matrix
* Obtain the Eigenvectors and Eigenvalues from the covariance matrix
* Sort eigenvalues in descending order and choose the top k Eigenvectors that correspond to the k largest eigenvalues
* nstruct the projection matrix W from the selected k Eigenvectors
* Transform the original data set X via W to obtain the new k-dimensional feature subspace Y

## Structure

.
├── gitignore
├── README
├── requirements.txt
├── colab/
│   └── pca.ipynb
├── script/
│   └── pca.py
│   └── pca.png
