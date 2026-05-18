# MNIST Digit Classifier

A convolutional neural network built in PyTorch that recognizes 
handwritten digits with 97.64% accuracy.

## What I built
A neural network trained on the MNIST dataset - 60,000 handwritten 
digit images. The model learns to recognize digits 0-9 by detecting 
edges and shapes across three layers.

## Model architecture
- Input: 784 pixels (28x28 image flattened)
- Layer 1: 784 to 128 neurons + ReLU
- Layer 2: 128 to 64 neurons + ReLU
- Layer 3: 64 to 10 neurons (one per digit)

## Results
- Training epochs: 5
- Final training loss: 0.0476
- Test accuracy: 97.64%

## What I learned
- How tensors work in PyTorch
- How neural networks learn through gradient descent
- How loss functions measure prediction error
- How the training loop works

## Built with
- Python
- PyTorch
- Google Colab

## Context
Built while reading "Attention is All You Need" (Vaswani et al. 2017) 
as part of teaching myself AI during summer 2026. First year EE student 
at University of Alabama.
