#Neural Networks

Implements a Multilayer Perceptron Neural Network and evaluate its performance in classifying handwritten digits using MNIST dataset.  

#File included in this exercise
1) mnist all.mat: original dataset from MNIST. In this file, there are 10 matrices for testing set and 10
matrices for training set, which corresponding to 10 digits. You will have to split the training data
into training and validation data.

2) nnScript.py: Python script for this programming project. Contains function definitions -
-preprocess(): performs some preprocess tasks, and output the preprocessed train, validation and
test data with their corresponding labels. 
-sigmoid(): compute sigmoid function. The input can be a scalar value, a vector or a matrix. 
-nnObjFunction(): compute the error function of Neural Network. 
-nnPredict(): predicts the label of data given the parameters of Neural Network. 
-initializeWeights(): return the random weights for Neural Network given the number of unit in
the input layer and output layer.