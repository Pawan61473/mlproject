# End to End Machine Learning Project

## Student Performance Prediction
This project aims to predict students' math scores based on various factors such as gender, race/ethnicity, parental education, lunch type, and test preparation. The dataset contains features that describe the students' demographics, educational background, and previous test performance.

### Dataset Description
The dataset includes the following features:
- Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
- The data consists of 8 column and 1000 rows. <br>

### Project Goal
The goal of this project is to build a predictive model that estimates a student's math score based on the other columns (features). By analyzing the impact of factors like gender, race/ethnicity, parental education, lunch, test preparation, and performance in reading and writing, we aim to predict the math scores.

### Project Workflow
Data Exploration: Understand the structure of the data and the distribution of each feature.
Data Preprocessing: Handle missing values, encode categorical variables, and scale numeric values where necessary.
Model Building: Train a machine learning model to predict math scores using features such as gender, parental education, etc.
Evaluation: Assess the model's performance using metrics like RMSE (Root Mean Squared Error), R² score, etc.

### Deployment
This project has been deployed using Flask for the backend and hosted on AWS Elastic Beanstalk.

Clone the repository:

git clone https://github.com/your-repo/student-performance-prediction.git <br>

Install dependencies:
pip install -r requirements.txt <br>
Run the Flask application locally: <br>
python app.py <br>
Navigate to http://localhost:5000 in your browser and use the interface to predict math scores by inputting other feature values.
