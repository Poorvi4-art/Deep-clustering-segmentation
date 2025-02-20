**Advanced Market Segmentation with Deep Clustering**
         This project uses Deep Clustering methods to segment customers better with deep learning and clustering. The objective is to find specific customer groups through behavioral and demographic information.

- Data Preprocessing:
Loads customer data, drops unwanted columns and standardizes.
Converts categorical variables into machine learning-friendly formats.

- Feature Extraction (VAE - Variational Autoencoder):
Leans a low-dimensional customer data representation.
Extracts hidden patterns prior to clustering.

- Deep Embedded Clustering (DEC):
Leverages deep learning to improve cluster assignments in an iterative way.
Enhances the conventional clustering algorithms with adapting feature representations.

- K-Means Clustering (Baseline):
Classic clustering algorithm applied to learned representations for comparison.

- Visualization & Evaluation:
Employed t-SNE to visualize clusters in 2D space.
Compares the results of DEC and K-Means.
Calculates Silhouette Score to quantify the quality of the clustering.
Outputs segmentation outcomes in table form.
