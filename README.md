# Customer-Segmentation-using-K-Means-Clustering
Customer-Segmentation-Analysis-Using-k-Means-Hierarchical-Clustering
This project is on Customer-Segmentation-Analysis-Using-k-Means-Hierarchical-Clustering

Introduction Customer segmentation is a crucial technique in retail analytics that helps businesses understand their customer base by grouping them based on similar purchasing behaviors. This project aims to apply k-Means and Hierarchical Clustering to segment customers using their spending habits. The insights derived can help businesses tailor marketing strategies and improve customer engagement.
Dataset Description The dataset consists of retail customer data with attributes such as: Customer ID – Unique identifier for each customer Age – Customer’s age Annual Income (k$) – Annual income in thousands of dollars Spending Score (1-100) – Customer’s spending habits (higher score = higher spending)
Data Preprocessing Steps Taken: Handling Missing Values – Checked and filled or removed any missing data. Data Normalization – Scaled numerical variables using StandardScaler to ensure fair clustering. Feature Selection – Used relevant features (Annual Income and Spending Score) for segmentation.
Exploratory Data Analysis (EDA) Distribution Analysis – Plotted histograms to analyze income and spending score distributions. Correlation Analysis – Checked relationships between attributes using heatmaps. Scatter Plots – Visualized income vs. spending patterns.
Clustering Techniques k-Means Clustering Used the Elbow Method to determine the optimal number of clusters. Applied k-Means and analyzed the cluster centroids. Visualized clusters using scatter plots. Hierarchical Clustering Used Dendrograms to identify optimal cluster numbers. Applied Agglomerative Hierarchical Clustering. Compared results with k-Means.
Evaluation & Visualization Silhouette Score – Measured clustering quality. Cluster Heatmaps & Pairplots – Visualized segment characteristics. Comparison of Methods – Discussed pros and cons of k-Means vs. Hierarchical Clustering.
Tableau Dashboard Imported clustered customer data into Tableau. Created interactive visualizations showing cluster distributions, spending trends, and income segmentation. Provided insights into customer groups and their purchasing behaviors.
Conclusion Identified distinct customer groups based on spending patterns. Recommended targeted marketing strategies for different segments. Discussed potential future improvements, such as including more demographic variables.
