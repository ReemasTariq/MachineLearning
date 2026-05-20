Final Questions
1. This is an unsupervised learning problem because the dataset does not contain target labels, and the model groups customers automatically based on similarities.

2. The `CUST_ID` column was removed because it is only a customer identifier and does not contribute to clustering.

3. Missing values were handled by replacing them with the mean of each column using `fillna()`.

4. Feature scaling is important because K-Means relies on distance calculations, and features with large values can dominate the clustering process.

5. The elbow method is used to determine the optimal number of clusters by identifying the point where inertia decreases more slowly.

6. The silhouette score measures how well data points fit within their clusters. A higher score indicates better cluster separation.

7. K-Means clustering groups customers with similar spending behavior and financial patterns into clusters.

8. PCA was used to reduce the dataset dimensions into two components for easier visualization of customer clusters.

9. Different clusters represent different customer behaviors, such as high spending customers, low activity customers, or customers who frequently use cash advances.

10. Businesses can use customer segmentation for targeted marketing, personalized recommendations, customer retention, and improving business decisions.
