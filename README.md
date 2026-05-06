# Handwritten Digit Recognition (MNIST)

## Problem Description
Building a Neural Network (MLP) to recognize handwritten digits (0-9)
using the MNIST dataset.

## Dataset
- Source: Built-in Keras dataset
- Training samples: 60,000 images
- Testing samples: 10,000 images
- Image size: 28×28 pixels

## Results Comparison

| Experiment | Activation | Neurons | Test Accuracy |
|------------|------------|---------|---------------|
| Exp 1      | ReLU       | 128→64  | 97.59%        |
| Exp 2      | Sigmoid    | 128→64  | 97.17%        |
| Exp 3      | ReLU       | 256→128 | 97.92%        |

## Best Result: 97.92% (Experiment 3)

## How to Run
1. Open the notebook in Google Colab
2. Run all cells in order (Runtime → Run All)
