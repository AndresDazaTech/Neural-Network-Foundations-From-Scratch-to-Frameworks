# 🧠 Neural Network Foundations: From Scratch to Frameworks

[![NumPy](https://img.shields.io/badge/Library-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/)
[![PyTorch](https://img.shields.io/badge/Framework-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)](https://wwww.tensorflow.org/)
[![Fashion-MNIST](https://img.shields.io/badge/Dataset-Fashion--MNIST-green?style=flat-square)](https://github.com/zalandoresearch/fashion-mnist)

## 📌 Overview
This project explores the foundations of neural networks by building models from the ground up using **NumPy** and then transitioning to modern deep learning frameworks, **PyTorch** and **TensorFlow/Keras**. By implementing the same architecture across different levels of abstraction, this project demonstrates a comprehensive understanding of forward/backward propagation, weight updates, and framework-specific optimization.

---

## 🎯 Learning Objectives
*   **Deconstruct** neural network components: layers, neurons, and activation functions ($ReLU$, $Softmax$).
*   **Implement** manual backpropagation and gradient descent from scratch.
*   **Architect** and train models using PyTorch's class-based structure.
*   **Develop** efficient pipelines using TensorFlow/Keras High-Level APIs.
*   **Optimize** performance through hyperparameter tuning and regularization techniques (Dropout, Learning Rate Scheduling).
*   **Diagnose** model health by analyzing training/validation curves to mitigate overfitting.

---

## 📊 Datasets
1.  **Fashion-MNIST (Primary):** 70,000 grayscale images (28x28) across 10 clothing categories.
2.  **CIFAR-10 (Advanced):** 60,000 color images (32x32) across 10 object classes (used for advanced testing).

---

## 🛠️ Project Architecture

### 1. The NumPy Implementation (The "Hard Way")
*   Manual implementation of the linear algebra behind neural networks.
*   **Focus:** Understanding the chain rule in backpropagation and the manual updating of weights and biases.

### 2. The PyTorch Implementation (Flexibility & Control)
*   Utilized custom `nn.Module` classes and explicit training loops.
*   **Techniques:** Dropout layers for regularization and `StepLR` for dynamic learning rate adjustment.
*   **Outcome:** High degree of control over the gradient flow and model state.

### 3. The TensorFlow/Keras Implementation (Efficiency & Scale)
*   Used the `Sequential` API for rapid prototyping.
*   **Techniques:** Integrated `compile()` and `fit()` workflows with built-in validation monitoring.
*   **Outcome:** Streamlined development with optimized performance.

---

## 📈 Key Results & Performance

| Approach | Feature | Validation Accuracy |
| :--- | :--- | :--- |
| **NumPy** | Pure Math / From Scratch | ~82% |
| **PyTorch** | Dropout + LR Scheduler | **~89.5%** |
| **TF/Keras** | Sequential API | ~88.7% |

*   **Regularization Impact:** Adding Dropout significantly reduced the gap between training and validation loss.
*   **Framework Comparison:** Observed that while Keras is faster for standard tasks, PyTorch provides superior debugging and customization for experimental architectures.

---

## 💡 Key Takeaways
*   **Intuition:** Building from scratch deepens the intuition required to debug complex models in professional frameworks.
*   **Optimization:** Hyperparameters (like learning rate) and architecture choices (like Dropout) often matter as much as the data itself.
*   **Workflow:** TensorFlow is excellent for production-ready standard models, while PyTorch is the preferred tool for research-oriented experimentation.

---

## 🛠️ Technologies Used
*   **Core:** Python, NumPy
*   **Deep Learning:** PyTorch, TensorFlow / Keras
*   **Analysis:** Scikit-learn (Confusion Matrices, Classification Reports)
*   **Visualization:** Matplotlib, Seaborn
*   **Environment:** Google Colab / Jupyter

---

## 🚀 How to Run
1.  Open the `.ipynb` notebook in **Google Colab**.
2.  Ensure you have the required libraries:
    ```bash
    pip install torch torchvision tensorflow scikit-learn matplotlib seaborn
    ```
3.  Run all cells to execute the comparison between NumPy, PyTorch, and TensorFlow.

---

## 👤 Author
**Andres Daza Catano**  
*ITAI 2376 – Deep Learning*  
Houston Community College — Spring 2026
