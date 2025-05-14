# 🧠 Face Recognition using Autoencoders, Eigenfaces, and Machine Learning Classifiers

This project explores and compares different feature extraction techniques—**Eigenfaces**, **Vanilla Autoencoders**, and **Convolutional Autoencoders**—combined with two classifiers: **Support Vector Machine (SVM)** and a **simple Neural Network (NN)** for face recognition tasks over casia dataset.

---

## 📁 Project Structure

| File/Script           | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| `ManualNormalization.py`    | Handles image resizing, Normalization, and other preprocessing tasks  |
| `eigen_NN.py`               | Uses Eigenfaces + Neural Network                                      |
| `eigen_svm.py`        | Uses Eigenfaces + SVM                                                       |
| `perceptron_NN.py`    | Uses Vanilla Autoencoder (encoder part) + Neural Network                    |
| `perceptron_svm.py`   | Uses Vanilla Autoencoder (encoder part) + SVM                               |
| `cae_NN.py`           | Uses Convolutional Autoencoder (encoder part) + Neural Network              |
| `cae_svm.py`          | Uses Convolutional Autoencoder (encoder part) + SVM                         |

---

## 🔍 Feature Extraction Methods

- **Eigenfaces**: Principal Component Analysis (PCA)-based dimensionality reduction technique.
- **Vanilla Autoencoder**: A basic feedforward neural network trained to reconstruct input; encoder used as feature extractor.
- **Convolutional Autoencoder**: Uses convolutional layers to learn spatial hierarchies in face data.

---

## 🤖 Classifiers

- **Neural Network (NN)**: Simple perceptron-based network used for classification.
- **Support Vector Machine (SVM)**: Scikit-learn's SVM implementation for face class prediction.

---

## 🚀 Workflow

1. **Preprocessing**: Input images are preprocessed and normalized.
2. **Feature Extraction**: One of the three methods is used to extract features.
3. **Classification**: Features are passed into either the NN or SVM for classification.

---

## 🧪 Evaluation

This structure enables a direct comparison between:
- Feature extractors (Eigenfaces vs Autoencoders)
- Classifiers (SVM vs NN)

---





