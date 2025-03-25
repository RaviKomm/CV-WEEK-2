# README: MNIST Digit Classification

## ✅ Project Overview
This project implements three popular machine learning models to classify handwritten digits using the MNIST dataset. The main goal was to evaluate model performance, tune parameters, and compare their classification accuracy.

## 🧠 Models Used
1. **K-Nearest Neighbors (KNN)**
2. **Support Vector Machine (SVM)**
3. **Logistic Regression**

## 📦 Dataset
- **Source**: `sklearn.datasets.load_digits()`
- **Samples**: 1797 grayscale images
- **Image Size**: 8x8 (flattened to 64 features)
- **Classes**: Digits 0–9
- **Split**: 80% training, 20% testing

## 📈 Accuracy Results
- **KNN Accuracy**: 98.33%
- **SVM Accuracy**: 97.78%
- **Logistic Regression Accuracy**: 97.50%

## 🔧 Hyperparameter Tuning
- **KNN**: GridSearchCV used to identify best `k` value → Best found: `k=3`
- **SVM** and **Logistic Regression**: Tuned using standard hyperparameters for optimal performance

## 📊 Insights
- All models showed high performance due to the simplicity of MNIST
- KNN slightly outperformed the others, but is slower with large datasets
- SVM and Logistic Regression showed competitive and stable results
- Visualization via matplotlib highlighted prediction distribution

## 📎 Files
- `mnist_classification.py`: Code for all three models
- Includes hyperparameter tuning, evaluation metrics, and visualization

## ✅ Conclusion
This project illustrates strong baseline models for digit classification. For future work, deeper models or CNNs could be applied to more complex datasets like full MNIST (28x28) or EMNIST.
