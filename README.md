## Breast Cancer Prediction using Machine Learning Classification ##

This project utilizes machine learning techniques to predict breast cancer based on various histological features.

Features Used:

1) Clump_thickness
2) Uniformity_Cell_Size
3) Uniformity_Cell_Shape
4) Marginal_Adhesion
5) Single_Epithelial_Cell_Size
6) Bare_Nuclei
7) Bland_Chromatin
8) Normal_Nucleoli
9) Mitoses
Frontend:

A user-friendly interface is built using Streamlit, allowing users to input their data and receive real-time predictions.

Machine Learning Algorithm:

This project implements the K-Nearest Neighbors (KNN) algorithm for classification.

K-Nearest Neighbors (KNN):

KNN leverages the concept of "similarity" to categorize new data points. It assumes that data points close together in feature space are likely to belong to the same class.
KNN is a non-parametric, supervised machine learning algorithm that classifies data points based on the proximity of their neighbors. 

Here's explanation:

1) Training: The model learns by analyzing a dataset with labeled examples .

2) Prediction: When presented with a new data point, KNN identifies the k nearest neighbors in the training set based on their feature similarity.

3) Classification: The majority class among the k neighbors is assigned as the predicted class for the new data point.
