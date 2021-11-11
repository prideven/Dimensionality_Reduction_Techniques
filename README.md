# Dimensionality Reduction Techniques

To avoid the curse of dimensionality and avoid overfitting particularly when we have a lot of features and relatively few samples one of the 
most common approach is that of reducing dimensionality in feature space. Reduction of dimensionality is the method of reducing 
the dimensionality of the function space by obtaining a collection of principal features.

The Following Dimensionality Reduction algorithms are analysed and compared:

- > PCA
- > SVD
- > LLE
- > ISOMAP
- > t-SNE
- > UMAP

# Dimenionality Reduction on Image Dataset


Analysis on Image DataSet

1. PCA: PCA and SVD did not perform well as the image dataset has high number of dimensions. 
2. SVD: PCA and SVD did not perform well as the image dataset has high number of dimensions. 
3. T-SNE: The data is distributed as small number of patches.
4. LLE: The data formed a small cluster of uninformed data. 
5. ISOMAP: Formed uniformed patches of clusters in the data distribution. 
6. UMAP: The data was were distributed more evenly to form clusters. Overall UMAP outperformed all the techniques and was very effective for visualization of the data.

# Dimenionality Reduction on Tabular Dataset

Analysis for Tabular data Set: 

1. Principal Component Analysis: Is the most preferred method for linear data. In PCA we divide the component set and calculated the most variance value and the less variance are discarded. 
2. SVD: The data distribution is more like PCA and works for linear data as well and worked better on the separating the clusters. 
3. LLE: The data distribution formed good patches of clusters and was uniformly distributed. 
4. t-SNE:  The technique provides extremely well for visualisations and also preferred for non linear data and formed good clusters in data distribution and are well separated.
5. ISOMAP: We use this technique when the data is strongly non-linear.
6. UMAP: This technique works well for high dimensional data and can run-time is shorter as compared to t-SNE. The data clusters patches are more non uniformly distributed.






 
