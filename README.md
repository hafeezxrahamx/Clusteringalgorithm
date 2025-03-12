# Clustering Techniques on the Iris Dataset

## Objective
The objective of this assessment is to evaluate the understanding and application of clustering techniques on the Iris dataset using KMeans and Hierarchical Clustering.

## Dataset
The dataset used in this project is the **Iris dataset**, available in the **sklearn library**. The dataset consists of 150 samples with four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

Since this is a clustering problem, the species column is **dropped** during preprocessing.

## Key Components
### 1. Loading and Preprocessing
- Load the **Iris dataset** from sklearn.
- Remove the **species column** to facilitate clustering.

### 2. Clustering Algorithm Implementation
#### A) KMeans Clustering 
- **Description**: KMeans is an iterative clustering algorithm that partitions data into K clusters based on minimizing the sum of squared distances between points and their assigned cluster centroids.
- **Suitability for Iris Dataset**: The Iris dataset contains naturally separable clusters, making KMeans an effective method for identifying species groups.
- **Implementation**:
  - Apply **KMeans clustering** on the preprocessed dataset.
  - **Visualize** the clusters using a scatter plot.

#### B) Hierarchical Clustering 
- **Description**: Hierarchical clustering builds a hierarchy of clusters using a bottom-up (agglomerative) or top-down (divisive) approach. The results are typically visualized using a dendrogram.
- **Suitability for Iris Dataset**: Since the Iris dataset contains well-separated groups, hierarchical clustering can effectively reveal relationships between data points.
- **Implementation**:
  - Apply **Hierarchical Clustering** on the preprocessed dataset.
  - **Visualize** the clusters using a dendrogram and scatter plot.

### 3. Timely Submission 
- Ensure that the assignment is submitted on time.

## Submission Guidelines
- **Provide the code** in a Jupyter Notebook format.
- **Upload the project** to GitHub.
- **Submit the GitHub link** as per the instructions.
- Ensure all explanations are **clear and concise**.

## Repository Structure
```
├── clustering_assignment
│   ├── README.md  # Project overview
│   ├── clustering_analysis.ipynb  # Jupyter Notebook with code and explanations
│   ├── dataset  # Contains the Iris dataset (if needed)
│   ├── images  # Cluster visualizations
```

---
### Author
Hafeez Rahman SH

