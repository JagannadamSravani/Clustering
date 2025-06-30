📊 Instagram User Segmentation using Clustering
📌 Overview
This project performs unsupervised learning to segment Instagram users based on two features:

Instagram Visit Score – indicating user engagement level.

Spending Rank (0–100) – indicating spending capacity.

The goal is to uncover patterns and cluster users into distinct groups using multiple clustering techniques.

📁 Dataset Description
Source: Instagram visits clustering.csv

Columns:

Instagram visit score – Numeric value showing engagement level.

Spending_rank (0 to 100) – Numeric rank showing user's spending power.

Preprocessing:

Dropped irrelevant identifiers (User ID).

Standardized features using StandardScaler.

📌 Techniques Used
✅ Clustering Algorithms:
K-Means Clustering

Agglomerative Hierarchical Clustering

Complete Linkage

Single Linkage

K-Medoids Clustering

✅ Supporting Methods:
Elbow Method to determine optimal k value.

Dendrograms for hierarchical visualization.

Scatter plots for cluster interpretation.

📈 Key Results
Algorithm	Inference
K-Means	Best clustered the data into 3 groups based on elbow plot and silhouette.
Agglomerative	Hierarchical structure shown in dendrogram, supported 3-cluster split.
K-Medoids	More stable clustering; robust to outliers.
Single Linkage	Chaining effect; poor separation in clusters.
Complete Linkage	Better separation but some overlap near cluster boundaries.

📊 Visualizations
📌 Elbow Plot – Chose optimal k=3

📌 Scatter Plot – Showed clear separation in K-Means clusters

📌 Dendrograms – Helped validate hierarchical relationships

🏁 Conclusion
Clustering techniques were successfully applied to segment Instagram users into 3 distinct clusters. These clusters reveal:

High-spending but low-engagement users,

High-engagement, low-spending users,

Balanced users (moderate in both).

Such insights are highly useful for targeted marketing or personalized recommendation strategies.
