# Predicting_Bikesharing_patterns
First Neural Network

Developed as a project for Udacity 'Deep Learning' Nanodegree. In this project, I built a neural network for predicting daily bike rental ridership..

## Results

The project meets all the specifications, which are as follows:

> Code Functionality
* All the code in the notebook runs in Python 3 without failing, and all unit tests pass.
* The sigmoid activation function is implemented correctly

> Forward Pass
* The forward pass is correctly implemented for the network's training.
* The run method correctly produces the desired regression output for the neural network.

> Backward Pass
* The network correctly implements the backward pass for each batch, correctly updating the weight change.
* Updates to both the input-to-hidden and hidden-to-output weights are implemented correctly.

> Hyperparameters
* The number of epochs is chosen such the network is trained well enough to accurately make predictions but is not overfitting to the training data.
* The number of hidden units is chosen such that the network is able to accurately predict the number of bike riders, is able to generalize, and is not overfitting.
* The learning rate is chosen such that the network successfully converges, but is still time efficient.
* The number of output nodes is properly selected to solve the desired problem.
* The training loss is below 0.09 and the validation loss is below 0.18.

## Conclusion

The predictions given by the model are quite accurate. However,the model overestimates bike ridership in December because it hasn't had sufficient holiday season training examples.
