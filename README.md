Anomaly Detection with KMeans
This project shows a simple example of anomaly detection using synthetic data generated with make_blobs.
KMeans clustering is used to group the data and detect outliers based on their distance from cluster centers.
🔹 Features
Generate synthetic data with sklearn.datasets.make_blobs
Apply KMeans for unsupervised anomaly detection
Visualize clusters and anomalies using Matplotlib and Seaborn
🔹 Workflow
Generate dataset
Fit KMeans model
Calculate distances to centroids
Mark far points as anomalies
Visualize results
🔹 Requirements
Python 3.x
scikit-learn
matplotlib
seaborn
numpy
🔹 Visualizations
The script includes plots showing:
Cluster assignments
Detected anomaly points highlighted in the graph
