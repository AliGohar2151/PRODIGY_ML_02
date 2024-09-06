# 🎯 Customer Segmentation using K-Means Clustering

This project demonstrates customer segmentation using K-Means clustering. The dataset used contains information about customers' annual income and spending scores. The goal is to group customers into distinct clusters based on these features to better understand customer behavior and create targeted marketing strategies.

## 📑 Table of Contents

- [📖 Introduction](#introduction)
- [📊 Dataset](#dataset)
- [📈 Elbow Method](#elbow-method)
- [📉 Clustering Results](#clustering-results)
- [⚙️ Installation](#installation)
- [🚀 Usage](#usage)

## 📖 Introduction

Customer segmentation is a technique to divide customers into distinct groups based on specific attributes, like their annual income and spending behavior. In this project, we use the K-Means clustering algorithm to group customers with similar characteristics together. This helps businesses to identify different types of customers and to create strategies tailored to each group's needs.

## 📊 Dataset

The dataset used for this project is `Mall_Customers.csv`. It includes the following features:

- **CustomerID**: A unique identifier for each customer.
- **Gender**: The gender of the customer.
- **Age**: The age of the customer.
- **Annual Income (k$)**: The annual income of the customer in thousand dollars.
- **Spending Score (1-100)**: A score assigned by the mall based on customer behavior and spending nature.

## 📈 Elbow Method

To determine the optimal number of clusters, the Elbow Method is used. It involves plotting the Within-Cluster Sum of Squares (WCSS) against the number of clusters and selecting the "elbow point" where the rate of decrease sharply slows down. 

## 📉 Clustering Results

Using the optimal number of clusters determined by the Elbow Method, the K-Means algorithm is applied to the dataset. The resulting clusters are visualized in a scatter plot, with different colors representing different clusters.

## ⚙️ Installation

To run this project locally, you need to have Python installed along with the required libraries.

1. Clone the repository:

    ```bash
    https://github.com/AliGohar2151/PRODIGY_ML_02.git
    cd PRODIGY_ML_02
    ```

2. Install the required dependencies:

    ```bash
    pip install pandas matplotlib scikit-learn
    ```

3. Run the script:

    ```bash
    python kmeans_clustering.py
    ```

## 🚀 Usage

- The script will output an Elbow plot to help you determine the optimal number of clusters.
- After determining the optimal number, the K-Means algorithm will group the customers into clusters.
- A scatter plot will be displayed, visualizing the clusters and their centroids.
