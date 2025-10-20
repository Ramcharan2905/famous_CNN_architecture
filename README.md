# CNN Architectures for CIFAR-10 Classification

This repository implements and compares several famous **Convolutional Neural Network (CNN) architectures** on the **CIFAR-10 image classification dataset**.

It includes implementations of classic models (LeNet-5, AlexNet), modern architectures (GoogleNet, ResNet, SENet), a custom-built CNN, and a notebook for fine-tuning a pre-trained model. The entire project is built using **TensorFlow 2.x**.

---

## 📘 Overview

This project serves as a hands-on exploration of building and training various deep learning models for image classification. It demonstrates how different architectural designs (from simple to complex) are implemented and trained from scratch.

It also provides a clear example of **transfer learning** by fine-tuning a model pre-trained on a larger dataset (like ImageNet) for the specific task of CIFAR-10 classification.

---

## 🧠 Problem Statement

Given an input image from the CIFAR-10 dataset, predict which of the following 10 classes it belongs to:

-   ✈️ airplane
-   🚗 automobile
-   🐦 bird
-   🐱 cat
-   🦌 deer
-   🐶 dog
-   🐸 frog
-   🐴 horse
-   🚢 ship
-   🚚 truck

---

## ⚙️ Tech Stack

-   **Python 3.x**
-   **TensorFlow 2.x**
-   **NumPy**
-   **Pandas**
-   **Matplotlib** & **Seaborn** (for visualization)
-   **Jupyter Notebook**

---

## 🚀 Features

-   **7 Different Models**: Implementations of LeNet-5, AlexNet, GoogleNet, ResNet, SENet, a custom CNN, and a fine-tuned model.
-   **Train from Scratch**: Demonstrates how to build and train complex models from the ground up.
-   **Transfer Learning**: Includes a practical example of fine-tuning a pre-trained model.
-   **TensorFlow 2.x**: All models are built using the modern Keras Sequential and Functional APIs.
-   **Data Handling**: Includes standard data loading, normalization, and categorization for the CIFAR-10 dataset.

---

## ▶️ How to Run

1.  **Clone the repository**
    ```bash
    git clone <your-repo-url>
    cd cifar10-cnn-architectures
    ```

2.  **Set up the environment** (Recommended)
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run notebooks**
    ```bash
    jupyter notebook
    ```
    Open any of the `.ipynb` files to view, run, and experiment with the models.

---

## 📊 Results

-   **Models**: LeNet-5, AlexNet, GoogleNet, ResNet, SENet, Custom CNN, Fine-Tuned Model
-   **Framework**: **TensorFlow**
-   **Task**: **Image Classification (10 classes)**
-   **Dataset**: **CIFAR-10**

This repository serves as a practical comparison of how different CNN architectures perform on a standard benchmark dataset, showcasing the evolution of network design.

---

## 📈 Learning Purpose

This project aims to help practitioners understand:
-   The fundamental building blocks of famous CNNs (Conv2D, MaxPooling, Residual Blocks, Inception Modules, SE Blocks).
-   How to implement and train deep learning models from scratch using Keras.
-   The application and benefits of transfer learning.
-   Performance comparison between different model architectures on a common task.

---

## ⭐ Acknowledgments

-   **CIFAR-10 Dataset** — [University of Toronto](https://www.cs.toronto.edu/~kriz/cifar.html)
-   **TensorFlow** — Deep learning framework
