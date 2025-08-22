# 📊 Student Score Prediction using Regression

This project builds a regression model to **predict student total scores** based on features like **final term score** and **project score**.  
The model is implemented in Python using **Scikit-learn** and achieves strong predictive performance after applying Ridge Regression with hyperparameter tuning.

---

## 🚀 Project Overview
- **Goal:** Predict `total_score` of students from study-related features.
- **Dataset:** Contains columns such as:
  - 'Student_ID', 
  - 'First_Name', 
  - 'Last_Name', 
  - 'Email', 
  - 'Gender', 
  - 'Age',
  - 'Department', 
  - 'Attendance (%)', 
  - 'Midterm_Score', 
  - 'Final_Score',
  - 'Assignments_Avg', 
  - 'Quizzes_Avg', 
  - 'Participation_Score',
  - 'Projects_Score', 
  - 'Total_Score', 'Grade', 
  - 'Study_Hours_per_Week',
  - 'Extracurricular_Activities', 
  - 'Internet_Access_at_Home',
  - 'Parent_Education_Level', 
  - 'Family_Income_Level', 
  - 'Stress_Level (1-10)',
  - 'Sleep_Hours_per_Night' 

- **Approach:**
  1. Data loading & EDA.  
  2. Baseline model (mean predictor).  
  3. Linear Regression – initial evaluation.  
  4. Ridge Regression with cross-validation.
  5. Final evaluation and model saving.

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/student-score-prediction.git
cd student-score-prediction
pip install -r requirements.txt

## Reqiurements
pandas
numpy
scikit-learn
matplotlib
seaborn


✅ Final Model: Ridge Regression (alpha=100)
✅ Average prediction error ≈ 3.9 points


📌 Key Takeaways

Ridge Regression outperformed Linear and Lasso.

Cross-validation ensured stability (5-fold CV).

Final model explains ~74% of variance in scores.

Low error margin → reliable for predicting student performance.