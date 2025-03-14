# Linear Classification Notebook
This notebook provides a detailed exploration of linear classification, which is a starting point of deep learning application in image classification problem. 

---

## Overview

Linear classification stands as a fundamental pillar in the edifice of machine learning. In this project, we:

- **Delve into Theory:** Instead of building a custom neural network module with autograd for a softmax linear classifier, this notebook adopts a straightforward approach to illustrate the core concepts of linear classification.
- **Data Exploration & Preprocessing:** Understand the cifar-10 image size and image precrossing.
- **Model Implementation:** Use Python to construct, train, and evaluate linear classifiers using libraries like PyTorch.
- **Visualization & Analysis:** Visualize decision boundaries and performance metrics through intuitive plots and graphs.
- **Validation:** Cross-Validation is applied to select proper hyperparameter for better generalization.

---

## Getting Started

### Requirements

- **Python 3.8+** (recommended)

- **Standard Library Modules:**
  - `math`
  - `time`
  - `random`

- **External Libraries:**
  - **PyTorch:** for tensor operations and neural network functionalities.
  - **Torchvision:** for accessing datasets like CIFAR10.
  - **Matplotlib:** for data visualization.

Install the external libraries using pip:

```bash
pip install torch torchvision matplotlib


