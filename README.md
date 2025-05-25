# Quantum Support Vector Machine (QSVM) from Scratch

This repository contains a Jupyter Notebook that implements a **Quantum Support Vector Machine (QSVM)** from scratch, providing a step-by-step exploration of the algorithm and its quantum adaptation.

## Overview

Support Vector Machines (SVM) are supervised learning algorithms used primarily for binary classification tasks. The goal of an SVM is to find the optimal hyperplane that separates two classes of data with the maximum margin. This notebook extends the classical SVM approach into the quantum domain, offering insights into how quantum computing can enhance machine learning models.

## Objectives

- **Visualize the SVM concept:** Demonstrate the geometric intuition behind SVMs by drawing the optimal separating line ("widest street") between two classes of data.
- **Implement a basic SVM:** Show how to construct and solve the SVM optimization problem.
- **Introduce quantum concepts:** Explore how quantum circuits and quantum kernels can be used to map classical data into higher-dimensional spaces for improved classification.
- **Build a QSVM from scratch:** Step through the development of a quantum-enhanced SVM, including data encoding, kernel computation, and classification.

## Features

- **Intuitive explanations:** The notebook includes markdown cells that explain key concepts, such as the SVM objective, margin maximization, and the role of quantum kernels.
- **Visualizations:** Illustrative plots help visualize the separation of classes and the decision boundaries.
- **Quantum kernel implementation:** Demonstrates how to construct and use quantum kernels for non-linear classification tasks.
- **Step-by-step code:** Each section builds on the previous one, making it easy to follow the logic and experiment with modifications.

## Requirements

- Python 3.x
- Jupyter Notebook
- Standard scientific libraries: `numpy`, `matplotlib`
- (Optional) Quantum computing libraries such as `qiskit` or `pennylane` for quantum kernel implementation

## Getting Started

1. Clone or download this repository.
2. Install the required Python packages.
3. Open the notebook `MyQSVMfromScratch.ipynb` in Jupyter.
4. Run the cells sequentially to follow the explanations and results.

## Example

The notebook starts by illustrating the classical SVM approach:

![SVM Visualization](attachment:2bfa4f81-9dd3-4bf5-b885-d32b3e855158.png)

It then proceeds to implement the quantum kernel and applies it to a sample classification problem.

## License

This project is provided for educational and research purposes.

## Acknowledgements

- Inspired by foundational work in quantum machine learning and SVMs.
- Visualization and conceptual explanations based on standard SVM literature.

---
*For questions or suggestions, please open an issue or contact the author.*
