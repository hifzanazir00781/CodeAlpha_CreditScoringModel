# Credit Scoring Model - CodeAlpha Internship Task 1

![Machine Learning](https://img.shields.io/badge/Domain-Machine%20Learning-blue)
![Python](https://img.shields.io/badge/Language-Python-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📋 Project Overview
This project was developed during my **Machine Learning Internship at CodeAlpha**. The goal is to build a predictive model that determines a person's creditworthiness based on historical financial data. 

By analyzing features such as income, debt levels, and payment history, the model classifies applicants as either **"Good"** or **"Bad"** credit risks. This automation helps financial institutions minimize risk and streamline the loan approval process.

## 🗂️ Dataset
The model uses the **German Credit Dataset**, which includes 20 categorical/symbolic attributes and a target variable representing the credit risk.
- **Features:** Account status, duration, credit history, purpose, amount, savings, employment, etc.
- **Target:** 1 (Good Credit), 2 (Bad Credit).

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** - `Pandas` & `NumPy`: Data manipulation
  - `Matplotlib` & `Seaborn`: Data visualization
  - `Scikit-learn`: Model building, data splitting, and evaluation

## 🚀 Project Workflow
1. **Data Loading:** Fetching the dataset from the UCI repository.
2. **Data Preprocessing:** Converting categorical text data into numerical format using Label Encoding.
3. **Exploratory Data Analysis (EDA):** Visualizing the distribution of credit classes.
4. **Data Splitting:** Dividing the dataset into Training (80%) and Testing (20%) sets.
5. **Model Training:** Implementing a **Random Forest Classifier** to learn patterns from the data.
6. **Evaluation:** Assessing performance using Accuracy Scores and Confusion Matrices.



## 📊 Results
The model achieves a competitive accuracy score. Key insights are visualized through:
- **Count Plots:** To understand class imbalance.
- **Confusion Matrix:** To evaluate True Positives vs. False Positives.

## 📖 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/YourUsername/Credit-Scoring-Model.git](https://github.com/YourUsername/Credit-Scoring-Model.git)
   
2. Install dependencies:
   ```bash
   pip install pandas seaborn matplotlib scikit-learn
3. Run the script:
   ```bash
   python credit_scoring.py

**Intern Name:** Hifza Nazir

**Organization:** CodeAlpha

**Date:** March 4, 2026
