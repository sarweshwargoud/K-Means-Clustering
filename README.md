# K-Means Clustering

## Overview
This project applies **K-Means clustering** to the **Mall Customers** dataset to segment customers into groups based on their annual income and spending score.  
The goal is to practice unsupervised learning, choose the right number of clusters, and evaluate clustering quality.

## Steps Performed
- Loaded and explored the dataset
- Selected numerical features: Annual Income and Spending Score
- Scaled features using StandardScaler
- Applied PCA to visualize data in 2D (optional)
- Used the **Elbow Method** to inspect optimal K
- Computed **Silhouette Score** for different K values
- Trained final K-Means model
- Visualized clusters with color-coded scatter plot
- Interpreted cluster centers in the original feature space

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## How to Run
1. Open the notebook in Google Colab  
2. Upload `Mall_Customers.csv` to the `data/` folder  
3. Run all cells from top to bottom  

## Output
- Elbow curve and Silhouette plot
- 2D scatter plot of clusters
- Silhouette score for final model
- Cluster center summary (income & spending score per cluster)
