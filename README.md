# 🩺 Diabetes Prediction Using Machine Learning

A machine learning project that predicts diabetes risk using health-related features from the Pima Indians Diabetes Dataset.

The project applies data preprocessing, feature engineering, classification algorithms, and model evaluation to build a predictive diabetes classification system.

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple)

- Python
- Pandas
- Scikit-learn
- NumPy
- Matplotlib
- Machine Learning
- Data Analysis

---

# 📌 Project Overview

Diabetes is a common health condition that can be predicted using various health and medical measurements.

This project uses the **Pima Indians Diabetes Dataset** to develop a machine learning classification system capable of predicting whether a person is likely to have diabetes based on input health-related features.

The project follows a complete machine learning workflow, from data preprocessing to model evaluation.

---

# 🎯 Objective

The objective of this project is to build and evaluate machine learning models for diabetes prediction.

The analysis focuses on:

- Data preprocessing
- Feature engineering
- Exploratory data analysis
- Classification
- Model evaluation
- Comparing prediction performance

---

# 📊 Dataset

The project uses the **Pima Indians Diabetes Dataset**.

The dataset contains health-related attributes used to predict the presence or absence of diabetes.

The target variable represents:

- `0` → No diabetes
- `1` → Diabetes

---

# ✨ Features

## 🧹 Data Preprocessing

The dataset is prepared before model training using:

- Data cleaning
- Feature preprocessing
- Handling input features
- Train-test splitting

## 🔧 Feature Engineering

Relevant features are prepared and transformed to make them suitable for machine learning models.

## 🤖 Machine Learning Models

The project implements:

- Decision Tree Classifier
- Logistic Regression

## 📈 Model Evaluation

Model performance is evaluated using:

- Accuracy Score
- Confusion Matrix

The implemented models achieved approximately **85% prediction accuracy**.

---

# 🔄 Machine Learning Workflow

```text
Diabetes Dataset
       │
       ▼
Data Loading
       │
       ▼
Data Preprocessing
       │
       ▼
Feature Engineering
       │
       ▼
Train-Test Split
       │
       ▼
Machine Learning Models
       │
       ├── Decision Tree
       │
       └── Logistic Regression
       │
       ▼
Model Prediction
       │
       ▼
Performance Evaluation
       │
       ├── Accuracy Score
       │
       └── Confusion Matrix
```

---

# 🧠 Model Architecture

```text
Input Health Features
          │
          ▼
   Data Preprocessing
          │
          ▼
   Feature Engineering
          │
          ▼
    Train-Test Split
          │
          ▼
 ┌─────────────────────┐
 │  Machine Learning   │
 │      Models         │
 ├─────────────────────┤
 │ Decision Tree       │
 │ Logistic Regression │
 └─────────────────────┘
          │
          ▼
     Predictions
          │
          ▼
    Model Evaluation
```

---

# 📈 Model Evaluation

The models are evaluated using accuracy and a confusion matrix.

### Accuracy

The implemented classification models achieved approximately:

**85% prediction accuracy**

### Confusion Matrix

The confusion matrix is used to understand:

- True Positive predictions
- True Negative predictions
- False Positive predictions
- False Negative predictions

---

# 📂 Project Structure

```text
Diabetes_prediction/
│
├── DIABETES_PREDICTION_USING_ML_FINAL.ipynb
├── diabetes.csv
└── README.md
```

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/itzchirag00/Diabetes_prediction.git
cd Diabetes_prediction
```

---

## 2. Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib jupyter
```

---

# 🚀 Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
DIABETES_PREDICTION_USING_ML_FINAL.ipynb
```

Run the notebook cells sequentially to perform the complete analysis and generate predictions.

---

# 📚 Key Learning Outcomes

Through this project, I gained hands-on experience in:

- Building machine learning classification models
- Working with healthcare-related datasets
- Data preprocessing
- Feature engineering
- Train-test splitting
- Implementing Decision Tree classification
- Implementing Logistic Regression
- Evaluating machine learning models
- Using accuracy score and confusion matrices
- Working with Pandas and Scikit-learn
- Understanding the machine learning workflow

---

# 🔮 Future Improvements

Possible enhancements for future versions:

- Compare additional classification algorithms
- Perform hyperparameter tuning
- Add precision, recall, and F1-score
- Implement cross-validation
- Improve feature preprocessing
- Add exploratory data visualizations
- Deploy the model as a web application
- Build an interactive prediction interface

---

# 👨‍💻 Author

**Chirag Sood**

B.E. Computer Science  
Thapar Institute of Engineering & Technology

GitHub: https://github.com/itzchirag00

LinkedIn: https://linkedin.com/in/chiragsood07

---

# 📜 License

This project is intended for educational and personal use.
