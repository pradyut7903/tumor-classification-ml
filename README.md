# tumor-classification-ml

This project aims to classify tumors as either benign or malignant using three different classification algorithms: Perceptron, Fisher's Discriminant, and Logistic Regression. The goal is to provide accurate predictions for tumor classification based on the provided dataset.

## Dataset
The dataset used in this project consists of various features extracted from tumor samples, such as size, shape, and texture. Each sample is labeled as either benign or malignant. The dataset is preprocessed and divided into training and testing sets to evaluate the performance of the classification algorithms.

## Algorithms
Perceptron: The Perceptron algorithm is a linear classifier that learns a decision boundary by iteratively updating the weights based on misclassified samples. It aims to find a hyperplane that separates the two classes.

Fisher's Discriminant: Fisher's Discriminant, also known as Linear Discriminant Analysis (LDA), seeks to find a linear combination of features that maximizes the ratio of between-class variance to within-class variance. It aims to reduce dimensionality while preserving class separability.

Logistic Regression: Logistic Regression is a probabilistic classification algorithm that models the relationship between the features and the probability of a tumor being benign or malignant. It estimates the parameters using maximum likelihood estimation and applies a sigmoid function to predict class probabilities.

## Results
After running the main script, the classification results will be displayed, including accuracy, precision, recall, and F1-score for each algorithm. These metrics will help evaluate the performance of the classifiers and provide insights into their effectiveness for tumor classification.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Your feedback is highly appreciated.
