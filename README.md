# Dimensionality-Reduction
Investigating Dimensionality Reduction and Clustering Techniques for Pancreatic Cell Data

High-dimensional data poses significant challenges to model training and construction due to the curse of dimensionality, resulting in reduced model performance and increased
computational overhead. This research paper investigates
various dimensionality reduction techniques for deep learning
applications to address these challenges. The study focuses on
the Muraro dataset, which contains single-cell transcriptome
data of the human pancreas. The proposed approach utilizes
PCA, kPCA, Autoencoders, UMAP, and t-SNE for dimensionality
reduction, followed by k-means clustering to evaluate the performance
of each algorithm. Silhouette scores are used to assess
cluster quality. The results indicate that nonlinear techniques,
particularly UMAP, outperform linear methods in preserving
global and local structures and achieving improved clustering
results. The optimal number of clusters for kPCA-transformed
data is consistently identified as four, while UMAP demonstrates
the highest silhouette score among the tested methods.
