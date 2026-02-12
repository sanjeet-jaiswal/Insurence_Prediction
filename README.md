# 🏥 Health Insurance Cost Prediction | Data Analysis & Machine Learning

A Machine Learning powered web application that predicts medical insurance charges based on user details such as age, BMI, smoking habits, and more.

🔗 **Live Demo:**  
👉 https://healtth-insurance-cost-prediction.onrender.com/

---

## 📚 Table of Contents

1. [Project Overview](#project-overview)
2. [Problem Statement](#problem-statement)
3. [Dataset Description](#dataset-description)
4. [Data Cleaning & Preprocessing](#data-cleaning--preprocessing)
5. [Feature Engineering](#feature-engineering)
6. [Exploratory Data Analysis](#exploratory-data-analysis)
7. [Model Building](#model-building)
8. [Model Evaluation](#model-evaluation)
9. [Web Application Development](#web-application-development)
10. [Deployment](#deployment)
11. [Key Learnings](#key-learnings)
12. [Future Improvements](#future-improvements)
13. [Tech Stack](#tech-stack)
14. [Author](#author)

---

## 📌 Project Overview

This project predicts health insurance charges using Machine Learning techniques.  
A Linear Regression model is trained on historical insurance data and deployed using Flask as an interactive web application.

Users can enter their details and instantly receive predicted insurance cost.

---

## 🎯 Problem Statement

Medical insurance costs depend on multiple real-world factors:

- Age
- BMI (Body Mass Index)
- Smoking habits
- Number of children
- Gender
- Region

The goal is to build a regression model that accurately predicts insurance charges based on these features.

---

## 📊 Dataset Description

The dataset contains the following features:

| Feature | Description |
|----------|------------|
| age | Age of the insured person |
| sex | Gender (Male/Female) |
| bmi | Body Mass Index |
| children | Number of dependents |
| smoker | Smoking status |
| region | Residential area |
| charges | Medical insurance cost (Target Variable) |

---

## 🧹 Data Cleaning & Preprocessing

- Checked for missing values
- Encoded categorical variables manually
- Split dataset into features (X) and target (y)
- Train-test split (80-20)
- Converted prediction input into NumPy array format

---

## ⚙ Feature Engineering

Categorical encoding used:

- Male = 0, Female = 1
- Smoker (Yes = 0, No = 1)
- Region encoded numerically

Feature order maintained during model prediction to ensure consistency.

---

## 📈 Exploratory Data Analysis

Performed analysis to understand:

- Smoking impact on insurance charges
- Age vs charges trend
- BMI vs cost relationship
- Distribution of insurance costs
- Correlation between features

---

## 🤖 Model Building

Algorithm Used:

- **Linear Regression**

Steps:
- Imported sklearn LinearRegression
- Model trained on training dataset
- Predictions made on both training and test data

---

## 📊 Model Evaluation

Evaluation Metric Used:

- **R² Score**

The model achieved good performance on both training and test data, indicating stable predictions without heavy overfitting.

---

## 🌐 Web Application Development

Framework Used:

- Flask (Python Web Framework)

Features:

- User-friendly input form
- Real-time insurance cost prediction
- Clean HTML + CSS UI
- Integrated trained ML model using joblib

---

## 🚀 Deployment

Deployment Platform:

- Render (Free Cloud Hosting)

Deployment Steps:

1. Trained model saved using joblib
2. Flask app created
3. requirements.txt added
4. GitHub repository connected to Render
5. Live web app deployed successfully

🔗 Live Application:  
https://healtth-insurance-cost-prediction.onrender.com/

---

## 🎓 Key Learnings

- End-to-end Machine Learning workflow
- Model serialization with joblib
- Flask backend development
- Handling form data using POST method
- Cloud deployment using Render
- Integrating ML model with web application

---

## 🔮 Future Improvements

- Compare multiple regression algorithms
- Add Bootstrap UI styling
- Add model selection option
- Add input validation
- Deploy using Docker
- Improve feature engineering

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- HTML
- CSS
- Render (Deployment)

---

## 👨‍💻 Author

**Sanjeet Jaiswal**  
Aspiring Data Scientist & Machine Learning Enthusiast  

📧 Email: sanjeet221601@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/sanjeetjaiswal/

---


