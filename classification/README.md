# Classification

## 1-MPC Classifier

This Python project, named "MPC Classifier," is designed for performing facial classification using Multi-Layer Perceptron (MLP) neural networks. The goal of this project is to classify faces into two categories, making it a binary classification problem. According to the evaluation results, the model does not exhibit overfitting or underfitting issues and achieves satisfactory accuracy on both the training and test datasets.

---

## 2-Maternal Health Risk Classification

This project is focused on maternal health risk classification. The dataset contains various health-related features, and the goal is to predict the risk level associated with maternal health based on these features.

### Model Comparison

In the end, we determine which of the trained models performs best for predicting maternal health risk. The table below summarizes the accuracy scores for each model on the test, training, and cross-validation datasets:

| Model                   | Test Accuracy | Train Accuracy | Cross-Validation Accuracy |
|-------------------------|---------------|----------------|---------------------------|
| RandomForestClassifier  | 80%           | 94%            | 85%                       |
| DecisionTree            | 80%           | 94%            | 83%                       |
| KNeighborsClassifier    | 68%           | 85%            | 71%                       |
| SVM                     | 69%           | 73%            | 70%                       |

The RandomForestClassifier model demonstrates the highest accuracy, making it the preferred choice for predicting maternal health risk.

---

## 3-Title: pd_speech_features Classification

This project involves classifying data from the "pd_speech_features" dataset using various machine learning models and evaluating their performance before and after applying Principal Component Analysis (PCA) for dimensionality reduction. The goal is to predict the target variable "class" based on a set of features.

It evaluates the impact of dimensionality reduction through PCA on model performance. The comparison of model accuracies before and after PCA provides insights into the effectiveness of dimensionality reduction techniques in improving or maintaining model performance.