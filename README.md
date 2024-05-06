# Customer Segmentation - Credit Cards

This project aims to develop a customer segmentation strategy for marketing purposes using data analysis and clustering techniques. The dataset contains information about the usage behavior of approximately 9000 active credit card holders over the last 6 months. By analyzing this data, we can identify distinct customer segments and tailor marketing strategies accordingly.

## About the Project

The dataset provides details about the credit card holders, including their balances, purchase behavior, credit limits, and payment patterns. It consists of the following columns:

- CUST_ID: Identification of Credit Card holder (Categorical)
- BALANCE: Balance amount left in their account to make purchases
- BALANCE_FREQUENCY: How frequently the Balance is updated
- PURCHASES: Amount of purchases made from account
- ONEOFF_PURCHASES: Maximum purchase amount done in one-go
- INSTALLMENTS_PURCHASES: Amount of purchase done in installment
- CASH_ADVANCE: Cash in advance given by the user
- PURCHASES_FREQUENCY: How frequently the Purchases are being made
- ONEOFFPURCHASESFREQUENCY: How frequently Purchases are happening in one-go
- PURCHASESINSTALLMENTSFREQUENCY: How frequently purchases in installments are being done
- CASHADVANCEFREQUENCY: How frequently the cash in advance being paid
- CASHADVANCETRX: Number of Transactions made with 'Cash in Advanced'
- PURCHASES_TRX: Number of purchase transactions made
- CREDIT_LIMIT: Limit of Credit Card for user
- PAYMENTS: Amount of Payment done by user
- MINIMUM_PAYMENTS: Minimum amount of payments made by user
- PRCFULLPAYMENT: Percent of full payment paid by user

## Clustering Algorithms Used

This project utilizes the following clustering algorithms for customer segmentation:

- **KMeans Clustering**: A centroid-based clustering algorithm that partitions data into K clusters by iteratively assigning data points to the nearest cluster center. Users can tune the number of clusters (hyperparameter) from the web interface.
- **Agglomerative Hierarchical Clustering**: A hierarchical clustering algorithm that builds a hierarchy of clusters by recursively merging the nearest clusters based on a linkage criterion. Users can tune the number of clusters (hyperparameter) and choose the linkage type and metric from the web interface.
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**: A density-based clustering algorithm that groups together data points that are closely packed, while marking outliers as noise. Users can tune the epsilon (eps) and min_samples hyperparameters from the web interface.

## Data Visualization

The project uses t-distributed Stochastic Neighbor Embedding (t-SNE) for data visualization. t-SNE is a dimensionality reduction technique commonly used for visualizing high-dimensional data in a lower-dimensional space. It helps in visualizing clusters and patterns in the data.

## Interactivity and Hyperparameter Tuning

This project allows users to interact with hyperparameters directly from the web interface. Users can dynamically adjust the hyperparameters of the clustering algorithms (such as the number of clusters, linkage type, metric, epsilon, and min_samples) and observe the effects on the clustering results in real-time.

## Dashboard Framework

The project is built using Dash, which is a productive Python framework for building web applications. Dash enables the creation of interactive and data-driven web applications directly from Python code, without the need for JavaScript or HTML.
