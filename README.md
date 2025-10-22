# **Binary Classification on Diabetes Dataset using Support Vector Classifier (SVC)**

This project performs **binary classification** on the **Diabetes dataset** using the **Support Vector Classifier (SVC)** algorithm from scikit-learn.  
The goal is to predict whether a person is diabetic or not based on medical attributes such as glucose level, BMI, insulin, and other features.

---

## 📘 **About the Project**

The project explores how different **kernel functions** — **Linear**, **Polynomial**, and **RBF (Radial Basis Function)** — affect classification performance.  
To achieve the best accuracy, **cross-validation** is used for tuning hyperparameters like `degree` (for the polynomial kernel) and `gamma` (for the RBF kernel).

---

## 🧩 **About the Model**

**Support Vector Classifier (SVC)** is a type of geometric classification model.  
Its decision boundary depends on the number of features used in the dataset:

- With **one input feature**, it is represented as a **point**.  
- With **two input features**, it becomes a **line**.  
- With **three input features**, it forms a **plane**.  
- With **more than three features**, it becomes a **hyperplane** in higher dimensions.

---

## ⚙️ **Steps Performed**

1. Import the required libraries (`pandas`, `sklearn`, etc.)
2. Load the **Diabetes dataset**
3. Split the data into **training** and **testing** sets
4. Apply **Support Vector Classifier** using:
   - Linear kernel  
   - Polynomial kernel (tune `degree` using cross-validation)  
   - RBF kernel (tune `gamma` using cross-validation)
5. Train and test the models
6. Compare **accuracy scores** for each kernel

---

## 📊 Results
- Linear kernel gave baseline accuracy around 75%
- Polynomial kernel improved accuracy after tuning `degree`
- RBF kernel achieved the highest accuracy (~80%)
- Final best model: **SVC with RBF kernel**

---

## 🛠️ Technologies Used
- Python 🐍  
- Pandas 📦  
- Scikit-learn 📊  
- NumPy 🔢  
- Jupyter Notebook 💻

---
## 🎯 Conclusion
Support Vector Classifier is a powerful supervised learning model that performs well on binary classification tasks.

By applying multiple kernels and tuning hyperparameters through cross-validation, we can improve model accuracy and generalization.



