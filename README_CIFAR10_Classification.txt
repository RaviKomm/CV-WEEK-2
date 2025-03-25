# README: CIFAR-10 Subset Image Classification

## ✅ Project Objective
This project focuses on implementing and comparing three machine learning models to classify images from a subset of the CIFAR-10 dataset. The selected subset includes three classes: Airplane, Automobile, and Bird. The purpose is to evaluate how different classifiers perform on real-world, colored image data.

## 🧠 Models Implemented
1. **Multiclass Support Vector Machine (SVM)**
2. **Softmax Classifier (Multinomial Logistic Regression)**
3. **Two-layer Neural Network** built using PyTorch

## 📦 Dataset
- **Source**: `torchvision.datasets.CIFAR10`
- **Classes Used**: 0 - Airplane, 1 - Automobile, 2 - Bird
- **Image Shape**: 32x32x3
- **Preprocessing**:
  - Normalization using torchvision transforms
  - Filtering dataset to only include 3 target classes
  - Flattening images for sklearn models (SVM and Softmax)

## 🧪 Model Training & Evaluation
- **SVM**: Linear kernel, trained on flattened RGB images
- **Softmax**: Trained using scikit-learn’s logistic regression
- **Neural Network**: 
  - Input: 3072 neurons
  - Hidden layer: 100 neurons + ReLU
  - Output: 3 neurons with Softmax
  - Loss: CrossEntropyLoss
  - Optimizer: Adam

## 📊 Performance Insights
- The SVM and Softmax models performed decently on flattened data but may struggle with more complex patterns due to lack of depth.
- The neural network performed better with GPU acceleration and demonstrated more adaptability to the image data.
- Plotting accuracy comparisons revealed strengths and trade-offs of each method.

## 📎 Files
- `image_classification.py`: All code including training and comparison
- CIFAR subset loaded using PyTorch and visualized with Matplotlib

## 📌 Future Scope
- Apply CNN for improved spatial feature extraction
- Use full 10-class CIFAR-10 dataset
- Implement batch processing and regularization in neural network
