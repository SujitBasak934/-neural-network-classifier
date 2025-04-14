# Neural Network Classifier for Letters A, B, and C

This project implements a simple feedforward neural network from scratch using NumPy to recognize binary image patterns of the letters A, B, and C.

## 🔍 Project Overview

- **Letters**: A, B, C represented as 5x6 binary pixel images (flattened to 30 features).
- **Model**: A neural network with:
  - Input layer: 30 neurons
  - Hidden layer: 16 neurons, Sigmoid activation
  - Output layer: 3 neurons, Softmax activation
- **Training**: Custom backpropagation with cross-entropy loss
- **Evaluation**: Prediction accuracy and loss visualization over epochs

## 🧠 Key Components

- `sigmoid`, `sigmoid_derivative`: Activation and its derivative
- `softmax`: For output probabilities
- `cross_entropy`: Loss function
- `predict`: Function to classify new inputs

## 📊 Training and Testing

- Model is trained on synthetic binary data for A, B, and C
- Epoch-wise training with accuracy and loss printout
- Visual prediction of letter classifications using `matplotlib`

## 📁 Files Included

- `Neural_Network_Letter_Recognition.ipynb`: Main Jupyter Notebook with code
- `README.md`: Project description and instructions

## 🛠️ Tools Used

- Python 3
- NumPy
- Matplotlib
- Jupyter Notebook

## 🚀 Run It Yourself

1. Open the Jupyter Notebook.
2. Run all cells in order.
3. Observe the printed predictions, loss graph, and visualizations.


