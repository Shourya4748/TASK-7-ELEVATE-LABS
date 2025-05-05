# TASK-7-ELEVATE-LABS


# 🧠 Breast Cancer Classification Using SVM

This project applies **Support Vector Machines (SVM)** to classify tumors as **Malignant** or **Benign** using the Breast Cancer Wisconsin dataset. The aim is to demonstrate both **linear** and **non-linear (RBF kernel)** SVM classification, along with visualization and model optimization.

## 🔍 Key Steps

* **Data Preparation**: Loaded and cleaned the dataset. Converted categorical labels to binary and scaled features for model training.
* **Dimensionality Reduction**: Applied **PCA** to reduce features to 2D, making visualization of decision boundaries possible.
* **Model Training**: Trained two SVM classifiers using linear and RBF kernels.
* **Visualization**: Plotted decision boundaries to visually compare how each kernel separates the classes.
* **Hyperparameter Tuning**: Used **GridSearchCV** to tune `C` and `gamma` for the RBF kernel.
* **Evaluation**: Assessed model performance using cross-validation, confusion matrix, and classification report.

## 🛠️ Tools

* Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn



