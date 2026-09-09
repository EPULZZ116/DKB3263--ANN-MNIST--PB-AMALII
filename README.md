# DKB3263 - Artificial Neural Network (MNIST)

## 📌 Project Overview
This project implements a simple Artificial Neural Network (ANN) using PyTorch in Google Colab to classify handwritten digits from the MNIST dataset.

## 🏗️ Model Architecture
- **Input Layer:** 784 neurons (28x28 flattened pixels)
- **Hidden Layer:** 128 neurons
- **Activation Function:** ReLU
- **Output Layer:** 10 neurons (Classes 0–9)

## ⚙️ Hyperparameters & Training Configuration
- **Loss Function:** CrossEntropyLoss
- **Optimizer:** Adam
- **Dataset Split:** 60,000 Training | 10,000 Testing
- **Epochs:** 5

## 📊 Hyperparameter Tuning Comparison
We compared the baseline model against a tuned model by adjusting the learning rate.

| Parameter | Baseline Model | Tuned Model |
| :--- | :--- | :--- |
| **Learning Rate** | 0.0001 | 0.001 |
| **Batch Size** | 64 | 64 |
| **Testing Accuracy** | *[Masukkan % Baseline contoh: 89.50%]* | *[Masukkan % Tuned contoh: 96.20%]* |

## 📈 Visualizations
Loss and Accuracy graph results are saved inside the `results/` directory.

## 🛠️ Tools Used
- Python / PyTorch / Torchvision
- Matplotlib / NumPy
- Google Colab (T4 GPU)
- GitHub
