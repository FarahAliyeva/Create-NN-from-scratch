# Create-NN-from-scratch
Heart Disease Risk Prediction using a Multi-Layer Perceptron (MLP) with 2 hidden layers (6 and 4 units) built entirely from scratch.


# Heart Disease Prediction with MLP from Scratch

This repository contains a Multi-Layer Perceptron (MLP) neural network built entirely from scratch (using only Python and NumPy) to predict heart disease risk based on the Cleveland Heart Disease dataset.



---

## Project Architecture 

- **Input Layer : 13 Features 
- **Hidden Layer : 6 Neurons(ReLU)
- **Hidden Layer 2 : 4 Neurons (ReLU)
- **Output Layer : 1 Neuron (Sigmoid)
- **Optimization:** Mini-batch Gradient Descent (Batch Size: 32, Learning Rate: 0.1)

##  Performance & Results 

- **Initial Loss:** ~0.6928 (Epoch 1)
- **Final Loss:** ~0.3384 (Epoch 100)
- **Final Training Accuracy:** **84.82%**
- The model shows stable convergence with Binary Cross-Entropy Loss steadily decreasing across 100 epochs.

