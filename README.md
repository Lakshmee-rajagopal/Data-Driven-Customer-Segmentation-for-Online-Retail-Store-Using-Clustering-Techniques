# Data-Driven Customer Segmentation for Online Retail Store Using Clustering Techniques

# **Goal of the Project**
The goal is to segment customers based on purchasing behavior for a UK-based online retail store, using clustering algorithms to uncover meaningful groups.

*  **Objectives:**

* Analyze transactional data to understand customer behavior.
* Apply clustering algorithms (K-Means, Agglomerative, DBSCAN) to identify customer segments.
* Evaluate clusters using Silhouette score and Davies-Bouldin index.

* **Output:**

* Customer segments and actionable insights.

* **Key Metrics:**

* Silhouette Score: Measures cluster cohesion and separation.
* Davies-Bouldin Index: Assesses cluster similarity; lower values are better.
* Cluster Count: Number of customer segments identified.

# **Data Story**

[Customer Segmentation Dataset](https://docs.google.com/spreadsheets/d/13MZp0G2rVA4-ogIAx99GI12KXGpHliPX/edit?usp=sharing&ouid=108296935564377927140&rtpof=true&sd=true)

* This project uses a real-world dataset sourced from the UCI Machine Learning Repository titled "Online Retail."

* The data captures over 500,000 transactions made between December 2010 and December 2011 by a UK-based online retail company specializing in unique all-occasion gifts.

* The company's customer base consists of both individual shoppers and wholesalers, making segmentation essential for targeted marketing strategies.

**The Dataset**

The dataset includes the following key features:

* InvoiceNo: Unique invoice identifier for each transaction

* StockCode: Unique product identifier

* Description: Product description

* Quantity: Number of items purchased

* InvoiceDate: Date and time of purchase

* UnitPrice: Price per unit of product

* CustomerID: Unique customer identifier

* Country: Customer's country of origin

With a total of 541,909 instances and 6 primary features, the dataset provides rich insights for customer segmentation.

# **Insights**

* The clustering models successfully identified different customer segments based on purchasing behavior.

* **Regular customers:** Represented by moderate transaction counts and spending (Clusters 0 and 1).

* **High-value customers:** Identified in KMeans Cluster 2 and DBSCAN Cluster -1, representing customers with higher spending and quantities.

* * These segments can help the business tailor marketing strategies, offer targeted promotions, or provide special services to high-value customers.

