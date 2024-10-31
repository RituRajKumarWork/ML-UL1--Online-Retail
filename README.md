# Unsupervised Learning: Clustering Project
Raj

This project demonstrates the application of **unsupervised learning** techniques, focusing on **clustering algorithms**. Through this project, we explore how clustering can reveal hidden patterns and structures in data without requiring labeled outputs.

## Project Overview

The main objective of this project is to showcase clustering methods and evaluate their effectiveness in discovering patterns in unstructured data. We primarily use **K-means** and **Hierarchical Clustering** to segment data into meaningful groups, visualizing and interpreting the results. Additionally, we calculate metrics like **silhouette scores** and **Davies-Bouldin index** to assess clustering quality.

## Dataset

The dataset used for this project is the [Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail) from the UCI Machine Learning Repository. This dataset contains transactional data for an online retail store and includes fields such as:
- Invoice number
- Stock code
- Description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

The dataset provides a real-world scenario for applying clustering to identify customer segments or purchasing patterns.

## Project Structure

- **Data Preprocessing**: Prepares the dataset by handling missing values, normalizing features, and reducing dimensions if needed.
- **Clustering Techniques**:
  - **K-means Clustering**: Segments data based on a predefined number of clusters.
  - **Hierarchical Clustering**: Organizes data into a hierarchical structure, visualized through a dendrogram.
- **Evaluation and Visualization**:
  - **Elbow Method** and **Silhouette Scores** help determine the optimal number of clusters.
  - **PCA and t-SNE visualizations** display cluster groupings in two-dimensional space.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/RituRajKumarWork/ML-UL1--Online-Retail.git
