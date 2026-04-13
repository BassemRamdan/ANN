# Artificial Neural Networks (ANN) 🧠

This folder contains introductory scripts and Jupyter Notebooks demonstrating foundational concepts of Artificial Neural Networks from scratch.

## Project Structure 📁
- **`sec1.py`:** An introductory Python script for neural network implementations.
- **`sec3.ipynb`:** Jupyter Notebook detailing core ANN mathematical components:
  - Error Calculations: Mean Squared Error (MSE)
  - Activation Functions: Sigmoid, ReLU, Perceptron step functions.
  - Forward Propagation step calculations.
  - Derivative calculations for backpropagation.
- **`sec4.ipynb`:** Additional Jupyter Notebook exploring further concepts and implementations in basic neural network theory.

## Key Concepts Covered 📚
- **Activation Functions:** Understanding how nonlinearities are applied to linear combinations of inputs.
- **Loss Functions:** Setting up `MeanSquareError` to evaluate model performance numerically.
- **Matrix Operations:** Implementing weights and biases using NumPy linear algebra functions (`X @ W + b`).
- **Derivatives:** Implementation of Sigmoid derivatives to understand gradients.

## How to Follow Along 💻
1. Clone this repository:
   ```bash
   git clone https://github.com/BassemRamdan/ANN.git
   ```
2. Navigate to the downloaded directory:
   ```bash
   cd ANN
   ```
3. Open up your Jupyter environment:
   ```bash
   jupyter notebook
   ```
4. Select `sec3.ipynb` or `sec4.ipynb` and step through the cells!

## Requirements 🛠️
You just need python and basic data science tools:
- `python` 3.x
- `numpy`
