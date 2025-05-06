# Task 8: Clustering with K-Means

## Objective
This project demonstrates the use of **K-Means clustering**, an unsupervised machine learning algorithm, to identify patterns and segment data. We apply clustering techniques to the **Mall Customer Segmentation Dataset** to uncover customer groups based on their spending habits and demographics.

## Tools and Libraries Used
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn (optional for enhanced visualization)

## Dataset
**Mall Customer Segmentation Dataset**  
You can download the dataset from [this link](#) *(Update this with the actual dataset URL)*.  
The dataset contains customer data with features like:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

## Project Workflow

### 1. Load and Visualize the Dataset
- Import the dataset using Pandas.
- Perform initial exploration to understand the structure and contents.
- (Optional) Apply **PCA** for dimensionality reduction to 2D for visualization.

### 2. Fit K-Means and Assign Cluster Labels
- Fit K-Means on relevant features (e.g., Income and Spending Score).
- Assign and store the cluster labels for each data point.

### 3. Use the Elbow Method to Find Optimal K
- Plot the **Within-Cluster Sum of Squares (WCSS)** for various values of K.
- Use the Elbow method to visually determine the optimal number of clusters.

### 4. Visualize Clusters with Color-Coding
- Use Matplotlib (and optionally Seaborn) to plot the clusters.
- Assign different colors to each cluster to interpret segments visually.

### 5. Evaluate Clustering using Silhouette Score
- Calculate the **Silhouette Score** to evaluate the quality of clustering.
- Use the score to compare the performance of different K values.

## Results
- Effective clustering of customers into meaningful segments.
- Visual analysis and Silhouette Scores provide insight into optimal grouping.

## How to Run
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/kmeans-customer-segmentation.git
    cd kmeans-customer-segmentation
    ```
2. Install required libraries:
    ```bash
    pip install pandas matplotlib scikit-learn seaborn
    ```
3. Run the notebook or script:
    ```bash
    jupyter notebook kmeans_clustering.ipynb
    ```
