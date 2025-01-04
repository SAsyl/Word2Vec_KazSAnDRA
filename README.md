# KazSAnDRA Analysis with Word2Vec and Dimensionality Reduction

This project explores the KazSAnDRA dataset, focusing on classifying data with evenly distributed classes. Two Word2Vec-based models were developed using vector dimensions of 64 and 128. To further analyze and visualize the data, dimensionality reduction techniques like PCA and UMAP were applied.

## Key Features
- **Dataset**: [KazSAnDRA](https://github.com/IS2AI/KazSAnDRA) with [balanced class distribution](https://github.com/IS2AI/KazSAnDRA/blob/main/dataset/02_pc_train_ros.zip).
- **Models**: Two Word2Vec implementations:
  - Vector size 64
  - Vector size 128
- **Dimensionality Reduction**:
  - PCA (Principal Component Analysis)
  - UMAP (Uniform Manifold Approximation and Projection)
- **Visualization**:
  - Tokens visualized and colored based on their frequency in positive and negative classes.

## Future Work
- Experiment with other word embeddings (e.g., GloVe, FastText).
- Implement additional classification algorithms for comparative analysis.
