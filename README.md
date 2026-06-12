**Employee Salary Classification**

## Project Overview

This project predicts whether an employee earns more than $50K or less than/equal to $50K based on employee details such as age, education, occupation, and working hours per week.

The model is trained using the Adult Census Income Dataset and deployed using Streamlit.

## Features Used

* Age
* Education
* Occupation
* Hours per Week

## Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Encoding using LabelEncoder
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Streamlit Deployment

## Algorithms Tested

* Logistic Regression
* Random Forest Classifier
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Gradient Boosting Classifier

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Streamlit
* Joblib

## Project Structure

Employee-Salary-Predictor/

* app.py
* best_model.pkl
* education_encoder.pkl
* occupation_encoder.pkl
* adult 3.csv
* requirements.txt

## Installation

Install required libraries:

pip install -r requirements.txt

## Run the Application

streamlit run app.py

## Model Performance

Best Model: Gradient Boosting Classifier

Accuracy: 79.22%

## Output

The application predicts whether an employee's annual income is:

- Greater than $50K
- Less than or equal to $50K

The prediction is displayed along with the model confidence score.

## Future Improvements

- Integrate FastAPI to expose the model as a REST API.
- Deploy the backend API using Render or Railway.
- Add user authentication and login functionality.
- Support bulk predictions using CSV upload and downloadable reports.
- Implement model monitoring and logging.
- Add data visualization dashboards for salary insights.
- Experiment with advanced ensemble models and hyperparameter tuning.
