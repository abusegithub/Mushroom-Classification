
# 🍄 Mushroom Classification — Machine Learning Project

**Predict whether a mushroom is Edible or Poisonous using ML**
*Complete project with dataset, notebook, visualizations, and saved model*

---

## 📌 Project Overview

This project builds a machine learning model to classify mushrooms as **Edible (e)** or **Poisonous (p)** based on their physical characteristics.

The dataset contains **23 categorical features** such as:

* cap shape
* cap surface
* cap color
* odor
* gill size
* spore print color
* habitat
* and more…

Using feature engineering and modern ML algorithms, the final model achieves **high accuracy and F1-score**, making it suitable for real-world decision-support systems.

---

## 📁 Project Structure

```
├── mushroom_classification.ipynb   # Jupyter Notebook
├── data/
│     └── mushrooms.csv             # Dataset
├── output/
│     ├── confusion_matrix.png
│     ├── feature_importances.png
│     ├── target_distribution.png
├── models/
│     └── best_mushroom_model.joblib
└── README.md
```

---

## 📊 Dataset

**Source:** UCI / Kaggle Mushroom Dataset
Contains **8,124 rows × 23 categorical features**.

**Target Column:**

```
class → p = poisonous, e = edible
```

All features are **categorical**, requiring encoding before training.

---

## 🧼 Data Preprocessing

Steps performed:

* Removed missing/unnecessary fields
* Label encoded all categorical features
* Checked class balance
* Trained–test split
* Feature importance visualization

Plots include:

* Class distribution
* Confusion matrix
* Feature importance
* Model comparison

---

## 🤖 Models Used

Various ML algorithms were tested:

| Model               | Accuracy  | F1-Score  |
| ------------------- | --------- | --------- |
| XGBoost Classifier  | ⭐ Highest | ⭐ Highest |
| Random Forest       | Excellent | Excellent |
| Logistic Regression | Good      | Good      |
| KNN / Naive Bayes   | Moderate  | Moderate  |

**Final chosen model:**

### ✔ XGBoost Classifier

Saved as:

```
models/best_mushroom_model.joblib
```

---

## 🚀 How to Run

### 1️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Run the notebook

Open:

```
mushroom_classification.ipynb
```

### 3️⃣ Dataset placement

Place the mushrooms dataset inside:

```
/data/mushrooms.csv
```

---

## 📈 Results

* Near-perfect classification performance
* Strong separation between poisonous & edible
* Odor, gill size, and spore print color are top predictors

---

## 🧠 Key Learnings

* Working with fully categorical datasets
* Label Encoding vs One-Hot Encoding
* Identifying strongest predictive features
* Avoiding overfitting with regularized models
* Building high-accuracy classification systems

---

## 🗂️ Uses / Applications

* Food safety systems
* Automated identification apps
* Educational ML demos
* Feature-importance visualization

---

## ⭐ Final Notes

This project is part of a 10-project ML portfolio series designed to build solid foundations in:

* Data cleaning
* EDA
* Model building
* Evaluation
* Saving/Deploying models
* Professional GitHub documentation

---

