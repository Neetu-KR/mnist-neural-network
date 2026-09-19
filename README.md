# MNIST Digit Classification

A simple neural network built with TensorFlow/Keras to classify handwritten digits (0–9) using the MNIST dataset.

## 📌 Project Overview
This project loads the MNIST dataset, trains a neural network to recognize handwritten digits, evaluates its accuracy, and compares results after adding a Dropout layer as an experiment.

## 📂 Contents
- `MNIST_Assignment.ipynb` — Jupyter notebook with full code and outputs
- Report (handwritten) — model design, results, and conclusions

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## 🚀 What the Notebook Does
1. Loads and visualizes sample MNIST images
2. Preprocesses data (normalization)
3. Builds and trains a neural network (Flatten → Dense(128, ReLU) → Dense(10, Softmax))
4. Evaluates test accuracy
5. Plots training/validation accuracy and loss
6. Tests the model on 5 sample images (actual vs predicted)
7. Runs an experiment adding a Dropout layer and compares results

## 📊 Results
| Model | Test Accuracy |
|---|---|
| Baseline | 97.43% |
| With Dropout (0.3) | 97.49% |

## ▶️ How to Run
1. Open `MNIST_Assignment.ipynb` in [Google Colab](https://colab.research.google.com) or Jupyter Notebook
2. Run all cells top to bottom
3. TensorFlow will automatically download the MNIST dataset

## 📄 License
This project is licensed under the MIT License.
