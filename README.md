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

## Objective

To group customers into meaningful segments using deep learning (Variational Autoencoder) and clustering (KMeans), allowing businesses to target each segment effectively.

## Features

- Feature extraction using Variational Autoencoders (VAE)
- Dimensionality reduction and clustering using KMeans
- Visualization of customer clusters using t-SNE and PCA
- Performance evaluation using silhouette scores, precision, recall, and diversification ratio

## Tech Stack

- Python
- TensorFlow / Keras
- Scikit-learn
- Matplotlib, Seaborn
- Pandas, NumPy

## Algorithms Used

- Variational Autoencoder (VAE) for unsupervised representation learning
- KMeans Clustering for segment formation
- t-SNE / PCA for visualizing high-dimensional clusters

## Visual Output Examples

- Cluster plots (t-SNE / PCA)
- Metric comparison tables (Silhouette Score, Precision, Recall)
- Segment-wise feature importance heatmaps

##  How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/deep-customer-segmentation.git
cd deep-customer-segmentation

# Create virtual environment
python -m venv env
source env/bin/activate  # Windows: env\\Scripts\\activate

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Deep_clustering_Segmentation.ipynb

