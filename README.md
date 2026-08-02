# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

This project develops a machine learning model to predict whether a patient has heart disease based on clinical and medical attributes. It demonstrates a complete end-to-end machine learning workflow, from data exploration and preprocessing to model training, hyperparameter tuning, and evaluation.

The objective is to compare multiple classification algorithms and identify the model that best predicts the presence of heart disease.

---

## 🎯 Problem Statement

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals make informed decisions and provide timely treatment.

This project aims to build a binary classification model that predicts whether a patient has heart disease using clinical features.

**Target Variable**

* **1** → Patient has heart disease
* **0** → Patient does not have heart disease

---

## 📂 Dataset

The project uses the **Heart Disease Dataset**, derived from the Cleveland Heart Disease dataset from the UCI Machine Learning Repository.

The dataset contains:

* **303 patient records**
* **13 clinical input features**
* **1 target variable**

### Features

* Age
* Sex
* Chest Pain Type (`cp`)
* Resting Blood Pressure (`trestbps`)
* Cholesterol (`chol`)
* Fasting Blood Sugar (`fbs`)
* Resting ECG (`restecg`)
* Maximum Heart Rate (`thalach`)
* Exercise-Induced Angina (`exang`)
* ST Depression (`oldpeak`)
* Slope of Peak Exercise ST Segment (`slope`)
* Number of Major Vessels (`ca`)
* Thalassemia (`thal`)
* Target (Heart Disease)

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Project Workflow

The project follows the standard machine learning lifecycle:

1. Problem Definition
2. Data Loading
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Data Visualization
6. Feature Analysis
7. Model Training
8. Hyperparameter Tuning
9. Model Evaluation
10. Model Comparison
11. Conclusion

---

## 🤖 Machine Learning Models

The following classification models are implemented and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest Classifier

Hyperparameter tuning is performed using:

* GridSearchCV
* RandomizedSearchCV

---

## 📈 Model Evaluation

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix
* Cross-Validation
* Classification Report

The best-performing model is selected based on its ability to generalize well to unseen data.

---

## 📁 Project Structure

```text
heart-disease-prediction/
│
├── end-to-end-heart-disease-classification.ipynb
├── heart-disease.csv
├── environment.yml
└── .gitignore
```

---

# 🚀 Getting Started

## Prerequisites

Before running this project, ensure that the following are installed on your system:

* Git
* Anaconda or Miniconda
* Jupyter Notebook

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/annthomas2706/heart-disease-prediction.git
```

### 2. Navigate to the project directory

```bash
cd heart-disease-prediction
```

### 3. Create the Conda environment

```bash
conda env create -f environment.yml
```

This command installs all the required Python packages listed in the `environment.yml` file.

### 4. Activate the environment

```bash
conda activate <environment_name>
```

Replace `<environment_name>` with the name specified at the top of the `environment.yml` file.

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 6. Open the notebook

Open **end-to-end-heart-disease-classification.ipynb** and run all the notebook cells from top to bottom.

---

## 🔮 Future Improvements

* Train on a larger and more diverse dataset.
* Perform additional feature engineering and feature selection.
* Evaluate advanced ensemble models such as XGBoost, LightGBM, and CatBoost.
* Deploy the final model using Streamlit or Flask.
* Monitor and periodically retrain the model using new data.

---

## 📚 Dataset Source

* Cleveland Heart Disease Dataset (UCI Machine Learning Repository)

---

## 👤 Author

**Ann Mary Thomas**

* GitHub: https://github.com/annthomas2706
* LinkedIn: https://www.linkedin.com/in/annmarythomas2706/
