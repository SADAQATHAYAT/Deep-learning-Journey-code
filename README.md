



https://developers-dot-devsite-v2-prod.appspot.com/machine-learning/crash-course/backprop-scroll for understanding and visualized deep learning 

# Deep Learning: From Theory to Code Implementation

Welcome to my comprehensive Deep Learning repository! This repository tracks my journey in mastering deep learning concepts, neural network architectures, and practical hands-on implementations using Python, PyTorch, and TensorFlow.

---

## 📌 Executive Summary

I built this project to document end-to-end learning, intuitive mathematical breakdowns, and production-ready code implementations for fundamental to advanced deep learning algorithms.

* **Target Stack:** Python, PyTorch, TensorFlow/Keras, NumPy, Matplotlib
* **Core Focus:** Mathematical intuition, forward/backward propagation mechanics, neural network optimization, and computer vision architectures.

---

## 🗺️ Curriculum & Topic Coverage

Below is the structured breakdown of topics covered in this repository, including detailed notes, intuitive explanations, and complete code walkthroughs.

### 1. Foundations of Neural Networks
* **Perceptrons & Multi-Layer Perceptrons (MLPs):**
  * Constructed single-layer and multi-layer perceptron models from scratch using NumPy.
  * Mapped linear decision boundaries and analyzed non-linear activation functions.
* **Forward & Backward Propagation:**
  * Derived partial derivatives and chain rule equations for error backpropagation.
  * Implemented gradient descent algorithms to update network weights iteratively.
* **Activation Functions:**
  * Analyzed and coded Sigmoid, Tanh, ReLU, Leaky ReLU, and Softmax functions.
  * Evaluated vanishing and exploding gradient problems across deep architectures.

---

### 2. Optimization & Model Regularization
* **Optimization Algorithms:**
  * Implemented SGD (Stochastic Gradient Descent), Momentum, RMSprop, and Adam optimizers.
  * Simulated convergence rates across various loss surfaces.
* **Regularization Techniques:**
  * Applied L1 (Lasso) and L2 (Ridge) weight decay to reduce overfitting.
  * Integrated Dropout layers and Batch Normalization to stabilize training dynamics.
* **Hyperparameter Tuning:**
  * Experimented with dynamic learning rate schedulers (Cosine Annealing, ReduceLROnPlateau).

---

### 3. Computer Vision & Convolutional Networks (CNNs)
* **CNN Mechanics:**
  * Coded 2D convolution operations, pooling (Max, Average), and stride/padding mechanics.
  * Visualized feature maps to analyze spatial hierarchy feature extraction.
* **Classical Architectures:**
  * Rebuilt key baseline architectures (LeNet-5, AlexNet, VGG, ResNet) in PyTorch.
  * Implemented Residual Connections (Skip Connections) to eliminate vanishing gradients in deep networks.
* **Practical Projects:**
  * Trained custom image classifiers on benchmark datasets (MNIST, CIFAR-10).
  * Executed transfer learning using pre-trained weights to solve custom computer vision tasks.

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python 3.10+
* **Deep Learning Frameworks:** PyTorch, TensorFlow / Keras
* **Scientific Computing:** NumPy, Pandas, SciPy
* **Visualization:** Matplotlib, Seaborn
* **Development Environment:** Jupyter Notebooks, VS Code

---

## 🚀 Getting Started

Follow these steps to clone the repository and run the notebooks locally.

### Prerequisites
Ensure you have Python installed on your system.

```bash
python --version

├── 01-foundations/
│   ├── perceptron_from_scratch.ipynb
│   ├── activations_and_gradients.ipynb
│   └── backpropagation_derivation.ipynb
├── 02-optimization-regularization/
│   ├── optimizers_comparison.ipynb
│   └── dropout_and_batchnorm.ipynb
├── 03-cnn-architectures/
│   ├── cnn_from_scratch.ipynb
│   ├── resnet_implementation.ipynb
│   └── transfer_learning_cv.ipynb
├── requirements.txt
└── README.md
