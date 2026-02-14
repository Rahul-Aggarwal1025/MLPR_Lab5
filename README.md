# MLPR_Lab5

# Face Detection and HSV-Based Clustering using K-Means

This project explores a computer vision pipeline that combines face detection and unsupervised learning. The objective was to detect faces in a group image, extract meaningful color features from each detected face, and cluster them using K Means based on similarity in HSV color space. 

Faces were detected using OpenCV’s Haar Cascade classifier after converting images to grayscale. For each detected face, the image was converted to HSV color space and the mean hue and saturation values were computed. These two values formed a 2D feature vector representing each face. K Means clustering with k=2 was applied to group faces by minimizing Euclidean distance between data points and cluster centroids.

The results show that faces can be grouped based on color similarity, and a new template face can be classified by predicting its nearest cluster. While this method does not perform true face recognition, it effectively demonstrates distance based clustering and feature representation in image processing. The approach is  useful for understanding how classical computer vision techniques integrate with machine learning algorithms.


<img width="956" height="640" alt="group_photo" src="https://github.com/user-attachments/assets/a8aef8d1-d912-48aa-8e3b-954cc7fdfad7" />
<img width="299" height="298" alt="final_tharror" src="https://github.com/user-attachments/assets/7c099650-65e7-44c0-a79b-16379bf9c609" />
