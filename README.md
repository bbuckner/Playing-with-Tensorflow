# Playing-with-Tensorflow
Deep Neural Network with Tensorflow on the MNIST Benchmark Fashion Dataset.

This is the first coding project I have attempted on my own that was not a problem from a book or online course.
The challenge for me in this project was combining these concepts that i had previously only used seperately: 1) Creating an adjustable layer deep neural network model 2) Loading a dataset from the internet into python and manipulating the data into the shape that the model will accept 3)Using tensorflow, placeholders 4)Training using mini batches 5)Hyperparameter tuning (running model with different values of lambda for L2_Regularization).

Using skills learned from Coursera, I created an adjustable deep neural network model that accepts an array of training and test data representing thousands of 28 X 28 pixel images and classifies them into 1 of 10 categories.

At the end, you can see the results of training the model with different values of the hyperparameter lambda (used in L2 Regularization).  I found that the optimal lamda value for training a deep neural network with 3 32 node hidden layers, a learning rate of .0001 for 1000 epochs with a minibatch size of 500 is around .09 (resulting in the highest test accuracy).

The model takes too long to run on my laptop, so i will not be training it any furthur, the run that you see doubled as a proof of concept to make sure the model did not crash.  If i were to modify it, I would use a cross validation set to tune more of the hyperparameters such as the layer dimensions or the learning rate.  I look forward to building Deep learning models in the future that can work on real world data and make an impact.


