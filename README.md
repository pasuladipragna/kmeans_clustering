# K-Means Clustering - Mall Customer Segmentation

This project performs **unsupervised learning** using **K-Means clustering** on a dataset of mall customers.

## ✅ Steps Performed

1. Loaded and explored the dataset
2. Selected relevant features (`Age`, `Annual Income`, `Spending Score`)
3. Used **Elbow Method** to determine optimal number of clusters
4. Applied **K-Means clustering**
5. Visualized clusters using **PCA**
6. Evaluated clustering using **Silhouette Score**

## 📊 Dataset Used

**Mall_Customers.csv**  
[Download here](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

## 📎 Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 📈 Results

- Optimal clusters (K): 5 (from Elbow Method)
- Silhouette Score: 0.55 (approx.)
- Clusters visualized using PCA

## 📁 Files

- `kmeans_clustering.py`: Main code file
- `mall_customers.csv`: Dataset
- `cluster_plot.png`: Cluster visualization
- `elbow_plot.png`: Elbow method plot

## 🚀 How to Run

pip install pandas matplotlib seaborn scikit-learn
python kmeans_clustering.py
