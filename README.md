# 🧠 Task 7: Support Vector Machines (SVM) - Breast Cancer Classification

## 📌 Objective
Use Support Vector Machines (SVM) for binary classification (Malignant vs Benign) using the Breast Cancer dataset. Train both **Linear** and **RBF** kernels, tune hyperparameters, and visualize decision boundaries using PCA.

---

## 🗂️ Dataset
We used the [Breast Cancer Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset) containing 30 features extracted from digitized images of breast masses.

**Target:**
- `diagnosis`: `M` = Malignant (1), `B` = Benign (0)

---

## 🛠️ Tools & Libraries Used
- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- PCA (for dimensionality reduction)
- Google Colab (for uploading and execution)

---

## 🧪 What This Project Covers
- ✅ Data loading and preprocessing
- ✅ SVM with Linear Kernel
- ✅ SVM with RBF Kernel
- ✅ Hyperparameter tuning using `GridSearchCV`
- ✅ Cross-validation
- ✅ PCA-based 2D Visualization of decision boundary
- ✅ Colab-compatible file upload feature

---

## 📈 Results

| Model        | Accuracy | Notes                         |
|--------------|----------|-------------------------------|
| SVM (Linear) | ~96%     | Simple and fast               |
| SVM (RBF)    | ~98%     | Better with non-linear data   |

> Final tuned model using RBF kernel performed the best after hyperparameter optimization.

---


---

## 📂 File Structure


