# README: Iris Neural Network Classification

## 📌 Project Overview
This project demonstrates the implementation of a simple two-layer neural network using PyTorch to classify the well-known Iris dataset. The objective was to understand core neural network concepts like forward propagation, backpropagation, training with optimizers, and evaluating model performance using industry-standard tools.

## ✅ Goals
- Build a two-layer neural network using PyTorch
- Apply backpropagation and use Adam optimizer
- Experiment with activation functions and weight initialization
- Evaluate model using accuracy, confusion matrix, and classification report

## 🧰 Tools and Libraries Used
- **Python** – Programming language
- **PyTorch** – Deep learning framework
- **scikit-learn** – For data preprocessing and metrics
- **Matplotlib** – For visualization
- **VS Code** – Code editor
- **GitHub Copilot** – AI-powered code assistance

## 📂 Dataset
- **Name**: Iris Dataset (from `sklearn.datasets`)
- **Samples**: 150 total
- **Features**: Sepal Length, Sepal Width, Petal Length, Petal Width
- **Classes**: Setosa, Versicolor, Virginica
- **Split**: 80% training, 20% testing

## 🏗️ Neural Network Architecture
- **Input Layer**: 4 features
- **Hidden Layer**: 10 neurons with ReLU activation
- **Output Layer**: 3 neurons with Softmax activation
- **Loss Function**: CrossEntropyLoss
- **Optimizer**: Adam (lr = 0.01)
- **Epochs**: 100

## 📉 Training Observations
- Loss decreased from 1.1397 to 0.6193 over 90 epochs
- Demonstrated stable learning and good convergence

## 📊 Evaluation Metrics
- **Accuracy**: 100% on test set (30/30 samples correct)
- **Precision / Recall / F1-score**: 1.0 for all classes
- **Confusion Matrix**: Perfect diagonal (no misclassifications)
- **Predicted Class Distribution**:
  - Setosa: 10
  - Versicolor: 9
  - Virginica: 11

## 📄 Output Summary
All outputs such as training progress, prediction distribution, classification report, and confusion matrix have been visualized and verified for correctness.

## 📎 Included Files
- `neural_network.py`: Full code implementation
- `Iris_Neural_Network_Presentation_TextOnly.pptx`: Final presentation (with detailed slide notes)
- `README_Iris_Neural_Network.txt`: This summary

## 🔮 Future Enhancements
- Add dropout layers to prevent overfitting
- Experiment with batch normalization
- Test model robustness with noisy or imbalanced datasets
- Extend architecture to deeper or convolutional neural networks

---

This project serves as a foundation for understanding neural networks in a simple and structured way. Perfect for students, beginners, and anyone interested in ML model development.

