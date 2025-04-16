# Zylentrix Machine Learning Assignment

This project involves a supervised machine learning classification task to predict student dropout based on their engagement with an online course.

## 📊 Dataset Overview

The dataset `learning_data.xlsx` contains student information and course interaction metrics. The features include:

| Column Name             | Description |
|-------------------------|-------------|
| `student_id`            | Unique identifier |
| `age`                   | Age of the student |
| `gender`                | Gender (Male / Female / Other) |
| `course_type`           | Course enrolled (Digital Marketing / Python / UI/UX) |
| `session_count`         | Number of sessions attended |
| `avg_session_duration`  | Average session duration (in minutes) |
| `quiz_attempts`         | Number of quiz attempts |
| `assignments_submitted` | Number of assignments submitted |
| `satisfaction_rating`   | Rating from 1 to 5 |
| `dropout`               | Target (1 = Dropped out, 0 = Completed) |

## 🔍 Objective

To build a classification model that predicts whether a student will drop out based on their course engagement behavior.

## 🧹 Key Steps

- Data cleaning and exploration
- Feature encoding and scaling
- Model building using classifiers (Logistic Regression, Decision Tree, etc.)
- K-Fold Cross Validation
- Final model evaluation and selection

## 📈 Evaluation

Model performance was measured using:
- Accuracy
- Confusion Matrix
- Cross-validation scores

Overfitting was evaluated by comparing cross-validation and final model scores.

## 📁 Files Included

- `ML Assignment.ipynb`: Jupyter notebook containing all code and outputs
- `learning_data.xlsx`: Dataset used
- `README.md`: Project summary
- `Report & Submission.pdf` Pdf containing report and summary of assignment

## 📝 Conclusion

The model provides meaningful insights on student engagement and helps in identifying dropouts early. This can assist institutions in designing targeted interventions to improve course completion rates.

