# Svm_make_moons_classification
## 🌙 SVM Classification on `make_moons` Dataset

This project demonstrates binary classification using Support Vector Machine (SVM) on a synthetic dataset from kaggle `make_moons`. It includes preprocessing, training, evaluation, visualization, and model saving steps.

## 🚀 Project Overview

- Binary classification using SVM
- Dataset: `make_moons` csv dataset download from `kaggle
- Train-test split for evaluation
- Model training with RBF kernel
- Evaluation using:
  - Confusion Matrix
  - ROC AUC Curve
- Visualization of the decision boundary
- Model saved using `joblib` for reuse

## 🧰 Libraries Used

- numpy
- pandas
- matplotlib  
- seaborn  
- scikit-learn  
- joblib  

## 📌 Project Workflow

1. ##  Load Dataset ##

- **Source**: https://www.kaggle.com/datasets/thembatman/make-moons-from-sklearn
- **Features**: 2 numerical features used for visual decision boundary
  
- **Target**: Binary classification (0 or 1) 
   

2. **Train-Test Split**:  
   Split the data into training and testing sets for 80% training, 20% testing.

3. **Model Building & Training**:  
   Train an SVM model using an RBF kernel to learn from the training data.

4. **Evaluation**:  
   Evaluate the model using a confusion matrix and ROC AUC score. Visualize ROC AUC curve.

5. **Decision Boundary Visualization**:  
   Plot the SVM decision boundary to visualize classification results on both training and test datasets.

6. **Model Saving**:  
   Save the trained model to a `.joblib` file for future use.

   📁 Project Structure

├── svm_moons_classification.ipynb
├── svm_moons_model.joblib
├── README.md

## ✅ Setup Instructions

1. Clone the repository.
2. Install dependencies listed in `requirements.txt`.
3. Run the notebook to generate plots, train the model, and save it.

## 💾 Requirements

You can install the required packages using: 
``pip install -r requirements.txt``
