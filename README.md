# Deep-features-for-Image-Retrieval

This is a solution to the programming assignment on Coursera under 'Machine Learning Specialisation' for 'Machine Learning : A Case Study Approach'.

In this project we perform following operations:

1) Computing summary statistics of the data.

2)  Creating category-specific image retrieval models.

3)  Computing nearest neighbors accuracy using SFrame operations.

We create a k-nearest neighbors classifier, where we use the label of neighboring points to predict the label of a test point.A nearest neighbor classifier predicts the label of a point as the most common label of its nearest neighbors.Here, we will measure the accuracy of a 1-nearest-neighbor classifier, i.e., predict the output as the label of the nearest neighbor in the training data.
For doing this we will create an SFrame with the distances from ‘dog’ test examples to the respective nearest neighbors in each class in the training data and then compute the number of correct predictions using 1-nearest neighbors for the dog class.

By doing this we build a new image retrieval model and explore their results on different parts of the image dataset
