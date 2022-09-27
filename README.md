# Image Classification: Logistic Regression on MNIST dataset using k-Fold Cross Validation and Pytorch


In this tutorial, we explain a simple real world example of logistic regression - image classification using k-Fold Cross Validation and Pytorch. Logistic Regression network is very simple and basic. It is difficult to get a trained model using Logistic regression network which gives high accuracy and less loss. For that reason we use k-Fold Cross Validation as it improves the efficiency and accuracy of the trained model.

k-Fold Cross Validation randomly picks the datapoints in each fold. So in each fold there are different datapoints on which training is done, thus improving the accuracy of the trained model.

For this we use MNIST Handwritten Digits Database for training, validating and testing our model.

MNIST dataset consists of images of 28 X 28 pixels that represents the handwritten numbers from 0 to 9. It also contains the output labels that the image actually represents.

Here, we use Stochastic Gradient Descent (SGD) for minimizing the cross entropy loss function.