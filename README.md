# Principal Component Analysis

Original made in Colabotory, it will have two version:

* Colaboratory
* Jupyter notebook
* Python script

In this repository  we will show how to apply PCA to reduce dimensionality in datasets.

Steps involved in PCA

* Standardize the data
* Compute covariance matrix
* Obtain the Eigenvectors and Eigenvalues from the covariance matrix
* Sort eigenvalues in descending order and choose the top k Eigenvectors that correspond to the k largest eigenvalues
* nstruct the projection matrix W from the selected k Eigenvectors
* Transform the original data set X via W to obtain the new k-dimensional feature subspace Y

## Structure

```
.
├── gitignore 
├── README
├── requirements.txt
├── jupyter/
│   └── pca.ipynb
├── script/
│   └── pca.py
│   └── pca.png
```

## Runing Project

### Installing Dependecies

* pip install -r requirements.txt

### Running Script

* python script/pca.py

### Running Jupyter Notebook

* jupyter notebook jupyter/pca.ipynb

### Running Colaboratory

* [See in Colaboratory](https://colab.research.google.com/drive/1oF_GRtYW3AlXGwqSsQFMvW-AACh2HcRn)
