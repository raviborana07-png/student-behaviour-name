🎓 Student Habits Performance Predictor

🌟 Project Goal

The main goal of this project was to understand how a student's daily habits and background factors influence their academic success, specifically their exam score.

We used machine learning to build a model that can predict a student's final exam score based on a variety of personal and routine factors.


---

📚 The Data We Used

Our dataset contains information from 1000 students, tracking 16 different factors.

Key Information Collected:

Study Habits: Daily study hours, attendance percentage.

Lifestyle: Sleep hours, social media time, Netflix hours, frequency of exercise.

Background: Age, gender, whether they have a part-time job, parental education level, quality of diet, and internet quality.

Mental Health: A mental health rating.

Target: The final Exam Score.



---

🔧 Our Process (How We Built the Predictor)

1. Cleaning Up:
We first tidied the data. This involved removing about 91 entries where we were missing the student's parental education level to ensure our model only trained on complete and reliable information.


2. Preparing for the Model:

We separated the numerical data (like hours and scores) from the category data (like gender and job status).

We converted all category data into a format that the machine learning models could understand (a process called One-Hot Encoding).



3. Testing the Models:
We tested two popular predictive models:

Linear Regression: Excellent for finding simple, direct relationships.

Random Forest: Great for handling complex, non-linear relationships.



4. Selecting the Best Model:
We used a rigorous testing method (Cross-Validation) to see which model performed best consistently.




---

✅ The Results

The Linear Regression model proved to be the most effective for this dataset, suggesting a clear and direct relationship between the input habits and the final exam score.

Performance Metrics:

Performance Metric	Final Score

R-squared (R²)	0.89
Root Mean Squared Error (RMSE)	3.47


What R² = 0.89 Means:

An R-squared score of 0.89 is very strong! It means that approximately 89% of the variation in a student's exam score can be successfully explained and predicted by the habits and factors we included in the model.

In practical terms, the model can predict a student's exam score with an average error of about 3.47 points (RMSE).


---
