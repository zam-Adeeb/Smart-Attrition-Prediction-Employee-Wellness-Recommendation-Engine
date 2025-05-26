# Smart-Attrition-Prediction-Employee-Wellness-Recommendation-Engine

# 💼 Smart Attrition Prediction & Employee Wellness Recommendation Engine

## 📌 Overview

This project is a Data Science-driven solution aimed at **predicting employee attrition** and **recommending wellness actions** for Human Resource (HR) departments. It integrates structured employee data, survey sentiment analysis, machine learning, and rule-based recommendations to help organizations retain valuable talent and improve workplace well-being.

---

## 🧩 Key Modules

### 1. Data Collection & Preprocessing

* Generates a dummy employee dataset.
* Applies label encoding and saves a clean CSV for modeling.
* Columns include: Age, Gender, Department, Tenure, Job Satisfaction, Income, Survey Comments, Attrition.

### 2. Exploratory Data Analysis (EDA)

* Visualizes:

  * Attrition by department
  * Monthly income vs. attrition
* Tools: Matplotlib, Seaborn

### 3. Attrition Prediction Model

* Machine Learning model using **Random Forest Classifier**
* Features: Age, Gender, Department, Tenure, JobSatisfaction, MonthlyIncome
* Evaluation Metrics: Classification report (Precision, Recall, F1 Score)

### 4. Sentiment & Wellness Analysis

* Uses **TextBlob** for sentiment analysis on employee survey comments.
* Categorizes employees into:

  * “At Risk”
  * “Stable”
  * “Thriving”

### 5. Recommendation System

* Rule-based engine providing HR-friendly wellness recommendations based on:

  * Attrition prediction
  * Sentiment classification
* Output saved to `final_output.csv`

---

3. **Generate Outputs**

   * Dataset: `employee_cleaned.csv`
   * Visuals: PNG files in EDA module
   * Final results: `final_output.csv`

---

## 🛠️ Technologies Used

* Python 3.x
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* TextBlob

---

## 📊 Sample Outputs

* ✅ Classification Report for Attrition Model
* ✅ Sentiment Score per employee
* ✅ Final recommendation list

---


## 👥 Author

Developed by: **Adeeb Ahemd (1DB21CS005)**
Submission: Internship Project in the field of Data Science
---

