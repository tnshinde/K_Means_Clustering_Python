Clustering based on: Annual Income and Spending Score for a retail company for their new product launch 

**Project Overview**
The goal of this project is to perform customer segmentation using the K-Means algorithm on a dataset containing information about customers' Annual Income and Spending Score. By clustering customers into segments, businesses can better understand their customer base and make data-driven marketing decisions.

📊 **Dataset Information**

The dataset used in this project includes:
Annual Income: Annual income of the customer.
Spending Score: A score assigned based on customer behavior and spending patterns.
The data was loaded from an Excel file (FYE_data.xlsx).

🗂️ **Project Structure**
├── FYE_data.xlsx               # Input dataset (replace with your file path)
├── customer_segmentation.py    # Python code for K-Means clustering
├── README.md                   # Project documentation

🔍 **Clustering Methodology**
1. Data Preprocessing
Extracted relevant columns: Annual Income and Spending Score.
Scaled the data using StandardScaler to ensure better clustering performance.
2. K-Means Clustering
Performed clustering with 2 clusters to understand the basic segmentation.
Extended to 3 clusters to identify finer customer segments.
Visualized the clusters using scatter plots for easy interpretation.

📈**Visualizations**
Scatter Plot with 2 Clusters:
Visualizes customer segmentation using Annual Income and Spending Score.
Scatter Plot with 3 Clusters:
Shows a more granular segmentation with an additional cluster.

🎯 **Results**
Explanation of the 2 Clusters
Cluster 0: Represents customers with a certain range of income and spending patterns.
Cluster 1: Represents another group with different spending behaviors.
Detailed summary of the number of customers, average annual income, and spending score for each cluster.
Explanation of the 3 Clusters
Cluster 0, 1, 2: Provides a more detailed segmentation with a third cluster, offering deeper insights into customer behavior.
Summary of the number of customers, average income, and spending score for each cluster

🤝 **Contributing**
Contributions are welcome. If you have ideas for improvement or find any issues, feel free to open an issue or submit a pull request.

