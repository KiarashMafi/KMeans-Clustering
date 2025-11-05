# Mall Customer Segmentation using K-Means Clustering

## Overview
This project applies **K-Means Clustering** to segment mall customers based on demographic and spending data. The goal is to identify distinct groups of customers to support data-driven marketing strategies.

## Files
- **KmeansClustering.ipynb** – Jupyter Notebook containing data analysis, visualization, and model implementation.
- **Mall_Customers.csv** – Dataset of mall customers including features such as gender, age, annual income, and spending score.

## Dataset Description
The dataset contains the following columns:
- `CustomerID`: Unique ID for each customer  
- `Gender`: Male or Female  
- `Age`: Age of the customer  
- `Annual Income (k$)`: Annual income in thousand dollars  
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature  

## Project Steps
1. **Data Loading & Exploration**  
   Load and inspect the dataset, check for missing values, and analyze distributions.

2. **Feature Selection**  
   Select relevant features for clustering (commonly Annual Income and Spending Score).

3. **Elbow Method**  
   Determine the optimal number of clusters by plotting the Within-Cluster Sum of Squares (WCSS).

4. **Model Training**  
   Apply the K-Means algorithm with the chosen number of clusters.

5. **Visualization**  
   Plot the customer clusters to interpret segments visually.

## Results
- Customers are grouped into clusters based on income and spending habits.
- Each cluster represents a unique customer type (e.g., high spenders, low spenders, average spenders).

## Dependencies
- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

Install dependencies with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run
1. Open the notebook `KmeansClustering.ipynb` in Jupyter.
2. Ensure the dataset `Mall_Customers.csv` is in the same directory.
3. Run all cells sequentially to reproduce the results.

## Author
Developed by **Kiarash**, focusing on simplicity, clarity, and clean implementation.
