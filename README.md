# Assignment Result: Clustering Analysis on Iris Dataset

In this assignment, we conducted clustering analysis on the Iris dataset using different preprocessing techniques and clustering algorithms. We evaluated the clustering performance using three evaluation metrics: silhouette score, Calinski-Harabasz score, and Davies-Bouldin score.

## Table 1: KMeans Clustering

| Preprocessing | Algorithm | Number of Clusters | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|---------------|-----------|--------------------|------------|-------------------|----------------|
| StandardScaler | KMeans    | 2                  | 0.351834   | 171.083538        | 0.919696       |
| StandardScaler | KMeans    | 6                  | 0.334297   | 174.073089        | 1.009533       |
| StandardScaler | KMeans    | 9                  | 0.337567   | 174.191869        | 1.009970       |
| MinMaxScaler   | KMeans    | 2                  | 0.337311   | 244.098113        | 1.015714       |
| MinMaxScaler   | KMeans    | 6                  | 0.334155   | 246.569434        | 0.996631       |
| MinMaxScaler   | KMeans    | 9                  | 0.334193   | 245.812344        | 1.046025       |
| PCA            | KMeans    | 2                  | 0.454271   | 732.708183        | 0.681194       |
| PCA            | KMeans    | 6                  | 0.443210   | 731.804473        | 0.728544       |
| PCA            | KMeans    | 9                  | 0.453941   | 733.623183        | 0.690693       |

## Table 2: Hierarchical Clustering

| Preprocessing | Algorithm   | Number of Clusters | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|---------------|-------------|--------------------|------------|-------------------|----------------|
| StandardScaler | Hierarchical | 2                  | 0.446689   | 222.719164        | 0.803467       |
| StandardScaler | Hierarchical | 6                  | 0.446689   | 222.719164        | 0.803467       |
| StandardScaler | Hierarchical | 9                  | 0.446689   | 222.719164        | 0.803467       |
| MinMaxScaler   | Hierarchical | 2                  | 0.504800   | 349.254185        | 0.747977       |
| MinMaxScaler   | Hierarchical | 6                  | 0.504800   | 349.254185        | 0.747977       |
| MinMaxScaler   | Hierarchical | 9                  | 0.504800   | 349.254185        | 0.747977       |
| PCA            | Hierarchical | 2                  | 0.598475   | 688.617548        | 0.560496       |
| PCA            | Hierarchical | 6                  | 0.598475   | 688.617548        | 0.560496       |
| PCA            | Hierarchical | 9                  | 0.598475   | 688.617548        | 0.560496       |
