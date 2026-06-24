# Customer-Segmentation-Using-Unsupervised-Learning
Customer segmentation using unsupervised machine learning techniques including K-Means and DBSCAN with PCA, t-SNE, and UMAP for exploratory analysis and customer behaviour discovery.


## Features

- Exploratory Data Analysis (EDA)
- Statistical analysis and data visualization
- Correlation analysis
- Dimensionality reduction using:
  - PCA
  - t-SNE
  - UMAP
- Customer segmentation using:
  - K-Means Clustering
  - DBSCAN Clustering
- Clustering evaluation using:
  - Silhouette Score
  - Davies-Bouldin Index
  - Calinski-Harabasz Index
  - Gap Statistic
- Cluster visualization and profiling

---

## Dataset

The dataset contains customer shopping behaviour information including:

- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

The dataset consists of 200 customer records.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- UMAP

---

## Project Structure

```text
Customer-Segmentation-Using-Unsupervised-Learning/
│
├── assignment2.ipynb     # Complete implementation
├── report.pdf            # Project report
├── screenshots/          # Visualizations and outputs
├── README.md
└── requirements.txt
```

---

## Methodology

### 1. Data Exploration

- Descriptive statistics
- Distribution analysis
- Correlation analysis
- Outlier detection
- Pairwise relationship analysis

### 2. Dimensionality Reduction

To visualize hidden structures within the data, the following techniques were applied:

- Principal Component Analysis (PCA)
- t-distributed Stochastic Neighbor Embedding (t-SNE)
- Uniform Manifold Approximation and Projection (UMAP)

Both t-SNE and UMAP revealed meaningful customer grouping patterns. :contentReference[oaicite:3]{index=3}

### 3. Clustering

Two clustering algorithms were implemented and compared:

#### K-Means

- Efficient centroid-based clustering
- Optimal number of clusters selected using the Elbow Method and Gap Statistic

#### DBSCAN

- Density-based clustering
- Detects noise points and irregular cluster structures

---

## Evaluation Metrics

Clustering performance was evaluated using:

- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Index
- Gap Statistic

DBSCAN achieved slightly better overall clustering performance compared to K-Means.

---

## Key Findings

- Customer behaviour exhibits distinct hidden patterns.
- Annual income and spending score were the most informative features for segmentation.
- Both K-Means and DBSCAN successfully identified meaningful customer segments.
- The identified clusters can support personalized marketing and business decision-making. 
---

## Running the Project

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Customer-Segmentation-Using-Unsupervised-Learning.git
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
assignment2.ipynb
```

---

## Author

**Piyumi Hettiarachchi**

Master of Data Science  
Swinburne University of Technology

---

## License

This project was developed for educational purposes as part of the COS80027 Machine Learning unit at Swinburne University of Technology.
