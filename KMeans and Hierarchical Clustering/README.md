**Overview:**

This project focuses on the segmentation of mall customers using two popular clustering techniques: K-Means clustering and Hierarchical clustering. The dataset used contains information about customers, including age, annual income, and spending score. The goal is to identify patterns and group customers based on their similarities in spending behavior.

**Data:**

The dataset used in this project is sourced from the Mall_Customers.csv file. It includes the following columns:

CustomerID: Unique identifier for each customer<br />
Gender: Gender of the customer (Male or Female)<br />
Age: Age of the customer<br />
Annual Income (k$): Annual income of the customer<br />
Spending Score (1-100): Spending score assigned by the mall based on customer behavior and spending nature<br />

**Exploratory Data Analysis (EDA):**

Checked for missing values: The dataset is clean with no missing values.<br />
Explored the distribution of gender.<br />
Analyzed the frequency of customers based on age, annual income, and spending score.

**K-Means Clustering:**

Selected features for clustering: Annual Income and Spending Score.<br />
Used the Elbow Method to determine the optimal number of clusters (K=5).<br />
Applied K-Means clustering with K=5.<br />
Visualized the clusters and centroids.

**Hierarchical Clustering:**

Visualized the dendrogram to determine the optimal number of clusters.<br />
Applied Hierarchical Clustering with K=5.<br />
Visualized the clusters.<br />

**Conclusion:**
The project concludes with customer segmentation using both K-Means and Hierarchical clustering techniques. The identified clusters can be used for targeted marketing strategies, allowing the mall to tailor its approach based on the distinct needs and preferences of each customer group.
