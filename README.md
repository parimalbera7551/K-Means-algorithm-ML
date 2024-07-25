# K-Means Clustering on Multi-Band Images
  # Overview
  This project demonstrates the application of K-means clustering on multi-band images. The images used in this project are 512x512 pixel grayscale images, and K-means clustering is applied to group the pixels into clusters based on their intensities.
  # Objective
  The main objective is to use K-means clustering to segment multi-band images into different clusters. This helps in understanding how K-means clustering groups similar pixel intensities and provides insights into the image's structure.
  # Implementation Details
  # Data Preparation
  # Image Loading:

Images are loaded from .gif files (band1.gif, band2.gif, band3.gif, band4.gif).
Each image is resized to 512x512 pixels and converted to grayscale.
   # Image Flattening:

Each image is flattened into a 1D array.
Flattened images are concatenated to form a combined dataset.
 # K-Means Clustering
  # Initialization:

Randomly initialize K centroids from the data.
  # Clustering Process:

Assign each data point to the nearest centroid.
Update centroids by calculating the mean of data points assigned to each centroid.
Iterate the process until convergence or a maximum number of iterations is reached.
  # Clustering Execution:

Perform K-means clustering for various values of K (2, 3, 4, 5, 6).
# Visualization
  # Cluster Labels:
The cluster labels are reshaped to match the original image dimensions.
Visualize the clustered images for each K value.
# Results
  # Cluster Labels:
The shape of cluster labels for each K value is displayed.
  # Cluster Visualization:
Random images from each clustering result are visualized using matplotlib.
 # Files
band1.gif, band2.gif, band3.gif, band4.gif: Image files used for clustering.
k_means_clustering.py: Python script implementing the K-means clustering and visualization.
 # Dependencies
numpy
PIL (Pillow)
matplotlib
  
