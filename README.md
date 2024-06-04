# Crops Dataset Multi-Class Classification

## Part 1: Crops Classifiers
### 1. Feature Engineering
Transforming Features (BoxCox Transformation and Log Transformation) and Labels
### 2. Cross-Validation
Cross-Validation Function that firstly applys the previously defined Transofrmations and Normalizes the data. Then it performs Cross-Validation for each of the given models and outputs the dictionary with train and test Accuracy and Standard deviation for each model.
### 3. Comparing the models
Plotting the best models' accuracies and Standard Deviations, as well as the Confusion Matrices against each other.

## Part 2: NumPy Implementation of a Neural Network for Crop Classification
### 1. Feature Engineering
The same steps were applied as in the 1st Part.
### 2. Neural Network Function
Raw NumPy implementation of a Neural Network. Accepts ReLU, Leaky ReLU, Softmax, Sigmoid and Tanh as the hidden layer activations. Output layer accepts only Softmax activation. Forward propagation is done with caching, and back propagation uses Adam as the optimizer.
### 3. Evaluating the results
Plotting the accuracy and loss over time, as well as the Confusion Matrix.

