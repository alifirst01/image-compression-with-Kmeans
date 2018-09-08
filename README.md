# image-compression-with-Kmeans
K means clustering algorithm for imagcompression 

### K Means
The K-means algorithm is a method to automatically cluster similar data examples together. K-means start by randomly picking elements from the data as center points for a number of clusters. It then iteratively compute distance between data points and their clusters and assign data points to their closest center thus minimizing distance among elements inside the cluster and finally recompute the centroids. This process repeats until distinct n clusters are formed.

### Image Compression
24-bit color representation of an image with each pixel is represented as three 8-bit unsigned integers (ranging from 0 to 255) that specify the red, green and blue intensity values.  
  
The goal is to use K-means algorithm to select the 16 colors that will be used to represent the compressed image.  
  
The centriods computed by the Kmeans are used as the colors that will be used to represent each pixel in the image reducing for 24 bit color to 16 bit color.
![image](img/compressed.png)
