# 🎓 Student Performance Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting **student academic performance** using supervised machine learning techniques.  
The model analyzes demographic and academic-related features to estimate student scores, with a primary focus on **mathematics performance**.

The objective of this project is to demonstrate an **end-to-end machine learning workflow**, including data preprocessing, feature engineering, model training, and evaluation.

> ⚠️ **Note:** This project is created strictly for **learning and demonstration purposes** and should not be used for real-world academic decision-making.

---

## 🚀 Features
- Predicts student performance based on multiple academic and demographic factors  
- Performs data cleaning and preprocessing on raw student data  
- Applies regression-based machine learning models  
- Evaluates model performance using standard ML metrics  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn  
- **Visualization:** Matplotlib, Seaborn  
- **ML Concepts:** Supervised Learning, Regression, Feature Engineering  

---


---

## 📊 Dataset
The dataset is sourced from **Kaggle – Students Performance in Exams** and contains information such as:

- Gender  
- Parental level of education  
- Lunch type  
- Test preparation course  
- Math, reading, and writing scores  

The dataset is used to analyze how different factors influence student performance.

---

## ⚙️ Workflow
1. Load and explore the dataset  
2. Clean and preprocess the data  
3. Encode categorical variables  
4. Train regression models  
5. Evaluate performance using RMSE and R² score  
6. Save the trained model  

---

## 📈 Model Evaluation
The trained models are evaluated using:
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help assess how well the model generalizes to unseen data.

---

## ▶️ How to Run the Project

```bash
# Clone the repository
git clone https://github.com/Praveen-kumar1Singh/student-performance-prediction-ml.git

# Navigate to the project directory
cd student-performance-prediction-ml

# Install required dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook notebooks/student_performance.ipynb

