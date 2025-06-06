# KMeans Clustering on Customer Segmentation

This project demonstrates the application of the K-Means clustering algorithm to segment customers based on their purchasing behaviors and demographics. By identifying distinct customer groups, businesses can tailor marketing strategies, enhance customer satisfaction, and optimize resource allocation.

## 📁 Repository Contents

* **Clustering with K-Means.ipynb**: A Jupyter Notebook detailing the step-by-step process of data preprocessing, applying K-Means clustering, and interpreting the results.

## 📊 Project Overview

### Objective

To perform customer segmentation using the K-Means clustering algorithm, enabling businesses to understand and target different customer groups effectively.([Scribd][1])

### Dataset

The dataset comprises customer information, including:([Medium][2])

* **CustomerID**: Unique identifier for each customer
* **Gender**: Gender of the customer
* **Age**: Age of the customer
* **Annual Income (k\$)**: Annual income of the customer in thousands
* **Spending Score (1–100)**: Score assigned based on customer behavior and spending nature([Medium][2])

This dataset is commonly used for learning purposes and is publicly available on platforms like Kaggle.

### Methodology

1. **Data Preprocessing**:

   * Handling missing values and outliers
   * Encoding categorical variables
   * Feature scaling using StandardScaler

2. **Determining Optimal Clusters**:

   * Utilizing the Elbow Method to identify the optimal number of clusters by plotting the Within-Cluster Sum of Squares (WCSS) against the number of clusters.

3. **Applying K-Means Clustering**:

   * Implementing the K-Means algorithm with the optimal number of clusters.
   * Assigning cluster labels to each customer.

4. **Visualization**:

   * Creating scatter plots to visualize the clusters.
   * Analyzing the characteristics of each cluster to derive meaningful insights.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

* Python 3.6 or higher
* Jupyter Notebook

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Shreyas-Meru/KMeans-Clustering-on-customer-segmentation.git
   ```



2. **Navigate to the project directory**:

   ```bash
   cd KMeans-Clustering-on-customer-segmentation
   ```



3. **Install the required packages**:

    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```



4. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```



5. **Open and run** `Clustering with K-Means.ipynb` to follow the analysis.

## 📈 Results

After applying K-Means clustering, customers are segmented into distinct groups based on their annual income and spending scores. 

* **Cluster 1**: High income, high spending score – Potential loyal customers.
* **Cluster 2**: Low income, high spending score – Budget-conscious yet active shoppers.
* **Cluster 3**: High income, low spending score – Potential targets for marketing campaigns.
* **Cluster 4**: Low income, low spending score – Less engaged customer segment.

Visualizations in the notebook provide a clear depiction of these clusters, aiding in strategic decision-making.

## 📚 References

* [Scikit-learn Documentation on K-Means Clustering](https://scikit-learn.org/stable/modules/clustering.html#k-means)
* [Mall Customer Segmentation Data – Kaggle Dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
