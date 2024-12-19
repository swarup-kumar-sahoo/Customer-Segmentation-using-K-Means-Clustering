# Customer Segmentation using K-Means Clustering

This project applies K-Means Clustering to perform customer segmentation based on annual income and spending score (1-100). The objective is to group customers into five distinct categories to better understand their behaviors and characteristics. 

## Table of Contents
1. [Objective](#objective)
2. [Dataset](#dataset)
3. [Approach](#approach)
4. [Technologies Used](#technologies-used)
5. [Results](#results)
6. [How to Run](#how-to-run)

---

## Objective
The primary goal is to segment customers into **five distinct groups** based on their:
- **Annual Income**
- **Spending Score (1-100)**

This segmentation will assist businesses in targeting and tailoring their strategies for different customer groups.

---

## Dataset
- **Total Customers**: 200
- **Attributes Used**:
  - Annual Income
  - Spending Score

The dataset was preprocessed and analyzed to prepare it for clustering.

---

## Approach
1. **Data Processing**:
   - Imported the dataset into Google Colab.
   - Preprocessed and analyzed data to handle any anomalies.

2. **Finding the Optimal Number of Clusters**:
   - Used the **Elbow Method** to identify the optimum number of clusters.
![elbow point graph](https://github.com/user-attachments/assets/948b72a3-b5f8-4fee-a12e-6835ddd4ea3c)
   - Plotted the Within-Cluster Sum of Squares (WCSS) against the number of clusters to find the "elbow point."

3. **K-Means Clustering**:
   - Applied the K-Means algorithm with the optimal number of clusters (5).
   - Identified cluster centroids and grouped customers accordingly.

4. **Visualization**:
   - Plotted clusters along with centroids to illustrate customer groups.
![coustmer groups](https://github.com/user-attachments/assets/f4acf4d9-2618-4951-acb6-af0b0c890e2f)


---

## Technologies Used
- **Google Colab**: Environment for executing Python code.
- **Python Libraries**:
  - `numpy` for scientific computing.
  - `pandas` for data manipulation.
  - `matplotlib` for visualization.
  - `seaborn` for creating a statistical graphs.
  - `sklearn` for implementing K-Means Clustering.

---

## Results
- Customers were successfully segmented into **five groups** based on their annual income and spending score.
- The cluster centroids were visualized, highlighting the key characteristics of each group.

---

This project provides a foundation for understanding customer segmentation and its practical application in business scenarios.
