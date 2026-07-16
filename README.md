# Advanced Unsupervised Machine Learning & Model Interpretation

This notebook explores unsupervised machine learning (clustering and dimensionality reduction) along with model interpretation techniques using two real-world datasets.

## Datasets

**Wholesale Customers** — customer segmentation dataset containing annual spending across multiple product categories (440 customers, 8 features).

**Olivetti Faces** — high-dimensional facial image dataset consisting of 400 grayscale face images of 40 individuals (64 × 64 pixels, 4,096 features).

Both datasets are downloaded automatically via **KaggleHub** within the notebook.

---

## What's Covered

### Clustering
- K-Means
- Hierarchical Clustering
- DBSCAN
- Gaussian Mixture Models (GMM)
- Mean Shift

### Dimensionality Reduction
- Principal Component Analysis (PCA)
- Kernel PCA
- t-SNE
- UMAP

### Evaluation
- Elbow Method
- Inertia
- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Index

### Model Interpretation
- Random Forest Feature Importance
- Permutation Importance
- SHAP (SHapley Additive Explanations)
- Partial Dependence Plots

---

## Structure

- `Advanced_Unsupervised_Machine_Learning_Model_Interpretation.ipynb` — Main notebook containing data preprocessing, clustering, dimensionality reduction, model evaluation, visualization, and interpretation.

---

## Requirements

- kagglehub
- numpy
- pandas
- matplotlib
- seaborn
- scipy
- scikit-learn
- umap-learn
- shap

---

## Usage

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the notebook from top to bottom. Both datasets are downloaded automatically via **KaggleHub**, and all preprocessing, analysis, visualizations, clustering, dimensionality reduction, and model interpretation steps are executed sequentially.

---

## Highlights

- End-to-end unsupervised machine learning workflow
- Customer segmentation using multiple clustering algorithms
- High-dimensional image analysis with the Olivetti Faces dataset
- Comparison of clustering algorithms using standard evaluation metrics
- Dimensionality reduction using PCA, Kernel PCA, t-SNE, and UMAP
- Explainable AI using Feature Importance, Permutation Importance, SHAP, and Partial Dependence Plots

---

## Notes

This project was developed for educational and portfolio purposes. It demonstrates practical implementation of unsupervised machine learning, dimensionality reduction, cluster evaluation, visualization, and model interpretation using Python and the Scikit-learn ecosystem.