# ML-Facial-Recognition-and-K-Means-Clustering
Jupyter notebook for detecting faces in images and clustering them into 2 groups based on hue and saturation

##  Aim
This project detects faces in an image, extracts hue and saturation, and clusters the faces using K-Means(k=2). 
A separate template face can be added to visualize which cluster it belongs to. 
The output includes a scatter plot of clustered faces, cluster centroids, and the template face for visual verification.

##  Methodology
1. Face Detection: Using Haar Cascade Classifier in OpenCV to detect faces in the main and template images.
2. Feature Extraction: Calculate hue and saturation for each face
3. Clustering: Applying K-Means(k=2) on the extracted features to group similar features into clusters.
4. Visualization: Plot a scatter plot of hue vs saturation, highlight cluster centroids, and add the template face to check which cluster it belongs to. 

## Key Findings
1. Faces with similar hue and saturation naturally group into clusters
2. K-Means successfully separates the faces

## Conclusions
1. Hue and Saturation are effective features for clustering faces.
2. This method can be used for quick similarity checks or as a first step in more advanced face recognition systems.
