# 🏠 House Price Prediction using Machine Learning

---
**Dataset**:
Name: California Housing Prices
Kaggle Link: https://www.kaggle.com/datasets/camnugent/california-housing-prices


## Setup
1. Create a empty folder named `House-Price-Prediction`
2. cd `House-Price-Prediction`
3. create an virtual env: `conda create -n myenv python=3.12`
4. activate the virtual env: `conda activate myenv`
5. Install Kernel : `pip install ipykernel`


A complete end-to-end Machine Learning Regression project that predicts house prices based on various housing features. This project demonstrates the entire machine learning workflow, from understanding the dataset to selecting and optimizing the best-performing model.

---

# 📌 Project Overview

The objective of this project is to build a machine learning model capable of accurately predicting house prices using historical housing data.

Instead of simply training a model, this project follows the complete Data Science lifecycle used in real-world industry projects.

The project covers:

- Data Understanding
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Data Preprocessing
- Machine Learning Pipelines
- Model Training
- Model Evaluation
- Cross Validation
- Hyperparameter Tuning
- Final Model Selection

---

# 🎯 Problem Statement

House prices depend on multiple factors such as:

- Location
- Number of Rooms
- Population
- Income
- House Age
- Latitude
- Longitude
- Distance from Ocean

The objective is to learn these relationships and predict the median house value for unseen houses.

---

# 📂 Dataset

The project uses the **California Housing Dataset**.

Each row represents one district in California.

The target variable is:

```
median_house_value
```

---

# 📊 Features

| Feature | Description |
|----------|-------------|
| longitude | Longitude of district |
| latitude | Latitude of district |
| housing_median_age | Median age of houses |
| total_rooms | Total rooms |
| total_bedrooms | Total bedrooms |
| population | Population |
| households | Number of households |
| median_income | Median income |
| ocean_proximity | Distance from ocean |
| median_house_value | Target Variable |

---

# 🧠 Machine Learning Workflow

```
Business Problem
        │
        ▼
Load Dataset
        │
        ▼
Understand Dataset
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Train-Test Split
        │
        ▼
Preprocessing Pipeline
        │
        ▼
Baseline Model
        │
        ▼
Multiple Model Comparison
        │
        ▼
Cross Validation
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Best Model
        │
        ▼
Final Prediction
```

---

# 📖 Project Phases

## Phase 1 — Environment Setup

- Install required libraries
- Import packages
- Configure notebook

### Purpose

Prepare the environment for data analysis and machine learning.

---

## Phase 2 — Data Loading

- Read CSV
- Explore dataset
- Understand shape
- View sample records

### Purpose

Load the dataset into memory for analysis.

---

## Phase 3 — Exploratory Data Analysis (EDA)

Performed:

- Shape
- Columns
- Data Types
- Missing Values
- Duplicate Values
- Statistical Summary
- Histograms
- Boxplots
- Correlation Matrix
- Target Distribution

### Purpose

Understand data quality and discover meaningful insights.

---

## Phase 4 — Data Preprocessing

Includes:

- Handling Missing Values
- Encoding Categorical Features
- Feature Selection
- Train-Test Split
- Pipeline Creation

### Purpose

Prepare raw data for machine learning algorithms.

---

## Phase 5 — Baseline Model

Initial model:

- Linear Regression

Purpose:

Establish a baseline performance before trying advanced models.

---

## Phase 6 — Model Comparison

Multiple regression algorithms are trained and compared using Cross Validation.

Examples include:

- Linear Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- HistGradientBoosting

Purpose:

Find the algorithm that performs best.

---

## Phase 7 — Model Evaluation

Evaluation metrics include:

- RMSE
- MAE

Purpose:

Measure prediction accuracy.

---

## Phase 8 — Hyperparameter Tuning

Uses:

- GridSearchCV

Purpose:

Optimize model performance by finding the best hyperparameters.

---

## Phase 9 — Final Model

The best tuned model is selected for final predictions.

---

# ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

# 📦 Libraries

```python
numpy
pandas
matplotlib
seaborn
scikit-learn
```

---

# 📈 Machine Learning Concepts Covered

- Supervised Learning
- Regression
- Exploratory Data Analysis
- Feature Engineering
- Missing Value Imputation
- One-Hot Encoding
- Pipelines
- Column Transformer
- Train-Test Split
- Cross Validation
- Model Evaluation
- Hyperparameter Tuning
- Model Selection

---

# 📊 Evaluation Metrics

The project evaluates models using:

## RMSE (Root Mean Squared Error)

Measures the average prediction error while penalizing larger mistakes.

Lower RMSE indicates better performance.

---

## MAE (Mean Absolute Error)

Measures the average absolute difference between predicted and actual values.

Lower MAE indicates better performance.

---

# 🚀 Project Structure

```
House-Price-Prediction/
│
├── data/
│     └── housing.csv
│
├── notebook/
│     └── house-price-prediction.ipynb
│
├── README.md
│
└── requirements.txt
```

---

# ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/house-price-prediction.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
house-price-prediction.ipynb
```

Run all cells sequentially.

---

# 📚 Learning Outcomes

After completing this project, you will understand:

- How to analyze datasets
- How to perform EDA
- How to clean data
- How to preprocess features
- How to build ML pipelines
- How to compare multiple models
- How Cross Validation works
- How Hyperparameter Tuning improves performance
- How to choose the best regression model

---

# 💡 Key Takeaways

- Always understand the dataset before training a model.
- Data preprocessing is as important as model selection.
- Pipelines help prevent data leakage.
- Cross Validation provides reliable performance estimates.
- Hyperparameter tuning can significantly improve model accuracy.

---

# 🎯 Future Improvements

- Feature Engineering
- Feature Selection
- Model Explainability (SHAP)
- Model Serialization using Pickle
- REST API using FastAPI
- Docker Deployment
- CI/CD Integration
- Cloud Deployment (AWS/Azure/GCP)

---

# 👨‍💻 Author

**Arun Jawlia**

Passionate about Machine Learning, Data Science, Artificial Intelligence, and Building Production-Ready AI Applications.

---

# ⭐ If you found this project useful, consider giving it a star!