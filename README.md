Customer Segmentation Using Unsupervised Learning
 Project Description

This project explores customer segmentation using unsupervised learning techniques.
The goal is to group customers into meaningful clusters based on their age, annual income, and spending score, allowing businesses to improve their marketing strategies.
 Dataset

    Name: Mall Customers Dataset

    Source: Kaggle - Customer Segmentation Dataset

    Attributes:

        CustomerID

        Gender

        Age

        Annual Income (k$)

        Spending Score (1–100)

 Technologies Used

    Python 3.x

    Jupyter Notebook

    Libraries:

        pandas

        numpy

        matplotlib

        seaborn

        scikit-learn (KMeans, DBSCAN, Agglomerative Clustering, GMM, Spectral Clustering)

 How to Run

    Install the required libraries:

    pip install pandas numpy matplotlib seaborn scikit-learn

    Open the provided Jupyter Notebook:
    Customer_Segmentation_Unsupervised_Learning.ipynb

    Run all cells sequentially.

    Follow the steps: EDA ➔ Preprocessing ➔ Modeling ➔ Evaluation ➔ Results.

 Project Structure
Section	Description
1. Introduction	Problem definition and dataset introduction
2. Data Description	Dataset details
3. EDA	Visual exploration of features
4. Preprocessing	Feature scaling
5. Dimensionality Reduction	PCA visualization
6. Modeling	KMeans, Agglomerative, DBSCAN, GMM, Spectral Clustering
7. Evaluation	Silhouette, Calinski-Harabasz, Davies-Bouldin metrics
8. Results and Analysis	Model comparison and discussion
9. Conclusion	Final thoughts and future directions
📈 Results Summary

    KMeans Clustering and Gaussian Mixture Models performed the best.

    DBSCAN was less effective due to uniform density in the dataset.

    Hierarchical Clustering provided good insights through dendrograms.

    Overall, unsupervised learning successfully revealed five customer segments.
