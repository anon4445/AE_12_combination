# Autoencoder with Different Optimizer-Loss Combinations 

This project demonstrates the implementation of an **Autoencoder** using various **optimizers** and **loss functions** to compress and reconstruct images from the MNIST dataset. The code evaluates performance using different optimizer-loss combinations and visualizes the results.

---

## Overview

An **Autoencoder** is a type of neural network designed to encode input data into a compressed representation and then decode it to reconstruct the original input. This implementation uses the MNIST dataset (handwritten digits) as input.

### Features:
- **Data Preprocessing**: Normalize and flatten the MNIST dataset.
- **Model Design**:
  - Encoder: Compresses input images into a low-dimensional representation.
  - Decoder: Reconstructs input images from the compressed representation.
- **Optimizer-Loss Combinations**: Train the autoencoder using different optimizer and loss function combinations.
- **Visualization**:
  - Training and validation losses for all combinations.
  - Comparison of original, encoded, and reconstructed images.

---

## Requirements

The project requires the following Python libraries:
- `TensorFlow`
- `NumPy`
- `Matplotlib`


