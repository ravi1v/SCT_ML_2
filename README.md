##  K-Means Clustering on Mall Customers
This project applies K-Means clustering on the Mall Customers Dataset to group customers based on Gender, Annual Income, and Spending Score. A 3D plot is used to visualize the clusters.

⚙️ Steps

Import & Load Data – Read Mall_Customers.csv.

Preprocess – Encode gender using LabelEncoder.

Select Features – ['Gender', 'Annual Income (k$)', 'Spending Score (1-100)'].

Elbow Method – Determine optimal number of clusters.

Apply K-Means – Use `KMeans`(n_clusters=2) from `scikit-learn`.

Visualize – Create a 3D scatter plot using `Matplotlib`.

 ## 📈 Output
Customers are segmented into 2 distinct clusters.
The 3D visualization clearly shows customer grouping patterns


## 🧰 Tools Used

Python, Pandas, Matplotlib (3D), Scikit-learn

##🚀 Run
```
pip install pandas
pip install matplotlib

pip install scikit-learn
```
