# 🌸 Iris Flower Classification — Machine Learning Project

## 📘 Objective
This project focuses on creating and evaluating machine learning models that can accurately classify Iris flowers (*Setosa*, *Versicolor*, *Virginica*) based on their measured features such as sepal and petal lengths and widths.

---

## 🧩 Steps Performed

### 1. **Data Loading**
- Loaded the **Iris dataset** using `sklearn.datasets`.
- Stored the feature matrix and labels in pandas DataFrames for easier exploration and processing.

### 2. **Exploratory Data Analysis (EDA)**
- Checked dataset dimensions, inspected sample rows, and reviewed class distribution.
- Used visualizations like pair plots and histograms to study feature patterns and how well the classes separate.

### 3. **Data Preprocessing**
- Split the dataset into **training** and **testing** subsets using `train_test_split`.
- Applied **StandardScaler** to normalize feature values for improved model performance.

### 4. **Model Training**
- Trained two machine learning models:
  - **K-Nearest Neighbors (KNN)**
  - **Random Forest Classifier**
- Implemented a **Pipeline** to connect preprocessing and model training steps into a unified workflow.

### 5. **Model Evaluation**
- Calculated accuracy on the test set.
- Generated **confusion matrices**, **classification reports**, and **cross-validation scores**.
- Compared both algorithms to determine which one performs best on the dataset.

---

## ⚙️ Tools & Libraries Used

| Category | Tools/Libraries |
|----------|------------------|
| Data Handling | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |
| Machine Learning | `scikit-learn` (`Pipeline`, `RandomForestClassifier`, `KNeighborsClassifier`) |
| Evaluation | `accuracy_score`, `classification_report`, `confusion_matrix`, `cross_val_score` |

---

## 🏁 Outcome
- The **Random Forest Classifier** provided the highest accuracy and showed strong generalization.
- PCA-based visualizations highlighted clear separation among the three Iris species.
- This project covers the full ML pipeline—from EDA and preprocessing to model training, comparison, and evaluation.

---
