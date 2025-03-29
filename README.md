# K-Means Clustering for Customer Segmentation

This project demonstrates the implementation of a **K-Means Clustering** model to segment customers based on their spending patterns and annual income. The goal is to identify meaningful customer groups for targeted marketing strategies.

## Dataset
The dataset used is **Mall_Customers.csv**, which contains the following features:
- **CustomerID**: Unique identifier for each customer
- **Genre**: Customer's gender
- **Age**: Customer's age
- **Annual Income (k$)**: Annual income in thousands of dollars
- **Spending Score (1-100)**: Score assigned based on spending behavior

## Project Overview
- The project focuses on using **K-Means Clustering** to identify customer groups based on their **Annual Income** and **Spending Score**.
- Optimal clusters are set to **5** for visualization purposes, but this can be adjusted as needed.

## Steps Implemented
1. **Data Preprocessing**:
   - Data loaded and cleaned for analysis.
2. **Feature Selection**:
   - Focused on `Annual Income (k$)` and `Spending Score (1-100)` for clear visual representation.
3. **Model Training**:
   - Implemented **K-Means Clustering** using `sklearn`.
4. **Cluster Visualization**:
   - Visualized the identified clusters using `matplotlib` for improved insights.

## Requirements
- Python 3.x
- Libraries: `pandas`, `matplotlib`, `seaborn`, `sklearn`

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```
3. Run the notebook:
   ```bash
   jupyter notebook kmeans_cluster.ipynb
   ```

## Results
The project successfully demonstrates:
- Effective customer segmentation using K-Means.
- Visual clusters representing customer behavior for marketing insights.

