# MNIST Handwritten Digit Classification using Neural Networks

This project implements a deep neural network using **TensorFlow/Keras** to classify handwritten digits from the **MNIST** dataset with high accuracy.

---

## Overview

- **Dataset**: MNIST (28x28 grayscale images of digits 0–9)
- **Model Architecture**:
  - Input Layer: 784 neurons (flattened 28x28 image)
  - Hidden Layer 1: 128 neurons, ReLU activation
  - Hidden Layer 2: 128 neurons, ReLU activation
  - Output Layer: 10 neurons, Softmax activation
- **Optimizer**: Adam
- **Learning Rate**: 0.001
- **Loss Function**: Sparse Categorical Crossentropy
- **Epochs**: 10
- **Framework**: TensorFlow 2.x / Keras

---

## Final Results

After training for 10 epochs:

-  **Training Accuracy**: 99.41%
-  **Training Loss**: 0.0184
-  **Validation Accuracy**: 97.38%
-  **Validation Loss**: 0.1540
-  **Test Accuracy**: 96.73%
-  **Test Loss**: 0.1823

---

### 🔧 Requirements

- Python ≥ 3.8
- TensorFlow ≥ 2.8
- NumPy
- Matplotlib (optional, for visualization)

Install dependencies:

```bash
pip install tensorflow numpy matplotlib
