# Deep-Learning
Experiment 1: Single Artificial Neuron (AND Gate)
A single neuron is implemented with a Heaviside step activation function.
The neuron is trained using the Perceptron learning rule on the AND gate dataset.
The model achieves perfect accuracy (1.0) after 10 epochs, and the confusion matrix shows no misclassifications.
Experiment 2: Single Layer Perceptron (SLP) for AND Gate
A Single Layer Perceptron is implemented with zero-initialized weights and trained using the same AND gate dataset.
The model achieves perfect accuracy (1.0) after 10 epochs, and the confusion matrix shows no misclassifications.
The epoch-wise error shows the model converging to a minimal error after several iterations.
Experiment 3: Single Layer Perceptron (SLP) for OR Gate
Similar to Experiment 2 but with the OR gate dataset.
The model again achieves perfect accuracy (1.0) after 10 epochs, with no misclassifications.
Experiment 4: Multi-Layer Perceptron (MLP) for XOR Gate
A Multi-Layer Perceptron (MLP) is implemented using PyTorch for the XOR gate dataset.
The model uses ReLU activation for the hidden layer and Sigmoid activation for the output layer.
The model is trained for 5000 epochs, with the loss decreasing over time.
The predictions match the expected XOR gate outputs, and the model achieves good performance after training.
Experiment 5: Activation Functions
The code snippet appears to involve loading a dataset (churn.csv) for a churn prediction task.
The dataset is cleaned, and the tenure feature is selected for training a logistic regression model.
The experiment is in progress, with the dataset being loaded and prepared for training.
