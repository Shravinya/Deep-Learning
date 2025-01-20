# Deep Learning Experiments

This repository contains various deep learning experiments using simple neural networks to solve logic gate problems and a churn prediction task using logistic regression.

## Experiments

### Experiment 1: Single Artificial Neuron (AND Gate)

- **Model:** A single neuron with a Heaviside step activation function.
- **Dataset:** AND gate dataset.
- **Training:** Perceptron learning rule.
- **Results:**
  - Perfect accuracy (1.0) after 10 epochs.
  - No misclassifications (as shown by the confusion matrix).

---

### Experiment 2: Single Layer Perceptron (SLP) for AND Gate

- **Model:** Single Layer Perceptron (SLP) with zero-initialized weights.
- **Dataset:** AND gate dataset.
- **Training:** Perceptron learning rule.
- **Results:**
  - Achieved perfect accuracy (1.0) after 10 epochs.
  - No misclassifications.
  - The epoch-wise error shows convergence to minimal error.

---

### Experiment 3: Single Layer Perceptron (SLP) for OR Gate

- **Model:** Single Layer Perceptron (SLP).
- **Dataset:** OR gate dataset.
- **Training:** Perceptron learning rule.
- **Results:**
  - Achieved perfect accuracy (1.0) after 10 epochs.
  - No misclassifications.

---

### Experiment 4: Multi-Layer Perceptron (MLP) for XOR Gate

- **Model:** Multi-Layer Perceptron (MLP) with ReLU activation for the hidden layer and Sigmoid activation for the output layer.
- **Dataset:** XOR gate dataset.
- **Training:** 5000 epochs with loss decreasing over time.
- **Results:**
  - Predictions match expected XOR gate outputs.
  - The model achieves good performance after training.

---

### Experiment 5: Activation Functions

- **Model:** Logistic Regression for churn prediction.
- **Dataset:** Churn dataset (`churn.csv`).
- **Training:** Dataset is cleaned, and the `tenure` feature is selected for training.
- **Results:** In progress, as the dataset is being loaded and prepared for training.

---


