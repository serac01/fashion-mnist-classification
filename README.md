# 👕 Fashion MNIST Classification

> A Machine Learning project developed in **Python** for the **Artificial Intelligence (5DV243)** course at **Umeå University**.

This project explores supervised image classification using the **Fashion MNIST** dataset. Two different machine learning approaches were implemented and evaluated: a **k-Nearest Neighbors (k-NN)** classifier and a **Multilayer Perceptron (MLP)** neural network. The models were trained, tuned through manual hyperparameter search, and compared based on their classification performance.

---

# ✨ Features

- 👕 Fashion MNIST image classification
- 🤖 k-Nearest Neighbors (k-NN) classifier
- 🧠 Multilayer Perceptron (MLP) neural network
- 🔍 Manual hyperparameter search
- 📊 Model performance evaluation
- 📈 Training loss visualization
- 📉 Accuracy comparison between classifiers
- 📝 Jupyter Notebook implementation
- ⚙️ Data preprocessing and normalization

---

# 🛠 Technologies

- Python
- Jupyter Notebook
- NumPy
- Matplotlib
- Scikit-learn
- Machine Learning
- Artificial Neural Networks

---

# 📚 Machine Learning Concepts

This project demonstrates several core Machine Learning concepts:

- Supervised Learning
- Image Classification
- k-Nearest Neighbors (k-NN)
- Multilayer Perceptron (MLP)
- Hyperparameter Tuning
- Model Evaluation
- Feature Scaling
- Train / Validation / Test Splits

---

# 👕 Dataset Overview

The project uses the **Fashion MNIST** dataset, a collection of grayscale images representing ten categories of clothing and accessories.

Each image:

- Has a resolution of **28 × 28 pixels**
- Represents a single fashion item
- Belongs to one of ten predefined classes

Examples of classes include:

- 👕 T-shirt / Top
- 👖 Trouser
- 👗 Dress
- 🧥 Coat
- 👟 Sneaker
- 👢 Ankle Boot
- 👜 Bag
- 👞 Sandal
- 👔 Shirt
- 🎩 Pullover

---

# 🤖 Implemented Models

## k-Nearest Neighbors (k-NN)

The k-NN classifier predicts the label of an unseen image by considering the most similar training samples.

Hyperparameters explored include:

- Number of neighbors (k)
- Distance metric
- Feature preprocessing

---

## Multilayer Perceptron (MLP)

A dense feed-forward neural network was trained to classify Fashion MNIST images.

The network was evaluated using different configurations of:

- Hidden layers
- Number of neurons
- Activation functions
- Learning parameters

Training performance was monitored through the loss curve.

---

# 📊 Model Evaluation

Both classifiers were evaluated using unseen test data after the final model selection.

Evaluation metrics include:

- Classification Accuracy
- Validation Accuracy
- Test Accuracy
- Training Loss (MLP)

The project compares the strengths and weaknesses of both approaches and discusses their suitability for real-world applications.

---

# 🧩 Project Structure

```text
FashionMNIST/
│
├── FashionMNIST.ipynb
├── report.pdf
├── images/
└── README.md
```

---

# 🏗 Workflow

The project follows a typical supervised machine learning pipeline.

```text
Dataset
    │
    ▼
Preprocessing
    │
    ▼
Train / Validation Split
    │
    ▼
Hyperparameter Search
    │
    ├── k-NN
    └── MLP
    │
    ▼
Model Evaluation
    │
    ▼
Performance Comparison
```

---

# 🚀 Getting Started

## Requirements

- Python 3.x
- Jupyter Notebook

Install the required packages:

```bash
pip install numpy matplotlib scikit-learn
```

Clone the repository:

```bash
git clone https://github.com/serac01/fashion-mnist-classification.git
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and execute all cells.

---

# 📈 Results

The assignment required achieving:

- **≥ 84%** accuracy using the k-NN classifier
- **≥ 88%** accuracy using the neural network

Different hyperparameter configurations were evaluated to identify the best-performing models while avoiding overfitting and preserving proper evaluation methodology.

---

# 📄 License

This project was developed for the **Artificial Intelligence** course at **Umeå University**.

It is intended for educational purposes.