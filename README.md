# 📊 Customer Churn Prediction

A Machine Learning project to predict whether a bank customer is likely to **churn (leave the bank)** based on customer demographic, financial, and account-related information.

The project covers the complete Machine Learning workflow, including **data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation**.

---

## 📌 Project Overview

Customer churn is an important business problem where existing customers stop using a company's products or services.

The objective of this project is to analyze customer data and build a Machine Learning model that can identify customers who are likely to leave the bank.

By predicting potential churners, organizations can take proactive actions such as improving customer experience, providing personalized offers, and implementing customer-retention strategies.

---

## 🎯 Objectives

* Understand the factors that influence customer churn.
* Perform exploratory data analysis on customer information.
* Clean and preprocess the dataset.
* Convert categorical features into numerical form.
* Split the dataset into training and testing sets.
* Apply feature scaling where required.
* Build and evaluate Machine Learning models.
* Predict whether a customer is likely to churn.

---

## 🗃️ Dataset

The project uses the **Churn Modelling dataset**, containing information about bank customers.

### Important Features

| Feature           | Description                               |
| ----------------- | ----------------------------------------- |
| `CreditScore`     | Customer's credit score                   |
| `Geography`       | Country of the customer                   |
| `Gender`          | Customer's gender                         |
| `Age`             | Customer's age                            |
| `Tenure`          | Number of years with the bank             |
| `Balance`         | Customer's account balance                |
| `NumOfProducts`   | Number of bank products used              |
| `HasCrCard`       | Whether the customer has a credit card    |
| `IsActiveMember`  | Whether the customer is an active member  |
| `EstimatedSalary` | Estimated customer salary                 |
| `Exited`          | Target variable indicating customer churn |

The dataset contains **10,000 customer records** and the target variable is `Exited`, where:

* `0` → Customer did not churn
* `1` → Customer churned

---

## 🔄 Machine Learning Workflow

The project follows a standard Machine Learning pipeline:

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Categorical Encoding
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Churn Prediction
```

---

## 🧹 Data Preprocessing

The following preprocessing techniques are used:

* Removing unnecessary columns
* Separating independent and dependent variables
* Encoding categorical variables
* Splitting data into training and testing sets
* Feature scaling
* Preparing the dataset for Machine Learning algorithms

---

## 🤖 Machine Learning

The project focuses on **Supervised Machine Learning** for a binary classification problem.

The target variable is:

```text
Exited
```

The model predicts whether a customer will:

```text
0 → Stay with the bank
1 → Leave the bank
```

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 📚 Concepts Covered

This project provides practical implementation of:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Categorical Encoding
* Train-Test Split
* Feature Scaling
* Classification
* Model Training
* Model Evaluation
* Customer Churn Prediction

---

## 📁 Repository Structure

```text
CHURN-Modelling-Dataset/
│
├── Churn_Modelling.csv
├── Churn_Modelling.ipynb
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── .gitignore
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/GouravSinghDosad/CHURN-Modelling-Dataset.git
```

### 2. Navigate to the project directory

```bash
cd CHURN-Modelling-Dataset
```

### 3. Install required libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```text
Churn_Modelling.ipynb
```

Run the notebook cells sequentially to reproduce the analysis and model-building process.

---

## 📈 Project Outcome

The project demonstrates how Machine Learning can be applied to customer data to identify customers who are more likely to churn.

The analysis helps understand customer characteristics associated with churn and provides a foundation for developing **data-driven customer retention strategies**.

---

## 🔮 Future Improvements

The project can be further improved by:

* Hyperparameter tuning
* Cross-validation
* Comparing multiple classification algorithms
* Handling class imbalance
* Feature importance analysis
* ROC-AUC analysis
* Building an interactive prediction application
* Deploying the trained model using Streamlit or Flask

---

## 👨‍💻 Author

**Gourav Singh Dosad**

* GitHub: [GouravSinghDosad](https://github.com/GouravSinghDosad)

---

## 📄 License

This project is licensed under the **GPL-3.0 License**.
