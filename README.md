# E-commerce Purchase Intent Prediction Using Logistic Regression

## 📌 Project Overview

This project uses **Logistic Regression** to predict whether an e-commerce website session will result in a purchase.

The model uses customer browsing and session behaviour to classify a session into:

* **0 → No Purchase**
* **1 → Purchase**

## 🎯 Problem Statement

Predict whether a website session will result in a purchase based on customer session behaviour.

## 📊 Dataset

The dataset contains **1,000 observations** and the following features:

| Feature           | Description                                     |
| ----------------- | ----------------------------------------------- |
| `pages_viewed`    | Number of pages viewed during the session       |
| `session_minutes` | Duration of the website session                 |
| `products_viewed` | Number of products viewed                       |
| `cart_additions`  | Number of products added to the cart            |
| `discount_seen`   | Whether a discount was seen                     |
| `previous_orders` | Number of previous orders                       |
| `target`          | Purchase outcome: 0 = No Purchase, 1 = Purchase |

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## 🔍 Project Workflow

1. Data loading
2. Data exploration
3. Checking missing values and duplicates
4. Exploratory Data Analysis (EDA)
5. Data visualization
6. Correlation analysis
7. Train-test split
8. Feature scaling using StandardScaler
9. Logistic Regression model training
10. Prediction
11. Model evaluation
12. Confusion matrix analysis
13. ROC curve and ROC-AUC analysis
14. Feature coefficient interpretation

## 🤖 Machine Learning Model

**Logistic Regression** is used because the target variable has two possible outcomes: purchase and no purchase.

The dataset is divided into:

* **80% Training Data**
* **20% Testing Data**

Feature scaling is performed using `StandardScaler`.

## 📈 Model Performance

The Logistic Regression model achieved approximately:

| Metric    | Score |
| --------- | ----: |
| Accuracy  |   73% |
| Precision |   74% |
| Recall    |   71% |
| F1 Score  |   72% |
| ROC-AUC   |  0.80 |

The ROC-AUC score of approximately **0.80** indicates that the model has a reasonably good ability to distinguish between purchase and non-purchase sessions.

## 💡 Key Findings

Customer website behaviour contains useful information for predicting purchase intent.

Features such as pages viewed, session duration, products viewed, cart additions, discount information and previous orders can contribute to predicting whether a customer will make a purchase.

Logistic Regression also provides interpretable coefficients, which help understand the influence of different features on the purchase prediction.

## ⚠️ Limitations

* The dataset is intended for educational purposes.
* It may not completely represent real-world e-commerce customer behaviour.
* Only a limited number of customer behaviour features are available.
* Logistic Regression assumes a linear relationship between the features and the log-odds of the target.

## 🚀 Future Improvements

The project can be improved by:

* Using a larger real-world dataset
* Adding more customer behaviour features
* Comparing Logistic Regression with Random Forest and Gradient Boosting
* Performing hyperparameter tuning
* Using cross-validation
* Deploying the model as a web application

## 📁 Repository Contents

```text
Ecommerce-Purchase-Intent-Logistic-Regression/
│
├── Ecommerce_Purchase_Intent_Logistic_Regression.ipynb
├── dataset_04_ecommerce_purchase_intent.csv
└── README.md
```

## 👩‍💻 Author

**Anamika Chauhan**

M.Sc. Student
Mathematics / Data Science
