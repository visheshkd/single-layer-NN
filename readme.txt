VISHESH KUMAR DWIVEDI

Objective : Implement a single layer neural network and use different learning rules to train
the network.
Programming Language : Python 3.7
IDE : ANACONDA 3(Spyder)

Methods Implemented :

_initialize_weights - This is where you create the weights for your model (bias is included in
the weights).

initialize_all_weights_to_zeros - This method initializes all weights to zero (bias is
included in the weights).

predict - Given array of inputs this method predicts array of corresponding outputs.

print_weights - This method prints the weight matrix (bias is included in the weights).

train - Given array of inputs, desired outputs as class indexes, and other parameters, this
method adjusts the weights using the appropriate learning rule. Note that this method should
implement batch training.

calculate_percent_error - Given array of inputs and desired outputs as class indexes this
method calculates percent error.

calculate_confusion_matrix - Given array of inputs and desired outputs as class indexes array
this method calculates the confusion matrix