# Clustering with K-Means in E-commerce

This repository contains a theoretical and practical study on customer segmentation using the K-Means algorithm, applied in the context of an e-commerce platform. The goal is to group customers based on their browsing and purchasing behavior to support targeted marketing strategies.

## Contents

### Theoretical Topics

- How the K-Means algorithm works
- Optimizing the number of clusters using the elbow method
- Evaluating clustering quality using:
  - Silhouette score
  - Sum of Squared Errors (SSE)

### Practical Work

- Dataset: `customer_behavior.csv`
- Exploratory data analysis and preprocessing
- Applying K-Means for customer segmentation
- Cluster visualization using charts

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/kauanhindlmayer/k-means-clustering.git
cd k-means-clustering
```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3 Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```
