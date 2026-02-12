---
layout: default
title: Lab 4
---

[Home](../index) \| [Assessment Information](../assessment-information) \| [Refresher](../refresher) \| [Blackboard Page](https://www.ole.bris.ac.uk/ultra/courses/_264181_1/outline) \| [Blackboard Forum](https://www.ole.bris.ac.uk/ultra/courses/_264181_1/engagement) \| [Unit Catalogue](https://upc.bristol.ac.uk/unit-programme-catalogue/UnitDetails.jsa?ayrCode=25%2F26&unitCode=COMS30050)
<br/>
[Data Projects](../data-projects) | Labs: [1](1-data-ingress) | [2](2-data-privacy-ethics) | [3](3-graph-database) | [4](4-exploration) | 5

---

# Lab 4: Data Exploration and Dimensionality Reduction 

This  lab builds on the lectures on Data Fusion and Data Exploration. The lab will involve exploring the Iris and the MNIST datasets and applying dimensionality reduction techniques. To help you prepare for the lab, you are provided with a Python notebook containing code to load a dataset, to do initial exploration, and to run the PCA and t-SNE algorithms.

#### Updates
- <span style="color:blue">12 Feb 2026.</span> Task specification available


## Prerequisites

- Download the IRIS dataset
- Download the MNIST dataset

## Before the Lab

To prepare for Lab 4, follow these steps before Thursday (give yourself plenty of time):
- Revisit the lecture on Data Exploration
- Go through the remedial material on statistics and dimensionality reduction (*Important:* Spend time on understanding the dimensionality reduction parts of the videos)
    - Descriptive Statistics: [Slides](https://www.ole.bris.ac.uk/bbcswebdav/xid-75181095_2) & [Video](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS30050_2025_TB-2/lectures/Week%204%20Materials/Raul%20Remedial%20Materials/data_exploration_1_descriptive_statistics.mov) [19 mins]
    - Transforms: [Slides](https://www.ole.bris.ac.uk/bbcswebdav/xid-75181096_2) & [Video](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS30050_2025_TB-2/lectures/Week%204%20Materials/Raul%20Remedial%20Materials/data_exploration_2_transforms.mov) [13 mins]
    - Dimensionality Reduction: [Slides](https://www.ole.bris.ac.uk/bbcswebdav/xid-75181097_2) & [Video](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS30050_2025_TB-2/lectures/Week%204%20Materials/Raul%20Remedial%20Materials/data_exploration_3_dimensionality_reduction.mov) [16 mins]
    - [Combined Slides](https://www.ole.bris.ac.uk/bbcswebdav/xid-75181094_2) 
    <br> *Acknowledgement: Niall Twomey, Raul Santos-Rodriguez*
- Explore the IRIS dataset [Important]
  - Download the dataset here:  [Iris.csv](https://www.ole.bris.ac.uk/bbcswebdav/xid-75184794_2)
  - Notebook to help you explore the dataset: [01_iris_species.ipynb](https://www.ole.bris.ac.uk/bbcswebdav/xid-75184791_2)
  - This includes code to load the Iris data, do some basic exploration and dimensionality reduction via PCA and t-SNE
- Download the MNIST dataset:
  - [mnist_train.mat](https://www.ole.bris.ac.uk/bbcswebdav/xid-75184797_2)
  - [mnist_test.mat](https://www.ole.bris.ac.uk/bbcswebdav/xid-75184796_2)
  
## Lab Tasks

- [Lab 4 Task Specification](#task-specification)
- Python notebook with code to load the MNIST data that is available in .mat file format and to plot scatter plots: [02_mnist.ipynb](https://www.ole.bris.ac.uk/bbcswebdav/xid-75184793_2) 
- Note the code expects the 'mnist' data files to be a sub-directory called 'mnist'


## Lab Solutions

- [Lab 4 Solution]() *(will be linked here)*

---
# Task Specification

## Exploratory tasks
- Compute the descriptive statistics for the Iris and the MNIST datasets
  - Central tendency:
    - Mean, Median, Mode
  - Variability:
    - Variance, Quartiles, Max and Min
  - Test the normality of the data
    - Kurtosis and Skewness
      - <https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.skew.html>
      - <https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.kurtosis.html>
  - More here: <https://docs.scipy.org/doc/scipy/reference/stats.html>
- In the Iris dataset are there any outliers?
  - Compute the quartiles (Q1, Q2, Q3, and Q4)
  - Compute the Inter Quartile Range (IQR)
    - IQR = Q3 – Q1
  - Are there any values less than Q1-1.5×IQR or greater than Q3+1.5×IQR?
- Apply dimension reduction algorithms and compare the outputs. Vary the default parameters and
observe the changes in the output.
  - PCA: <https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html>
  - t-SNE: <https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html>
  - UMAP: <https://umap-learn.readthedocs.io/en/latest/basic_usage.html>
  - Random projections: <https://scikit-learn.org/stable/modules/random_projection.html>

```
from sklearn.random_projection import johnson_lindenstrauss_min_dim
from sklearn.random_projection import GaussianRandomProjection

min_dim = johnson_lindenstrauss_min_dim(n_samples = X_train.shape[0], eps = 0.9)
grp = GaussianRandomProjection(n_components = 2)
X_new = grp.fit_transform(Xs)
```

- Additional task: Could we identify clusters automatically?
  - K-means clustering
    - <https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html>
