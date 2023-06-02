# Deep-Learning---MLP-NN

Implementation of a multi-layer perceptron using purely NumPy and Pytorch routines. The network consists
of a series of linear layers with ReLU activation functions followed by a final linear layer and
softmax activation. As a loss function, I used the common cross-entropy loss for classification tasks.

Part of the success of neural networks is the high efficiency on graphical processing units
(GPUs) through matrix multiplications. Therefore, all of the code uses matrix multiplications
rather than iterating over samples in the batch or weight rows/columns.
