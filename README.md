# 🧠 Decision Tree Classification – Breast Cancer Diagnosis

## 📌 Course
**CCS4340 - Machine Learning**  
**Lab Sheet 08 – Real-World Dataset Exercise**

---

## 📚 Objective

This assignment applies Decision Tree Classification to the **Breast Cancer Wisconsin Diagnostic Dataset** to predict whether a tumor is **benign** or **malignant** based on various medical features.

---

## 🎯 Learning Outcomes

By completing this lab, you will be able to:

- Load and preprocess a real-world dataset using pandas
- Encode categorical variables for machine learning models
- Train a Decision Tree Classifier with Scikit-learn
- Visualize the decision tree structure
- Evaluate model performance using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
- Compare Gini impurity vs Entropy as splitting criteria
- Analyze how `max_depth` affects model performance and overfitting

---

## 📁 Dataset

- **Source**: [Kaggle - Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **File**: `data.csv`
- **Features**: 30 numerical features related to cell nucleus measurements
- **Target**: `diagnosis` — M (Malignant), B (Benign)

---

## 🛠️ Technologies Used

- Python 3
- pandas
- scikit-learn
- matplotlib

---

## 🚀 How to Run

1. Clone the repository or open the notebook in Google Colab / Jupyter.
2. Download `data.csv` from Kaggle and place it in your working directory.
3. Run the script or notebook step by step:

```python
# 1. Load and clean dataset
# 2. Encode diagnosis column
# 3. Train-test split
# 4. Train decision tree
# 5. Visualize the tree
# 6. Evaluate model
# 7. Compare Gini vs Entropy
# 8. Try different max_depth values
