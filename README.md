## End to End Machine Learning Project

### Student Performance Prediction
This project aims to predict students' math scores based on various factors such as gender, race/ethnicity, parental education, lunch type, and test preparation. The dataset contains features that describe the students' demographics, educational background, and previous test performance.

# Dataset Description
The dataset includes the following features:
Gender: Sex of the students
Values: Male, Female

Race/Ethnicity: The ethnic group to which the student belongs
Values: Group A, Group B, Group C, Group D, Group E

Parental Level of Education: The highest level of education completed by the student's parents
Values: bachelor's degree, some college, master's degree, associate's degree, high school

Lunch: The type of lunch the student had before taking the test
Values: standard, free/reduced

Test Preparation Course: Whether the student completed a test preparation course before taking the exam
Values: completed, not completed

Math Score: The student's score in the math test
Numeric values
Reading Score: The student's score in the reading test
Numeric values

Writing Score: The student's score in the writing test
Numeric values
Project Goal
The goal of this project is to build a predictive model that estimates a student's math score based on the other columns (features). By analyzing the impact of factors like gender, race/ethnicity, parental education, lunch, test preparation, and performance in reading and writing, we aim to predict the math scores.

# Project Workflow
Data Exploration: Understand the structure of the data and the distribution of each feature.
Data Preprocessing: Handle missing values, encode categorical variables, and scale numeric values where necessary.
Model Building: Train a machine learning model to predict math scores using features such as gender, parental education, etc.
Evaluation: Assess the model's performance using metrics like RMSE (Root Mean Squared Error), R² score, etc.

# Deployment
This project has been deployed using Flask for the backend and hosted on AWS Elastic Beanstalk.

Clone the repository:

git clone https://github.com/your-repo/student-performance-prediction.git
Install dependencies:

pip install -r requirements.txt
Run the Flask application locally:
python app.py
Navigate to http://localhost:5000 in your browser and use the interface to predict math scores by inputting other feature values.
