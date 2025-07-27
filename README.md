# Neural Network for Pattern Recognition

This repository contains a simple feedforward neural network implemented from scratch using NumPy. The network is trained to classify 2D data points generated from four Gaussian distributions. The implementation includes support for multiple training methods and visualizations of the decision boundaries.

---

## Features

- Custom 2D data generator using Gaussian distributions
- Feedforward neural network with one hidden layer
- Three training methods:
  - Standard Backpropagation
  - Backpropagation with Momentum
  - Backpropagation with Adaptive Learning Rate
- Decision boundary visualization
- Accuracy evaluation

---

## File Structure

- `main.ipynb`: Jupyter notebook containing the full implementation, training code, and visualizations.

---

## Data Generation

Data is generated using four 2D Gaussian distributions:
- Two distributions for class **+1**
- Two distributions for class **-1**

Function:
```python
X, y = data_generator(m, s, N, seed=42)
