# minst-digit-recognizer
This project builds a simple neural network from scratch (without using deep learning libraries like TensorFlow or PyTorch) to classify handwritten digits from the MNIST dataset. It uses:

A two-layer neural network: one hidden layer with ReLU activation, and an output layer with softmax activation for multiclass classification (digits 0–9).

Forward propagation to compute predictions and backpropagation to compute gradients and update weights using gradient descent.

Data normalization to improve training performance.

One-hot encoding for the output labels.

Accuracy tracking during training and visualization of how the model improves over time.

The model is trained on a large dataset of handwritten digits and then evaluated on a development set to check how well it generalizes.

File : digit-recognizer pt 2 has an accuracy of 88% 
File : digit-recognizer is a slower version of the above and has some bugs
