# Dimensionality Reduction Techniques

Dimensionality reduction techniques are essential in data science for visualizing and analyzing high-dimensional datasets. This project demonstrates the following techniques:

1. Locally Linear Embedding (LLE)
2. t-Distributed Stochastic Neighbor Embedding (t-SNE)
3. Isomap
4. Uniform Manifold Approximation and Projection (UMAP)
5. Multidimensional Scaling (MDS)
6. Randomized Principal Component Analysis (Randomized PCA)
7. Kernel Principal Component Analysis (Kernel PCA)
8. Incremental Principal Component Analysis (Incremental PCA)
9. Factor Analysis
10. Autoencoders

---
Youtube : https://www.youtube.com/watch?v=-Kw4UaQJphE 

YouTube for Alternative Databricks : https://www.youtube.com/watch?v=eXPPW3-3Jwg 
---

## Part 1: Dimensionality Reduction in Colab

### Image Dataset

- **Dataset Used**: [Olivetti Faces Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_olivetti_faces.html)
- **Techniques Applied**:
  - Locally Linear Embedding (LLE)
  - t-SNE (Interactive Visualization)
  - Isomap
  - UMAP (Interactive Visualization)
  - Multidimensional Scaling (MDS)
  - Randomized PCA
  - Kernel PCA
  - Incremental PCA
  - Factor Analysis
  - Autoencoders
- **Code and Execution**:
  The implementation is detailed in the Colab notebook: https://github.com/intimanjunath/Dimensionality_Reduction/blob/main/Dimensionality_Reduction_Olivetti_Faces_dataset.ipynb.

---

### Tabular Dataset

- **Dataset Used**: Breast Cancer Dataset from Scikit-learn
- **Techniques Applied**:
  - Locally Linear Embedding (LLE)
  - t-SNE (Interactive Visualization)
  - Isomap
  - UMAP (Interactive Visualization)
  - Multidimensional Scaling (MDS)
  - Randomized PCA
  - Kernel PCA
  - Incremental PCA
  - Factor Analysis
  - Autoencoders
- **Code and Execution**:
  The implementation is detailed in the Colab notebook: https://github.com/intimanjunath/Dimensionality_Reduction/blob/main/Dimensionality_Reduction_Breast_Cancer_dataset.ipynb.

---

## Part 2: Dimensionality Reduction in Databricks

This part showcases dimensionality reduction techniques in the Databricks environment, leveraging its scalable computing capabilities.

### Steps:
1. **Setup Databricks Environment**:
   - Configure a Databricks cluster.
   - Install necessary packages (`umap-learn`, `scikit-learn`, etc.).
2. **Dataset**:
   - Tabular dataset: Breast Cancer Dataset
3. **Techniques Applied**:
   - Randomized PCA using PySpark
   - t-SNE
   - UMAP
   - Autoencoders
4. **Code and Execution**:
   - Detailed steps are documented in the Databricks notebook: https://github.com/intimanjunath/Dimensionality_Reduction/blob/main/B_Dimensionality_Reduction_Workflow_Databricks.ipynb.
   - Alternative code for DAtabricks notebook : https://github.com/intimanjunath/Dimensionality_Reduction/blob/main/data_bricks_Demonstrate_dimensionality.ipynb

---

## Results and Comparison

| **Technique**       | **Image Dataset** | **Tabular Dataset** | **Observations**                                                                 |
|----------------------|-------------------|----------------------|----------------------------------------------------------------------------------|
| Locally Linear Embedding (LLE) | ✅                | ✅                   | Good for non-linear data, sensitive to noise.                                   |
| t-SNE               | ✅ (Interactive)  | ✅ (Interactive)     | Excellent for visualizing clusters, but computationally expensive.              |
| Isomap              | ✅                | ✅                   | Effective for globally non-linear manifolds.                                    |
| UMAP                | ✅ (Interactive)  | ✅ (Interactive)     | Similar to t-SNE but faster and better at preserving global structure.          |
| Multidimensional Scaling (MDS) | ✅                | ✅                   | Works well for linear separable data, but limited scalability.                  |
| Randomized PCA      | ✅                | ✅                   | Suitable for large datasets, but assumes linear separability.                   |
| Kernel PCA          | ✅                | ✅                   | Extends PCA to non-linear datasets using kernels.                               |
| Incremental PCA     | ✅                | ✅                   | Handles large datasets efficiently by processing in chunks.                     |
| Factor Analysis     | ✅                | ✅                   | Focuses on explaining variance in terms of underlying latent factors.           |
| Autoencoders        | ✅                | ✅                   | Learns latent space representations, effective for non-linear transformations.  |

---

## How to Use

### 1. Colab Notebooks:
- Clone the repository:
  ```bash
  git clone https://github.com/your-username/dimensionality-reduction.git
