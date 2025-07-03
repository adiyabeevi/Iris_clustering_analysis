# Iris Dataset Clustering Project

##  Objective
This project applies **unsupervised clustering techniques** on the famous **Iris dataset** to explore natural groupings in flower data based on their physical features — without using the species labels.

---

##  Dataset Used
- **Name**: Iris Dataset  
- **Source**: `sklearn.datasets.load_iris()`  
- **Features**:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)

> The **target column (species)** was **removed** to simulate a real clustering problem.

---

##  Processes Used

1. **Data Loading**
   - Loaded the Iris dataset using scikit-learn.
   - Converted it into a DataFrame with 4 numerical features.

2. **Data Preprocessing**
   - Removed the target (`species`) column.
   - Verified there were no missing values.

3. **KMeans Clustering**
   - Applied KMeans with 3 clusters.
   - Assigned cluster labels.
   - Visualized clusters using a scatter plot.

4. **Hierarchical Clustering**
   - Applied Agglomerative Clustering with 3 clusters.
   - Plotted a dendrogram to show cluster merging.
   - Visualized clusters with a scatter plot.

5. **Observations**
   - Both clustering methods grouped data points effectively.
   - The visual results closely resembled the actual iris species, showing strong natural grouping in the data.


