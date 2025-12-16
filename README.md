# Learning Rate in Neural Network Training

## Overview
This project explores the effect of the learning rate hyperparameter on neural network training using the MNIST dataset.  Different learning rates were tested to analyze their impact on convergence, stability, and accuracy.

## Experiment Setup
- Model: Multilayer Perceptron (MLP)
- Optimizer: Adam
- Dataset: MNIST
- Epochs: 15
- Learning Rates: 0.1, 0.001, 0.00001

## Results
| Learning Rate | Test Accuracy |
|--------------|--------------|
| 0.1 | 13.87% |
| 0.001 | 97.75% |
| 0.00001 | 92.66% |

- High learning rates caused unstable training.
- Very small learning rates slowed convergence.
- A moderate learning rate achieved the best performance.

## Conclusion
The learning rate is a critical hyperparameter that directly affects training stability and model performance.
