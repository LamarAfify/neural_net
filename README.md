# 🧠 Fashion MNIST Classifier using MLPClassifier

This project uses a **Multi-Layer Perceptron (MLPClassifier)** from `scikit-learn` to classify clothing items from the **Fashion MNIST** dataset.

It demonstrates:
- Preprocessing and filtering data
- Training an MLP neural network
- Evaluating model accuracy and confusion matrix
- Per-class accuracy reporting

---

## 📁 Dataset

This project uses a **balanced subset** of the Fashion MNIST dataset:

- `fashion_mnist_20bal_train.csv` – training data
- `fashion_mnist_20bal_test.csv` – testing data

> Each CSV file contains pixel values of 28×28 grayscale images (flattened into rows), with a `class` label column indicating the clothing category.

---

## 🧪 Dependencies

- Python 3.x
- `pandas`
- `scikit-learn`

Install them via pip:
```bash
pip install pandas scikit-learn

```

---

## 🚀 How to Run

1. Place the CSV files in the same directory as the script:
   - `fashion_mnist_20bal_train.csv`
   - `fashion_mnist_20bal_test.csv`

2. Run the script:

```bash
python fashion_mnist_mlp.py
