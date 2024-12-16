# K-Nearest Neighbours (K-NN) Classification

## Objective
The objective of this assignment is to implement and evaluate the K-Nearest Neighbours algorithm for classification using the given dataset.

## Dataset
The dataset contains various features to classify the type of animal.

## Tasks
1. **Analyze the data using visualizations**:
   - Use tools like histograms, scatter plots, and pair plots to understand data distribution and relationships.
   
2. **Preprocess the data by handling missing values & outliers, if any**:
   - Check for missing values and handle them accordingly.
   - Identify and handle outliers using techniques like the IQR method.
   
3. **Split the dataset into training and testing sets (80% training, 20% testing)**:
   - Use appropriate methods to split the data into training and testing sets.
   
4. **Implement the K-Nearest Neighbours algorithm using a machine learning library like scikit-learn on the training dataset**:
   - Train the K-NN model using appropriate libraries.
   
5. **Choose an appropriate distance metric and value for K**:
   - Experiment with different values of K (e.g., 3, 5, 7) and distance metrics (e.g., Euclidean, Manhattan).
   
6. **Evaluate the classifier's performance on the testing set using accuracy, precision, recall, and F1-score metrics**:
   - Evaluate the model using appropriate performance metrics.
   
7. **Visualize the decision boundaries of the classifier**:
   - Use visualization techniques to plot the decision boundaries.

## Interview Questions

1. **What are the key hyperparameters in KNN?**
   The key hyperparameters in K-Nearest Neighbours (K-NN) include the number of neighbors \( K \), the distance metric, and the weighting function. The number of neighbors \( K \) determines how many neighboring points will influence the classification of a given data point. The distance metric, such as Euclidean, Manhattan, or Minkowski, dictates how the distance between data points is calculated. The weighting function can be uniform, where all neighbors are equally weighted, or distance-based, where closer neighbors have more influence on the classification. Tuning these hyperparameters is crucial for optimizing the performance of the K-NN algorithm.

2. **What distance metrics can be used in KNN?**
   In K-Nearest Neighbours (K-NN), several distance metrics can be employed to measure the similarity or dissimilarity between data points. The most commonly used metric is the Euclidean distance, which calculates the straight-line distance between two points in space. Another popular metric is the Manhattan distance (also known as L1 distance), which measures the distance between points along the axes at right angles. Minkowski distance is a generalization of both Euclidean and Manhattan distances, where a parameter \( p \) determines the metric: \( p = 1 \) corresponds to Manhattan distance, and \( p = 2 \) corresponds to Euclidean distance. Other metrics like Chebyshev distance, which considers the maximum absolute difference in any dimension, and Hamming distance, particularly useful for categorical data, can also be used depending on the nature of the dataset and the problem at hand. Each metric can significantly affect the performance of the K-NN classifier, so choosing the appropriate one is crucial.
