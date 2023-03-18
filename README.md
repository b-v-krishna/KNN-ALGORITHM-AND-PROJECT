# KNN ALGORITHM FROM SCRATCH AND A PROJECT USING KNN CLASSIFICATION

<H2>THIS REPOSITORY CONTAINS TWO PROJECTS</H3>
<h3>1.Introduction<h3>
This first file contains a Python implementation of a K-Nearest Neighbors (KNN) classifier to predict whether a person has diabetes or not, based on certain medical features. KNN is a supervised machine learning algorithm that can be used for classification or regression tasks.

<h3>Dataset<h3>
The dataset used in this project is the Pima Indians Diabetes Database from Kaggle, which contains the medical record data of Pima Indian women collected over a period of time. The dataset consists of 768 observations and 8 input features such as age, BMI, blood pressure, etc. The target variable is a binary variable indicating whether the person has diabetes or not.

<h3>Implementation</h3>
The KNN algorithm has been implemented as a Python class KNN_Classifier(), which takes the distance metric as input and has three methods:
<ol>
<li>get_distance_metric(): Computes the distance between a training data point and a test data point using either Euclidean or Manhattan distance metric.</li>
<li> nearest_neighbors(): Finds the k nearest neighbors of a test data point in the training dataset using the distance metric.</li>
<li>predict(): Predicts the class of the new data point based on the class labels of its k nearest neighbors.</li>
</ol>
<h3>Model Performance</h3>
The model accuracy is 74%. It means that 74 observations out of 100 observations are it is predicting correct. 

<h3>2.IRIS FLOWER CLASSIFICATION USING KNN</h3>
<h3>Introduction</h3>
This project involves building a KNN model to classify the Iris flower species based on four input features: sepal length, sepal width, petal length, and petal width. The dataset contains 150 rows and 5 columns.

<h3>Dataset Description</h3>
The dataset contains information about three species of Iris flowers: Iris setosa, Iris versicolor, and Iris virginica. There are 50 samples for each species. Each sample has four features: sepal length, sepal width, petal length, and petal width. The dataset is available in the iris.csv file.

<h3>Data Visualization</h3>
The counts of each species in the dataset were visualized using a countplot from the Seaborn library.
<h3>Model Performance</h3>
The KNN model was trained on 60% of the data and tested on the remaining 40%.The model achieved an accuracy of 98% on the test set.


