# Anomaly Detection with KMeans

This project demonstrates a simple example of anomaly detection using synthetic data generated with `make_blobs`.

KMeans clustering is used to group the data and detect outliers based on their distance from cluster centers.

## Features

- Generate synthetic data with `sklearn.datasets.make_blobs`
- Apply KMeans for unsupervised anomaly detection
- Visualize clusters and anomalies using Matplotlib and Seaborn

## Workflow

1. Generate dataset  
2. Fit KMeans model  
3. Calculate distances to centroids  
4. Mark distant points as anomalies  
5. Visualize the results

## Requirements

- Python 3.x  
- scikit-learn  
- matplotlib  
- seaborn  
- numpy  

## Visualizations

The project includes plots showing clusters and detected anomaly points.
