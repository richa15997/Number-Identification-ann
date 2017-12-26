# Number-Identification-ann

This project focuses on identifying numbers using Artificial Neural Network implemented in Octave,using 2 layers of the Neural Network. Both the layers have sigmoid activation function.

# Dataset

The dataset contains 5000 images of size 20x20 pixels. The data contains handwritten numbers from 0-9, which is to identified by the user. 

# Steps
To initialize the functions first we visualize our data and load the weights for theta1 and theta2. 
Perform forward propagation and compute the cost. 
Compute the cost using L2 regularization 
Perform gradient checking to ensure the cost is accurately computed.
Back-Propagtion is done to reinitialize the weights with 50 iterations.

To train the original model we randomly initialize weights of theta. 
Compute cost using L2 regularization with lambda=3.
