# Task 2: Customer Segmentation – Mall Customers

## Objective
Cluster customers into segments based on their **Annual Income** and **Spending Score** to understand customer behavior and help with marketing strategies.

---

## Dataset
**Name:** Mall_Customers.csv  
**Source:** Kaggle  
**Attributes:**
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Workflow Steps

### 1. Load & Preprocess the Data
- Drop `CustomerID` (not useful for clustering).
- Encode `Gender` into numeric (Male = 0, Female = 1).
- Scale the features using `StandardScaler`.

### 2. Determine Optimal Number of Clusters
- Use **Elbow Method** to identify best `k` value for K-Means.

### 3. Apply K-Means Clustering
- Perform clustering with selected `k`.
- Assign and label clusters.

### 4. Visualize Clusters
- Plot clusters using:
  - `Annual Income` vs `Spending Score`

### 5. Bonus – DBSCAN Clustering
- Try **DBSCAN** for density-based clustering.
- Visualize and compare results.

### 6. Analyze Spending Patterns
- Calculate average spending score for each KMeans cluster.

---

## Visualizations
- Elbow Curve (to choose `k`)
- KMeans Cluster Plot
- DBSCAN Cluster Plot

---

## Insights
- Customers are grouped based on spending habits and income levels.
- Useful for targeted promotions or loyalty programs.

---

## Output Example
```bash
Average Spending Score per KMeans Cluster:
Cluster
0    79.5
1    20.0
2    60.7
3    39.5
4    90.3
