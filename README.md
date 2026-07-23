# Student Performance Prediction

This is an end-to-end Machine Learning project that predicts a student's **Math Score** based on demographic and academic factors such as gender, ethnicity, parental education level, lunch type, test preparation course, reading score, and writing score.

## Features

* Data Ingestion
* Data Transformation
* Model Training
* Hyperparameter Tuning
* Model Evaluation
* Flask Web Application
* Prediction Pipeline

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* CatBoost
* Flask

## Dataset Features

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch
* Test Preparation Course
* Reading Score
* Writing Score

### Target Variable

* Math Score

## Machine Learning Workflow

1. Data Ingestion
2. Data Preprocessing
3. Feature Transformation
4. Training Multiple Regression Models
5. Hyperparameter Tuning
6. Model Evaluation using R² Score
7. Best Model Selection
8. Model Deployment with Flask

## Models Evaluated

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* AdaBoost Regressor
* K-Neighbors Regressor
* XGBoost Regressor
* CatBoost Regressor

The best-performing model is selected automatically based on evaluation metrics.

## How to Run

Clone the repository:

```bash
git clone <repository-url>
cd <repository-name>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Flask application:

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

