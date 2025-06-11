# 🎗️ Breast Cancer Classification with Random Forest

This machine learning project predicts whether a breast tumor is malignant or benign using the Breast Cancer Wisconsin dataset.

## 📂 Dataset
- **Source:** scikit-learn's built-in `load_breast_cancer` dataset
- **Features:** 30 numeric features describing tumor characteristics like:
  - Mean radius
  - Mean texture
  - Mean perimeter
  - Mean area
  - Mean smoothness
  - … and more

## 📊 Model
We used a **Random Forest Classifier** to:
- Load and explore the dataset
- Preprocess and split the data
- Train the model on 80% of the data
- Evaluate performance on the remaining 20%

## ✅ Results
- **Accuracy:** 96.5%
- **Precision:** 0.96
- **Recall:** 0.99
- **F1 Score:** 0.97

## 🛠️ Tools & Libraries
- Python
- scikit-learn
- Pandas, NumPy
- Seaborn & Matplotlib for visualization

## 🚀 How to Run
1. Run the notebook in Jupyter or Google Colab.
2. No need to upload any dataset — it's built-in via `sklearn.datasets`.

## 📁 Output
Includes model performance metrics and confusion matrix.
