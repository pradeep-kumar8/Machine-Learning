# Customer Segmentation using KMeans Clustering
This project demonstrates customer segmentation using KMeans clustering on transactional data. The objective is to group customers into distinct segments based on their purchasing behavior.

## Project Overview
Customer segmentation is a crucial task in marketing that helps businesses tailor their strategies for different customer groups. This project applies KMeans clustering on customer data using three main features:

1. Monetary (Total Amount Spent)
2. Frequency (Number of Transactions)
3. Recency (Days Since Last Transaction)
4. The process includes:

### Data Preprocessing
Outlier Removal
Feature Scaling
Clustering using KMeans
Visualizing Clusters using PCA
Files in Repository
data.csv: Sample dataset containing customer transactional data.
customer_segmentation_kmeans.ipynb: Jupyter Notebook containing the entire workflow.

### Workflow
#### 1. Data Preprocessing
Missing values are identified and removed.
New features like Amount and Recency are computed.
2. Outlier Removal
Outliers are detected using boxplots and removed using the IQR method.
Outlier Detection Boxplot:

![image](https://github.com/user-attachments/assets/2f176f9c-3277-4b7c-93cc-ad2ceec9a8b4)


#### 3. Clustering
Data is scaled using StandardScaler.
The optimal number of clusters is determined using the Elbow Method.
Elbow Method Plot:

![image](https://github.com/user-attachments/assets/03d58c5d-3766-4598-8ec2-652d65768e95)


### KMeans clustering is applied to group customers.
#### 4. Visualization
Clusters are visualized in 2D using PCA for better interpretation.
PCA Cluster Visualization:

![image](https://github.com/user-attachments/assets/cccd905b-b757-4adf-8688-ba555ceec079)


#### 5. Insights
Segmented customers are analyzed based on their spending patterns, transaction frequency, and recency.
