# Unsupervised-Learning-on-the-Iris-Dataset-A-Clustering-Approach

##  Overview
This project applies **unsupervised machine learning techniques** to analyze patterns in the Iris dataset. The goal is to group similar data points into clusters without using predefined labels.

Two clustering algorithms are implemented and compared:
- KMeans Clustering  
- Hierarchical Clustering  

---

##  Objective
- Perform clustering on the Iris dataset  
- Identify natural groupings in the data  
- Compare clustering techniques  
- Visualize cluster formations  

---

##  Dataset Description
The dataset contains 150 samples with the following features:
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

> Note: The species (target) column is removed for clustering.

---

##  Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

##  Methodology

#### 1. Data Preprocessing
- Loaded dataset from sklearn  
- Converted into DataFrame  
- Removed target column  
- Applied feature scaling  

#### 2. KMeans Clustering
- Applied clustering with K = 3  
- Visualized clusters using scatter plots  

#### 3. Hierarchical Clustering
- Used Agglomerative clustering  
- Created dendrogram  
- Visualized clusters  

---

##  Results & Insights
- Both algorithms identified 3 clusters matching the dataset structure  
- One cluster is clearly distinct, while the other two slightly overlap  
- KMeans is faster and efficient  
- Hierarchical clustering provides better insight into relationships  

---

##  Visualizations
- KMeans Cluster Plot  
- Hierarchical Cluster Plot  
- Dendrogram  

---

##  Conclusion
Both clustering techniques effectively identified patterns in the dataset.  
KMeans is suitable for efficient clustering, while Hierarchical clustering helps understand relationships between data points.

---
