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

- **KMeans Clustering**: A centroid-based clustering algorithm that partitions data into K clusters by iteratively assigning data points to the nearest cluster center.
- **Agglomerative Hierarchical Clustering**: A hierarchical clustering algorithm that builds a hierarchy of clusters by recursively merging the nearest clusters based on a linkage criterion.
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**: A density-based clustering algorithm that groups together data points that are closely packed, while marking outliers as noise.

## Getting Started

1. Clone the repository:
