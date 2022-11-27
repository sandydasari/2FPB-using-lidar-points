# Course Project

## Project Title: 2D Building Footprint Extraction using LiDAR


This project was done as part of course at IIT Bombay.

Abstract: In this project, aerial LiDAR points are used to extract 2D footprints and are visualized on the base map. Various Machine Learning algorithms were experimented to extract the building points from the raw data. Different clustering algorithms like K-Means and DBSCAN were explored to convert LiDAR points into optimal building clusters. Algorithms like Convex Hull and Alpha Shape are explored to extract the footprints by converting the clusters into polygons.

### Dataset Used: [Netherland Lidar Data](Dataset/C_37EZ1_7415_sample.las)

### Libraries Used:

1. Open Street Maps
2. GeoPandas
3. Pandas
4. Numpy
5. Torch
6. Geemap (map view)
7. Laspy (lidar points)
8. Rasterio
9. Kepler GL (interactive map)
10. Sklearn (SVC, GNB, RF, DT)
11. Keras
12. KMeans, DBSCAN
13. ConvexHull,Alpha Shape
14. torch
15. keplergl


### Table of Contents:

#### 1. Implementation of various ML algorithms :
	
	Code: CS_725_ML_classification.ipynb 
	
	Dataset location : Dataset/classification.csv
	
#### 2. Implementation of GAN :
	
	Code: CS_725_GAN.ipynb 

	Dataset location : Dataset/GAN_input.csv

#### 3. Implementation of K-Means and Convex Hull  :
	
	Code: CS_725_Experimentation_using_Kmeans,_Convex_Hull.ipynb 
	
	Dataset location : Dataset/lidar_points.csv

#### 4. Final Footprint Extracation Model :
	The below code contains the final model:
	- LiDAR point classification using ANN
	- Clustering buildings using DBSCAN
	- Footprint extraction using Alpha Shape
	
	Code: CS_725_Lidar_Project.ipynb

	Dataset location : Dataset/C_37EZ1_7415_sample.las
	
___Run the file [CS_725_Lidar_Project.ipynb](CS_725_Lidar_Project.ipynb) to view the final model.___

