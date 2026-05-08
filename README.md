# Deep Learning with PyTorch

My journey in learning deep learning with PyTorch. This repository contains notebooks that guide you through fundamentales of building neural networks from scratch.

## Notebooks

### Notebook 1: PyTorch Fundamentals
- **File**: [Learn_pytorch.ipynb](Learn_pytorch.ipynb)
- **Colab**: [Open in Google Colab](https://colab.research.google.com/drive/1TKiwWCmVgELbgycPN3vCEuli1V1smNzt?usp=sharing)
- **Topics covered**:
  - Tensor operations and manipulations
  - Building basic neural network layers
  - Forward and backward pass
  - Loss functions and optimization
  - Training loop fundamentals

### Notebook 2: 2-Layer MLP for XOR
- **File**: [2_Layer_MLP_That_Learns_XOR.ipynb](2_Layer_MLP_That_Learns_XOR.ipynb)
- **Colab**: [Open in Google Colab](https://colab.research.google.com/drive/1T4ek77OZuiyIak63tJv1NMPTOywjSuv9?usp=sharing)
- **Topics covered**:
  - Multi-Layer Perceptron (MLP) architecture
  - Implementing XOR logic (a non-linearly separable problem)
  - Activation functions
  - Gradient descent training
  - Model evaluation

## What is XOR?

The XOR (exclusive OR) problem is a classic toy problem in neural networks:

| Input A | Input B | Output |
|--------|--------|--------|
| 0      | 0      | 0      |
| 0      | 1      | 1      |
| 1      | 0      | 1      |
| 1      | 1      | 0      |

Unlike AND and OR gates, XOR is not linearly separable, which means a single perceptron cannot solve it. This requires a multi-layer network with non-linear activation functions.

## Learning Path

1. Start with **Learn_pytorch.ipynb** to understand PyTorch basics
2. Progress to **2_Layer_MLP_That_Learns_XOR** to see how deeper networks solve complex problems

## Requirements

- Python 3.x
- PyTorch
- NumPy

## Quick Start (Local)

```bash
# Clone the repository
git clone https://github.com/yourusername/deeplearning_pytorch.git
cd deeplearning_pytorch

# Run notebooks locally with Jupyter
jupyter notebook
```

## Quick Start (Colab)

Click the Colab links above to open notebooks directly in Google Colab.

## License

MIT