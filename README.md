# Machine Learning Project

A comprehensive Machine Learning project covering **classification, clustering, and regression** using real-world datasets. The project focuses on data exploration, preprocessing, model development, evaluation, and comparison.

## 📌 Project Overview

This project was developed as a Machine Learning final project and is divided into three main areas:

* **Classification** — Predicting the presence of heart disease
* **Clustering** — Discovering groups within the Wine dataset using K-Means
* **Regression** — Predicting house prices using multiple regression models

The project also includes exploratory data analysis, data preprocessing, model evaluation, visualization, and model comparison.

---

## 🧠 Machine Learning Tasks

### 1. Classification — Heart Disease

**Goal:** Predict whether a patient has heart disease based on medical features.

**Dataset:** Heart Disease Dataset (Cleveland)

**Techniques:**

* Exploratory Data Analysis (EDA)
* Data quality checks
* Feature analysis
* Train/test splitting
* Decision Tree
* AdaBoost
* Random Forest
* Model evaluation and comparison

**Evaluation metrics:**

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

📁 [`classification/`](./classification/)

---

### 2. Clustering — Wine Dataset

**Goal:** Identify natural groups within wine samples using unsupervised learning.

**Dataset:** Wine dataset

**Techniques:**

* Data exploration
* Missing-value and duplicate checks
* Feature scaling using StandardScaler
* K-Means clustering
* Elbow Method
* Silhouette Score
* PCA for dimensionality reduction
* Cluster profiling

The optimal number of clusters is selected using **Silhouette Score**, supported by the Elbow Method.

📁 [`clustering/`](./clustering/)

---

### 3. Regression — Housing Prices

**Goal:** Predict house prices based on property characteristics.

**Dataset:** Housing Prices Dataset

**Techniques:**

* Data cleaning
* Missing-value handling
* Outlier treatment
* Categorical encoding
* Feature scaling
* Train/test splitting
* Model comparison
* Hyperparameter tuning
* Cross-validation
* Residual analysis

**Models explored:**

* Linear Regression
* Decision Tree Regressor
* AdaBoost Regressor
* Random Forest
* Gradient Boosting
* K-Nearest Neighbors (KNN)
* Support Vector Regression (SVR)

**Evaluation metrics:**

* MAE
* MSE
* RMSE
* R² Score

📁 [`regression/`](./regression/)

---

## 🛠️ Technologies & Libraries

**Programming Language**

* Python

**Data Manipulation**

* Pandas
* NumPy

**Visualization**

* Matplotlib
* Seaborn
* Plotly

**Machine Learning**

* Scikit-learn

**Development Environment**

* Jupyter Notebook

---

## 📂 Project Structure

```text
machine-learning-final-project/
│
├── README.md
│
├── classification/
│   ├── classification.ipynb
│   ├── classification_phase2.ipynb
│   └── heart_disease.csv
│
├── clustering/
│   ├── kmeans_clustering.ipynb
│   └── wine_dataset.csv
│
├── regression/
│   ├── regression.ipynb
│   ├── regression_phase2.ipynb
│   └── housing_prices.csv
│
└── presentation/
    └── ML_final_project_presentation.pptx
```

---

## 🔍 Workflow

The project follows a typical Machine Learning workflow:

```text
Data Collection
      ↓
Data Understanding
      ↓
Exploratory Data Analysis
      ↓
Data Cleaning & Preprocessing
      ↓
Feature Engineering / Scaling
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
Final Analysis & Conclusions
```

---

## 📊 Key Learning Outcomes

Through this project, I practiced:

* Working with real-world datasets
* Performing exploratory data analysis
* Identifying and handling data-quality issues
* Preparing data for Machine Learning
* Applying supervised and unsupervised learning algorithms
* Comparing different Machine Learning models
* Selecting appropriate evaluation metrics
* Using visualization to understand model performance
* Applying hyperparameter tuning and cross-validation
* Interpreting model results

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/machine-learning-final-project.git
```

### 2. Navigate to the project

```bash
cd machine-learning-final-project
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open any notebook inside the `classification`, `clustering`, or `regression` folders.

---

## 📈 Project Presentation

The final project presentation is available in:

📁 [`presentation/`](./presentation/)

---

## 👩‍💻 Author

**Jana Elmanzalawy**

Computer Science Student | Data Engineering Student

Interested in **Data Engineering, Machine Learning, Python, and SQL**.

---

## ⭐ Future Improvements

Possible future improvements include:

* Adding more advanced feature engineering
* Experimenting with additional Machine Learning algorithms
* Improving model interpretability
* Deploying selected models as interactive applications
* Building automated data pipelines for model preparation
* Adding a dedicated requirements file for reproducibility
