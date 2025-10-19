 Fashion MNIST Classification

This project uses a Neural Network (MLP) built with TensorFlow & Keras to classify fashion items from the Fashion MNIST dataset

 Dataset

* **Shape:** (60,000, 28, 28) training images
* **Classes:** 10 fashion categories (e.g., T-shirt, Trouser, Sneaker, Bag, etc.)
* **Preprocessing:** Images normalized by dividing pixel values by 255

## 🏗️ Model Architecture

* **Flatten Layer:** Converts 2D images (28×28) to 1D vectors
* **Dense(300, ReLU)**
* **Dense(100, ReLU)**
* **Dense(10, Softmax)** → Output layer for 10 fashion classes

## ⚙️ Training

* **Loss:** Sparse Categorical Crossentropy
* **Optimizer:** Adam
* **Metrics:** Accuracy
* Includes **validation set** to monitor model performance


## ✅ Results

The model achieves **high accuracy** on both training and test sets for classifying fashion items.

---

Would you like me to make this README in a **GitHub-styled format** (with emojis, badges, and a “How to Run” section)? It’ll look more professional.
